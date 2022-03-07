---
type: ressources

options:
  title-key: title
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

  miniature-keys: 
    - author
    - tags

  tags-keys: 
    - key: type
      color: primary
    - key: tags
      color: info

  filters: 
    activate: true
    items: 
      - name: type
      - name: tags

items:
  - file: ./texts/ressources/items/book-PM-Menger-Le_travail_createur.md

dict:
  author:
    fr: Auteur
    en: Author
  type:
    fr: Type de ressource
    en: Ressource type
  tags:
    fr: tags
    en: tags
---
