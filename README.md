# @madebywild/prettier-config

To use it in your project, you need to install this package and prettier:

```bash
npm i @madebywild/prettier-config prettier --save-dev
```

Then, edit your projects `package.json`:

```json
{
  "prettier": "@madebywild/prettier-config"
}
```

How to bump version:

```bash
npm version patch -m "Bumped version" && npm publish --access public
```
