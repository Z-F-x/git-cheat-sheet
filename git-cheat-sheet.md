# GitHub

## Create project and files locally, then create repo at git first then push files to that repo

`git init`

` git add .`

`git commit -m "Initial commit"  `

`git remote add origin https://github.com/yourusername/your-repo-name.git`

`git push -u origin main `

## Create repository locally first and create the repo at git and push files

`git init`

` git add .`

`git commit -m "Initial commit"  `

### This will create a public repository

`gh repo create <repoName> --public --source=. --remote=origin --push`

### This will create a private repository

`gh repo create <repoName> --private --source=. --remote=origin --push`

## Authentication from CLI

`gh auth login`

## Accessing Your GitHub repo from CLI

`gh repo list`

## Install repos from repo list

`gh repo clone yourusername/repo-name`
