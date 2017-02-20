## NPM - Installing a Package
Simple install (no management, package.json unchanged):
```bash
npm install d3
```
Install and update package.json:
```bash
npm install d3 --save
```

Update to package.json:
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
  "license": "ISC",
  "dependencies": {
    "d3": "^4.6.0"
  }
}
```