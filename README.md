# @madebywild/config-prettier

To use it in your project, you need to install this package and prettier:

```bash
npm i @madebywild/config-prettier prettier --save-dev
```

Then, edit your projects `package.json`:

```json
{
  "prettier": "@madebywild/config-prettier"
}
```

How to bump version:

```bash
npm version patch -m "Bumped version" && npm publish --access public
```
