# My first page repo

A simple practice repo for learning **ESLint**, **Prettier**, and **Husky** with basic Node tooling.

## Installation

```bash
npm install
```

**Run(dev)**

```bash
npm run dev
```

## Environment Variables

- Create a .env (or .env.local) based on this example:

`````md
`API_URL` – [API base](https://api.example.com)

## Scripts

- npm run lint – run ESLint
- npm run lint:fix – auto-fix lint issues
- npm run format – format with Prettier (if added)
- npm run prepare – installs Husky hooks (runs after npm install)

## Technologies Used

- Node.js • ESLint v9 (flat config) • Prettier • Husky • lint-staged

### `markdown-practice.md`

````md
# Markdown Practice

## Headings

### Subheading (H3)

- Bullet item one
- Bullet item two
- Bullet item three

1. First step
2. Second step
3. Third step

Inline code: run `git status` and `npm run lint`.

```bash
npm install
npm run lint
```

### Quick add → commit → push

```bash
git add README.md markdown-practice.md
git commit -m "docs: add README and markdown practice"
git push
```
````
`````
