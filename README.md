# todo-vuejs

Simple todo vuejs app that works with GitHub Pages

## Generate a `package.json` file

First step is to generate a `package.json` file. You can add the file yourself but it is easier with the command:

```console
# generates package.json file
$ npm init
```

Some questions will prompt and finally, the `package.json` file will be generated.

## Add VueJS

Add Vue with npm as specified in the [documentation](https://v3.vuejs.org/guide/installation.html#npm):

```console
# latest stable
$ npm install vue@next
```

## Setting up Webpack

From the [official documentation](https://webpack.js.org/guides/getting-started/):

> Webpack is used to compile JavaScript modules. Once installed, you can interact with webpack either from its CLI or API. If you're still new to webpack, please read through the core concepts and this comparison to learn why you might use it over the other tools that are out in the community.
warning

### Add webpack

Add Webpack as specified in the [documentation](https://webpack.js.org/guides/getting-started#basic-setup):

```console
# latest stable
npm install webpack webpack-cli --save-dev
```

### Create the project structure

You will need to add the `index.html` file and the `index.js` file:

📦todo-vuejs
 ┣ 📂src
 ┃ ┗ 📜index.js
 ┣ 📜.gitignore
 ┣ 📜index.html
 ┣ 📜LICENSE
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┗ 📜README.md
