# Vue 3 + TypeScript + Vite

Includes Tailwind CSS through the Vite plugin, ESLint for Vue and TypeScript,
and Prettier for formatting. The starter page displays Hello and a clickable counter,
with no custom styles or image assets. Tailwind is imported in `src/style.css`,
so utility classes are ready to use.

Vue Router is configured in `src/router/index.ts`, with the home page in
`src/views/HomeView.vue`. Pinia is registered in `src/main.ts`; the starter counter
uses `src/stores/counter.ts`. Production hosting should serve `index.html` for
unmatched paths to support browser history routing.

```sh
npm install
npm run dev
npm run build
npm run lint
npm run lint:fix
npm run format
npm run format:check
```

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).
