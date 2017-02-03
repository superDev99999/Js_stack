# JavaScript Stack from Scratch

[![Build Status](https://travis-ci.org/verekia/js-stack-from-scratch.svg?branch=master)](https://travis-ci.org/verekia/js-stack-from-scratch) [![Join the chat at https://gitter.im/js-stack-from-scratch/Lobby](https://badges.gitter.im/js-stack-from-scratch/Lobby.svg)](https://gitter.im/js-stack-from-scratch/Lobby)

[![Yarn](/img/yarn.png)](https://yarnpkg.com/)
[![React](/img/react.png)](https://facebook.github.io/react/)
[![Redux](/img/redux.png)](http://redux.js.org/)
[![ESLint](/img/eslint.png)](http://eslint.org/)
[![Webpack](/img/webpack.png)](https://webpack.github.io/)
[![Mocha](/img/mocha.png)](https://mochajs.org/)
[![Chai](/img/chai.png)](http://chaijs.com/)
[![Flow](/img/flow.png)](https://flowtype.org/)

Welcome to my modern JavaScript stack tutorial: **JavaScript Stack from Scratch**.

> **This is V2 of the tutorial, major changes happened since the initial 2016 release. See the [Change Log](/CHANGELOG.md) for more info!**

This is a minimalistic and straight-to-the-point guide to assembling a JavaScript stack. It requires some general programming knowledge, and JavaScript basics. **It focuses on wiring tools together** and giving you the **simplest possible example** for each tool. You can see this tutorial as *a way to write your own boilerplate from scratch*.

You don't need to use this entire stack if you build a simple web page with a few JS interactions of course (a combination of Browserify/Webpack + Babel + jQuery is enough to be able to write ES6 code in different files with CLI compilation), but if you want to build a web app that scales, and need help setting things up, this tutorial will work great for you.

Since the goal of this tutorial is to assemble various tools, I do not go into details about how these tools work individually. Refer to their documentation or find other tutorials if you want to acquire deeper knowledge in them.

A big chunk of the stack described in this tutorial uses React. If you are beginning and just want to learn React, [create-react-app](https://github.com/facebookincubator/create-react-app) will get you up and running with a React environment very quickly with a premade configuration. I would for instance recommend this approach to someone who arrives in a team that's using React and needs to catch up with a learning playground. In this tutorial you won't use a premade configuration, because I want you to understand everything that's happening under the hood.

Code examples are available for each chapter, and you can run them all with `yarn && yarn start` or `npm install && npm start`. I recommend writing everything from scratch yourself by following the **step-by-step instructions** of each chapter.

**Every chapter contains the code of previous chapters**, so if you are simply looking for a boilerplate project containing everything, just clone the last chapter and you're good to go.

The code of this tutorial works on Linux, macOS, and Windows.

## Table of contents

[01 - Node, Yarn, `package.json`](/tutorial/01-node-yarn-package-json)

[02 - Babel, ES6, ESLint, Flow](/tutorial/02-babel-es6-eslint-flow)

[03 - Express, PM2](/tutorial/03-express-pm2)

[04 - Webpack, React](/tutorial/04-webpack-react)

[05 - Redux, Immutable](/tutorial/05-redux-immutable)

[06 - Mocha, Chai, Mocking](/tutorial/06-mocha-chai-mocking)

## Coming up next

React Router, Server-Side Rendering, Styling, Enzyme.

## Translations

- (**Tutorial v1.0.0**) [中文](https://github.com/pd4d10/js-stack-from-scratch) by [@pd4d10](http://github.com/pd4d10)
- (**Tutorial v1.0.0**) [Italiano](https://github.com/fbertone/js-stack-from-scratch) by [Fabrizio Bertone](https://github.com/fbertone)
- (**Tutorial v1.0.0**) [日本語](https://github.com/takahashim/js-stack-from-scratch) by [@takahashim](https://github.com/takahashim)

If you want to add your translation, please read the [translation recommendations](/how-to-translate.md) to get started!

## Credits

Created by [@verekia](https://twitter.com/verekia) – [verekia.com](http://verekia.com/).

License: MIT
