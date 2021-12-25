# Clean TS template
## ⚡️ Quick start
1. create new repo using this template 
2. change Name in package.json
3. write script in src
4. "yarn dev"
##  Source structure
### ./src/types
**Folder For self-declare types.**
## ⓘ Template info
* default paths @ -> src/
* Hot reload by default using ts-node-dev
* Add lint by default
## ⌘ Command
### Run hot reload
```bash
yarn dev
```
### Run one time
```bash
yarn start:ts
```
### Lint check
```bash
yarn lint
```
### Lint fix
```bash
yarn lint:fix
```
### Build
```bash
yarn build
```
### Start
```bash
yarn start
```
## 🗄 Template structure
## 📦 Used packages
| Name                                                                                                   | Version    | Type       |
| ------------------------------------------------------------------------------------------------------ | ---------  | ---------- |
| [@types/node](https://www.npmjs.com/package/@types/node)                                               | `@lastest` | typed      |
| [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)     | `@lastest` | lint       |
| [@typescript-eslint/parser](https://www.npmjs.com/package/ts-node)                                     | `@lastest` | lint       |
| [eslint](https://www.npmjs.com/package/eslint)                                                         | `@lastest` | lint       |
| [ts-node](https://www.npmjs.com/package/ts-node)                                                       | `@lastest` | runtime    |
| [ts-node-dev](https://www.npmjs.com/package/ts-node-dev)                                               | `@lastest` | runtime    |
| [tsc-alias](https://www.npmjs.com/package/tsc-alias)                                                   | `@lastest` | runtime    |
| [tsconfig-paths](https://www.npmjs.com/package/tsconfig-paths)                                         | `@lastest` | runtime    |
| [typescript](https://www.npmjs.com/package/typescript)                                                 | `@lastest` | runtime    |


## Other config 
-  Change compilerOptions.target to great compatible version that currently support in your nodejs (or you can keep it es6 by default)
    | Nodejs |Target |
    |--------|-------|
    | 12 & up|es2019 |
    | 14 & up|es2020 |
    | 16 & up|es2021 |
    | 17 & up|es2022 |
## ⚠️ License
