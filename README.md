# @releaseband/prettier-config

prettier shareable config

## Installing

```bash
npm i -D @releaseband/prettier-config
npx install-peerdeps --dev @releaseband/prettier-config
```

create `.prettierrc.js` file in the **root project folder**:

```js
module.exports = require('@releaseband/prettier-config');
```

create `.prettierignore` file in the **root project folder**:

```text
node_modules/
.idea/
.vscode/
.history/
CHANGELOG.md
```

add script in `package.json`:

```json
{
  "scripts": {
    "prettier": "prettier . --write --ignore-unknown"
  }
}
```
