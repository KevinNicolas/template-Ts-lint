# Template: "Ts-lint"

> ### Linters and formaters
>
> <a href="https://eslint.org/" >
> <img alt="ESLint logo" src="https://d33wubrfki0l68.cloudfront.net/204482ca413433c80cd14fe369e2181dd97a2a40/092e2/assets/img/logo.svg" itemprop="image" width="17"> ESLint</a>,
> <a href="https://prettier.io/">
> <img alt="Prettier logo" src="https://prettier.io/icon.png" width="17" /> Prettier</a>,
> <a href="https://typicode.github.io/husky/#/">🐶 Husky</a> (<a href="https://github.com/okonet/lint-staged#readme">🚫💩 Lint-staged</a>, 
>   <a href="https://commitlint.js.org/#/">
>   <img alt="Commit-lint logo." src="https://commitlint.js.org/assets/icon.svg" itemprop="image" width="17" /> Commit-lint
>   </a>)

<br><br>

# Select a branch
+ <a href="https://github.com/KevinNicolas/template-Ts-lint/tree/pnpm">
    <img alter="pnpm logo." src="https://d33wubrfki0l68.cloudfront.net/2f3acb83b7d2349f2194bc38c0f22f295908dc33/5220f/es/img/pnpm-no-name-with-frame.svg" width="17" /> pnpm
</a>


<!-- ## Start

### Pre-requirements

- <span href="https://pnpm.io/es/"><img alter="pnpm logo." src="https://www.svgrepo.com/show/354126/npm-icon.svg" width="17" /><b> npm</b></span> package manager

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

After this modifies, delete "package-lock.yaml" file and "node_modules"(if exist), next, run the equivalent of "npm install", remove remote origin (`git remote remove origin`) and delete "README.md" -->
