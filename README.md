# cookiecutter-p5js

A cookiecutter for p5js projects, based on the es6-boilerplate cookiecutter by @agconti.

## Overview
This project takes care of the setup and configuration so you can focus on making your app awesome. Scaffolding a project takes seconds and it gives you the essentials, like ES6 through Babel and a viable scss framework, to get started. This project aims to get out of your way, and to allow you easily create while providing a solid foundation for your project to mature in the future.

## Quick Start
Install [cookiecutter](https://github.com/audreyr/cookiecutter):
```bash
pip install cookiecutter
```

Scaffold your project:
```
cookiecutter gh:rpalo/cookiecutter-p5js 
```

# Minimal Mode

There is a more minimal version of this cookiecutter template for those without the need to have an 80MB node_modules folder for a simple project.  To scaffold a project using the minimal version, simply run:
```
cookiecutter gh:rpalo/cookiecutter-p5js --checkout minimal
```

# Features

- ES6 today via [Babel](https://babeljs.io/)
- Live reload via [browser-sync](http://www.browsersync.io/)
- Sass via [gulp-sass](https://www.npmjs.com/package/gulp-sass)
- Testing with [Mocha](https://mochajs.org/) and [Chai](http://chaijs.com/)
- CSS prefixing via [autoprefixer](https://github.com/postcss/autoprefixer)
- CSS resets via [Normailize.css](https://necolas.github.io/normalize.css/)
- CSS Minification via [gulp-minify-css](https://www.npmjs.com/package/gulp-minify-css)

## Contributing
Want a new feature or find a bug? Submit a Pull Request! This project adheres to the [Contributor Covenant](http://contributor-covenant.org/version/1/2/0/).
