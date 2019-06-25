# dev-tailwindcss

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## tailwind

### install

```
# Using npm
npm install tailwindcss --save-dev

# Using Yarn
yarn add tailwindcss --dev
```

### tailwind.css

```
// src/assets/css/tailwind.css
@tailwind base;

@tailwind components;

@tailwind utilities;
```

### Import this css file inside main.js entry file.

```
// main.js

// other imports
import '@/assets/css/tailwind.css'
```

### Configure PostCSS

```
yarn tailwind init
# or npx tailwind init
```

modify `package.json`

```
"postcss": {
    "plugins": {
      "tailwindcss": "./tailwind.config.js",
      "autoprefixer": {}
    }
},
```

### Reference

[Setup Tailwind@next in Vue CLI 3 project](https://gokatz.me/blog/setup-tailwind-vue-3-project/)