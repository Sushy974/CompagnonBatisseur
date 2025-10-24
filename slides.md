---
title: Proposition commerciale — Compagnons-Bâtisseurs
theme: default
presenter: true
colorSchema: light
layout: cover
fonts:
  sans: 'Inter'
  heading: 'Monstera, Montserrat, Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial'
# Fond blanc (charte Créapp-i)
background: '#ffffff'
class: text-center
---

<style>
/* ---- Polices web (fallback si Monstera non chargée) ---- */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Montserrat:wght@700;800&display=swap');

/* ---- Palette Créapp-i (vert #168C71) ---- */
:root{
  --brand-25:  #e6f7f2;
  --brand-50:  #ccefe5;
  --brand-100: #99dfcb;
  --brand-200: #66cfb1;
  --brand-300: #33bf97;
  --brand-400: #1aa37d;
  --brand-500: #168C71;
  --brand-600: #127560;
  --brand-700: #0e5e4f;
  --brand-800: #0a473e;
  --brand-900: #06302d;
  --bg-main:   #f5f5f5;
  --bg-white:  #ffffff;
  --text-strong: #1a1a1a;
  --text-soft:   #4a4a4a;
  --text-light:  #6b7280;
}

/* ---- Globaux ---- */
.slidev-layout, .slidev-page, .slidev-page div, .slidev-page p, .slidev-page li {
  color: var(--text-strong);
  text-align: center;
}
h1,h2,h3,h4 {
  font-family: "Monstera", Montserrat, Inter, sans-serif;
  color: var(--text-strong);
  letter-spacing: 0.2px;
}
h1 { font-weight: 800; font-size: 1.8rem; }
h2 { font-weight: 800; font-size: 1.3rem; }
h3 { font-weight: 700; font-size: 1.1rem; }
p, li { font-size: 0.95rem; line-height: 1.5; }

/* ---- Composants carte ---- */
.card {
  background: #ffffff;
  color: var(--text-soft);
  border-radius: 16px;
  padding: 24px;
  box-shadow: 0 2px 8px rgba(0,0,0,.06);
}
.card.alt {
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0,0,0,.06);
}

.pill {
  display:inline-flex; align-items:center; gap:.5rem;
  background: var(--brand-500);
  color: white !important;
  padding:.4rem .85rem; border-radius:999px; font-weight:700; font-size:.8rem;
  box-shadow: 0 2px 6px rgba(22,140,113,.15);
}

.grid-2 { display:grid; grid-template-columns:1fr 1fr; gap:22px; justify-items: center; }
.grid-3 { display:grid; grid-template-columns:repeat(3,1fr); gap:18px; justify-items: center; }

.kpi {
  background: #ffffff;
  border-radius:12px;
  padding:14px 16px;
  color:var(--text-soft);
  box-shadow: 0 2px 6px rgba(0,0,0,.06);
}
.kpi b { color: var(--brand-600); }

/* ---- Tableaux ---- */
table{
  width:100%; border-collapse:separate; border-spacing:0; overflow:hidden;
  background:#fff; color:var(--text-soft); border-radius:12px;
  box-shadow: 0 2px 8px rgba(0,0,0,.06);
}
th,td{ padding:12px 16px; font-size: 0.95rem; }
thead th{
  background: var(--brand-500);
  color: white;
  text-align:left;
  font-weight:700;
}
tbody tr:not(:last-child) td { border-bottom:1px solid #f0f0f0; }

/* ---- Boutons ---- */
.btn {
  display:inline-block;
  background: var(--brand-500);
  color:white !important;
  text-decoration:none;
  padding:10px 20px;
  border-radius:8px;
  font-weight:700;
  font-size: 0.95rem;
  letter-spacing:.2px;
  box-shadow: 0 4px 12px rgba(22,140,113,.25);
  transition: all 0.2s ease;
}
.btn:hover {
  background: var(--brand-600);
  box-shadow: 0 6px 16px rgba(22,140,113,.3);
}
.btn.secondary {
  background: white;
  color:var(--brand-600) !important;
  box-shadow: 0 2px 8px rgba(0,0,0,.08);
}
.btn.secondary:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,.12);
}

/* ---- Logos ---- */
.logo-row{ display:flex; gap:24px; align-items:center; flex-wrap:wrap; justify-content: center; }
.logo-row img{
  background: white;
  border-radius:12px;
  padding:20px;
  box-shadow:0 2px 8px rgba(0,0,0,.06);
  max-width: 180px;
  min-height: 90px;
  object-fit: contain;
  transition: all 0.3s ease;
}
.logo-row img:hover {
  transform: translateY(-2px);
  box-shadow:0 4px 12px rgba(0,0,0,.1);
}

