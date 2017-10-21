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

