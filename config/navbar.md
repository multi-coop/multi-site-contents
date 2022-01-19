---
background-color: white
logo-left: ./images/logos/logo-multi-003.png
fixed-top: true

buttons-left-centered: true

buttons-left: 

  - name: who-are-we 
    # link: /who-are-we
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Qui sommes-nous
      en: Who are we
    submenu: 
      # - name: manifesto
      #   link: /manifesto
      #   component: simpleLink
      #   label: 
      #     fr: Manifeste
      #     en: Manifesto
      - name: what-we-do
        link: /what-we-do
        component: simpleLink
        label: 
          fr: La coopérative
          en: The cooprative
      - name: origin
        link: /origin
        component: simpleLink
        label: 
          fr: Historique
          en: Origin
      - name: team
        link: /team
        component: simpleLink
        label: 
          fr: Equipe
          en: Team

  - name: offer 
    # link: /offer
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Offre de services
      en: Services
    submenu: 
      - name: offer
        link: /offer
        component: simpleLink
        label: 
          fr: Présentation
          en: Presentation
      # - name: dev
      #   link: /dev
      #   component: simpleLink
      #   label: 
      #     fr: Développement
      #     en: Development
      # - name: data
      #   link: /data
      #   component: simpleLink
      #   label: 
      #     fr: Data & algos
      #     en: Data & algos
      # - name: design
      #   link: /design
      #   component: simpleLink
      #   label: 
      #     fr: Design
      #     en: Design
      # - name: audit
      #   link: /audit
      #   component: simpleLink
      #   label: 
      #     fr: Conseil
      #     en: Audit
      - name: references
        link: /references
        component: simpleLink
        label: 
          fr: Références
          en: References
  
  - name: contact 
    # link: /contact
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Contact
      en: Contact
    submenu: 
      - name: infos
        link: /infos
        component: simpleLink
        label: 
          fr: Infos
          en: Infos
      - name: contribute
        link: /contribute
        component: simpleLink
        label: 
          fr: Contribuer
          en: Contribute
      # - name: legal
      #   link: /legal
      #   component: simpleLink
      #   label: 
      #     fr: Mentions légales
      #     en: Legal

buttons-right: 

  - name: recruit 
    # link: /recruit
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Jobs
      en: Jobs
    submenu: 
      - name: join
        link: /join
        component: simpleLink
        label: 
          fr: Pourquoi nous rejoindre
          en: Why join us
      - name: jobs
        link: /jobs
        component: simpleLink
        label: 
          fr: On recrute
          en: We recruit

  - name: we-like
    disabled: false
    # link: /we-like
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: On aime
      en: We like
    submenu: 
      # - name: network
      #   link: /network
      #   component: simpleLink
      #   label: 
      #     fr: Notre réseau
      #     en: Our network
      # - name: podcast
      #   link: /podcasts
      #   component: simpleLink
      #   label: 
      #     fr: Podcasts
      #     en: Podcasts
      - name: blog
        link: /blog
        component: simpleLink
        label: 
          fr: Blog
          en: Blog

  - name: switch-locale
    component: switchLocaleDropdown
    options: [ arrowless, uppercase, rounded, hoverable ]
    

--- 

# Navbar config file
