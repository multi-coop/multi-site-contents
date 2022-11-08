---
name: Datami

clients: 
  - ANCT
  - Fabmob
  - Open Data France

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

    Datami possède différentes fonctionnalités visant à simplifier l'édition de données et leur enrichissement :

    - visualisation sous forme de tableau, de fiches, de cartographie ou data-visualisations
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


technos: [ Javascript, Vue.js, Bulma, Buefy, Git, Maplibre, ApexCharts ]

refs:
  - name: site
    link: https://datami.multi.coop/
    fr: Site vitrine de Datami

code:
  - name: app
    link: https://gitlab.com/multi-coop/datami-project/datami
    fr: Code source de l'application 
  - name: docs
    link: https://datami-docs.multi.coop/
    fr: Documentation
  - name: deploy
    link: https://datami-widget.multi.coop/
    fr: Déploiement

images:
  - ./images/references/datami/datami-landing.png
  - ./images/references/datami/multifiles-preview-01.png
  - ./images/references/datami/gitfile-md-preview-01.png
  - ./images/references/datami/gitfile-csv-preview-01.png
  - ./images/references/datami/gitfile-json-preview-01.png
  - ./images/references/datami/explowiki-preview-01.png


---
