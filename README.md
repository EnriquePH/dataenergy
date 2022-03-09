[![Netlify Status](https://api.netlify.com/api/v1/badges/d638f799-bbf7-4905-99e0-7696e734c879/deploy-status)](https://app.netlify.com/sites/blissful-brahmagupta-f99171/deploys)

# Data Energy
**Data Science Blog**


## Branding

 * Name: Data Energy
 * Domain Name:  [https://www.dataenergy.biz/](https://www.dataenergy.biz/)
 * Web3 domain:  dataenergy.x
 * Design a Logo


## Select Static site generator and framework

 * [Hugo](https://gohugo.io/)
 * Blogdown


## Theme

Build a custom theme from scratch 

git clone https://github.com/Andrew-Shay/lektor-theme-simple-strap
git submodule add https://github.com/EnriquePH/lektor-theme-simple-strap themes
Images
Photo
Graphic Design

## Git version control

### New repo

 * github.com: create new repo
 * Add .gitignore: `git touch .gitignore`
 * Initialize repository:  `git init`
 * git commit -m "first commit"
 * git branch -M main
 * git remote set-url origin git@github.com:EnriquePH/dataenergy.git
 * git push --set-upstream origin main
 
### SSH key access to github

 * Create keys: `ssh-keygen` to  file github_rsa
 * cat ~/.ssh/github_rsa.pub and copy key to github.com
 * Add SSH private key to the ssh-agent: `ssh-add ~/.ssh/github_rsa`
 * Test connection: `ssh -T git@github.com`


### Important files

* Choose a LICENCE
* Add README.md

### Blogdown

packageVersion("blogdown")
blogdown::new_site(theme = "EnriquePH/Binario")

`git submodule add https://github.com/EnriquePH/hugo-tanka ./themes/dataenergy-tanka`
blogdown::stop_server()
blogdown::check_site()
blogdown::serve_site()
blogdown::install_theme("EnriquePH/dataenergy-tanka")

git submodule add https://github.com/EnriquePH/Binario ./themes/dataenergy-binario

# Style
Technical Writing style
Correct grammar and sintaxis
Lint code



# Hosting
GH Pages
Google Firebase
Netlify

# Continous Integration
Local -> Git gh-pages -> Travis-CI -> Firebase

# Deploy to GitHub Pages

https://www.dataquest.io/blog/how-to-setup-a-data-science-blog/
https://www.ttested.com/integrating-hexo-and-jupyter/
https://docs.getpelican.com/en/latest/quickstart.html#installation
https://github.com/danielfrg/pelican-jupyter

# Social Networks
LinkedIn
Twitter
Stackoverflow

# Community
Kaggle
Numerai
R-bloggers
Python-bloggers

# Monetization
BAT / Brave Browser
* Sign up Brave Creators    
* create file: `./content/.well-known/brave-rewards-verification.txt`    

# Search Engine Optimization
Google Analytics

https://themes.gohugo.io/themes/minimal/

git submodule add https://github.com/themefisher/twenty-twenty-hugo themes/twenty-twenty-hugo


git remote set-url origin git@github.com:EnriquePH/dataenergy.git

