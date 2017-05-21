# create-bot
[![NPM version](https://img.shields.io/npm/v/create-bot.svg?style=flat)](https://npmjs.com/package/create-bot)

This is a [CLI](https://en.wikipedia.org/wiki/CLI) that wraps [SAO](https://github.com/egoist/sao) and [template-bot](https://github.com/telegraf/template-bot), so running `create-bot my-bot` is equivalent to running `sao bot my-bot`.

## Install

```bash
npm install create-bot -g
```

Or using `yarn`

```bash
yarn global add create-bot
```

## Usage

```bash
# Generate project in specific folder
create-bot my-bot
cd my-bot
```

Alternatively, if you have `yarn^0.24`, you can use the `yarn create` command:

```bash
yarn create bot my-bot
```
