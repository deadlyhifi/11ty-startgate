# 11ty Startgate

This is forked from [deventy](https://github.com/ianrose/deventy), it’s so very like it you may as well go there.

A minimal 11ty starting point for building static websites with modern tools. Uses the CLI of each tool. Allowing a much easier upgrade path for each individual development tool.

Features:

- [11ty](https://www.11ty.io/)
- [Sass/SCSS](https://github.com/sass/node-sass)
- [Webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [light-server](https://github.com/txchen/light-server)
- [PostCSS](https://postcss.org/)
- [CSSnano](https://cssnano.co/)
- [Autoprefixer](https://github.com/postcss/autoprefixer)

## Getting Started

Install all dependencies using npm:

```
$ npm install
```

### To Develop

```
$ npm run dev
```

And in debug mode:

```
$ npm run dev:debug
```

You can view the website at the given access URL:

```
$ light-server is listening at http://localhost:4000
```

The local url is configured in `.lightserverrc`

### To Build

```
npm run build
```
