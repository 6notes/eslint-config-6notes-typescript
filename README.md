# README.md

# Installation

```
npm install git+https://github.com/6notes/eslint-config-6notes-typescript.git
```

## Why

- `@eslint/js` is just ESLint, used for enforcing/warning rules.
- `@eslint/js` is just Prettier, used for enforcing styles.
- `@stylistic/eslint-plugin` is for spaces after comment lines.
  - `# Valid comment`
  - `#Invalid comment`
  - It's here because I just like the style.
- `eslint-config-prettier` to let Prettier override possible ESLint rules that
  conflict with Prettier stylistic rules.
- `typescript-eslint` for ESLint rules for TypeScript.
- `eslint-plugin-sort-keys-custom-order` for ordering objects while also
  allowing customization (ex. `id` first despite alphabetical order)
- `eslint-plugin-simple-import-sort` for ordering imports
