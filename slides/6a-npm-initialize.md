## NPM - Initializing Your Project
[https://docs.npmjs.com/getting-started/installing-node](https://docs.npmjs.com/getting-started/installing-node)<br /><br />
To get NPM running in your project (from your root):
```bash
npm init 
```

![NPM initialization wizard](img/npm-init-wizard.png)

Results in package.json:
```json
{
  "name": "pnwds-2017",
  "version": "1.0.0",
  "description": "Demo Site for PNWDS 2017",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}
```

Located in your project root:
![package.json](img/package.json.png)
