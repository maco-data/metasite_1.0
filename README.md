# metasite_1.0

Fully functioning website using Next13, Framer Motion, and Tailwind CSS

## What I learned

-   Learned to put code snippets in the README file by using markdown syntax.

-   After having all the files set I tried running `npm run dev` but recieved the following error:

```console
> metaverse13@0.1.0 dev
> next dev

 sh: next: command not found
```

Checking the files with `npm ls` I found that some dependencies were not installed in the project:

```console
metaverse13@0.1.0 /Users/user/metasite_1.0
├── UNMET DEPENDENCY autoprefixer@^10.4.13
├── UNMET DEPENDENCY eslint-config-airbnb@^19.0.4
├── UNMET DEPENDENCY eslint-config-next@13.0.3
├── UNMET DEPENDENCY eslint-plugin-import@^2.26.0
├── UNMET DEPENDENCY eslint-plugin-jsx-a11y@^6.6.1
├── UNMET DEPENDENCY eslint-plugin-react-hooks@^4.6.0
├── UNMET DEPENDENCY eslint-plugin-react@^7.31.10
├── UNMET DEPENDENCY eslint@^8.27.0
├── UNMET DEPENDENCY framer-motion@^7.6.7
├── UNMET DEPENDENCY next@13.0.3
├── UNMET DEPENDENCY postcss@^8.4.19
├── UNMET DEPENDENCY react-dom@18.2.0
├── UNMET DEPENDENCY react@18.2.0
└── UNMET DEPENDENCY tailwindcss@^3.2.4

npm ERR! code ELSPROBLEMS
npm ERR! missing: autoprefixer@^10.4.13, required by metaverse13@0.1.0
npm ERR! missing: eslint-config-airbnb@^19.0.4, required by metaverse13@0.1.0
npm ERR! missing: eslint-config-next@13.0.3, required by metaverse13@0.1.0
npm ERR! missing: eslint-plugin-import@^2.26.0, required by metaverse13@0.1.0
npm ERR! missing: eslint-plugin-jsx-a11y@^6.6.1, required by metaverse13@0.1.0
npm ERR! missing: eslint-plugin-react-hooks@^4.6.0, required by metaverse13@0.1.0
npm ERR! missing: eslint-plugin-react@^7.31.10, required by metaverse13@0.1.0
npm ERR! missing: eslint@^8.27.0, required by metaverse13@0.1.0
npm ERR! missing: framer-motion@^7.6.7, required by metaverse13@0.1.0
npm ERR! missing: next@13.0.3, required by metaverse13@0.1.0
npm ERR! missing: postcss@^8.4.19, required by metaverse13@0.1.0
npm ERR! missing: react-dom@18.2.0, required by metaverse13@0.1.0
npm ERR! missing: react@18.2.0, required by metaverse13@0.1.0
npm ERR! missing: tailwindcss@^3.2.4, required by metaverse13@0.1.0

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/user/.npm/_logs/2022-11-26T13_51_48_581Z-debug-0.log
```

This happened becaused I did not installed the project dependencies.

To fix this problem I ran `npm install`. After this I managed to run the command `npm run dev` and everything was fine with the project.

-   Learned about the structure of a Next 13 application.

-   Used set variables for repeating code. This technique helped me save time as it is code I used in diferent parts.

-   Learned to debug the my code, sometimes there were grammar errors or the incorrect syntax.

## Deployment on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

[Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

