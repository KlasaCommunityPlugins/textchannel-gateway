# Getting Started

## Installing the channel gateways plugin

> This requires Klasa Master and Discord.js Master

To get the functionality of the plugin you will need to first install it and then include it in your Client.

> I assume you know how to open a command prompt in a folder where you want to install this. Please don't prove me wrong.

```sh
npm install --save @kcp/channel-gateways
```

### Using the plugin

In your main file which contains

```js
const { Client } = require('klasa');
```

you need to put

```js
const { Client } = require('klasa');

Client.use(require('@kcp/channel-gateways'));
```

and then you can continue your bot as normal.
