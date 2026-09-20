
# Site vitrine Professionnel - Volny Moget

Ce dépôt contient le code source de mon site vitrine en ligne, accessible à l'adresse : **[moget.online](https://moget.online)**.

---

## 🇫🇷 Version Française

### 📌 à propos du projet
Ce site web est mon site vitrine professionnel.
Il présente mon parcours d'ancien Officier Marinier, mes compétences en gestion de projet Agile, ainsi que mon expertise naissante en numérique et Intelligence Artificielle.
Il sert également de point d'entrée pour mes services proposés.
Conçu pour être performant et sécurisé, il me sert également de terrain d'application pour les bonnes pratiques de développement web et de conformité (RGPD/Cybersécurité).

### 🛠️ Technologies utilisées
*   **Structure :** HTML5 sémantique pour une accessibilité et un SEO optimisés.
*   **Style :** CSS3 responsive (Mobile-First) avec une mise en page moderne (Flexbox/Grid).
*   **Dynamisme :** JavaScript natif (Vanilla JS) pour les interactions de l'interface (menu burger).
*   **Formulaire :** Intégration de l'API Formspree pour un traitement sécurisé des contacts sans backend lourd .

### 🛡️ Sécurité et Conformité
Le projet intègre une architecture de sécurité moderne validée par les standards de *Mozilla Observatory* :
*   **Content Security Policy (CSP) :** Restriction stricte des sources de scripts et de formulaires via les en-têtes HTTP.
*   **Fichier `.htaccess` personnalisé :** Activation du HSTS, redirection HTTPS forcée, en-têtes contre le clickjacking (`X-Frame-Options`) et blocage du listage de dossiers (`Options -Indexes`) pour protéger les documents du dossier `assets/`  .
*   **Conformité RGPD :** Validation CNIL intégrée avec recueil de consentement explicite sur le formulaire .

### 📂 Structure du projet
/
├── index.html                  (Page d'accueil ci-dessus)
├── parcours.html               (Page Mon parcours / Compétences / Diplômes)
├── consultant-pme.html         (Page Conseil sociétés)
├── coaching-personnel.html     (Page Coaching pour les particuliers : Gestion budget, stress, temps)
├── chef-projet.html            (Page Chef de projet Odoo services, redirigé vers la société Sudokeys)
├── formation.html              (Page Formation inidividuelle, et/ou collective numérique, bienveillance, bien être...)
├── contact.html                (Formulaire de contact)
├── connexion-nas.html          (Portail de connexion NAS apprenants ESDIC)
├── mentions-legales.html
├── contact.php
├── security.md
├── readme.md
├── style.css                   (Fichier CSS unique)
└── script.js                   (Fichier JS unique)
