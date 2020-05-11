<p align="center">
  <a href="" rel="noopener">
    <img src="./docs/logo.png" alt="Project logo">
  </a>
</p>

<h3 align="center">
Simple product cart, a mobile application built with React Native and TypeScript to practice Context API from ReactJS.
Developed on Rocketseat Bootcamp. 🚀🚀
</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/leon-carvalho/gomarketplace-rn.svg)](https://github.com/leon-carvalho/gomarketplace-rn/issues)
[![Repo Languages](https://img.shields.io/github/languages/count/leon-carvalho/gomarketplace-rn?color=%2304D361.svg)](https://img.shields.io/github/languages/count/leon-carvalho/gomarketplace-rn)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/leon-carvalho/gomarketplace-rn.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
  <img width="320px" src="./docs/demo.gif" alt="Project demonstration"></a>
</p>

<p align="center">
  This application was built as a challenge on Rocketseat's Bootcamp to practice React Native, TypeScript, routing, Async Storage and Context API. It was bootstrapped using this [template](https://github.com/Rocketseat/gostack-template-fundamentos-react-native) containing folder structure, routes, tests and dependencies already installed.
<br>
</p>

## 📝 Table of Contents

- [Getting Started](#getting_started)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them.

> Please check [this docs](https://react-native.rocketseat.dev/) available in Brazilian Portugues to learn to configure your environment to use React Native or use the official documentation available in English [react native docs](https://reactnative.dev/)

**NodeJS** <br>
[NodeJS](https://nodejs.org/en/)

**A JavaScript package manager like NPM or Yarn** <br>
[Node.js](https://nodejs.org/en/)
[Yarn](https://yarnpkg.com/pt-BR/docs/install)

**Git installed in your machine (Mac and Linux already has Git installed by default)** <br>
[Download Git to your SO](https://git-scm.com/downloads)

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

> Before start check if you have an Android or IOS simulator/emulator open or a real device connected via USB

```shell
# open your terminal/cmd and clone this repository
git clone https://github.com/leon-carvalho/gomarketplace-rn.git

# access folder gomarketplace-rn
cd gomarketplace-rn

# install dependencies using your favorite package manager
yarn
# or with NPM usign npm install
npm install

# open a new terminal, access gomarketplace-rn and start fake API running
yarn json-server server.json -p 3333

# [ IOS Only ] - this steps are required only on IOS
cd ios
pod install

#  remember to go back to root if you are on IOS
cd ..

# run app

# IOS
react-native run-ios
# Android
react-native run-android


# The app should open in your emulator/simulator or in your real device connected via USB 🎉🎉🎉
```

## 🔧 Running the tests <a name = "tests"></a>

```shell
# open your terminal/cmd and clone this repository
git clone https://github.com/leon-carvalho/gomarketplace-rn.git

# access folder gomarketplace-rn
cd gomarketplace-rn

# install dependencies using your favorite package manager
yarn
# or with NPM usign npm install
npm install

# [ IOS Only ] - this steps are required only on IOS
cd ios
pod install

#  remember to go back to root if you are on IOS
cd ..

# run the tests
yarn test
# or with NPM
npm run test
```

## ⛏️ Built Using <a name = "built_using"></a>

- Jest
- React Native
- TypeScript
- AsyncStorage
- React Navigation
- Styled Components
- React Native Vector Icons
- React Native Gesture Handler
- React Native Iphone X Helper
- ESLint, Prettier and EditorConfig

## ✍️ Authors <a name = "authors"></a>

- [@leon-carvalho](https://github.com/leon-carvalho)
- Feel free to send me feedbacks on [Linkedin](https://www.linkedin.com/in/leonardo-dev/)

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- [Rocketseat Team](https://rocketseat.com.br/)
- [Diego Fernandes, CTO at Rocketseat](https://github.com/diego3g)
