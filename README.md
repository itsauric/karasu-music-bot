# Karasu

This is a music bot created by using the [sapphire framework][sapphire] & [discord-player@dev][discord-player] with this project being written in TypeScript

### Prerequisite

```sh
yarn install
yarn build
```

You should also go to `src/.env` and put in your `TOKEN` & `OWNERS` IDs, it is also recommended to add `src/.env` to your `.gitignore`

### How can I generate a command?

```sh
sapphire generate command <name>
```

### Development

This example can be run with `tsc-watch` to watch the files and automatically restart your bot.

```sh
yarn run watch:start
yarn dev
```

### Hot Module Reloading

It is advised to firstly build the dist folder and then use `yarn dev`, this will enable [@sapphire/plugin-hmr][sapphire-hmr] and will actively reload modules when they are updated.

## License

Dedicated to the public domain via the [Unlicense], courtesy of the Sapphire Community and its contributors ---> generated from the Sapphire CLI

[sapphire]: https://github.com/sapphiredev/framework
[sapphire-hmr]: https://www.npmjs.com/package/@sapphire/plugin-hmr
[discord-player]: https://github.com/Androz2091/discord-player/tree/develop
[unlicense]: https://github.com/sapphiredev/examples/blob/main/LICENSE.md
