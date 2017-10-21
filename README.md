# learning_eslint

## Basic installation & kickoff

`npm install -g eslint`

run:

`npm install eslint --save-dev`

`eslint --init`

## Check linting errors

`eslint .`

## Auto fix errors

`eslint --fix`

## Use Pre-Commit to fix linting errors before git commit

Install:
`npm i pre-commit --save-dev`

## NPM script
```
  scripts": {
      "eslint": "eslint src",
  },
```
## Error: ESLint Can not find module 'eslint-config-airbnb-base' Referenced from .eslintrc.js

Install the latest ESLint
 
`npm install eslint -g`

Install eslint-config-airbnb-base

`npm install eslint-config-airbnb-base -g`

Install eslint-plugin-import

 
`npm install eslint-plugin-import -g`

Restart VSCode (very important). Try again, maybe the problem is gone. 

**Source:**
[Coldfusion](https://coldfunction.com/p/91)
[Coldfusion Translated](https://translate.google.com/translate?sl=auto&tl=en&js=y&prev=_t&hl=en&ie=UTF-8&u=https%3A%2F%2Fcoldfunction.com%2Fp%2F91&edit-text=)
