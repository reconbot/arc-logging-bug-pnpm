# reproduce pnpm warning bug

- `npm install -g pnpm` # feel free to delete this when you're done it's just an npm package
- `pnpm i`
- `pnpm start`


```sh

    http://localhost:3333

✓ Sandbox Started in 18ms
❤︎ Local environment ready!

⚠️ Warning: You may have a dependency that could be inaccessible in production
  | Please run: npm i .pnpm
⚠️ Warning: You may have a dependency that could be inaccessible in production
  | Please run: npm i .pnpm
  ```
