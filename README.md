# 📄 CV en ligne — Bootcamp Web Epitech

> Mini-projet réalisé lors du **Bootcamp Web (Day 04-05)** à **Epitech Paris** : concevoir et développer un CV en ligne, interactif, responsive et hébergeable.

---

## 🎯 Objectif

Transformer un CV classique en une **page web** qui met en valeur mon parcours, mes compétences et ma personnalité, destinée à des recruteurs, dans le cadre de ma recherche d'**alternance en cybersécurité (SOC Analyst)** à partir de janvier 2027.

---

## ✨ Fonctionnalités

| Fonctionnalité                  | Description                                                                                         |
| ------------------------------- | --------------------------------------------------------------------------------------------------- |
| 🎨 **Thème terminal**           | Fond sombre, police JetBrains Mono, accent vert, curseur qui clignote, titres préfixés par `##`     |
| 📱 **Responsive**               | Tailles de texte fluides (`clamp()`), grilles qui s'adaptent (`auto-fit`), media queries sous 768px |
| 🍔 **Menu burger**              | Sur mobile, menu en popover HTML (sans JavaScript), le burger se transforme en croix                |
| 🌀 **Animations & transitions** | Curseur animé, soulignement de la nav, survols des cartes, boutons et liens                         |
| 🗂️ **Frise chronologique**      | Formation et pratique cybersécurité présentées sous forme de timeline                               |
| ✉️ **Formulaire de contact**    | Envoi de mail via [Formspree](https://formspree.io/), validation des champs, anti-spam              |
| ♿ **Accessibilité**            | HTML sémantique, contour visible au clavier, respect de `prefers-reduced-motion`                    |

---

## 🛠️ Technologies

- **HTML5** : structure sémantique, attribut `popover`
- **CSS3** : variables, Flexbox / Grid, `clamp()`, animations, media queries, nesting
- **Formspree** : envoi du formulaire de contact sans back-end

Aucun framework ni JavaScript.

---

## 📁 Structure du projet

```
.
├── index.html                  # Page du CV
├── assets/
│   ├── images/                 # Avatar pixel art + icônes GitHub / LinkedIn
│   └── styles/
│       ├── abstracts/          # Variables (couleurs, tailles, espacements) et keyframes
│       ├── base/               # Reset, styles globaux, typographie
│       ├── layout/             # Mise en page, header, footer
│       ├── components/         # Éléments réutilisables : carte, étiquettes, frise
│       └── sections/           # Styles propres à une section (À propos, Compétences)
├── docs/
│   └── digitalResume.pdf       # Sujet de l'exercice
└── README.md
```

Les classes CSS suivent la convention **BEM** (`bloc__element--modificateur`).

---

## 🚀 Lancer le projet en local

```bash
# Cloner le dépôt
git clone https://github.com/Drack0r/T-WEB-500-PAR-5-1-webd04-4.git
cd T-WEB-500-PAR-5-1-webd04-4

# Ouvrir directement dans le navigateur
xdg-open index.html

# ou lancer un petit serveur local
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

Aucune dépendance ni étape de build n'est nécessaire.

---

## ✅ Contraintes du sujet

- [x] Code propre et bien structuré
- [x] Séparation claire entre HTML et CSS
- [x] HTML valide (W3C Validator sans erreur)
- [x] Effets : transitions et/ou animations
- [x] Éléments interactifs
- [x] Formulaire de contact
- [x] Design responsive
- [x] Design attrayant

---

## 👤 Auteur

**Antonin Chevolleau** — Étudiant en Pre-MSc à Epitech Paris

- 💼 LinkedIn : [antonin-chevolleau](https://www.linkedin.com/in/antonin-chevolleau)
- 🐙 GitHub : [@Drack0r](https://github.com/Drack0r)
- ✉️ Contact : via le formulaire du site

---

<p align="center">Projet réalisé dans le cadre du Bootcamp Web — Epitech 2026</p>
