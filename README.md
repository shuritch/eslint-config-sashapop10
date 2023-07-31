<h1 align="center">My ESlint config</h1>

**1**. Install required packages: <br/>

```bash
npm i -D eslint prettier eslint-plugin-import eslint-config-sashapop10 eslint-config-prettier eslint-plugin-prettier
```

**2**. Add `"extends": ["sashapop10"]` to your `.eslintrc`.

**3**. _(optional)_ Add following scripts

```json
// package.json
{
  "scripts": {
    "lint": "eslint . && prettier --check \"**/*.js\" \"**/*.json\" \"**/*.md\" \".*rc\" \"**/*.yml\"",
    "fmt": "prettier --write \"**/*.js\" \"**/*.json\" \"**/*.md\" \".*rc\" \"**/*.yml\"",
    "test": "npm run -s lint"
    //...
  }
  //...
}
```

<h2 align="center">Copyright & contributors</h2>

<p align="center">
Copyright © 2023 <a href="https://github.com/LeadFisherSolutions/eslint-config-leadfisher/graphs/contributors">sashapop10</a>.
eslint-config-sashapop10 is <a href="./LICENSE">MIT licensed license</a>.<br/>
</p>
