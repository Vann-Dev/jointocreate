## Introduction

> A simple package that allow to make private voice channel at discordjs

## Support

[Support server](https://discord.gg/hM8U8cHtwu) <a href = "https://discordapp.com/users/435497505883422721/"><img src = "https://imgur.com/RSEvkDl.png" height= 15px width = 15px> Discord </a>&nbsp;&nbsp;


## Code Samples

This is a sample code to use this package

```
const { client } = require("discord.js");
const client = new Client();
const { joinToCreate } = require('jointocreate')

client.on("ready", ()=>console.log("READY"));

//import the  joinToCreate package
jointocreate(client, 'YOUR_CHANNEL_ID');

client.login('YOUR_BOT_TOKEN')
```
