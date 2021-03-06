---
title: ""
---

> A static website generator to create dynamic website using React components

**Note that _Statinamic_ is at an early stage, there is still some work to do,
some tests to write.**

_Do not hesitate to:_

- ask question on [the support chat](https://gitter.im/MoOx/statinamic),
- [open an issue](https://github.com/MoOx/statinamic/issues/new)
  when you find a bug (or think you have).

**Remember to look at the
[docs](https://github.com/MoOx/statinamic/tree/master/docs)
folder as a example.**

---

## Easy to use

Write your content in [Markdown](https://en.wikipedia.org/wiki/Markdown) files.
Implement your design with JavaScript files, using [React](http://facebook.github.io/react/).

No template language to learn. Just JavaScript (or JSX if you like it).

You can just grab some packages on the [NPM ecosystem](http://npmjs.org/)
to help you building your website, blog or even your small app.

_Statinamic_ will help you to generate and deploy a generated website in a
breath.


## Static and dynamic?

The technology
([React](http://jlongster.com/Removing-User-Interface-Complexity,-or-Why-React-is-Awesome)).
used to generate pages can render pages on both client and server
(~~Isomorphic~~ [Universal](https://medium.com/@mjackson/universal-javascript-4761051b7ae9)
rendering).
So when the client has established a connection with your website, they can get
the same UX as an app by grabbing the minimal amount of data for each new page.

## Choose your flavor

The way Statinamic is done helps you to customize everything:
choose your own Markdown engine (with your own plugins), your CSS preprocessor, etc
thanks to Webpack.

## Awesome DX (Developer Experience)

During development, enjoy the benefit of hot loading with visual errors in your layout !

<!--
## Setup a website in a flash

```console
$ npm install MoOx/statinamic
$ ./node_modules/.bin/statinamic new my-website
$ cd my-website
$ npm start

# Now just wait for you browser to show up :)
```

**[The _new_ command above is not ready yet](https://github.com/MoOx/statinamic/issues/16).**
-->

---

➠ [Read the documentation](docs/)
