# react-sass-boilerplate

## Install

```
$ npm install
```

## Development

```
$ npm start
```

Go to http://localhost:3000

```
$ npm run sass
```

Compile SCSS to CSS

```js
// package.json
"scripts": {
    "sass": "node-sass -wr --source-map true SCSS-FILE_PATH CSS-FILE_PATH"
  },
```

Customize file path

(※ [Options](https://www.npmjs.com/package/node-sass#command-line-interface): watch, recursive, source-map)

## Production

Set the `NODE_ENV` to production

```
$ NODE_ENV=production npm start
```

## Option

```json
// package.json
"author": "AUTHOR_NAME <AUTHOR_EMAIL@email.com> (https://AUTHOR_URL.com)"
```

Set the package `author` name, email, url(optional)

## License

[MIT license](https://github.com/facebook/react/blob/master/LICENSE)
