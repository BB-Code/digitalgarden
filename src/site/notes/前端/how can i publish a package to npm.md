---
{"dg-publish":true,"dg-home":true,"permalink":"/前端/how can i publish a package to npm/","tags":["gardenEntry"],"dgPassFrontmatter":true,"noteIcon":""}
---



>init a repo

`npm init -y`


>write a  js file call index.js


```js
console.log(new Date().getTime())
```

>modify package.json

```json
bin: './index.js'
```

>publish repo


run `npm publish `