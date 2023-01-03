# Concordium React Reference Implementations

Concordium is a science-based proof-of-stake blockchain created for all, with in particular business applications in mind. [Read more about concordium](https://www.concordium.com/about)

This repository provides sample implementations of following ways in which a developer can interact with an on chain contract on Concordium.

- Using Frontend React Code (using [Web SDK](https://github.com/Concordium/concordium-node-sdk-js/tree/main/packages/web) and [Concordium Browser Wallet](https://chrome.google.com/webstore/detail/concordium-wallet/mnnkpffndmickbiakofclnpoiajlegmg?hl=en-US))

Please do note that this is **not** an exhaustive list of the languages supported by concordium. There are are SDK's present to interact with the contracts using multiple other languages. A complete list can be found [here](https://developer.concordium.software/en/mainnet/net/guides/sdks-apis.html)

## Contents of Repository

- [market-ui](./market-ui/README.md)
  React based frontend DAPP for marketplace contract. This is the typescript code which can be used with Concordium Browser Wallet to interact with CIS2-Multi and Marketplace Contract in Browser based environments.
- [mint-ui](./mint-ui/README.md)

## Get Started

Throughout this repository [Concordium Testnet](https://testnet.ccdscan.io/) is being used to demo the functionality.

- Interact with Contracts
  - Using [Frontend React Code](./market-ui/README.md)
