---
title: Environment setup
description: Setting up the development environment.
---

This page will help you install and build the Food Star React Native app.

### NodeJS
Make sure you have a recent version (8.11 or later) of [Node](https://nodejs.org/en/download) installed globally. We recommend installing Node and Watchman using Homebrew. Run the following commands in a Terminal after installing Homebrew: brew install node brew install watchman If you have already installed Node on your system, make sure it is Node 8.3 or newer. Watchman is a tool by Facebook for watching changes in the filesystem. It is highly recommended you install it for better performance.

### Yarn
Please follow [yarn](‌​https://yarnpkg.com/en/docs/install) official install guide

### Expo CLI
Expo CLI is part of the expo package, and you can use it by leveraging npx — a Node.js package runner. No external installation is required.

For example, to see a list of available commands in Expo CLI, open the terminal on your development machine and run the following command:
```sh
npx expo -h
```

Now, run the following command to check which Expo account is currently authenticated on your machine:
```sh
npx expo whoami
```

If you already have an Expo account, you can log in to it by running the command:
```sh
npx expo login
```
