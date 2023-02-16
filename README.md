GeoLocation demo contracts
=========================

## Intro
The Geolocation contracts suite is meant be used in your dApps as an on-chain verification tool to check the validity of the Proofs received by a W3bstream node. The image below describes the architecture of a typical dApp that would make use of the Trusted-Location API in conjunction with an on-chain Verifier contract: 

![geolocation-app-flow](https://user-images.githubusercontent.com/77351244/219445568-44de3241-e328-4e6f-b1df-506e1f3d6b19.png)

For more information check out the "Trusted GPS Location" page in the official W3bstream documentation, [here](https://docs.w3bstream.com/introduction/readme)


## Local Development

The following assumes the use of `node@>=12`.

### Install Dependencies

`yarn`

### Compile Contracts

`yarn compile`

### Run Tests

`yarn test`
