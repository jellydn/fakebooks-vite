# Welcome to fakebooks-vite 👋

![Version](https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000)
[![Twitter: jellydn](https://img.shields.io/twitter/follow/jellydn.svg?style=social)](https://twitter.com/jellydn)

> How to migrate vite to create-react-app

### 🏠 [Homepage](https://github.com/jellydn/fakebooks-vite/tree/feature/wp2vite)

### ✨ [Demo](https://fakebooks-vite.vercel.app/)

## Install

```sh
yarn install
```

## Usage

### Vite

```sh
yarn dev
yarn vite-build
```

### Create-React-App

```sh
yarn start
yarn build
```

## Why

The development speed is about 80% faster than that of webpack, and the construction speed is about 50% faster than that of webpack.

## How

### Step 1

Run automatic conversion tool https://github.com/tnfe/wp2vite

```sh
npx wp2vite
```

### Step 2

Fix import alias

<img width="1539" alt="image" src="https://user-images.githubusercontent.com/870029/164909707-dc16c863-402e-4f1e-9753-c6c7ee29358d.png">

Remove legacy plugin

<img width="1214" alt="image" src="https://user-images.githubusercontent.com/870029/164909672-9226e71e-6b1c-445c-8045-0c5cfc845d37.png">

### Result

- Start development environment less than 1 second (223ms).
  <img width="866" alt="image" src="https://user-images.githubusercontent.com/870029/164910000-582a8cc5-3b0e-41b9-a7e6-b4f0fe2aeefa.png">

- Build command
  <img width="1787" alt="image" src="https://user-images.githubusercontent.com/870029/164899355-91bd6295-9b2a-423d-8e52-9c9b37eac220.png">

## Author

- Website: https://productsway.com/
- Twitter: [@jellydn](https://twitter.com/jellydn)
- Github: [@jellydn](https://github.com/jellydn)

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
