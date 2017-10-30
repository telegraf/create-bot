# create-bot
[![NPM version](https://img.shields.io/npm/v/create-bot.svg?style=flat)](https://npmjs.com/package/create-bot)

CLI for fast Telegram Bot scaffolding.

## Install

🔥 If you have installed `yarn^0.24` or `npm5` you good to go without any extra installation!
Just call `yarn create bot` or `npx create-bot`:

```bash
npx create-bot cool-bot
cd cool-bot
```

```bash
yarn create bot cool-bot
cd cool-bot
```

## Local install

Using `npm`:

```bash
yarn global add create-bot
```

Or using `yarn`:

```bash
npm install create-bot -g
```

## Usage

```bash
# Generate project in specific folder
create-bot cool-bot
cd cool-bot
```

# Credits

This is a [CLI](https://en.wikipedia.org/wiki/CLI) that wraps [SAO](https://github.com/egoist/sao) and [template-bot](https://github.com/telegraf/template-bot), so running `create-bot cool-bot` is equivalent to running `sao bot cool-bot`.
