# Installing

create [.npmrc](https://docs.npmjs.com/cli/v7/configuring-npm/npmrc) file in the **root project folder**:

```
echo @releaseband:registry=https://npm.pkg.github.com > .npmrc
```

```
npm i -D @releaseband/prettier-config
npx install-peerdeps --dev @releaseband/prettier-config
```

`prettier.config.js`:

```js
module.exports = require('@releaseband/prettier-config');
```