/* ---- Encart titre page de couverture ---- */
.glass {
  background: white;
  border-radius: 16px;
  padding: 32px 40px;
  display: inline-block;
  box-shadow: 0 4px 16px rgba(0,0,0,.08);
}
</style>

<div class="glass" style="width:100%; max-width:900px">
  <h1 style="font-size:1.75rem; margin-bottom:8px">Proposition commerciale</h1>
  <h2>Compagnons-Bâtisseurs</h2>
</div>

<div style="height:16px"></div>

<div class="card">
  <p><b>Création d'un système d'information sur mesure</b></p>
  <div class="logo-row" style="margin-top:10px">
    <img src="https://static.wixstatic.com/media/513107_4949f92e885b46b2b8cfa717825386c5~mv2.png" alt="Logo Créapp-i" style="height: 120px; width: auto;">
    <img src="https://www.compagnonsbatisseurs.eu/assets/img/Logo_simple_C_H_web.png" alt="Logo Compagnons-Bâtisseurs" style="height: 120px; width: auto;">
  </div>
</div>

---

# Présentation de Créapp-i

<div class="grid-2">
  <div class="card">
    <div class="pill">À propos</div>
    <h2>Agence de développement sur mesure</h2>
    <p>Basée à La Réunion, Créapp-i transforme vos idées en <b>solutions digitales concrètes</b>, de la conception à la mise en œuvre.</p>
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
    <p>Digitaliser et centraliser la <b>gestion des chantiers</b>, fluidifier la communication <b>terrain ↔ administration</b>, assurer la <b>traçabilité</b> des interventions, devis, photos et documents, et réduire l'usage du papier pour un impact éco-responsable.</p>
  </div>
  <div class="card">
    <div class="pill">Bénéfices</div>
    <p>Un outil simple, moderne et collaboratif avec une synchronisation en temps réel et une adoption facilitée pour les utilisateurs non technophiles.</p>
  </div>
</div>

---

# Objectifs du projet

<div class="card" style="margin-bottom:16px; text-align:left">
  <div class="pill">🎯 Objectifs principaux</div>
  <p>Enregistrer directement toutes les informations d'un <b>projet de travaux</b> (visite, devis, photos, documents). Garantir un <b>partage fluide des données</b> entre terrain et administration. <b>Supprimer les processus papier</b> au profit d'une gestion numérique simple.</p>
</div>

<div class="grid-2">
  <div class="card" style="text-align:left">
    <div class="pill">👥 Objectifs utilisateurs</div>
    <p>Interface <b>intuitive et accessible</b> pour utilisateurs non technophiles. Centraliser les données pour améliorer la <b>communication entre équipes</b>.</p>
  </div>
  <div class="card" style="text-align:left">
    <div class="pill">⚙️ Objectifs techniques</div>
    <p>Solution <b>légère et maintenable</b>. <b>Synchronisation en temps réel</b> entre les applications web. <b>Accessibilité optimale</b> sur différents supports.</p>
  </div>
</div>

---

# Déroulement du projet (Partie 1)

<div class="grid-2">
  <div class="card">
    <div class="pill">Phase 1</div>
    <h2>Analyse & Spécifications</h2>
    <ul>
      <li>Recueil des besoins (animateurs, administratifs)</li>
      <li>Cas d'utilisation MVP (visites, devis, interventions, documents, photos)</li>
      <li>Cahier des charges & priorisation</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Phase 2</div>
    <h2>Conception</h2>
    <ul>
      <li>Maquettes & parcours utilisateurs</li>
      <li>Organisation des données pour gérer plusieurs structures en parallèle</li>
      <li>Règles de sécurité & stockage</li>
    </ul>
  </div>
</div>

---

# Déroulement du projet (Partie 2)

<div class="grid-2">
  <div class="card">
    <div class="pill">Phase 3</div>
    <h2>Développement</h2>
    <ul>
      <li>Apps Web Animateurs & Administratifs</li>
      <li>Modules : chantiers, devis, diagnostics, interventions, documents, statistiques</li>
      <li>Tests fonctionnels</li>
    </ul>
  </div>
  <div class="card">
    <div class="pill">Phase 4</div>
    <h2>Mise en place & Formation</h2>
    <ul>
      <li>Déploiement production</li>
      <li>Formation des équipes Compagnons-Bâtisseurs</li>
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

# Devis forfaitaire

<div class="card" style="margin-bottom:14px; padding:24px">
  <div class="pill">Projet (forfait global)</div>
  <div style="margin-top:16px">
    <p style="font-size:1rem; margin:8px 0"><b>Montant total HT :</b> <span style="font-size:1.2rem; color:var(--brand-600)">15 600 €</span></p>
    <p style="font-size:1rem; margin:8px 0"><b>TVA (8,5 %) :</b> <span style="font-size:1.2rem">1 326 €</span></p>
    <p style="font-size:1.05rem; margin-top:12px"><b>Total TTC :</b> <span style="font-size:1.5rem; color:var(--brand-600); font-weight:800">16 326 €</span></p>
  </div>
