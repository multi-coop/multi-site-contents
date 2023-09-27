---
type: network

options:
  title-key: title
  subtitle-key: subtitle
  illustration-key: logo
  illustration-height: 50px
  columns-size: full
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

  tags-keys: 
    - key: type
      color: light
    - key: tags
      color: info

  filters: 
    activate: true
    items: 
      - name: type
      - name: tags

items:
  - file: ./texts/network/items/cgscop.md #
  - file: ./texts/network/items/urscop-idf.md
  - file: ./texts/network/items/numeum.md #
  - file: ./texts/network/items/systematic.md #
  - file: ./texts/network/items/april.md
  - file: ./texts/network/items/cooptech.md
  - file: ./texts/network/items/assemblee-virtuelle.md #
  - file: ./texts/network/items/mednum.md
  - file: ./texts/network/items/federation-pros-osm.md
  - file: ./texts/network/items/social-good-accelerator.md

dict:
  type:
    fr: Type de structure
    en: Structure type
  tags:
    fr: tags
    en: tags
---
