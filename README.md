# Vite Tauri Template
This is a starter template for those who want to make a desktop application with web technologies. This template uses the below stack.

## Vite.js
[Vite.js](https://vitejs.dev/) is a new modern bundler for javascript which is blazing fast and includes many sensible defaults.

## Vue 3
[Vue.js](https://vuejs.org/) is an incremental frontend framework which is an absolute joy to work with. It has seen very impressive improvements in version 3 including Composition Api, script setup, dynamic css binding and ... .

## Vuetify 3
[Vuetify](https://vuetifyjs.com/) is arguably the best component library for Vue 3 and is currently in alpha stage but will soon be ready for production. Lots of premade components will make your job as application developer easier and more fun.

### Bonus: Vue Global Api
[Vue Global Api](https://github.com/antfu/vue-global-api) globally registers commonly used composition api functions such as `ref`, `reactive` and ... . makes your `script setup` sections cleaner.

## Installation

- `yarn`  or `npm i`

- Modify these files according to your app.
  - `index.html`
  - `package.json`
  - `public/favicon.ico`
  - `src/assets/logo.*`
  - `src-tauri/tauri.conf.json`

## Usage

- `yarn serve` launches vite and you can test and develop your app in the browser at `http://localhost:8080`.

- `yarn build` builds web application and packages them with tauri in `src-tauri/target`


## License
Do whatever you want with it!
