<p align="center">
  <img src="http://rcrd.me/lent-a-cal/assets/img/logo.svg" width="100">
</p>
# Cineza Lent a Cal - Projeto de Aprendizagem Front-end

[Access the website](http://rcrd.me/lent-a-cal/)

This project uses:
- [Pug](https://pugjs.org/)
- [Sass](http://sass-lang.com/)
- [Grunt](https://gruntjs.com/)
- [Browsersync](https://www.browsersync.io/)

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
- [Grunt](https://gruntjs.com/)

```sh

# Clone this repository
git clone git@github.com:ricardogouveia3/lent-a-cal.git
cd lent-a-cal.git

# install dependencies
npm install

```

After that, you should be good to go :)

### Folders/Files Structure

```sh
├── assets/
│   ├── css/
│   │   └── *.sass
│   │   └── *.css
│   ├── img
│   │   └── *.png
│   │   └── *.jpg
│   │   └── *.svg
│   │   └── favicon.ico
│   ├── js/
│   │   └── *.js
├── Gruntfile.js
├── index.html
├── index.pug
├── package.json
├── README.md
```
These structure will change during the project.

### Code Standarts

Not implemented **yet**.


### Tasks

- `grunt uglify`: uglifies raw.js file into index.min.js
- `grunt concat`: concat index.min,js into index.js
- `grunt sass`: build [everything].sass into style.css
- `grunt watch`: call for watch files

- `grunt`: run all default tasks continuously; start local server


## License

[MIT License](http://ricardogouveia3.mit-license.org/) © Ricardo Álvaro Gouveia Gomes Filho