---
routes: 

  # LANDING
  - name: home 
    url: /
    sections: 
      - name: logo
        component: LogoAnimated
        options: [ no-translation ]
        files:
          fr: ./texts/landing/landing-head-fr.md
          en: ./texts/landing/landing-head-fr.md
      - name: head
        component: TextComponent
        options:
          columns-size: half
        files:
          fr: ./texts/landing/catchphrase-fr.md
          en: ./texts/landing/catchphrase-en.md
      - name: btn-to-offer-products
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          buttons: 
            - link: /offer
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Découvrez notre offre de service
                en: Discover our services
            - link: /products
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Découvrez nos produits open source
                en: Discover our open source products
  
  # WHO ARE WE
  - name: cooperative
    url: /cooperative
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: three-quarters
        files:
          fr: ./texts/who-are-we/cooperative-fr.md
          en: ./texts/who-are-we/cooperative-en.md

  # - name: manifesto
  #   url: /manifesto
  #   sections: 
  #     - name: logo
  #       component: LogoAnimated
  #       options: [ no-translation ]
  #       files:
  #         fr: ./texts/landing/landing-head-fr.md
  #         en: ./texts/landing/landing-head-fr.md
  #     - name: manifesto
  #       component: TextComponent
  #       options:
  #         columns-size: half
  #         columns-divider: h1
  #       files:
  #         fr: ./texts/who-are-we/manifesto-fr.md
  #     - name: goals
  #       component: TextComponent
  #       options:
  #         columns-size: three-quarters
  #       files:
  #         fr: ./texts/who-are-we/goals-fr.md

  - name: manifesto-temp
    url: /manifesto-temp
    sections: 
      - name: manifesto-temp
        component: TextComponent
        options:
          columns-size: full
        files:
          fr: ./texts/who-are-we/manifesto-temp-fr.md

  - name: origin
    url: /origin
    options: [ menu ]
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/who-are-we/origin-fr.md
      - name: head
        component: TextComponent
        files:
          fr: ./texts/who-are-we/goals-fr.md

  - name: team 
    url: /team
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/team/team-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/team/team-data.md


  # OFFER
  - name: offer
    url: /offer
    sections: 
      - name: logo
        component: LogoAnimated
        options: [ no-translation ]
        files:
          fr: ./texts/landing/landing-head-fr.md
          en: ./texts/landing/landing-head-fr.md
      - name: offer-head
        component: TextComponent
        options:
          columns-size: half
          # columns-divider: h1
        files:
          fr: ./texts/offer/offer-head-fr.md
      - name: btn-to-products
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          buttons: 
            - link: /products
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Découvrez nos produits open source
                en: Discover our open source products

  - name: offer-temp
    url: /offer-temp
    sections: 
      - name: offer-temp
        component: TextComponent
        options:
          columns-size: full
        files:
          fr: ./texts/offer/offer-temp-fr.md

  - name: products
    url: /products
    sections: 
      - name: products-head
        component: TextComponent
        files:
          fr: ./texts/references/products-head-fr.md
      - name: products-data
        component: DataGrid
        files:
          fr: ./texts/references/products-data.md
      - name: btn-to-offer
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          buttons: 
            - link: /offer
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Découvrez notre offre de service
                en: Discover our services

  - name: references
    url: /references
    sections: 
      - name: refs-head
        component: TextComponent
        files:
          fr: ./texts/references/references-head-fr.md
      - name: refs-data
        component: DataGrid
        files:
          fr: ./texts/references/references-data.md
  
  - name: network
    url: /network
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/we-like/network-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/we-like/network-data.md

  - name: podcasts
    url: /podcasts
    sections:
      - name: head
        component: TextComponent
        files:
          fr: ./texts/podcasts/podcasts-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/podcasts/podcasts-data.md

  - name: blog
    url: /blog
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/blog/blog-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/blog/blog-data.md

  # CONTACT
  # - name: contact
  #   url: /contact
  #   sections: 
  #     - name: head
  #       component: TextComponent
  #       files:
  #         fr: ./texts/contact/contact-head-fr.md

  - name: infos
    url: /infos
    sections: 
      - name: logo
        component: LogoAnimated
        options: [ no-translation ]
        files:
          fr: ./texts/landing/landing-head-fr.md
          en: ./texts/landing/landing-head-fr.md
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
          columns-divider: h1
        files:
          fr: ./texts/contact/infos-head-fr.md

  - name: contribute
    url: /contribute
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
          columns-divider: h1
        files:
          fr: ./texts/contact/contribute-head-fr.md

  - name: legal
    url: /legal
    sections: 
      # - name: data
      #   component: TextDataComponent
      #   files:
      #     fr: ./texts/contact/legal-data.md
      - name: legal-text
        component: TextComponent
        files:
          fr: ./texts/contact/legal-mentions-fr.md

  # JOBS
  - name: join 
    url: /join
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
        files:
          fr: ./texts/jobs/join-head-fr.md
      - name: btn-to-jobs
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          buttons: 
            - link: /jobs
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Découvrez nos offres d'emploi
                en: Discover our job offers

  - name: jobs 
    url: /jobs
    sections: 
      - name: head
        component: TextComponent
        files:
          fr: ./texts/jobs/jobs-head-fr.md
      - name: btn-to-join
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          buttons: 
            - link: /join
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Pourquoi rejoindre multi ?
                en: Why joining multi ?
      - name: data
        component: DataGrid
        files:
          fr: ./texts/jobs/jobs-data.md
--- 
