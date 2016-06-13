# Blockchain-Developer-Resources

A list of opininated links to resources useful to blockchain and bitcoin developers.

---

## Bitcoin

### Non-Technical Introductions

#### Non-Technical Videos (Very Intro)
  * [Bitcoin explained and made simple](https://www.youtube.com/watch?v=s4g1XFU8Gto) (3m:24s) by [The Guardian](http://www.theguardian.com/)
  * [The Essence of How Bitcoin Works (Non-Technical)](https://www.youtube.com/watch?v=t5JGQXCTe3c) (5m:24s) by [Curious Inventor](http://Patreon.com/CuriousInventor)
  
#### Non-Technical Videos (More Detail)
  * [Blockchain University — Bitcoin & the Blockchain: An Introduction](https://www.youtube.com/watch?v=ZUoXUW9zVMs) (26m:16s) by [@ChristopherA](https://twitter.com/ChristopherA) 
  * [Bitcoin 101 - What is Bitcoin?](https://www.youtube.com/watch?v=Bhe61JaNFLU) (22m:32s) by [James D'Angelo WBN](https://www.youtube.com/channel/UCgo7FCCPuylVk4luP3JAgVw)
 
#### Non-Technical Videos (Intermediate & Related Topics)
  * [Blockchain University — Bitcoin Keys Addresses and Wallets](https://www.youtube.com/watch?v=Ic76iSnCb_0) (1h:06m:43s) by [@ChristopherA](https://twitter.com/ChristopherA)
  * [Bitcoin Sidechains](https://www.youtube.com/watch?v=6sXNVIaNL2Y) (5m:54s) by [Diginomics](https://diginomics.com/)

#### Non-Technical Articles

##### (unsorted)
  * http://www.coindesk.com/information/what-is-bitcoin/
  * http://money.cnn.com/infographic/technology/what-is-bitcoin/
  * https://hbr.org/2016/05/the-impact-of-the-blockchain-goes-beyond-financial-services

### Technical Introductions

#### Technical Videos
  * [How Bitcoin Works in 5 Minutes (Technical)](https://www.youtube.com/watch?v=l9jOJk30eQs) (5m:25s)  by [Curious Inventor](http://Patreon.com/CuriousInventor)
  * [How Bitcoin Works Under the Hood](https://www.youtube.com/watch?v=Lx9zgZCMqXE) (22m:24s) by [Curious Inventor](http://Patreon.com/CuriousInventor)
  * [Mechanics of Bitcoin](https://www.youtube.com/watch?v=t3hJsFpPmXs) (1h:19m:49s) by [Princeton 
Bitcoin and Cryptocurrency Technologies Online Course](https://www.coursera.org/course/bitcointech)

#### Technical Books
  * [Mastering Bitcoin](https://github.com/aantonop/bitcoinbook) by Andreas M. Antonopoulos LLC

### Local-client Javascript Tools & Playgrounds

These tools can be cloned from github to allow you to use your browser to play around with various bitcoin capabilities:

  * [Bip32 Generator](https://github.com/bip32/bip32.github.io) `git clone https://github.com/bip32/bip32.github.io.git ; cd bip32.github.io ; open index.html` lets you create Bip32 Deterministic Heirarchical Keys (prefix xpub* and xprv*) based on a simple brainwallet (aka arbitrary mnemonic) passphrase.
  * [Bip39 Mnemonic Code Converter](https://github.com/dcpos/bip39) `npm install bip39 ; npm run compile` lets you create Bip39 mnemonics (typically 12 words) used for deterministic keys, typically for Bip32.

### Testnet Faucets

You'll need bitcoin testnet coins while developing apps with bitcoin. List in rough order of reliability and number of coins offered.

  * [Sidechains Elements Project Testnet Faucet](https://testnet-faucet.elementsproject.org) - 10 BTC per day per ip
  * [TP Faucet](http://tpfaucet.appspot.com) - 1.9 BTC per request

## Javascript & Bitcoin

At Blockchain University we use a number of Javascript based examples to teach the more technical details of Bitcoin. You are not required to have an in-depth knowledge of Javascript, but learning some basics is very useful.

### Setting Up on Mac

If using a Mac, you'll need some basic knowledge how to use the Terminal and the Mac's command line interface, and you'll need to install brew, node and git. A basic tutorial on how to do this is at https://github.com/ChristopherA/intro-mac-command-line

You can also use this script which sets up your Mac automatically, but the above teaches you how do to do it manually https://github.com/blockchainu/prepare-osx-for-blockchain-webdev

### Introduction to Javascript

Javascript is in both server (node) and client (browser) development. Some basics of Javascript are common to both. Here are some resources for learning about Javascript that are generally applicable to both platform.

  * [Learn Javascript](https://www.gitbook.com/book/gitbookio/javascript/details) - a free online book with interactive exercises.

### Introduction to Node & Javascript

Server-based Javascript typically uses Node. These Javascript learning resources are node specific:

  * I like the command-line based [nodeschool.io](http://nodeschool.io) tutorials, as they require you to both use the command line and to create real working code. These are the basic interactive tutorials, but there are many more available.
   * Learn javascripting basics `npm install -g javascripting`
   * Learn Node basics: `npm install -g learnyounode`
   * Learn git: `npm install -g git-it`

### Online courses on Javascript

Most of these courses teach general Javascript, but tend to be more client-side Javascript oriented.

Free online courses:
  * [Code Academy: Javascript](http://www.codecademy.com/tracks/javascript) is an online interactive course that comes highly recommend. The course says 10 hours, but one of our students reported that it took him about 17 hours over 5 days, and found Q&A forum and glossary both helpful.
  * http://javascriptissexy.com/how-to-learn-javascript-properly/
  * http://web.stanford.edu/class/cs101/
  * https://www.udemy.com/refactoru-intro-js/?dtcode=DvGKZ5c30m1I

Some non-free online courses:
  * http://www.lynda.com/JavaScript-tutorials/Nodejs-Essential-Training/141132-2.html
  * https://www.udemy.com/courses/search?ref=home&q=javascript

### General Javascript Books and eBooks

Some general Javascript online books in eBook (in rough order of preference)

http://eloquentjavascript.net
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
http://bonsaiden.github.io/JavaScript-Garden/

### Bitcore.js
  * [Bitcoin 101 - Getting Started With Bitcore - A Full JavaScript Implementation of Bitcoin](https://www.youtube.com/watch?v=TmkN8yYyOv8)
    * https://github.com/wobine/blackboard101/blob/master/BitcoreDayOne.html - code for the above
  * [Bitcoin Quick Tools](https://github.com/chulini/bitcoin-quick-tools) - Simple browser-based app (loaded locally) that is Bitcore.js. Has key and address generator and simple transaction tool. Useful working example of browserfy bitcore.js code.

---
### Bitcoin Standards

* BIP32 - Bitcoin Deterministic Heirarchical Keys
  * Good article on [Deterministic Wallets](http://blog.richardkiss.com/?p=313)
  * Discussion of [BIP32 Advantages and Flaws](https://bitcoinmagazine.com/8396/deterministic-wallets-advantages-flaw/)
  * The [BIP0032 Standard](https://en.bitcoin.it/wiki/BIP_0032)
  * [Bip32 Generator](https://github.com/bip32/bip32.github.io) `git clone https://github.com/bip32/bip32.github.io.git ; cd bip32.github.io ; open index.html` lets you create Bip32 Deterministic Heirarchical Keys (prefix xpub* and xprv*) based on a simple brainwallet (aka arbitrary mnemonic) passphrase.

### 

* Blockchain Explorers
  * [Blockr.io](http://btc.blockr.io)
  * 
---

## Altcoins

  * [CoinGecko](https://www.coingecko.com/en) has charts for a number of altcoins, but more importantly, attempts to measure developer and user community activity.


---

## Sidechains

Sidechains are new blockchains, but are backed by Bitcoin rather than being an altcoin. Using "two-way pegging" these sidechains provide a method for developers to make changes and play around with blockchain rules in a separate blockchain, while keeping these coins linked to Bitcoin.

### Introduction
  * [Ask Dr. Bitcoin: What are Side-Chains](http://siliconangle.com/blog/2014/04/21/bitcoin-sidechains/)

### Concepts
  * The Initial Two-Way Pegging [proposal](http://sourceforge.net/p/bitcoin/mailman/message/32108143/) by Adam Back
  * Blockstream Whitepaper [Enabling Blockchain Innovations with Pegged Sidechains](https://www.blockstream.com/sidechains.pdf)

### Projects
  * [Sidechain Elements Project] (https://github.com/ElementsProject/elementsproject.github.io/) - Open source github project investigating and experiment with various bitcoin sidechain concepts
