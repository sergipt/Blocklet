# BLOCKLET

An all-in-one Cryptocurrency wallet, built for IOS & Android mobile.

## Features

* Exchange Information for the provided currencies
* Market Graph Information for popular currencies
* Back end API of historical token prices (40+)
* Currency calculator
* Latest Cryptocurrency News
* User Token Portfolio

## Screenshots

![Awww](https://ipfs.io/ipfs/Qma9YERxPvMZhtJBPVbxXd3ZmXP7ZdBkF3jdBoMGvmSYjP "Yeah")
![Awww](https://ipfs.io/ipfs/QmTSBMyaMyxz2877F9Tow2QMt4pvhPmBuHnAnMsZ3HEyRU "Yeah")
![Awww](https://ipfs.io/ipfs/QmXY1Fzjqq3N1k95z7tqHh1Gkfg8ddg3ffaabhcFA83wGi "Yeah")
![Awww](https://ipfs.io/ipfs/QmaisLR6dC2ENopMYbrzWFeapyzRDyPgc8pPDqjDAR2X7V "Yeah")
![Awww](https://ipfs.io/ipfs/QmSZBiqxPApGGiYQNcWG1aFFCLaEcaky2KgugYkkjE4voP "Yeah")

## Usage

* `git clone https://github.com/rainierlouis/Blocklet.git` or download the zip file.

### Frontend:

* `cd /client`.

* `npm install` to begin dependencies installation.

* `npm start` to boot up the development server.

* Scan the barcode with the Expo app on your phone or follow the terminal instructions to load up the emulator on your machine.

### Backend:

* cd /server

* `npm install` to begin dependencies installation.

* `mongod` to start database

* `nodemon App.js` to boot up the server & initialise API to begin fetching data.

## Technology Stack

**Front:**

* React Native / Elements / Animatable
* React Navigation
* Redux
* Expo

**Back:**

* Node.js
* Koa.js
* MongoDB / Monk

**Misc:**

* Block.io API
* Homemade API (historical prices)
* News API  
* Google & Facebook API (Logins)
