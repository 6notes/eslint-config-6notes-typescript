# README.md

# Useful commands

## Installation

```
npm install --save-dev git+https://github.com/6notes/eslint-config-6notes-typescript.git
```

## Uninstall

```
npm uninstall --save-dev git+https://github.com/6notes/eslint-config-6notes-typescript.git
```

## Debug

```
#Example: `npx eslint --debug eslint.config.js`
npx eslint --debug PATH_TO_YOUR_eslint.config.js
```

## Why

- `@eslint/js` is just ESLint, used for enforcing/warning rules.
- `prettier` is just Prettier, used for enforcing styles.
- `typescript-eslint` for ESLint rules for TypeScript.
- `@stylistic/eslint-plugin` is for spaces after comment lines.
  - `# Valid comment`
  - `#Invalid comment`
  - It's here because I just like the style.
- `eslint-config-prettier` to let Prettier override possible ESLint rules that
  conflict with Prettier stylistic rules.
- `eslint-plugin-sort-keys-custom-order` for ordering objects while also
  allowing customization (ex. `id` first despite alphabetical order)
- `eslint-plugin-simple-import-sort` for ordering imports
