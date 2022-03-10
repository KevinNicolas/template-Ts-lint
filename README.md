# Template: "Ts-lint"

> ### Linters and formaters
>
> <a href="https://eslint.org/" >
> <img alt="ESLint logo" src="https://raw.githubusercontent.com/KevinNicolas/template-Ts-lint/861b1782a0d418d7119749dd5b632a2cdce643a8/images/eslint-logo.svg" itemprop="image" width="17"> ESLint</a>,
> <a href="https://prettier.io/">
> <img alt="Prettier logo" src="https://github.com/KevinNicolas/template-Ts-lint/blob/main/images/prettier-logo.png?raw=true" width="17" /> Prettier</a>,
> <a href="https://typicode.github.io/husky/#/">🐶 Husky</a> (<a href="https://github.com/okonet/lint-staged#readme">🚫💩 Lint-staged</a>, 
>   <a href="https://commitlint.js.org/#/">
>   <img alt="Commit-lint logo." src="https://raw.githubusercontent.com/KevinNicolas/template-Ts-lint/861b1782a0d418d7119749dd5b632a2cdce643a8/images/commitlint-logo.svg" itemprop="image" width="17" /> Commit-lint
>   </a>)

## Start

### Pre-requirements

- <a href="https://npm.io/es/"><img alter="npm logo." src="https://raw.githubusercontent.com/KevinNicolas/template-Ts-lint/3f1a6ec0eb8e1c528fcfd5ac30353216bb660ee6/images/npm-logo.svg" width="17" /> npm</a> package manager

### Setup

Clone this respository and run:

```
    npm i
```

## Use other package manager

<span>If you want use other package manage you need change "npm" commands of next files for the equivalent of you package manager (the next examples are made with npm/npx)</span>

    .husky
    ├ commit-msg: [Line 4]: npx --no-install commitlint --edit
    ├ post-merge: [Line 4]: npm install
    └ pre-commit:
        ├ [Line 4]: npm run tsc
        ├ [Line 5]: npm run lint-staged
        ├ [Line 6]: npm run lint:fix
        └ [Line 6]: npm run format
    package.json:
    ├ [Line 11]: "build": "npm run lint && npm run format && tsc"
    ├ [Line 33]: "npm run eslint --fix"
    └ [Line 34]: "npm run prettier --write"

After this modifies, delete "npm-lock.yaml" file and "node_modules"(if exist), next, run the equivalent of "npm install", remove remote origin (`git remote remove origin`) and delete "README.md"
