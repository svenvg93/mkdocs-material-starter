# Dev Container 

`mkdocs serve -a 0.0.0.0:8000`

# Setup

## Github
- Click on the user this template & create a new repository
- Give the repository a name and click on create repository

## Cloudflare
Now the template is ready we will build the first version of the site to make sure everything is ready to go!
- Go to https://dash.cloudflare.com
- Go to `Workers & Pages`
- Click `Create`
- Go to pages and connect to git
- Link your github accout if needed
- Choose your repository you just made and click begin setup
- In the build setting choose for `Mkdocs` as framework

![Scherm­afbeelding 2024-07-08 om 17 40 57](https://github.com/svenvg93/mkdocs-material-starter/assets/4511676/c64915c5-cf09-43cf-97ec-c2c686806753)

Now cloudflare will clone your github repro, build the website and publish it.
If succesfull click continue project
It will get a generate domain name like `mkdocs-em9.pages.dev`
