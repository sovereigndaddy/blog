---
title:  "Using Sparrow Wallet with BitBox02"
date:   2022-06-02 05:34:00 -0500
show_title: false
show_edit_on_github: false
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87 , .4), rgba(139, 34, 139, .4))'
    src: /img/SparrowWallet/sparrow-logo.jpg
---
<br/>
Since you should ALWAYS be concerned with privacy when utilizing Bitcoin, this post will be about my use of the [Sparrow Wallet](https://sparrowwallet.com/) along with my [BitBox02](https://shiftcrypto.ch/bitbox02/) hardware wallet. In combination these devices are helping me accomplish adequate privacy when sending and receiving Bitcoin transactions while at the same time increasing my usability of the wallet.

# Why BitBox02
A couple years back I purchased the [BitBox02](https://shiftcrypto.ch/bitbox02/) Bitcoin-only edition and I haven't regretted it for a second. It has top of the line security and a great user interface which allows for simple and easy usage. The BitBox02 has been designed around security and the potential vulnerabilities that its users could face when sending and receiving Bitcoin, so when I use the device I'm confident that my risk of compromise is extremely low.

One item to call out here, the Bitcoin-only edition is the ONLY option that you should buy if you're planning on purchasing a BitBox02. This edition has its firmware exclusively dedicated to supporting Bitcoin, which in turn means less code and less attack surface for potential malicious attacks.

# Why Sparrow Wallet
[Sparrow Wallet](https://sparrowwallet.com/) is a non-custodial Bitcoin wallet with a strong focus on privacy, security, and usability. It is designed to be connected to your own Bitcoin full node and can operate in both online and offline fashions. It provides great advanced features that allow the ability to dig into your Bitcoin transactions for a clearer understanding, thus leading to a better control of your Bitcoin transactions.

## Features
- Desktop based wallet. Safer than a browser based wallet.
- Adheres to the PSBTs standard
- Supports Single sig and multisig
- All common hardware wallets are supported
- Utilizes the [Argon2](https://github.com/P-H-C/phc-winner-argon2) is a password-hashing function for increased encryption
- Lightweight wallet
- Has built in blockchain explorer so you can search any Bitcoin transactions since its inception back in 2009
- Allows [coinjoins](https://www.investopedia.com/terms/c/coinjoin.asp) with Whirlpool for increased privacy
- Provides a detailed view of byte level transactions.
- Provides full control and configuration during the transaction creation and signing process


# Setup

## Sparrow Wallet Install
Download the Sparrow Wallet from the [downloads](https://www.sparrowwallet.com/download/) page.

## Verify the Release
I've preached this before, but ALWAYS verify your installation file is the one you expected to download and was not compromised during the download.

## Configuration
After you've verified your download, start the configuration.

Since I'm using my own node, I'm going to select the "Private Electrum server" option and enter the IP address for my node.

![Private Server Connection](/img/SparrowWallet/server-connection.jpg)

*Note: Click on the "Test Connection" button to confirm your connection is successful. You should see a message like shown in the screenshot above.*

## Create Wallet
Creating a wallet is extremely easy, simply navigate under the File menu and then select "New Wallet" (Shortcut CTRL+N).

Enter the wallet name and then click on "Create Wallet".

![Enter Wallet Name](/img/SparrowWallet/enter-wallet-name.jpg)

## Wallet Settings

### Default Settings
For this post, I'm going to leave the "Policy Type" and "Script Type" settings defaulted but just be aware that these settings can be tweaked to your liking and to match whichever situation you are needing to address, whether that be a multisig situation or maybe you want to utilize Bitcoin Taproot; whatever it may be, Sparrow Wallet has you covered.

### Keystores
Now comes the fun :) connecting our BitBox02 wallet.

#### Connect Hardware Wallet
Under Keystores, click on the "Connected Hardware Wallet" button

![Connect Hardware Wallet](/img/SparrowWallet/connect-hardware-wallet-button.jpg)

#### Scan for device
At this point, we need to connect our BitBox02 wallet to our computer so it can be scanned and found by Sparrow Wallet.

Once connected to our computer, click on the "Scan..." button.
