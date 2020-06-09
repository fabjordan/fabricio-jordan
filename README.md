<h1 align="center"> Personal Template Vue.JS </h1>

<p align="center">
  <a href="https://github.com/fabjordan/about-me/commits/master">
    <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/fabjordan/about-me?style=flat-square&color=ff69b4">
  </a>
  
  <a href="https://github.com/fabjordan/about-me/stargazers">
    <img alt="GitHub Stars" src="https://img.shields.io/github/stars/fabjordan/about-me">
  </a>

  <a href="https://github.com/fabjordan/about-me/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/fabjordan/about-me?style=flat-square&color=yellow">
  </a>

  <img alt="Repository Size" src="https://img.shields.io/github/repo-size/fabjordan/about-me?style=flat-square&color=blueviolet">
</p>

<p align="center">
  <a href="#thinking-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-creating-your-own-template">Creating your own template</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :thinking: About

This project is a simple personal template developed based on the Vue.JS ecosystem (Vue CLI, Vue Router, BootstrapVue).

<div align="center">

![](/src/assets/images/print.png)

</div>

## :rocket: Technologies

This project was developed with the following technologies:

- [Vue.js](https://vuejs.org/)
- [Vue CLI](https://cli.vuejs.org/)
- [Vue Router](https://router.vuejs.org/)
- [BootstrapVue](https://bootstrap-vue.org/)
- [Eslint](https://eslint.org/)

## :computer: Creating your own template

To use this template do the following:

```bash
git clone https://github.com/fabjordan/about-me.git
yarn install
yarn serve
```

Compiles and minifies for production:
```nodejs
yarn build
```

Lints and fixes files:
```nodejs
yarn lint
```

Customize configuration:
See [Configuration Reference](https://cli.vuejs.org/config/).


## Deploy this project to github pages

> Create a new file in root directory of your project and name it ‘vue.config.js’.
```nodejs
module.exports = {
    publicPath: '/about-me/'
}
```

> comment out the "/dist" line in your .gitignore

> run the build:
```nodejs
yarn build
```

> install vue-cli-ghpages:
```nodejs
yarn global add vue-cli-ghpages
```

> execute:
```nodejs
vue-cli-ghpages
```

> or simply:
```nodejs
vcg
```

> Go to the GitHub Pages section in the repository settings. Select the branch and click Save.
Wait until the notification alert reads: "Your site is published at ..."



## :memo: License

MIT
