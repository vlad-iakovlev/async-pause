# async-pause

Asynchronous pause

![GitHub CI](https://img.shields.io/github/workflow/status/vlad-yakovlev/async-pause/CI/main?label=github-ci)
[![Codecov](https://img.shields.io/codecov/c/github/vlad-yakovlev/async-pause/main)](https://codecov.io/gh/vlad-yakovlev/async-pause)
[![NPM](https://img.shields.io/npm/v/async-pause)](https://www.npmjs.org/package/async-pause)

## How to install

```sh
npm install async-pause
```

## How to use

```ts
import { asyncPause } from 'async-pause'

(async () => {
  console.log('foo');
  await asyncPause(1000);
  console.log('bar'); // Will be executed after a second
})();
```
