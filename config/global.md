---
app_name : Coopérative numérique multi
app_default_locale: fr
app_locales: [ fr, en ]
app_md_flavor: github
app_icon: ./images/logos/logo-multi-003-m.png
app_favicon: ./images/logos/favicon_multi.ico

routes: ./config/routes.md
navbar: ./config/navbar.md
footer: ./config/footer.md
legal: ./config/legal.md

# colors multi:
#   text: #063442
#   dark: #2F746E
#   main: #4FC4AF
#   light: #C1E7D2
#   secondary_light: #FDF3CF
#   secondary: #FFC07A
#   secondary_dark: #ED7901
#   secondary_text: #494048

custom_colors: true
colors:
  primary: '#4FC4AF'
  loading_color: '#C1E7D2'
  accent: '#4FC4AF'
  secondary: '#FFC07A'
  info: '#494048'
  warning: '#ED7901'
  error: '#D1335B'
  success: '#03BD5B'

custom_css: true
custom_css_files:
  - ./styles/custom-css-multi.css
  # - https://raw.githubusercontent.com/multi-coop/multi-site-contents/julien-update-colors/styles/custom-css-multi.css

matomo: 
  matomo_active: true
  matomo_server: multi.matomo.cloud
  matomo_site_id: 3
  matomo_track_outlinks: true

seo_keywords: [
  cooperative, data, dev, web, scop, coop,
  multi, git
]

---


# Config file

This file `config.md` contains the main configuration in the yaml part on top... :kissing_heart:
