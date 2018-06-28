# Systemantic Node Sass Boilerplate

At Systemantic we are solving problems and sharing the knowledge with our community. Here we present many projects as boilerplates that would help developers avoiding the headache of configuration and setting environment. Our boilerplates contain the latest Web technologies and dev tools.

The Node.js Sass boilerplate project helps the Systemantic developers to create unified and structured projects using HTML5 and Sass language based on pure Node.js dev tools

## Guide

### Cloning the project

First start by cloning the project on your workdir

```bash
 $ git clone git@github.com:Systemantic/node-sass-boilerplate.git
```

### Remove the .git folder

You need to remove the git folder and initiating a new one

```bash
$ cd node-sass-boilerplate
$ rm -rm .git
$ git init
```

### Install dependencies

Install the Node.js packages dependencies, by typing the following command.

```bash
$ npm install
```

### Start the project

Great!! :ok_hand: now start you project and enjoying the live reload. No need for CMD+R to refresh your updates after each change.

```bash
$ npm start
```

## Project Structure

```
.
├── README.md
├── build // The build folder
├── index.html // You home page
├── package.json
└── sass // Put your styles here
    ├── abstracts
    │   ├── _functions.scss
    │   ├── _mixins.scss
    │   ├── _placeholders.scss
    │   └── _variables.scss
    ├── base
    │   ├── _reset.scss
    │   └── _typography.scss
    ├── components
    │   ├── _buttons.scss
    │   ├── _cover.scss
    │   └── _dropdown.scss
    ├── layout
    │   ├── _footer.scss
    │   ├── _forms.scss
    │   ├── _grid.scss
    │   ├── _header.scss
    │   ├── _navigation.scss
    │   └── _sidebar.scss
    ├── main.scss
    ├── pages
    │   └── _home.scss
    ├── themes
    └── vendors
```
