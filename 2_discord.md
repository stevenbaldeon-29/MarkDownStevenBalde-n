# Documentació del Bot de Discord

![logotipo discord](https://tse2.mm.bing.net/th/id/OIP.QRS9vpssDlJVqDEALDpkWQHaFa?r=0&pid=Api&h=220&P=0)

Pots registrar la teva aplicació al [Portal de Desenvolupadors de Discord]( https://discord.com/developers/applications)

Per fer que el bot respongui, escoltem
l'esdeveniment `messageCreate` i utilitzem el `mètode message.reply()`.

```JAVASCRIPT
client.on('messageCreate', message => {
if (message.content === 'ping') {
message.reply('pong!');
}
});
```
