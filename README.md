# @necrobits/vite-plugin-semi-theme
This is a fork from https://github.com/boenfu/vite-plugin-semi-theme, which contains urgent bug fixes
- [theme options docs](https://github.com/DouyinFE/semi-design/tree/main/packages/semi-webpack#api)

```js
// vite.config.js
import { defineConfig } from "vite";
import semi from "vite-plugin-semi-theme";

export default defineConfig({
  plugins: [
    semi({
      theme: "@semi-bot/semi-theme-yours",
      // options: {
      // ... 👆
      //},
    }),
  ],
});
```
