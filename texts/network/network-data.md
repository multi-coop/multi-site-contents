---
type: network

options:
  title-key: title
  columns-size: one-third
  has-readmore: false

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
  - file: ./texts/network/items/mednum.md

dict:
  type:
    fr: Type de structure
    en: Structure type
  tags:
    fr: tags
    en: tags
---
