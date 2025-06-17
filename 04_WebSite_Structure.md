# Structure d'un site Web

## Structure typique d'un projet Web 
```
mon-projet/
│
├── public/             # Fichiers accessibles publiquement (HTML, CSS, JS, images)
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── img/
│
├── src/                # Code source (backend, logique métier)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── utils/
│
├── tests/              # Tests unitaires ou d’intégration
│
├── config/             # Fichiers de configuration (ex: base de données)
│
├── node_modules/       # Modules Node (ne pas versionner)
│
├── .gitignore          # Fichiers/dossiers à ignorer par Git
├── package.json        # Dépendances et scripts
└── README.md           # Documentation
```
## Structure simple pour un projet Web

```
mon-projet/
│
├── index.html         # Page principale
├── style.css          # Feuille de style CSS
├── script.js          # Script JavaScript (facultatif)
├── images/            # Dossier pour les images
│   └── logo.png
├── .gitignore          # Fichiers/dossiers à ignorer par Git
└── README.md          # Documentation simple (facultatif)

```
## Fichiers courants à la racine d'un site web ou projet

| **Fichier**         | **But / Description**                                    |
|---------------------|----------------------------------------------------------|
| `robots.txt`        | Indique aux moteurs de recherche quelles pages indexer ou non |
| `sitemap.xml`       | Liste toutes les URLs du site pour aider le référencement (SEO) |
| `.htaccess`         | Fichier de configuration pour serveurs Apache (redirections, sécurité, etc.) |
| `favicon.ico`       | Icône du site affichée dans l’onglet du navigateur      |
| `manifest.json`     | Fichier de configuration pour les Progressive Web Apps (PWA) |
| `humans.txt`        | Informations sur les développeurs et créateurs du site (facultatif) |
| `.gitignore`        | Indique à Git quels fichiers/dossiers ne pas versionner  |
| `README.md`         | Documentation du projet, souvent en Markdown             |
| `LICENSE`           | Licence du projet (ex: MIT, GPL)                         |
| `CONTRIBUTING.md`   | Guide pour contribuer au projet                           |

---