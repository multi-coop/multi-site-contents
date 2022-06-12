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
      - name: cooperative
        link: /cooperative
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
          fr: Nos prestations
          en: Our services
      - name: products
        link: /products
        component: simpleLink
        label: 
          fr: Nos produits open source
          en: Our open source products
      - name: references
        link: /references
        component: simpleLink
        label: 
          fr: Nos références
          en: Our references
  
  - name: contact 
    link: /infos
    component: simpleLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Contact
      en: Contact
      # submenu: 
      #   - name: infos
      #     link: /infos
      #     component: simpleLink
      #     label: 
      #       fr: Infos
      #       en: Infos
      #   - name: contribute
      #     link: /contribute
      #     component: simpleLink
      #     label: 
      #       fr: Contribuer
      #       en: Contribute
      # - name: legal
      #   link: /legal
      #   component: simpleLink
      #   label: 
      #     fr: Mentions légales
      #     en: Legal

buttons-right: 

  - name: recruit 
    link: /jobs
    component: simpleLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Jobs
      en: Jobs
    # submenu: 
    #   - name: join
    #     link: /join
    #     component: simpleLink
    #     label: 
    #       fr: Pourquoi nous rejoindre
    #       en: Why join us
    #   - name: jobs
    #     link: /jobs
    #     component: simpleLink
    #     label: 
    #       fr: On recrute
    #       en: We recruit

  - name: blog
    link: /blog
    component: simpleLink
    label: 
      fr: Blog
      en: Blog

  - name: we-like
    disabled: false
    # link: /we-like
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Notre univers
      en: Our universe
    submenu:
      - name: network
        link: /network
        component: simpleLink
        label: 
          fr: Notre réseau
          en: Our network
      - name: ressources
        link: /ressources
        component: simpleLink
        label: 
          fr: Ressources
          en: Ressources
      - name: shares-simulator
        link: /shares-simulator
        component: simpleLink
        label: 
          fr: Simulateur de répartition
          en: Repartition simulator
      - name: gitribute-cooptech
        link: /gitribute-cooptech
        component: simpleLink
        label: 
          fr: Annuaire des coopératives
          en: Tech coops in France
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

  - name: switch-locale
    component: switchLocaleDropdown
    options: [ arrowless, uppercase, rounded, hoverable ]
    

--- 

# Navbar config file
