# 🔥 Next.js boilerplate made by Arthouse

**Features:**

- Focus on DX
- Next.js w/ Typescript
- Tailwind
- ESLint + Prettier
- Configured VSCode
- Pre-Commit linter via Husky
- Webpack Bundle Analzyer
- Next.js Bundle Analysis Github Action
- Yarn

Todo:

- Bundle Analyzer
- Configured Next SEO https://github.com/garmeeh/next-seo
  - SEO metadata
  - JSON-LD
  - Open Graph
- i18n w/ next-translate + language-switcher component
- Themable
- One-click deploy to Netlify and Vercel

Maybe:

- Preact Option

## Getting started

Local dev

```
yarn dev
```

## Next.js w/ Typescript

- Explain .tsconfig.json (Path aliases), next.config.js

# Tailwind

CSS Reset

## ESLint + Prettier

- Explain .eslintrc.json, .eslintignore, .prettierrc.json, .prettierignore
- VSCode config

## Configured VSCode

Explain:
.vscode/extensions.json
.vscode/settings.json

## Bundle Analysis

- Webpack
- Next.js

From https://github.com/hashicorp/nextjs-bundle-analysis:
Since this plugin works by comparing the base bundle against each PR, the first time it is run, it will fail since it has no base to compare against. This is expected - ideally you can just commit the changes directly to your default branch, where it will run to generate the base bundle, then anything that branches off after that will have a valid comparison point and the script will work as expected.

## License

Licensed under the MIT License, Copyright © 2021
