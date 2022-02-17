## Simple-Panel
## El mejor dashboard para Aoi.js

# ¿Como Usarme?
```js
const aoidash = require('simple-panel')
const dash = new aoidash.Dash({
port: Puerto donde la app estara,
bot: bot,
command: './commands', //Tu folder donde estan tus comandos
username: "username", //Usuario para el panel
password: "password" //Contraseña para inicar sesion
})
dash.start()
```
Pon eso después de tu const bot
## Ejemplo con Aoi.js
```js
const aoi = require("aoi.js")
const bot = new aoi.Bot({
token: "token",
prefix: "!",
intents: ["GUILDS", "GUILD_MESSAGES"]
})
const aoidash = require('simple-panel')
const dash = new aoidash.Dash({
port: 8080,
bot: bot,
command: './commands', //Tu folder donde estan tus comandos
username: "Emmaa", //Usuario para el panel
password: "i love you <3" //Contraseña para inicar sesion
})
dash.start()
```
## Prueba Beta
[Click here](https://emmaa.doctor-stars.studio)

Usuario: `user`
Contraseña: `pass`
### Creador del proyecto 
ItzEmmaa#8675 :3 Mi servidor de desarollo: [Click Aqui](https://discord.gg/2WHg3Qs6AK)


