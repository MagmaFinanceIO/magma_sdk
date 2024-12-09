<a name="readme-top"></a>

![NPM](https://img.shields.io/npm/l/%40magmaprotocol%2Fmagma-sui-clmm-sdk?registry_uri=https%3A%2F%2Fregistry.npmjs.com&style=flat&logo=npm&logoColor=blue&label=%40magmaprotocol&labelColor=rgb&color=fedcba&cacheSeconds=3600&link=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2F%40magmaprotocol%2Fmagma-sui-clmm-sdk)
![npm](https://img.shields.io/npm/v/%40magmaprotocol%2Fmagma-sui-clmm-sdk?logo=npm&logoColor=rgb)
![GitHub Repo stars](https://img.shields.io/github/stars/MagmaProtocol/magma-clmm-sui-sdk?logo=github)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a >
    <img src="https://archive.magma.zone/assets/image/logo.png" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">Magma-CLMM-SUI-SDK</h3>

  <p align="center">
    Integrating Magma-CLMM-SUI-SDK: A Comprehensive Guide, Please see details in document.
    <br />
    <a href="https://magma-1.gitbook.io/magma-developer-docs/developer/dev-overview"><strong>Explore the document »</strong></a>
<br />
    <br />
  </p>
</div>

## Introduction

Magma-CLMM-SUI-SDK is the official software development kit (SDK) specifically designed for seamless integration with Magma-CLMM. It provides developers with the necessary tools and resources to easily connect and interact with Magma-CLMM, enabling the development of robust and efficient applications.

## Getting Started
To integrate our SDK into your local project, please follow the example steps provided below.
Please see details in document.
### Prerequisites
  ```sh
  npm i @magmaprotocol/magma-sui-clmm-sdk
  ```

### Setting Up Configuration
Our SDK now includes a default initialization method that allows for quick generation of the Magma SDK configuration. You can utilize the src/config/initMagmaSDK method to swiftly initialize the configuration. You have the option to select either 'mainnet' or 'testnet' for the network.
  ```typescript
  import { initMagmaSDK } from '@magmaprotocol/magma-sui-clmm-sdk'

  const magmaClmmSDK = initMagmaSDK({network: 'mainnet})
  ```
If you wish to set your own full node URL and simulate address, you can do so as follows:
  ```typescript
  import { initMagmaSDK } from '@magmaprotocol/magma-sui-clmm-sdk'

  const network = 'mainnnet';
  const fullNodeUrl = "https://..."
  const simulationAccount = "0x..."
  const magmaClmmSDK = initMagmaSDK({network, fullNodeUrl, simulationAccount})
  ```

Now, you can start using Magma SDK.

### Typrscript Doc
You can view this typescript sdk in
<a href="https://magma-1.gitbook.io/magma-developer-docs/developer/dev-overview"><strong> Magma Development Documents. </strong></a>
<br />

## LICENSE
MAGMA-SUI-SDK released under the Apache license. See the [LICENSE](./LICENSE) file for details.

## More About Magma
Use the following links to learn more about Magma:
Learn more about working with Magma in the [Magma Documentation](https://magma-1.gitbook.io/magma-docs).

Join the Magma community on [Magma Discord](https://discord.com/channels/1009749448022315008/1009751382783447072).
