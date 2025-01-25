# Automate Code Formatting
Sample repo for my blog post 📝 [Automate Code Formatting with Prettier, ESLint, Husky, and lint-staged](https://blog.alyssaholland.me/automate-code-formatting)

## Install Dependencies
```
npm install
```

## Prettier
**Check if files are formatted**
```
npm run prettier:check
```

**Format files supported by Prettier**
```
npm run prettier:write
```

## ESLint
**Lint files**
```
npm run lint
```

**Fix files**
```
npm run lint:fix
```
This option instructs ESLint to try to fix as many issues as possible. The fixes are made to the actual files themselves and only the remaining unfixed issues are output.