</div>

<div class="grid-2">
  <div class="card" style="text-align:left">
    <div class="pill">✅ Inclus dans le forfait</div>
    <ul style="margin-top:10px; font-size:0.95rem; line-height:1.6">
      <li><b>Formation complète</b> des équipes</li>
      <li><b>Documentation</b> technique & fonctionnelle</li>
      <li><b>Support</b> post-livraison (1 mois)</li>
      <li><b>Mises en production</b></li>
    </ul>
  </div>
  <div class="card" style="text-align:left">
    <div class="pill">📋 Livrables</div>
    <ul style="margin-top:10px; font-size:0.95rem; line-height:1.6">
      <li>Application web <b>Animateurs</b></li>
      <li>Plateforme <b>Administrative</b></li>
      <li>Documentation technique</li>
    </ul>
  </div>
</div>

---

# Maintenance optionnelle

<div class="card" style="margin-bottom:14px; padding:24px">
  <div class="pill">Tarif maintenance</div>
  <div style="margin-top:16px">
    <p style="font-size:1rem; margin:8px 0"><b>HT :</b> <span style="font-size:1.2rem; color:var(--brand-600)">300 € / mois</span></p>
    <p style="font-size:1rem; margin:8px 0"><b>TVA (8,5 %) :</b> <span style="font-size:1.2rem">25,50 €</span></p>
    <p style="font-size:1.05rem; margin-top:12px"><b>Total TTC :</b> <span style="font-size:1.5rem; color:var(--brand-600); font-weight:800">325,50 € / mois</span></p>
  </div>
</div>

<div class="grid-2">
  <div class="card" style="text-align:left">
    <div class="pill">🔧 Rétablissement du service</div>
    <p style="margin-top:12px">Intervention prioritaire en cas d'incident avec diagnostic et correction rapides pour garantir la continuité de votre activité.</p>
  </div>
  <div class="card" style="text-align:left">
    <div class="pill">🔒 Sécurité & RGPD</div>
    <p style="margin-top:12px">Mises à jour régulières de sécurité et performance. Contrôles de conformité RGPD avec rapport périodique des actions effectuées.</p>
  </div>
</div>

---

# Contact

<div class="card">
  <div class="pill">Coordonnées</div>
  <p><b>Alexandre MAILLOT — Dirigeant Créapp-i</b></p>
  <p>📞 06 92 78 29 75 · 📧 alexandre.maillot@creapp-i.com</p>
  <p>🏢 26 chemin bateau, 97425 Les Avirons</p>
  <p>💼 SIRET : 951 325 943 00011 · 🌐 www.creapp-i.com</p>
</div>

---

# Authentification

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Authentification</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>me connecter</b> avec mon e-mail et mot de passe afin d'accéder à mes chantiers.</li>
    <li>En tant qu'<b>animateur</b>, je dois être <b>automatiquement associé</b> à ma structure afin de voir uniquement mes données.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>me déconnecter</b> afin de sécuriser ma session.</li>
  </ul>
</div>

<div class="card" style="text-align:left; margin-top:18px">
  <div class="pill">Administratif — Authentification</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>me connecter</b> avec mon e-mail et mot de passe afin d'accéder à mes dossiers.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>me déconnecter</b> pour sécuriser ma session.</li>
  </ul>
</div>

---

# Gestion des chantiers (Partie 1)

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Chantiers</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>voir la liste de mes chantiers</b> afin de suivre leur avancement.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>créer un nouveau chantier</b>.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>modifier un chantier existant</b> afin de corriger ou compléter ses informations.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>ajouter des documents au chantier</b> afin de centraliser les justificatifs.</li>
    <li>En tant que <b>système</b>, je dois <b>changer automatiquement le statut du chantier</b> afin de refléter son avancement réel.</li>
  </ul>
</div>

---

# Gestion des chantiers (Partie 2)

<div class="card" style="text-align:left">
  <div class="pill">Administratif — Chantiers</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>consulter les chantiers en détail</b> afin de vérifier les informations et documents.</li>
  </ul>
</div>

---

# Problèmes

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Problèmes</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>ajouter un problème avec une photo « avant »</b> afin de documenter la situation initiale.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>voir la liste complète des problèmes</b> afin de préparer les interventions.</li>
  </ul>
</div>

---

# Devis (1/2)

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Devis</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>créer un devis lié à un chantier</b> afin d'estimer le coût des travaux.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>ajouter, modifier et supprimer des articles</b> afin d'ajuster le contenu du devis.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>faire signer le devis sur tablette</b> afin d'obtenir la preuve d'accord du client.</li>
    <li>En tant que <b>système</b>, je dois <b>verrouiller le devis signé</b> afin de garantir son intégrité.</li>
  </ul>
