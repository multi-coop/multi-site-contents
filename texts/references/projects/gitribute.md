---
name: Gitribute

clients: 
  - Fabmob
  - Open Data France
  - ANCT

period: 
  fr: depuis 2022 (développement continu)

type:
  fr:
    - widget
    - générique 
    - open-data

description:
  fr: |
    Outil générique de type widget, permettant de visualiser et d'éditer des données hébeergées sur Github ou Gitlab, voire sur un mediawiki.

    Gitribute possède différentes fonctionnalités visant à simplifier l'édition de données et leur enrichissement :

    - visualisation sous forme de tableau ou de tuiles
    - visualisation des différences entre la version originale et la version éditée par l'utilisateur
    - recherche par filtres ou en fulltext
    - import / export des données
    - consolidation de données par requête à des APIs externes
    - appliquer un schéma de données sur des données de type tableur
    - bouton pour copier/coller facilement le bloc html du widget
    - parcours simplifié permettant de créer une merge request
    - injection de données externes (référentiels, clé étrangères)

approach:
  fr: 
    - 
    - outil générique de visualisation et d'édition de données
    - widget intégrable dans tout site web
    - accent mis sur la simplicité d'utilisation et l'UX 
    - responsive

resources:
  fr: 
    - 1 développeur fullstack lead 
    - 1 développeur fullstack junior 


technos: [ Javascript, Vue.js, Bulma, Buefy, Git ]

refs:
  - name: Open Data France
    link: hhttps://demo-odf-data-observatoire.netlify.app/
    fr: Visualisation des données de l'observatoire de l'Open Data d'OpenDataFrance
  - name: Fabmob
    link: https://demo-explowiki.netlify.app/
    fr: Visualisation des projets du site mediawiki de la Fabmob

code:
  - name: app
    link: https://gitlab.com/multi-coop/gitribute
    fr: frontend 
  - name: docs
    link: https://gitribute-docs.multi.coop/
    fr: frontend
  - name: deploy
    link: https://gitribute.multi.coop/
    fr: Déploiement

images:
  - ./images/references/gitribute/multifiles-preview-01.png
  - ./images/references/gitribute/gitfile-md-preview-01.png
  - ./images/references/gitribute/gitfile-csv-preview-01.png
  - ./images/references/gitribute/gitfile-json-preview-01.png
  - ./images/references/gitribute/explowiki-preview-01.png


---
