# Youtube build with React EMCAScript 6.

## Usage

```zsh
npm install
npm run build
```

Optionally, to run from a web server:

```zsh
npm install -g live-server
live-server
```

The gist of it is this:

* Using [webpack](http://webpack.github.io/), traverse the dependency tree.
* With the help of [babel](https://babeljs.io/), transpile any occurences of ECMAScript 6 syntax.
* Output the result to `dist/bundle.js`.

