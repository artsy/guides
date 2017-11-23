## JavaScript General

### Language

* Use TypeScript for larger projects.
* If it's a small project or a quick script, using a modern version of node can help avoiding transpilation. This
  greatly simplifies using the project as a dependency or working on it.

### Features

* Use ES6's `export` and `import` syntax.
* Avoid [using default exports][defaults]. If you have specific reasons for using a default export, use syntax like:

```js
const myThing = "Hello"
export default myThing
```

Which will work around a few of the issues.

[defaults]: https://basarat.gitbooks.io/typescript/docs/tips/defaultIsBad.html
