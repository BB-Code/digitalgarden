---
{"dg-publish":true,"permalink":"//how-can-i-use-node-js-create-a-server/","tags":["gardenEntry"]}
---



> tools


download the node.js 
download the vscode


>write code call with sever.js in a file

```js
const http = require('http');
http.createServer((req,res)=>{
	ress.send('server is running')
}).listen(3000)
```


>run code

open cmd and run `node sever.js`
