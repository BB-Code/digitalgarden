---
{"dg-publish":true,"dg-home":true,"permalink":"/前端/how can i use node.js create a server/","tags":["gardenEntry"],"dgPassFrontmatter":true}
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
