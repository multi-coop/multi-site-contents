---
title: Une stratégie R&D pour multi ? 
tags: [ multi, R&D ]
created: 10/01/2021
author: Julien Paris
---

En s'inspirant de la posture d' "éditeur" de logiciel, de quelle manière poser les bases d'une stratégie/méthodo lors de chaque nouveau projet ? Quel type de checklist / canevas d'analyse utiliser pour avoir une cohérence de projet en projet ? Comment s'assurer un peu contre le *bus factor* ? 


# Vers une stratégie de R&D globale

**Note** : Ceci est un **draft**, une sorte d'endroit où on peut commencer à réfléchir sur l'offre de service de la coopérative. C'est pas parfait donc n'hésitez pas à ajouter vos réactions / doutes / commentaires... 


## Pourquoi cette réflexion ?

> Julien : le 09/11/2021
>
>  Mon souci au départ est qu'on va se retrouver à suivre et développer plein de projets différents, dans plein de temporalités différentes, avec des équipes elles aussi différentes... si on part ainsi sans y réfléchir on va se retrouver avec plein de développements qui n'ont rien à voir les uns avec les autres, et surtout on aura rapidement rien à apprendre les uns des autres au sein de la coopérative... 

La problématique que je cherche à poser se décompose ainsi : 

- Comment rendre notre **offre de service claire et cohérente** ?
- Quelle(s) ligne(s) suivre pour garder **une cohérence dans les développements** ?
- Comment **capitaliser sur les développements** afin d'avoir des propositions de plus en plus convaincantes pour les clients,  perdre moins de temps à chaque fois qu'on a un nouveau projet facturé ou à facturer, et permettre à d'autres membres de la coopérative de pouvoir contribuer et s'entraider ?

En s'inspirant de la posture d' "éditeur" de logiciel, de quelle manière poser les bases d'une stratégie/méthodo lors de chaque nouveau projet ? Quel type de *checklist* / canevas d'analyse utiliser pour avoir une cohérence de projet en projet ? Comment s'assurer un peu contre le *bus factor* ? 

-----

_Proposition à *challenger*_ : 

## Une "ligne éditoriale" pour des briques logicielles (ou méthodo design) libres

- quel que soit l'outil/produit il doit être **divisible en modules interopérables** / utilisables avec un ou plusieurs des outils/produits qu'on a ou qu'on sera appelé à développer ;
- les **langages utilisés doivent pouvoir l'être par la majorité des devs**, pas de trucs trop exotiques pour assurer le passage de relais : python, js, docker, doc en français/anglais... ;
- **le socle admin sys** doit être mutualisé au max ;
- on inclut systématiquement une **réflexion sur l'XP / UX** ;
- **pas de dev sans designer** ;
- pas de produit sans **une équipe d'au moins 2 personnes** côté tech ;
- *No fork* / ***no forking way***, on cherche à généraliser le problème ;
- **pas de produit sans une stratégie** de communication, une stratégie commerciale autour du produit, et une stratégie de pérennisation ;
- **on se forme / on échange** sur tous les outils / micro-produits réalisés par la coopérative ;
- on investit dans **la documentation** ;




## Des "collections" de méso/micro-produits interopérables

- collection "**basics**" : gestion d'utilisateurs et de mots de passe, gestion ds groupes, proxies pour mailing, ...
- collection "**data**" : outils de backend + BDD de gestion de données génériques ou semi-spécialisées (données tabulaires, séries temporelle, ...) + gestion en frontend (datapatch, spreadsheep, baserow...)
- collection "**dataviz**" :  web components front de  dataviz se branchant à des micro-produits "data" ou "transformateurs"
- collection "**connecteurs**" :  interfaces entre des micro-produits "data" et des API / services externes
- collection "**transformateurs**" : intermédiaires entre des micro-produits data  et dataviz, calcul d'indicateurs (agrégation, …)
- collection "**vitrines**" : solutions pour la partie statique de sites et pas perdre de temps sur ça, voire CMS, pouvant accueillir des micro-produits front : basics, socials, dataviz...
- collection "**socials**" : outils de chat / de commentaires / de temps réel / ...
- collection "**sécurité**" : authentification / pseudonimisatiion...


----
## "Produits" déjà développés (dont on possède un bon savoir-faire)

- slides [ici](https://nextcloud.jailbreak.paris/s/AErLTbensMCFLoc)

Produits phares : 
- [Apiviz](https://www.multi.coop/references?item=.%2Ftexts%2Freferences%2Fprojects%2Fapiviz.md)
- [Validata](https://www.multi.coop/references?item=.%2Ftexts%2Freferences%2Fprojects%2Fvalidata.md)
- [Data patch](https://www.multi.coop/references?item=.%2Ftexts%2Freferences%2Fprojects%2Fdata-patch.md)
- Vitrine
- [Odamap](https://www.multi.coop/references?item=.%2Ftexts%2Freferences%2Fprojects%2Faides-entreprises.md)
- ...
