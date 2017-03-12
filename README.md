# polymer-redux [![build](https://travis-ci.org/daggerok/polymer-redux.svg?branch=master)](https://travis-ci.org/daggerok/polymer-redux)

- all friends-* conponents are loosely-coupled
- components knowns nothing about each other and theirs data
- polymer-redux using ReduxBehavior mixin, provides to each component automatically listening of redux store
- friends-input component is dispatching the data
- friends-counter and friends-list having properties with statePath, to listen store ations

```bash
npm i
npm start
```

update npm versions

```bash
npm i -g npm-check-updates
ncu -u
```