</div>

---

# Devis (2/2)

<div class="card" style="text-align:left">
  <div class="pill">Administratif — Devis</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>ouvrir un devis</b> afin de vérifier son contenu.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>modifier un devis</b> afin de corriger ou ajuster les montants avant validation.</li>
    <li>En tant que <b>chef de travaux</b>, je dois pouvoir <b>valider ou rejeter un devis</b> afin d'autoriser ou refuser les travaux.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>créer une révision d'un devis signé</b> afin de produire une nouvelle version à re-signer.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>ajouter un commentaire de validation</b> afin d'informer l'animateur.</li>
    <li>En tant que <b>système</b>, je dois <b>verrouiller les devis signés, invalider les signatures en cas de révision, et archiver automatiquement les devis validés</b>.</li>
  </ul>
</div>

---

# Interventions

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Interventions</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>ajouter une intervention sur un chantier</b> afin de planifier une action terrain.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>accéder à la liste des problèmes à traiter depuis l'intervention</b> afin de les résoudre sur place.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>prendre une photo « après » pour un problème</b> afin de le marquer comme résolu.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>faire signer la fin des travaux</b> afin de valider l'intervention.</li>
  </ul>
</div>

---

# Visites

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Visites</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>planifier une visite client</b> afin de suivre l'évolution du chantier.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>saisir des notes de visite</b> afin de documenter l'échange.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>faire signer la visite si nécessaire</b> afin d'attester de la présence.</li>
  </ul>
</div>

---

# Calendrier

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Calendrier</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>voir le calendrier de mes interventions et visites</b> afin de planifier mon activité.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>ajouter une intervention ou une visite directement depuis le calendrier</b> afin de gagner du temps.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>ouvrir la fiche d'un chantier depuis un événement</b> afin d'accéder à ses détails.</li>
  </ul>
</div>

---

# Documents

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Documents</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>voir et télécharger les documents existants</b> afin de les consulter sur le terrain.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>supprimer un document</b> afin de maintenir la base à jour.</li>
  </ul>
</div>

<div class="card" style="text-align:left; margin-top:18px">
  <div class="pill">Administratif — Documents</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>voir et télécharger les documents d'un chantier</b> afin de contrôler leur conformité.</li>
    <li>En tant que <b>système</b>, je dois <b>classer automatiquement les documents par type et chantier</b>.</li>
  </ul>
</div>

---

# Ergonomie

<div class="card" style="text-align:left">
  <div class="pill">Animateur — Ergonomie</div>
  <ul>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>naviguer simplement entre les modules</b> afin de travailler efficacement sur le terrain.</li>
    <li>En tant qu'<b>animateur</b>, je dois pouvoir <b>recevoir des messages clairs en cas d'erreur ou de succès</b>.</li>
  </ul>
</div>

<div class="card" style="text-align:left; margin-top:18px">
  <div class="pill">Administratif — Ergonomie</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>naviguer rapidement entre les modules</b> afin d'analyser et valider efficacement.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>rechercher rapidement un chantier ou un devis</b> afin de gagner du temps.</li>
  </ul>
</div>

---

# Administration centrale

<div class="card" style="text-align:left">
  <div class="pill">Administrateur central</div>
  <ul>
    <li>En tant qu'<b>administrateur central</b>, je dois pouvoir <b>accéder à la vue consolidée des structures</b> afin de suivre leur activité.</li>
    <li>En tant qu'<b>administrateur central</b>, je dois pouvoir <b>ajouter ou désactiver une structure</b> afin de gérer le réseau national.</li>
  </ul>
</div>

---

# Gestion des utilisateurs

<div class="card" style="text-align:left">
  <div class="pill">Administratif — Utilisateurs</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>créer, modifier et supprimer des comptes</b> afin de gérer les accès.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>réinitialiser le mot de passe d'un utilisateur</b> afin de l'aider à se reconnecter.</li>
  </ul>
</div>

---

# Archivage & Traçabilité

<div class="card" style="text-align:left">
  <div class="pill">Administratif — Archivage</div>
  <ul>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>consulter les chantiers archivés</b> afin d'accéder aux dossiers clos.</li>
    <li>En tant qu'<b>administratif</b>, je dois pouvoir <b>rechercher un dossier archivé</b> afin de retrouver un document spécifique.</li>
    <li>En tant que <b>système</b>, je dois <b>archiver automatiquement les chantiers terminés</b> afin de garantir la conformité RGPD.</li>
  </ul>
</div>

<div class="card" style="text-align:left; margin-top:18px">
  <div class="pill">Système — Traçabilité</div>
  <ul>
    <li>En tant que <b>système</b>, je dois <b>journaliser chaque modification</b> pour assurer la traçabilité.</li>
  </ul>
</div>
