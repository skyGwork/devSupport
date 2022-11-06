## mpm

> Get list of globally installed packages

- `npm list -g --depth 0` or `npm list -g`

```bash
    $ npm list -g

    C:\Users\skyde\AppData\Roaming\npm
    ├── @aws-amplify/cli@9.2.1
    ├── aws-cdk@2.38.1
    ├── eslint@7.24.0
    ├── minify@9.1.0
    ├── npm@8.9.0
    └── typescript@4.7.4

```

$ npm init -y
Wrote to D:\devExpo\css-scssProjects\package.json:

```json
{
  "name": "advancedcss",
  "version": "1.0.0",
  "description": "- A VSCode Extension that help you to compile/transpile your SASS/SCSS files to CSS files at real-time.",
  "main": "index.js",
  "scripts": {
    "compile-scss": "sass --watch scss/main.scss css/main.css",
    "go-live": "set PORT=8000 && live-server",
    "watch-live": "npm-run-all --parallel goLive compileScss",
    "concat-css": "concat -o css/concat.css css/main.css css/src/demo1.css css/src/demo2.css",
    "prefix-css": "postcss --use autoprefixer -b 'last 10 versions' css/concat.css -o css/prefix.css"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/skyGwork/AdvancedCSS.git"
  },
  "keywords": [],
  "author": "webphin",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/skyGwork/AdvancedCSS/issues"
  },
  "homepage": "https://github.com/skyGwork/AdvancedCSS#readme",
  "devDependencies": {
    "autoprefixer": "^10.4.8",
    "concat": "^1.0.3",
    "live-server": "^1.2.2",
    "nodemon": "^2.0.19",
    "postcss-cli": "^10.0.0",
    "sass": "^1.54.0"
  }
}
```
