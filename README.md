<a href="https://pcards.near.page" target="_blank">pcards.near.page</a>, <a href="https://pcards.testnet.page" target="_blank">pcards.testnet.page</a><br />

## Introduction
Near Postcards dApp is an example of a fully decentralized Near protocol service that stores all data directly on the blockchain itself, including design templates and web interface.

Also, the service is an example of integrating any application into an official wallet through the Collectibles tab. Just open a postcard image in a new browser tab and you will be redirected to the project page.

In this way, you can significantly improve the usability of your application.

### Usage

The service provides the ability to send NFT images simulating paper postcards with a postage stamp with the flag of the country of origin, postal seals and stamps.

The sender can write a short text (200 characters) which will be displayed on the NFT postcard.

Open <a href="https://pcards.near.page" target="_blank">pcards.near.page</a>, log in and fill out the form to send a postcard.

After successful sending, you will be redirected to the page with postcards of the receiver.


<img src="https://telegra.ph/file/1dee2c369f02a4a6761c3.png" />

### Video
https://youtu.be/jYkiEB18GeY

### Build
```
$ cargo build --target wasm32-unknown-unknown --release
$ copy target\wasm32-unknown-unknown\release\near_postcards.wasm main.wasm 
```
### Deploy
```
$ near deploy --wasmFile main.wasm --accountId account.near
```

### Support
<a href="https://t.me/nearwatch">Near.Watch technical support group (telegram)</a>
