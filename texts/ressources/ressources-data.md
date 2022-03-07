---
type: ressources

options:
  title-key: title
  illustration-key: cover
  columns-size: full
  has-readmore: true

  list: true
  shuffle: true

  card-modal: true
  card-modal-config:
    full-screen: true
    column-left: false
    column-right: true
    infos-texts: 
      - author

  tags-keys: 
    - key: medium
      color: primary
    - key: topics
      color: info

  filters: 
    activate: true
    items: 
      - name: medium
      - name: topics

items:
  - file: ./texts/ressources/items/book-Menger-Le_travail_createur.md
  - file: ./texts/ressources/items/book-Dardot-Laval-Commun.md

dict:
  author:
    fr: Auteur
    en: Author
  medium:
    fr: Type de ressource
    en: Ressource type
  topics:
    fr: tags
    en: tags
---
