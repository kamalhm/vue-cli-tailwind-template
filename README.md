# Vue CLI Tailwindcss Template

## Rough steps to configure manually

1. Create a vue project
2. Add tailwindcss with `yarn add tailwindcss`
3. Separate postcss config (optional)
4. Create tailwind.css file in `./src/assets/css/tailwind.css` 
   Fill tailwind.css with
   ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities; 
    ```
5. Initialize tailwind config with `npx tailwind init`
6. Use tailwind.css from App.vue's styles


## Contributing

This is very rough steps that I create due to not finding an updated way to install tailwindcss into vue-cli, and I'm not even sure that it's optimal, if you know a better way, please don't hesitate to make a pull request!


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
