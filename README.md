# Bitgreen Proposal Generator

## Get Started

Before being able to use this repository, you will need to build the @dashevo/dashcore-lib for browser which is a required dependency. This can be done easily by running:

```
npm install
npm run build
```

You will find in the vendor folder the file index.js which index.html reference. This file handle a browserified version of @dashevo/dashcore-lib aswell as some inner logic that you can find in "js/index.js".

## Addendum

After installation, modify 'node_modules/@dashevo/dashcore-lib/lib/networks.js' lines 135-137 to read:

```
  pubkeyhash: 0x26,
  privatekey: 0x2e,
  scripthash: 0x06,
```
