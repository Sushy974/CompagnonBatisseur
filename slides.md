---
# Thème & métadonnées
theme: default
title: "Proposition commerciale — Compagnons Bâtisseurs"
presenter: "Créapp-i — Alexandre Maillot"
author: "Créapp-i"
colorSchema: light
highlighter: shiki
aspectRatio: 16/9
fonts:
  sans: Inter
  mono: Fira Code
layout: cover
# Couleurs inspirées de creapp-i.com (bleu nuit + cyan)
# NB: on les surcharge via <style> ci-dessous
---

<style>
/* ---------- Palette marque inspirée de creapp-i.com ---------- */
/* Bleu nuit (fond), cyan (accent), bleu moyen (secondaire) */
:root {
  --brand-bg:rgb(18, 42, 66);     /* bleu nuit */
  --brand-primary: #112a46;/* bleu profond */
  --brand-secondary: #1b3b5a; /* bleu moyen */
  --brand-accent: #06b6d4; /* cyan */
  --brand-accent-2: #38bdf8; /* sky */
  --brand-text: #e6f1ff;   /* blanc bleuté */
  --brand-muted: #9fb3c8;  /* gris bleuté */
}

/* ---------- Habillage global Slidev ---------- */
.slidev-layout, .slidev-page {
  background: radial-gradient(1200px 800px at 80% 10%, var(--brand-secondary) 0%, var(--brand-bg) 60%) !important;
  color: var(--brand-text);
}

h1, h2, h3 { letter-spacing: .2px; }
a { color: var(--brand-accent); text-decoration: none; border-bottom: 1px solid color-mix(in srgb, var(--brand-accent), transparent 70%); }
strong { color: white; }

/* Cards */
.card {
  background: color-mix(in srgb, var(--brand-primary) 85%, black 15%);
  border: 1px solid color-mix(in srgb, var(--brand-accent), transparent 80%);
  border-radius: 18px;
  padding: 18px 20px;
  box-shadow: 0 8px 24px rgba(0,0,0,.25);
}

/* Badges */
.badge {
  display: inline-block;
  padding: 6px 10px;
  border-radius: 999px;
  font-size: .8rem;
  color: #002b36;
  background: var(--brand-accent);
  margin-right: 8px;
}

/* Titres accentués */
h1 .accent, h2 .accent { color: var(--brand-accent); }

/* Listes plus aérées */
ul li { margin: 6px 0; }

/* Footer */
.footer {
  position: absolute; bottom: 16px; left: 24px;
  font-size: 12px; color: var(--brand-muted);
}
</style>

<!-- Couverture -->
# Proposition commerciale  
## <span class="accent">Compagnons Bâtisseurs</span>

Une solution d’information sur-mesure : simple, sécurisée, orientée terrain.

<div class="footer">Créapp-i — Agence de développement d’applications sur-mesure (La Réunion) — creapp-i.com</div>

---

layout: center
class: text-center

# Qui sommes-nous ?
### Créapp-i, agence de développement à La Réunion
<div class="card">

- Nous transformons vos idées en **solutions digitales concrètes**.
- Accompagnement **de la conception à la mise en production**.
- Approche **collaborative et agile**, focus **qualité** et **simplicité d’usage**.
</div>

Notes:
- Positionner la proposition: proximité, réactivité, livrables concrets.

---

# Notre équipe

<div class="card">

**Chef de projet**  
- **Alexandre MAILLOT** — Pilotage, cadrage fonctionnel, architecture

**Développeurs**  
- **Alexandre MAILLOT** — Backend / Firebase / Intégration  
- **Nathan CHATEAU** — Frontend Flutter, UI/UX

</div>

::: right
**Forces clés**  
- Expertise **Flutter Web** & **Firebase**  
- Culture **produit** & **terrain**  
- Sens du **design utile** (UX simple)
:::

---

# Enjeux & objectifs

