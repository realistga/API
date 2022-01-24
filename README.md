# realist.js
<a href="https://discord.gg/8ZBYQAS4Q9" target="_blank"><img src="https://img.devsforum.net/tr/img/h1Z2X3.png" alt="Join our discord" width="256"></a><br>
**Support:** [https://discord.com/MsdGCyC3ry](https://discord.com/MsdGCyC3ry) <br>
**NPM:** [npmjs.com/package/realist.js](https://www.npmjs.com/package/realist.js)<br>

## Installation
*If you have trouble with the installation, please feel free to visit our [discord](https://discord.com/MsdGCyC3ry) address.*
- `npm i realist.js`

# Define Module & Client
```js
const Discord = require("discord.js");
const client = new Discord.Client();
const realist = require("realist.js");
const dbl = new realist("TOKEN-HERE", client);

client.login("MTk4NjIyNDgzNDcxOTI1MjQ4.Cl2FMQ.ZnCjm1XVW7vRze4b7Cq4se7kKWs");
```

# Certificate Application
```js
dbl.certificateApplication("Bla bla bla bla bla bla bla bla bla bla bla bla...", () => {
    console.log("Certificate successfully applied.");
})
```

# Vote Checking
```js
dbl.checkVote("userId").then((value) => {
    if(value === 1) {
        console.log("User voted.")
    } else {
        console.log("User not voted.")
    }
})
```


# All Operations
```js
const realist = require('vcodes.js');
const { Client } = require("discord.js");
const client = new Client();
const dbl = new vCodes("vCodes-Bot-Token-Here", client)

dbl.on("ready", () => {
    console.log('vCodes ready!')
})

dbl.checkVote("userId").then((value) => {
    if(value === 1) {
        console.log("User voted.")
    } else {
        console.log("User not voted.")
    }
})

dbl.certificateApplication("Bla bla bla bla bla bla bla bla bla bla bla bla...", () => {
    console.log("Certificate successfully applied.");
})

client.on("ready", () => {
    console.log("Logged as in "+client.user.tag)
})

client.login("Discord-Bot-Token")
```

