---
routes: 

  # LANDING
  - name: home 
    url: /
    sections: 
      - name: logo
        component: LogoAnimated
        options:
          columns-size: two-thirds
          no-translation: true
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
          columns-size: three-quarters
          buttons-size: half
          buttons: 
            - link: /offer
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Notre offre de service
                en: Our services
            - link: /products
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Nos produits open source
                en: Our open source products
            - link: /references
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Nos références
                en: Our references
  
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
      - name: btn-to-team
        component: ButtonsComponent
        options:
          columns-size: three-quarters
          buttons-size: half
          buttons: 
            - link: /team
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Découvrez l'équipe
                en: Discover the team
            - link: /references
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Nos références
                en: Our references

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
        options:
          columns-size: two-thirds
        files:
          fr: ./texts/who-are-we/origin-fr.md
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
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
      - name: btn-to-jobs
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: full
          custom-classes: mt-6
          buttons: 
            - link: /jobs
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Nos offres d'emploi
                en: Our job offers

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
                fr: Nos produits open source
                en: Our open source products
            - link: /references
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Nos références
                en: Our references

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
          buttons-size: full
          buttons: 
            - link: /offer
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Notre offre de service
                en: Our services

  - name: references
    url: /references
    sections: 
      - name: btn-to-offer-products
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          custom-classes: mb-6
          buttons: 
            - link: /offer
              icon-left: arrow-right-bold
              rounded: true
              outlined: false
              color: light
              label: 
                fr: Notre offre de service
                en: Our services
            - link: /products
              icon-left: arrow-right-bold
              rounded: true
              outlined: false
              color: light
              label: 
                fr: Nos produits open source
                en: Our open source products
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

  - name: our-cooperative
    url: /our-cooperative
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
        files:
          fr: ./texts/our-cooperative/our-cooperative-head-fr.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/our-cooperative/our-cooperative-data.md

  - name: shares-simulator
    url: /shares-simulator
    sections: 
      - name: simulator
        component: WidgetComponent
        options:
          columns-size: two-thirds
          js: https://multi-site-simulator-test.netlify.app/js/app.js
          css: https://multi-site-simulator-test.netlify.app/css/app.css
          html: |
            <multi-shares-simulator 
              locale="fr"
              cooperative="multi"
              partvalue="25"
              minbenefs="0"
              benefs="100000"
              repart='{
                "reserves":40,
                "participation":50,
                "dividendes":10
              }'
              team='[
                { "name":"Johan Richer", "parts":100, "workTime":100, "yearTime": 12 },
                { "name":"Julien Paris", "parts":100, "workTime":100, "yearTime": 12 },
                { "name":"Thomas Brosset", "parts":40, "workTime":40, "yearTime": 12 },
                { "name":"Pierre Camilleri", "parts":100, "workTime":60, "yearTime": 12 },
                { "name":"Quentin Loridant", "parts": 100, "workTime":80, "yearTime": 12 }
              ]'
            />


  - name: blog
    url: /blog
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
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
          buttons-size: full
          buttons: 
            - link: /team
              icon-left: arrow-right-bold
              rounded: true
              outlined: true
              label: 
                fr: Découvrez l'équipe
                en: Discover the team
            - link: /jobs
              icon-left: arrow-right-bold
              rounded: true
              label: 
                fr: Nos offres d'emploi
                en: Our job offers

  - name: jobs 
    url: /jobs
    sections: 
      - name: btn-to-join
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: two-thirds
          custom-classes: mb-5
          buttons: 
            - link: /join
              icon-left: arrow-right-bold
              rounded: true
              outlined: true
              label: 
                fr: Pourquoi rejoindre multi ?
                en: Why joining multi ?
      - name: head
        component: TextComponent
        files:
          fr: ./texts/jobs/jobs-head-fr.md
      - name: simulator
        component: WidgetComponent
        options:
          columns-size: two-thirds
          js: false
          css: |
            .welcomekit-jobs-list-item {
              margin: 0;
              padding: 0;
            }
            .welcomekit-jobs-list-item-link {
              position: relative;
              display: block;
              margin: 0;
              padding: 30px 5px;
              border-bottom: 1px solid #eee;
              text-decoration: none;
              transition: all 0.2s;
            }
            .welcomekit-jobs-list-item-link:after {
              position: absolute;
              top: 50%;
              right: 30px;
              width: 20px;
              height: 20px;
              margin-top: -10px;
              content: ' ';
              border-top: 1px solid #ddd;
              border-right: 1px solid #ddd;
              transform: rotate(45deg);
              transition: all 0.2s;
            }
            .welcomekit-jobs-list-item-link:hover {
              background: #f5f5f5;
              border-bottom-color: #ddd;
            }
            .welcomekit-jobs-list-item-link:hover:after {
              right: 20px;
              border-top-color: #aaa;
              border-right-color: #aaa;
            }
            .welcomekit-job-name {
              margin: 0 0 10px 0;
              padding: 0;
              font-weight: 500;
              font-size: 19px;
              line-height: 20px;
            }
            .welcomekit-job-infos {
              margin: 0;
              padding: 0;
            }
            .welcomekit-job-infos > li {
              position: relative;
              display: inline-block;
              margin: 0 34px 0 0;
              color: #aaa;
            }
            .welcomekit-job-infos > li:before {
              position: absolute;
              top: 6px;
              left: -20px;
              content: ' ';
              display: block;
              height: 6px;
              width: 6px;
              background: #ddd;
              border-radius: 50%;
            }
            .welcomekit-job-infos > li:first-child:before {
              display: none;
            }
            .welcomekit-job-infos > li.welcomekit-job-description {
              display: block;
              margin: 10px 0 0 0;
              padding: 10px 20px;
              border-left: 2px solid #eee;
            }
            .welcomekit-job-infos > li.welcomekit-job-description p,
            .welcomekit-job-infos > li.welcomekit-job-description ul {
              margin: 0;
              padding: 0 0 10px 0;
              color: #bbb;
            }
            .welcomekit-job-infos > li.welcomekit-job-description ul li {
              border-left: 1px solid #eee;
              padding-left: 10px;
              margin-bottom: 10px;
            }
            .welcomekit-job-infos > li.welcomekit-job-description pre {
              border-left: 1px solid #eee;
              padding-left: 10px;
              overflow: auto;
            }
            .welcomekit-job-infos > li.welcomekit-job-description:before {
              display: none
            }
            .welcomekit-office-city,
            .welcomekit-department-name {
              display: block;
              padding: 15px;
              background: #eee;
              border-top: 1px solid #e0e0e0;
              border-bottom: 1px solid #e0e0e0;
              font-weight: 500;
              font-size: 17px;
              line-height: 18px;
              text-transform: uppercase;
            }
            .welcomekit-warning {
              display: block;
              padding: 50px 0;
              text-align: center;
            }
          html: |
            <script src='https://www.welcomekit.co/assets/embed.js' type='text/javascript'></script>
            <script type='text/javascript'>
              welcomeKitReady(function() {
                var wk = new WelcomeKitEmbed('J78KpaG')
                wk.group('job')
                wk.display(["department","officeCity","contractType","createdAt","startDate"])
                wk.locale('fr')
                wk.website('multi')
                wk.render()
              })
            </script>
            <div id='welcomekit-embed'></div>
      # - name: data
      #   component: DataGrid
      #   files:
      #     fr: ./texts/jobs/jobs-data.md
--- 
