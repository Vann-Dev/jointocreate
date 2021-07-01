## Introduction

> A simple package that allow to make private voice channel at discordjs



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
