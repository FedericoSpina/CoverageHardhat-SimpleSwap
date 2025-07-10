# 🏗 Scaffold-ETH 2

---

## ⚠️ DISCLAIMER
> [!WARNING]
> Due to some known issues, the `yarn start` command may not always work for deploying the website and using the Debug Contracts page in Scaffold-ETH 2. Please refer to the official documentation or community channels for troubleshooting and updates.

> [!WARNING]
> Debido a algunos problemas conocidos, es posible que el comando `yarn start` no siempre funcione para implementar el sitio web y usar la página Contratos de depuración en Scaffold-ETH 2. Consulte la documentación oficial o los canales de la comunidad para solucionar problemas y obtener actualizaciones.

## TESTING PROYECT OF SIMPLE SWAP
## FedericoS.
---

<h4 align="center">
  <a href="https://docs.scaffoldeth.io">Documentation</a> |
  <a href="https://scaffoldeth.io">Website</a>
</h4>

🧪 An open-source, up-to-date toolkit for building decentralized applications (dapps) on the Ethereum blockchain. It's designed to make it easier for developers to create and deploy smart contracts and build user interfaces that interact with those contracts.

⚙️ Built using NextJS, RainbowKit, Hardhat, Wagmi, Viem, and Typescript.

- ✅ **Contract Hot Reload**: Your frontend auto-adapts to your smart contract as you edit it.
- 🪝 **[Custom hooks](https://docs.scaffoldeth.io/hooks/)**: Collection of React hooks wrapper around [wagmi](https://wagmi.sh/) to simplify interactions with smart contracts with typescript autocompletion.
- 🧱 [**Components**](https://docs.scaffoldeth.io/components/): Collection of common web3 components to quickly build your frontend.
- 🔥 **Burner Wallet & Local Faucet**: Quickly test your application with a burner wallet and local faucet.
- 🔐 **Integration with Wallet Providers**: Connect to different wallet providers and interact with the Ethereum network.

![Debug Contracts tab](https://github.com/scaffold-eth/scaffold-eth-2/assets/55535804/b237af0c-5027-4849-a5c1-2e31495cccb1)

## Requirements

Before you begin, you need to install the following tools:

- [Node (>= v20.18.3)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Testing

To run smart contract coverage tests, follow these steps:

1. Install dependencies in the project root:

```
yarn install
```

2. Install Hardhat Toolbox as a dev dependency:

```
npm install --save-dev @nomicfoundation/hardhat-toolbox
```

3. Move to the `packages/hardhat` directory:

```
cd packages/hardhat
```

4. Run the coverage tests:

```
npx hardhat coverage
```

This will generate a coverage report for your smart contracts.

## Documentation

Visit our [docs](https://docs.scaffoldeth.io) to learn how to start building with Scaffold-ETH 2.

To know more about its features, check out our [website](https://scaffoldeth.io).

## Contributing to Scaffold-ETH 2

We welcome contributions to Scaffold-ETH 2!

Please see [CONTRIBUTING.MD](https://github.com/scaffold-eth/scaffold-eth-2/blob/main/CONTRIBUTING.md) for more information and guidelines for contributing to Scaffold-ETH 2.
