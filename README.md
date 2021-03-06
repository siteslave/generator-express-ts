# generator-express-ts 
[![NPM version][npm-image]][npm-url] [![NPM downloads](https://img.shields.io/badge/download-100%2B%2Fmonth-green.svg?style=flat)](https://www.npmjs.com/package/generator-express-ts)
> Yeoman generator for creating an application using Express and TypeScript.

## Installation

First, install [Yeoman](http://yeoman.io) and generator-express-ts using [npm](https://www.npmjs.com/) (we'll assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo typescript
npm install -g generator-express-ts
```

Then generate your new project:

```bash
yo express-ts
```

After generating your project, cd into it, compile TypeScript files into JavaScript files:
```bash
tsc
```

After everything is finished, run your project:
```
node app/bin/www.js --harmony
```

## Getting To Know Yeoman

Yeoman has a heart of gold. He&#39;s a person with feelings and opinions, but he&#39;s very easy to work with. If you think he&#39;s too opinionated, he can be easily convinced. Feel free to [learn more about him](http://yeoman.io/).

## License

MIT © [infeng](https://github.com/infeng)


[npm-image]: https://badge.fury.io/js/generator-express-ts.svg
[npm-url]: https://npmjs.org/package/generator-express-ts
[travis-image]: https://travis-ci.org/infeng/generator-express-ts.svg?branch=master
[travis-url]: https://travis-ci.org/infeng/generator-express-ts
[daviddm-image]: https://david-dm.org/infeng/generator-express-ts.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/infeng/generator-express-ts
[coveralls-image]: https://coveralls.io/repos/infeng/generator-express-ts/badge.svg
[coveralls-url]: https://coveralls.io/r/infeng/generator-express-ts
