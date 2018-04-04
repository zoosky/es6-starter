# es6-starter
ES6, babel, webpack, rollup project starter.

**Start**

Write all of your ES6 shits in the `src` folder.

**Build**

*Webpack*

To transpile your ES6 code to ES5 use the command `npm run build:webpack`. This will create a `commonjs2` ES5 version (usable for nodejs `required()` or `import`) of your code from `src` in the `dist` folder.

*Rollup*

Use the command `npm run build:rollup` to build a `umd` version (for browser) of the sample code.

Usage - `<script src="path/to/code"></script>`

**Test** *(not unit test)*

This repo comes with a running sample. To see the running sample do the following : 

1. Build the source code, both `webpack` and `rollup`.
2. To test the webpack build, run `npm run test:runscript`.
3. To test the rollup build, run `npm run test:openbrowser` or run `tester.html` in your browser and see the console logs.

**Commands**

- `npm run start:dev` or `yarn start:dev` - runs the build script with `--watch` flag.
- `npm run build:webpack` or `yarn build:webpack` - builds the code from `src` using webpack.
- `npm run build:rollup` or `yarn build:rollup` - builds the code from `src` using rollup.
- `npm run build:all` or `yarn build:all` - builds both webpack and rollup.
- `npm run test:runscript` or `yarn test:runscript` - will run the code from `dist` folder using nodejs.

> Happy coding!

**Made with :heart: by Jofferson Ramirez Tiquez**

See 
* https://github.com/babel/babel-preset-env/issues/203
* http://babeljs.io/learn-es2015/
