# Introduction to the NodeJS ecosystem
*[Jonas Weber](https://github.com/a_jaguar), [Dominik Schreiber](https://github.com/dominikschreiber)*
January 2016

This is an interactive script to accompany the NodeJS introductionary workshop at the *Programmierwochende '16*. It assumes basic knowledge of programming concepts and the usage of git, but gives a brief intro in mentioned concepts when they occur.

## How to read

The interactivity of this script is reached by serving different chapters as *git branches*. To advance to chapter `n` one will perform

```bash
git checkout chapter-n
```

which switches the git repository to the branch representing the next chapter.

In every branch, the textual content is contained in the [`README.md`](./README.md). The reader will as well find a `spec.js` that states the goals of the chapter using [mocha](http://mochajs.org/) and a near-empty `index.js` where he is asked to perform exercises in. Furthermore there is a `package.json` that defines [npm](https://npmjs.org)-related tasks and &ndash; for the most of the time &ndash; can be ignored.

After solving the exercises in `index.js` the reader may test its solution using

```bash
npm test
```

## Preliminaries

In order to follow the exercises, we ask the reader to install

- *git* &ndash; either bare-bones from [git-scm.com](http://git-scm.com/) or packaged into the [GitHub Desktop Client](https://desktop.github.com/)
- [*NodeJS*](https://nodejs.org) &ndash; this contains [npm](https://npmjs.org) as well.