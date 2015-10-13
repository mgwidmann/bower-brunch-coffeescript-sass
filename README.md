# Brunch
## SASS CoffeeScript Jade Auto-Reload

This is a Brunch skeleton repo for Brunch+Bower+Coffeescript+SASS.

Started with [HashNuke's Brunch](https://github.com/HashNuke/brunch-bower-babel-starter) and tweaked it for coffeescript and sass with auto reloading.

## Install

Install brunch & bower

```
npm install -g bower brunch
```

## Usage

```
brunch new http://github.com/mgwidmann/brunch-bower-coffeescript-sass path/to/new-project-dir
cd new-project-dir
npm install
```

To use ES6 instead, remove coffeescript from `package.json` and replace with:

```
"babel": "^5.8.23",
"babel-brunch": "^5.1.2",
```
