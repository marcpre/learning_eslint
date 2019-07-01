# learning_eslint

## Basic installation & kickoff

`npm install -g eslint`

or with plugins

`npm install --save-dev eslint babel-eslint eslint-config-airbnb eslint-config-babel eslint-config-prettier eslint-plugin-import`

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
    "lint": "eslint src",
    "lint:fix": "eslint --fix"
  },
```

## VSCode and ESLint

1. Install [vscode eslint plugin](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
2. Create a file called extensions.json in a directory named `.vscode` in the root of the project, with the following content:

```
{
  "recommendations": [
    "dbaeumer.vscode-eslint",
    "esbenp.prettier-vscode",
    "dzannotti.vscode-babel-coloring"
  ]
}
```

# ERRORS

## "Cannot find module prettier"

Install `npm i prettier --save-dev` from [NPM Prettier](https://www.npmjs.com/package/prettier)

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
