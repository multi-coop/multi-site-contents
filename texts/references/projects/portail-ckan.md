---
name: Portail de données interne CKAN

clients: 
  - Etablissement public

period: 
  fr: automne-hiver 2022
  en: fall-winter 2022

type:
  fr:
    - ouverture-des-données
    - open-data
    - ckan
    - portail-de-données
  en:
    - open-data
    - ckan
    - data-portal

description:
  fr: |
    Portail de données interne : un projet fédérateur à partir d’un projet urbain
    
    # Résumé du projet
    
    Multi a accompagné un acteur majeur de l'aménagement public en Île-de-France 
    dans la mise en place d’un portail de données interne basé sur CKAN. La plateforme 
    vise à faciliter le partage de données de projet et de référence, en interne 
    comme avec les partenaires extérieurs.
    
    ## Problème
    
    En l'absence d'une stratégie claire et d’un outil adapté, l’établissement 
    rencontrait des difficultés à centraliser et diffuser les données produites dans 
    le cadre des projets. Cela engendrait des doublons, des conflits de versions et 
    une faible capitalisation des connaissances.
    
    ## Besoin
    
    Le client souhaitait une solution de catalogage et de partage de données – 
    notamment spatiales – accessible à des utilisateurs non techniques, et permettant 
    une gestion fine des droits selon les profils (internes/externes).
    
    ## Solution
    
    Multi a déployé une plateforme CKAN personnalisée, hébergée en France, et a 
    accompagné l’organisation dans la structuration de ses données, la formation 
    des utilisateurs et le support à l’adoption de l’outil.

    # Le projet dans le détail

    ## Contexte
    
    Bien que de taille modeste (environ 50 collaborateurs), cet établissement public 
    travaille avec de nombreux partenaires, clients et prestataires. La construction 
    d'une vision partagée du territoire repose sur l'accès à des données fiables, 
    homogènes et bien documentées. L’ambition portée par la plateforme était de 
    favoriser la coopération autour d’une base commune d’information.
    
    ## Situation
    
    Dans le cadre d’un projet portant sur l’étude de la pollution d’un secteur 
    d’aménagement, l’établissement a été missionné pour rassembler et structurer 
    un grand nombre de données hétérogènes. Ce projet a été choisi comme point de 
    départ pour initier une démarche plus large de gestion et de mutualisation 
    des données.
    
    ## Critères
    
    La solution recherchée devait répondre à plusieurs exigences :

        • Permettre le partage de données en interne comme en externe,
        • Offrir un contrôle fin des droits d’accès et de modification selon les utilisateurs ou groupes,
        • Être accessible à des utilisateurs non techniques
    
    Concernant l’infrastructure, la solution devait :
    
        • Être hébergée et maintenue sur des serveurs situés en France,
        • Limiter son emprunte environnementale .

    ## Solution mise en œuvre
    
    Multi a assuré l’intégration et le déploiement d’un portail CKAN configuré 
    selon les besoins métier du client. L’intervention a couvert :

        • La personnalisation du schéma de métadonnées,
        • La définition fine des rôles et permissions,
        • L’hébergement de la solution sur une infrastructure française, éco-responsable (ISO 14001 / ISO 50001) et conforme au RGPD,
        • La rédaction d’un manuel d’usage adapté aux cas concrets de l’organisation,
        • La formation des équipes internes,
        • Un support technique dédié pour les utilisateurs partenaires.
  en: |
      # Project Summary

      Multi supported a major public planning stakeholder in the Île-de-France 
      region in implementing an internal data portal based on CKAN. The platform 
      is designed to facilitate the sharing of project and reference data, both 
      internally and with external partners.
      
      ## Problem
      
      In the absence of a clear strategy and suitable tools, the organization 
      struggled to centralize and disseminate data produced during projects. 
      This led to duplication, version conflicts, and poor knowledge capitalization.
      
      ## Need
      
      The client was looking for a data cataloging and sharing solution — 
      particularly for spatial data — that would be accessible to non-technical 
      users and allow fine-grained permission management based on user profiles (internal/external).
      
      ## Solution
      
      Multi deployed a customized CKAN platform, hosted in France, and 
      supported the organization in structuring its data, training users, 
      and facilitating adoption of the tool.

      
      # Project Details
      
      ## Context
      
      Although modest in size (around 50 staff members), this public institution 
      collaborates with numerous partners, clients, and service providers. Building 
      a shared understanding of the territory depends on access to reliable, consistent, 
      and well-documented data. The ambition of the platform was to foster collaboration 
      around a common information base.
      
      ## Situation
      
      As part of a project to study pollution in a development area, the institution was 
      tasked with gathering and organizing a large volume of heterogeneous data. This 
      initiative was chosen as a starting point to launch a broader data management 
      and sharing strategy.
      
      ## Requirements
      
      The desired solution had to meet several key requirements:
      
          • Enable data sharing with both internal and external users,
          • Provide fine-grained access and editing rights by user or group,
          • Be accessible to non-technical users.
      
      As for infrastructure, the solution needed to:
      
          • Be hosted and maintained on servers located in France,
          • Minimize its environmental footprint.
      
      ## Implemented Solution
      
      Multi handled the integration and deployment of a CKAN portal tailored to 
      the client’s business needs. The scope of the work included:
          • Customizing the metadata schema,
          • Defining roles and permissions in detail,
          • Hosting the solution on an eco-responsible (ISO 14001 / ISO 50001), GDPR-compliant French infrastructure,
          • Writing a user guide tailored to the organization’s real-world use cases,
          • Training internal teams,
          • Providing dedicated technical support for partner users.

approach:
  fr: 
    - agile
    - ouverture
    - co-construction

resources:
  fr: 
    - 1 consultant
    - 1 devops
  en: 
    - 1 consultant
    - 1 devops

technos: [ CKAN, Docker, PostGIS ]

refs:
  - name: CKAN - The world's leading open-source data portal platform
    link: https://ckan.org/
    fr: CKAN

images:
  - ./images/references/portail-ckan/portail-ckan-01.png
  - ./images/references/portail-ckan/portail-ckan-02.png
  - ./images/references/portail-ckan/portail-ckan-03.png

---
