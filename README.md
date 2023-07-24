# Chrome Extension with Vue 3 + Vite

This template should help get you started developing a Chrome extension with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.


## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.<br>

### `npm run build`

Builds the app for production to the `dist` folder.<br>

## Install the extension

When the build completes, open Chrome or Edge and navigate to chrome://extensions. Make sure to turn on the developer mode switch.<br>

Drag your dist folder into the Extensions Dashboard to install it. Your extension icon will be in the top bar. The icon will be the first letter of the extension's name.<br>

## Profit with Vite HMR

Once you've found the extension icon, right-click it and choose "Inspect popup window". This will open the popup and the popup dev tools window. We need to inspect the popup to keep it open while making changes.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).
