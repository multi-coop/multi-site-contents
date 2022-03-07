---
type: network

options:
  title-key: title
  illustration-key: logo
  columns-size: one-third
  has-readmore: false

  list: true
  shuffle: true

  card-modal: false
  card-modal-config:
    full-screen: true
    column-left: false
    column-right: true
    infos-texts: 
      - type

  miniature-keys: 
    - type
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
  - file: ./texts/network/items/codeurs-en-liberte.md
  - file: ./texts/network/items/data-for-good.md
  - file: ./texts/network/items/eig.md
  - file: ./texts/network/items/fairness.md
  - file: ./texts/network/items/latitudes.md
  - file: ./texts/network/items/mednum.md
  - file: ./texts/network/items/urscop.md
  - file: ./texts/network/items/usages-communs.md

dict:
  type:
    fr: Type de structure
    en: Structure type
  tags:
    fr: tags
    en: tags
---
