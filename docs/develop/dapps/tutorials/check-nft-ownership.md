---
description: This tutorial will show to you how to create Nft ownership checking telegram bot app, using ton.js, Ton Connect 2.0 and tonapi.io
---

# Check NFT ownership with TON

## 📖 What you'll learn

In this article, you'll learn how to:

- create a Telegram Bot connected with TON (using ton.js)
- work with tonapi.io in order to check ownership of NFT
- apply TON Connect 2.0 auth standard in a bot UI

Finally, develop an easy-to-use Telegram bot application that allows users to quickly and easily verify the ownership of their NFTs.

## 📒 Prerequisites 

Before we begin, please make sure you have the following things installed:

- [NodeJS](https://nodejs.org/en/download/)(Look for 16 version)
- A TON Connect compatible wallet (e.g. [Tonkeeper](https://tonkeeper.com/))


```
## 🚀 Let's get started!

Open your editor (preferably Visual Studio) and in the terminal and run 

```
bash npm2yarn
npx create-react-app nft_check --template typescript
```

This will create the usual typescript template application. You can run it using these commands.

```
bash npm2yarn
npm install
npm start

```
This will give you an example counter app. Now, let's install the needed dependencies. 

- grammy
- ton
- dotenv
- ton connect UI React 

You can install them using this command.

```
bash npm2yarn

npm install ton dotenv grammy @grammyjs/conversations @tonconnect/ui-react

Now let's create new structure and add the following folders under src : bot, hooks. You can already create .env file, we will fill it in later. 


## 🛠️ Creating Bot on Telegram 

First things first, we need to get an api token from [BotFather](https://t.me/botfather) by sending message. Then you perform /start, /newbot, then name your app and get your api token.

We will be using [Grammy] framework for [Telegram Web Application for Bots](https://core.telegram.org/bots). 

After general clean up, new App.js page will look like this:

```js


```


### Bot start

To start use this command:


```
bash npm2yarn
npm start

```

If your bot doesn't work correctly, compare your code with non template version [from this repository](https://github.com/murluki/telegram_bot_nft_check_no_template) or [from this repository](https://github.com/murluki/telegram_nft_check). If it didn't help, feel free to write me in telegram. You can find my telegram account below.

## References

 - Made for TON as part of [ton-footsteps/173](https://github.com/ton-society/ton-footsteps/issues/173)
 - By Murluki([Telegram @murluki_prg](https://t.me/murluki_prg), [Murluki on GitHub](https://github.com/murluki))
 - [Non template code version](https://github.com/murluki/telegram_bot_nft_check)
 - [Template code version](https://github.com/murluki/telegram_nft_check_no_template)