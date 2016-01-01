# Getting to know NodeJS (hello world version)

Looks like you've managed to open the first chapter. Great! Now, let's dig into work:

In this chapter, the you will

- get an overview of *what NodeJS is*,
- verify that your *NodeJS installation works*,
- write a basic *Hello, World!* script, and
- execute that script *on your machine*.

## What is NodeJS, anyways?

A formal introduction of NodeJS is out of scope for this course, but in minimal words it is

- the [V8 JavaScript engine](https://developers.google.com/v8/) (the one that's running in Chrome as well)
- enriched with some [native bindings](https://www.npmjs.com/package/node-gyp), and
- packaged to an application that is capable of executing JavaScript files.

That, for itself, is not much, but is has a great deal of implications:

- an asynchronous programming model that suits web tasks better than most traditional web servers do,
- a fast-growing community with [3rd-party modules](https://www.npmjs.com/) for nearly every task (see `chapter-2`), as well as
- a single programming language for both client and server.

*(We'll elaborate on the aforementioned properties in this course, so it's not a great deal if you didn't get every aspect right now.)*

## Using NodeJS

NodeJS is a command line application, there is (by default) no fancy front-end to it. That means, you have to open a console (chances are you have the one where you performed `git checkout chapter-1` already open).

Now, to run anything using the `node` binary, you have to type exactly that into the command line:

```bash
node
```

The [REPL](https://nodejs.org/api/repl.html) (*R*ead-*E*valuate-*P*rint-*L*oop) opens. You can now type arbitrary JavaScript code:

```javascript
> 1 + 1
```

To close the REPL press `ctrl+d`.

A more common way to test if a command line program is working is to ask for its version:

```bash
node --version
```

You can get a list of all [flags](https://en.wikipedia.org/wiki/Command-line_interface#Command-line_option) by running

```bash
node --help
```

## Hello, World!

Now, to the obligatory [Hello, World!](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) script.

Open `index.js` and fill it with `'Hello, World!'`.

```javascript
// file: index.js
process.stdout.write('Hello, World!')
```

This is the minimal portion of code: a *String* (the `'…'`) that is written (`write`) to the standard output (`stdout`) of the current `process`.

To execute it, run

```bash
node index.js
```

This is basic way of running NodeJS programs: there is a JavaScript file (`index.js`) that is executed by the `node` binary.

## Hello, Chapter 2!

You've got it. Great!

To advance to the next chapter, run

```bash
git checkout chapter-2
```