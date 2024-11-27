# React + TypeScript + Vite + Tailwind

This template provides a minimal setup to get React working in Vite, TypeScript, and Tailwind.

## Getting Started 🚀

1. Clone the repo.
2. Install dependencies: `pnpm install`
3. Start the dev server: `pnpm dev`

### Or

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmoinulmoin%2Fchadnext&env=POSTGRES_PRISMA_URL,POSTGRES_URL_NON_POOLING,GITHUB_CLIENT_ID,GITHUB_CLIENT_SECRET,NEXTAUTH_SECRET,NEXTAUTH_URL,NEXT_PUBLIC_APP_URL,RESEND_API_KEY,UPLOADTHING_SECRET,UPLOADTHING_APP_ID,UPLOADTHING_URL)

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## License 📄

MIT License. [LICENSE](https://github.com/moinulmoin/chadnext/blob/main/LICENSE)