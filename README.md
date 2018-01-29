# Static Starter

Simple boilerplate to get a static HTML/CSS/JS project up and running.

## Features 🍬

Just a directory with some good starter bits:

### Basic file structure 📂

```
source/
|   + index.html
|__ css
|   |__ base/
|   |__ modules/
|   |__ site/
|       + style.scss
|__ images/
|__ js/
|   + scripts.js
```

### Minimal styling 🎨

* A few SCSS variables (colors & fonts)
* A few handy mixins
* A bunch of empty sass partials for organization. Use 'em or don't.

All of the above are there for sanity, but feel free to trash 'em all.

### Build tool ⚒

This project uses Gulp for:

* SASS compilation
* Image compression
* Concat and minifying js
* Flatten html directory structure
* Move all directory and assets to `_build`

## Getting started 🚦

### 1. Let's get this project to your machine ⬇️

Move into directory of your choice:

```
cd path/to/directory-of-your-choice
```

Create the project inside that directory:

```
git clone https://github.com/luclemo/static-starter.git
```

### 2. Working locally 👩‍💻

_Assuming you already have gulp and npm installed globally_

Install node packages from `package.json`:

```
npm install
```

Launch local server:

```
gulp
```

Files are served at localhost:3000 from the `_build` directory.

Your browser will automatically reload to show you your changes on save.