- <span class="badge">Digitalisation</span> Remplacer les processus papier par des **flux 100 % numériques**  
- <span class="badge">Traçabilité</span> Dossiers **fiables**, **auditables**, conformes financeurs  
- <span class="badge">Simplicité</span> Outil **intuitif** pour profils non technophiles  
- <span class="badge">Collaboration</span> Synchronisation **temps réel** terrain ↔ administratif  
- <span class="badge">Sécurité</span> Conformité **RGPD**, cloisonnement multi-structures

Notes:
- Insister sur valeur opérationnelle: gain de temps et réduction erreurs.

---

# Portée fonctionnelle (vue synthétique)

::: columns
::: column
### Application **Animateurs**
- Authentification & rôles
- **Chantiers** (création, suivi)
- **Diagnostics** (photos avant/après)
- **Devis** (signature tablette, verrouillage)
- **Interventions & Visites**
- **Calendrier**, **Documents**, **Stats locales**
:::
::: column
### Application **Administrative**
- Tableau de bord global
- **Chantiers** (contrôle, archivage)
- **Devis** (révision/validation)
- **Documents** (complétude, conformité)
- **Supervision multi-structures**
- **Reporting** (PDF)
:::
:::

---

# Architecture (macro)

- **Frontend** : Flutter Web  
- **Backend/Data** : **Firestore** (multi-base par structure), **Storage** (fichiers)  
- **Automatisations** : **Cloud Functions** (TypeScript)  
- **API métier** : DartFrog (extensions spécifiques)  
- **Sécurité** : Auth Firebase + *custom claims* `structureId`  
- **CI/CD** : CodeMagic — *staging* & *prod*

> Objectif : **robustesse**, **scalabilité**, **maintenance simplifiée**.

---

# Roadmap & livrables

| Phase | Intitulé | Durée | Livrables |
|---|---|---:|---|
| 1 | **Conception & cadrage** | **3 j** | Ateliers, parcours, maquettes |
| 2 | **Développement** | **2 mois** | Modules Animateurs & Admin, sécurité, API |
| 3 | **Tests & validation** | **1 mois** | Recette, corrections, doc utilisateur |
| 4 | **Mise en production** | **1 sem.** | Déploiement, formation, transfert |

<div class="footer">Planning prévisionnel — ajustable selon retours de recette</div>

---

# Chiffrage (estimatif)

| Poste | Volume | TJM HT | Sous-total |
|---|---:|---:|---:|
| **Conception & maquettage** | 3 j | 600 € | 1 800 € |
| **Développement complet** | 40 j | 600 € | 24 000 € |
| **Tests & MEP** | 10 j | 600 € | 6 000 € |
|  |  |  | **31 800 € HT** |

> Inclus : documentation, recette utilisateur, formation.

---

# Maintenance & garanties

**Forfait gestion mensuelle : 500 € HT**

- **Garantie disponibilité** : rétablissement prioritaire en cas de panne  
- **Sécurité & RGPD** : mises à jour régulières, contrôles de performance  
- **Rapport** des actions & optimisations (trimestriel)  
- Évolutions **sur devis**

Notes:
- Clarifier périmètre forfait vs. évolutions.

---

# Facteurs de succès

- **Simplicité d’usage** (UX terrain first)  
- **Adoption accompagnée** (formation, support)  
- **Itérations courtes** (retours intégrés rapidement)  
- **Mesure** (indicateurs d’activité & qualité)

---

layout: center
class: text-center

# Pourquoi Créapp-i ?
### Expertise **Flutter/Firebase**, approche **produit**, exécution **agile**

---

# Prochaines étapes

1. Validation de la proposition  
2. Ateliers de conception & maquettage  
3. Lancement du développement  
4. Recette, formation, mise en service

> Nous sommes prêts à démarrer. ✨

---

# Contacts

**Créapp-i — Alexandre MAILLOT**  
📞 06 92 78 29 75  
✉️ alexandre.maillot@creapp-i.com  
📍 26 chemin Bateau — 97425 Les Avirons  
SIRET **951 325 943 00011** — TVA **FR94951325943**  
🌐 https://www.creapp-i.com
