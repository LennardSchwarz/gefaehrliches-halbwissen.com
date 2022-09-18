# gefaehrliches-halbwissen.com
Code for the website gefaehrliches-halbwissen.com

# Template
Vue js with two components:
-particles bg for vue
-body

# Dev Process
## Dev
```bash
npm run serve
```

# Prod
push to main. GH Actions build and deploy. 

### set custom domain
Due to Action setup, you have to set the custom domain in the github settings manually after every run.

## gh pages Actions
https://github.com/marketplace/actions/vue-to-github-pages

## hover
Setup like this:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## CNAME
CNAME entry for www to gh page.

## A records
A records to point to GH pages DNS servers to correctly forward "gefaehrliches-halbwissen.com" to gh pages.

# Design
## Favicon
https://favicon.io/favicon-generator/

see zz_assets folder

## Color pallette
Cappuccino
https://www.color-hex.com/color-palette/389



# Docker Backend Wordpress
Backend is hosted as a wordpress docker container with wp plugin.