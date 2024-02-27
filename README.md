# Minecraft Bedrock Online Bot with Xbox account for server
## How to use
### Command line
Create a file and name it **index.js**
paste this code in **index.js** file 
```js
const bedrock = require('bedrock-protocol')
const client = bedrock.createClient({
  host: 'myrandomserver.net',   // optional
  port: 19132,         // optional, default 19132
  username: 'auth is false',   // the username you want to join as, optional if online mode
  offline: false       // optional, default false. if true, do not login with Xbox Live. You will not be asked to sign-in if set to true.
})
```
run: ``npm init -y``

then run: ``npm install bedrock-protocol``

To start the bot run: ``node index.js``- required your server be online 
- to add your server ip open index.js then put replace **myrandomserver.net** your server ip
### Discord
https://discord.gg/wGx6kK5C3q
### Video Tutorial
https://youtu.be/vwoQPdJaC7o?si=u9dk30-iIVcJteSr
