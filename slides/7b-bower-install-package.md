## Bower - Installing a Package
Simple install (no management, bower.json unchanged):
```bash
bower install bootstrap
```
Install and update bower.json:
```bash
bower install bootstrap --save
```

Update to bower.json:
```json
{
  "name": "pnwds-2017",
  "authors": [
    "Andrew Howell <ahowell@forumone.com>"
  ],
  "description": "Demo Site for PNWDS 2017",
  "main": "",
  "license": "MIT",
  "homepage": "",
  "ignore": [
    "**/.*",
    "node_modules",
    "bower_components",
    "test",
    "tests"
  ],
  "dependencies": {
    "bootstrap": "^3.3.7"
  }
}
```