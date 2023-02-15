# DevAssist Browser Extension

DevAssist is an open-source browser extension. When interacting with any smart contract using Metamask wallet, the DevAssist Extension is activated and provides an explanation in plain English of the smart contract's code. This explanation is generated by ChatGPT after thoroughly analyzing the code. This means that users no longer need to be Solidity developers to understand what they are about to confirm and risk their crypto assets.
![alt text](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FitZP4d2R7tNhEVkUrPpA%2Fuploads%2F5gkBMMmWy48tstGmxinM%2FDevAssist%20Screenshots.png?alt=media&token=0fc28551-3023-4c66-bdc6-3af8e87c993a)
This Chrome extension allows users to decode and understand a blockchain smart contract.

The extension is automatically triggered on each transaction and shows a popup with a detailed description of the transaction's contract.

Additionally, you can manually query our platform by cliking on the extension icon.

You can get the official extension from [Chrome Web Store](https://chrome.google.com/webstore/category/extensions)

## Developers Mode

First install npm packages

```
npm install
```

You can run the extensions in a development mode by running the following command:

```
npm run dev
```

It should create a `build` folder with the builded plugin.

You can load it to Chrome by:

1. Browse to `chrome://extensions/`
2. Enable **Developer mode**
3. Click on **[Load unpacked]**
4. Choose the `build` folder

You can load it to Brave by:

1. Browse to `brave://extensions/`
2. Enable **Developer mode**
3. Click on **[Load unpacked]**
4. Choose the `build` folder
