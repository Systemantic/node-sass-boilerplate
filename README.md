## Systemantic Node Sass Boilerplate

At Systemantic we are solving problems and sharing the knowledge with our community. Here we present many projects as boilerplates that would help developers avoiding the headache of configuration and setting environments. Our boilerplates contain the latest Web technologies and dev tools.

The Node.js Sass boilerplate project helps the Systemantic developers to create unified and structured projects using HTML5 and Sass language based on pure Node.js dev tools

### Guide

#### Cloning the project

First start by cloning the project on your workdir

```bash
 $ git clone git@github.com:Systemantic/node-sass-boilerplate.git
```

#### Remove the .git folder

You need to remove the git folder and initiating a new one

```bash
$ cd node-sass-boilerplate
$ rm -rm .git
$ git init
```

#### Install dependencies

Install the Node.js packages dependencies, by typing the following command.

```bash
$ npm install
```

#### Start the project

Great!! :ok_hand: now start you project and enjoying the live reload. No need for CMD+R to refresh your updates after each change.

```bash
$ npm start
```

### References

* [The Sass Guide lines](https://sass-guidelin.es/#architecture)

### Project Structure

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

### License (MIT)

Copyright 2018-2019 Systemantic, https://github.com/Systemantic/node-sass-boilerplate

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
