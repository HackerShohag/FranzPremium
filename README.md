<img src="./build-helpers/images/icon.png" alt="" width="150"/>

# Franz 5 (Premium) [![Build and Release](https://github.com/HackerShohag/FranzPremium/actions/workflows/main.yml/badge.svg)](https://github.com/HackerShohag/FranzPremium/actions/workflows/main.yml)

Messaging app for WhatsApp, Slack, Telegram, HipChat, Hangouts and many many more. Find the premium build in the artifacts section.

## [Download Franz](https://www.meetfranz.com)
👉 www.meetfranz.com

### Or use homebrew (macOS only)

`$ brew cask install franz`

(Don't know homebrew? [brew.sh](https://brew.sh/))

## Development

### Preparations

#### Install Linux OS dependencies
[Guide: Linux distribution specific dependencies](docs/linux.md)

#### Fix native modules to match current electron node version
```bash
$ npm run rebuild
```

### Install dependencies
Run the following command to install all dependencies, and link sibling modules with Franz.
```bash
$ npx lerna bootstrap
```

If you previously ran `npm install` it sometimes is necessary to delete your `node_modules` folder before running `npx lerna bootstrap`. 

### Run Franz Development App
Run these two commands __simultaneously__ in different console tabs.

```bash
$ npm run dev
$ npm run start
```
Be aware that the development database will be reset regularly.

## Packaging
```bash
$ npm run build
```

## How can I support the project?
If you have found a bug that hasn't been reported yet or want to request a new feature, please open a new issue.

## I need help?
Join the Franz community on [Slack](http://slack.franz.im) and get in touch with us.

## Create your own plugins/recipes
You can find all the Information at the [Plugins repository](https://github.com/meetfranz/plugins).
For questions feel free to ask in the [community Slack](http://slack.franz.im)

## License
Franz 5 is open-source licensed under the Apache-2.0 License.
