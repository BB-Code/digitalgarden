---
{"dg-publish":true,"dg-home":false,"permalink":"/前端/how can i use node.js create a server/","dgPassFrontmatter":true,"noteIcon":""}
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

<script src="https://utteranc.es/client.js"
        repo="BB-Code/digitalgarden"
        issue-term="pathname"
        theme="github-dark-orange"
        crossorigin="anonymous"
        async>
</script>