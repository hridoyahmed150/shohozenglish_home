# shohozenglish_home
# PSD to HTML, CSS via SCSS

## Description
* Practice project to show the conversion from PSD to modern HTML5 and CSS
  using Sass
  
## New Tools
Running Sass is a time saver but there is a better way and that is through
build tools like gulp and grunt. The newest and most build tool is webpack

## What gulp and our modern tooling does for us
* We installed the gulp dev server
  - This will auto refresh the page with changes and it's faster than
    live-reload because it is `virtual`
* We use git and github for version control
  - [git
    intro](https://github.com/hridoyahmed150/shohozenglishgit.md)

## Install Instructions
* Clone repo 

`$ git clone https://github.com/hridoyahmed150/shohozenglish.git`

* `$ cd shohozenglish`

## Clone specific remote branch
## How do I pull down a specific branch?
1. Get the name of all the branches

`$ git branch -a`

1. Fetch branch

`$ git fetch <remote> <rbranch>:<lbranch>`

3. Checkout that branch

`$ git checkout <lbranch>`

## Install all dependencies
`$ npm install`
* This will install all the packages inside package.json

## Run dev server
`$ gulp `

## View in browser
* localhost:8000
