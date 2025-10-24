---
title: Proposition commerciale — Compagnons-Bâtisseurs
theme: default
presenter: true
colorSchema: light
layout: cover
fonts:
  sans: 'Inter'
  heading: 'Monstera, Montserrat, Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial'
# Fonds verts pour toutes les slides (défaut)
background: linear-gradient(145deg, #1fb78f 0%, #0e6e49 40%, #0a573a 80%, #094d34 100%)
class: text-center
---

<style>
/* ---- Polices web (fallback si Monstera non chargée) ---- */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Montserrat:wght@700;800&display=swap');

/* ---- Palette Creapp-i (verts contrastés) ---- */
:root{
  --brand-25:  #e7fff3;
  --brand-50:  #cffff0;
  --brand-100: #b7f7e2;
  --brand-200: #8eeccf;
  --brand-300: #5fdcb9;
  --brand-400: #36c9a1;
  --brand-500: #1fb78f;
  --brand-600: #149a77;
  --brand-700: #0e7e60;
  --brand-800: #0b614b;
  --brand-900: #0a573a; /* vert fond principal */
  --ink-0:    #ffffff;
  --ink-1:    #f9fafb;
  --ink-2:    #e5eef0;
  --ink-3:    #d1dbe0;
  --text-strong: #000000;
  --text-soft:   #333333;
  --ring: rgba(255,255,255,.22);
}

/* ---- Globaux ---- */
.slidev-layout, .slidev-page, .slidev-page div, .slidev-page p, .slidev-page li {
  color: var(--text-strong);
  text-align: center;
}
h1,h2,h3,h4 { 
  font-family: "Monstera", Montserrat, Inter, sans-serif; 
  color: var(--brand-900); 
  letter-spacing: 0.2px;
}
h1 { font-weight: 800; }
h2 { font-weight: 800; }
h3 { font-weight: 700; }

/* ---- Composants lisibles sur fond vert ---- */
.card {
  background: #ffffff;
  color: var(--text-soft);
  border: 2px solid var(--brand-200);
  border-radius: 22px;
  padding: 22px;
  box-shadow: 0 10px 26px rgba(0,0,0,.18);
}
.card.alt { 
  background: linear-gradient(135deg, #f9fffb 0%, var(--brand-25) 100%);
  border: 2px solid var(--brand-300);
}

.pill {
  display:inline-flex; align-items:center; gap:.5rem;
  background: linear-gradient(135deg, var(--brand-100) 0%, var(--brand-200) 100%);
  color: var(--brand-900);
  border: 2px solid var(--brand-400);
  padding:.35rem .75rem; border-radius:999px; font-weight:700; font-size:.85rem;
  box-shadow: 0 4px 12px rgba(31,183,143,.2);
}

.grid-2 { display:grid; grid-template-columns:1fr 1fr; gap:22px; justify-items: center; }
.grid-3 { display:grid; grid-template-columns:repeat(3,1fr); gap:18px; justify-items: center; }

.kpi {
  background: linear-gradient(135deg, #fff 0%, var(--brand-25) 100%);
  border: 2px solid var(--brand-200);
  border-radius:18px; 
  padding:14px 16px; 
  color:var(--text-soft);
  box-shadow: 0 4px 12px rgba(31,183,143,.1);
}
.kpi b { color: var(--brand-800); }

/* ---- Tableaux ---- */
table{
  width:100%; border-collapse:separate; border-spacing:0; overflow:hidden;
  background:#fff; color:var(--text-soft); border-radius:16px; border:2px solid var(--brand-200);
  box-shadow: 0 8px 22px rgba(0,0,0,.12);
}
th,td{ padding:12px 14px; }
thead th{ 
  background: linear-gradient(135deg, var(--brand-100) 0%, var(--brand-200) 100%); 
  color:var(--brand-900); 
  text-align:left; 
  font-weight:800; 
  border-bottom:2px solid var(--brand-300); 
}
tbody tr:not(:last-child) td { border-bottom:1px dashed var(--brand-200); }

/* ---- Boutons ---- */
.btn {
  display:inline-block; 
  background: linear-gradient(135deg, var(--brand-500) 0%, var(--brand-600) 100%);
  color:white !important; 
  text-decoration:none;
  padding:10px 16px; 
  border-radius:14px; 
  font-weight:800; 
  letter-spacing:.2px;
  border: 2px solid var(--brand-700);
  box-shadow: 0 8px 22px rgba(31,183,143,.3);
}
.btn.secondary {
  background: linear-gradient(135deg, #ffffff 0%, var(--brand-25) 100%);
  color:var(--brand-800) !important; 
  border: 2px solid var(--brand-300);
  box-shadow: 0 4px 12px rgba(31,183,143,.2);
}

/* ---- Logos ---- */
.logo-row{ display:flex; gap:24px; align-items:center; flex-wrap:wrap; justify-content: center; }
.logo-row img{ 
  background: linear-gradient(135deg, #fff 0%, var(--brand-25) 100%); 
  border-radius:16px; 
  padding:20px; 
  border: 2px solid var(--brand-200); 
  box-shadow:0 6px 16px rgba(31,183,143,.15);
  max-width: 200px;
  min-height: 100px;
  object-fit: contain;
  transition: transform 0.3s ease;
}
.logo-row img:hover {
  transform: scale(1.05);
}

/* ---- Encarts translucides pour titres sur fond vert ---- */
.glass {
  backdrop-filter: blur(6px);
  background: linear-gradient(180deg, rgba(31,183,143,.25), rgba(31,183,143,.15));
  border: 2px solid rgba(31,183,143,.4);
  border-radius: 18px;
  padding: 12px 16px;
  display: inline-block;
  box-shadow: 0 8px 22px rgba(31,183,143,.2);
}
</style>

<div class="glass">
  <h1>Proposition commerciale</h1>
  <h2>Compagnons-Bâtisseurs</h2>
</div>

<div style="height:16px"></div>

<div class="card">
  <p><b>Création d'un système d'information sur mesure</b></p>
  <div class="logo-row" style="margin-top:10px">
    <img src="https://static.wixstatic.com/media/513107_4949f92e885b46b2b8cfa717825386c5~mv2.png" alt="Logo Creapp-i" style="height: 120px; width: auto;">
    <img src="https://www.compagnonsbatisseurs.eu/assets/img/Logo_simple_C_H_web.png" alt="Logo Compagnons-Bâtisseurs" style="height: 120px; width: auto;">
  </div>
</div>

---

# Présentation de Creapp-i

<div class="grid-2">
  <div class="card">
    <div class="pill">À propos</div>
    <h2>Agence de développement sur mesure</h2>
    <p>Basée à La Réunion, Creapp-i transforme vos idées en <b>solutions digitales concrètes</b>, de la conception à la mise en œuvre.</p>
    <ul>
      <li>Processus modernisés et simplifiés</li>
      <li>Outils <b>efficaces, intuitifs</b> et accessibles</li>
      <li>Accompagnement de bout en bout</li>
    </ul>
  </div>
  <div class="card alt">
    <div class="pill">Équipe projet</div>
    <h2>Intervenants</h2>
    <div class="grid-2">
      <div class="kpi"><b>Alexandre MAILLOT</b><br/>Chef de projet & Développeur</div>
      <div class="kpi"><b>Nathan CHATEAU</b><br/>Développeur</div>
    </div>
  </div>
</div>

---

# Enjeux du projet

<div class="grid-2">
  <div class="card">
    <div class="pill">Enjeux</div>
    <ul>
      <li>Digitaliser et centraliser la <b>gestion des chantiers</b></li>
      <li>Fluidifier la communication <b>terrain ↔ administration</b></li>
      <li>Assurer la <b>traçabilité</b> des interventions, devis, photos et documents</li>
      <li>Réduire l’usage du papier (impact éco-responsable)</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Bénéfices</div>
    <ul>
      <li>Outil simple, moderne et collaboratif</li>
      <li>Synchronisation temps réel via <b>Firebase</b></li>
      <li>Adoption facilitée pour utilisateurs non technophiles</li>
    </ul>
  </div>
</div>

---

# Objectifs principaux

<div class="grid-2">
  <div class="card">
    <div class="pill">Application Animateurs</div>
    <ul>
      <li>Visites, diagnostics, interventions</li>
      <li>Devis, documents, photos</li>
      <li>Statistiques et calendrier</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Plateforme Administrative</div>
    <ul>
      <li>Validation des devis & supervision</li>
      <li>Archivage & reporting</li>
      <li>Multi-structures & journalisation</li>
    </ul>
  </div>
</div>

<div class="card" style="margin-top:18px">
  <div class="pill">Architecture</div>
  <ul>
    <li>Base de données centralisée <b>Firebase</b> (sécurité, stockage, synchro temps réel)</li>
    <li>Interfaces <b>intuitives</b> et accessibles</li>
  </ul>
</div>

---

# Déroulement du projet

<div class="grid-2">
  <div class="card">
    <div class="pill">Phase 1</div>
    <h2>Analyse & Spécifications</h2>
    <ul>
      <li>Recueil des besoins (animateurs, administratifs)</li>
      <li>Cas d’utilisation MVP (visites, devis, interventions, documents, photos)</li>
      <li>Cahier des charges & priorisation</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Phase 2</div>
    <h2>Conception</h2>
    <ul>
      <li>Maquettes & parcours utilisateurs</li>
      <li>Architecture Firebase multi-structures</li>
      <li>Règles de sécurité & stockage</li>
    </ul>
  </div>
</div>

<div class="grid-2" style="margin-top:18px">
  <div class="card">
    <div class="pill">Phase 3</div>
    <h2>Développement</h2>
    <ul>
      <li>Apps Web Animateurs & Administratifs</li>
      <li>Modules : chantiers, devis, diagnostics, interventions, documents, statistiques</li>
      <li>Tests fonctionnels & pilotes</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Phase 4</div>
    <h2>Mise en place & Formation</h2>
    <ul>
      <li>Déploiement production</li>
      <li>Formation des équipes CB</li>
      <li>Documentation technique & fonctionnelle</li>
    </ul>
  </div>
</div>

---

# Planning & délais

<div class="card">
<table>
  <thead>
    <tr><th>Phase</th><th>Durée estimée</th></tr>
  </thead>
  <tbody>
    <tr><td>Maquettage</td><td><b>2 jours</b></td></tr>
    <tr><td>Développement</td><td><b>19 jours</b></td></tr>
    <tr><td>Mise en place & formation</td><td><b>3 jours</b></td></tr>
  </tbody>
</table>
<p style="margin-top:10px; color:#0b614b"><b>Durée totale : 24 jours (≈ 5 semaines)</b></p>
</div>

---

# Devis forfaitaire 💶

<div class="grid-2">
  <div class="card">
    <div class="pill">Projet (forfait global)</div>
    <ul>
      <li><b>Montant total HT :</b> 15 600 €</li>
      <li><b>TVA (8,5 %) :</b> 1 326 €</li>
      <li><b>Total TTC :</b> <b style="color:#0b614b">16 326 €</b></li>
    </ul>
 
  </div>
  <div class="card alt">
    <div class="pill">Option — Maintenance mensuelle</div>
    <ul>
      <li><b>HT :</b> 300 €</li>
      <li><b>TVA (8,5 %) :</b> 25,50 €</li>
      <li><b>Total TTC :</b> <b style="color:#0b614b">325,50 €</b></li>
    </ul>
  </div>
</div>

---

# Maintenance optionnelle

<div class="grid-2">
  <div class="card">
    <div class="pill">Garantie 1</div>
    <h2>Rétablissement du service</h2>
    <ul>
      <li>Intervention prioritaire en cas d’incident</li>
      <li>Diagnostic & correction rapides</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Garantie 2</div>
    <h2>Sécurité & RGPD</h2>
    <ul>
      <li>Mises à jour sécurité & performance</li>
      <li>Contrôles réguliers de conformité RGPD</li>
      <li>Rapport périodique des actions</li>
    </ul>
  </div>
</div>

---

# Contact

<div class="card">
  <div class="pill">Coordonnées</div>
  <p><b>Alexandre MAILLOT — Dirigeant Creapp-i</b></p>
  <p>📞 06 92 78 29 75 · 📧 alexandre.maillot@creapp-i.com</p>
  <p>🏢 26 chemin bateau, 97425 Les Avirons</p>
  <p>💼 SIRET : 951 325 943 00011 · 🌐 www.creapp-i.com</p>
</div>

---

# Annexe — Liste des Use Cases Compagnons-Bâtisseurs

<div class="card">
  <p>Reprise intégrale du fichier <b>« Compagnon Bâtisseur — Usecase.csv »</b></p>
  <ul>
    <li>Cas d’utilisation détaillés (animateurs, administratifs, supervision, etc.)</li>
    <li>Référence fonctionnelle pour valider le périmètre</li>
  </ul>
  <p style="opacity:.9">👉 Si la liste est longue, éclater en plusieurs slides (copier-coller Markdown depuis le CSV).</p>
</div>

---

layout: center
# Fonds vert partout, merci 🙏
<p><a class="btn" href="mailto:alexandre.maillot@creapp-i.com">Nous contacter</a> <a class="btn secondary" href="https://www.creapp-i.com">Site web</a></p>
