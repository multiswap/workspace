# Multiswap Monorepo
Monorepo aggregating all Multiswap repositories as submodules.
Multiswap is a multi-chain fork of Uniswap.

## Supported Networks
Multiswap is meant to be a a multi-chain Uniswap solution. Future implementations could potentially also make it multi-protocol giving users the option to select which smart contracts it connects to (eg. support for Sushiswap). Below a list of the supported networks and in parenthesis the protocol contracts the frontend points to.

### Mainnets
- Ethereum Mainnet (Uniswap)
- RSK Mainnet (RSKSwap)

### Testnets
- Local Ethereum Ganache (Custom Deployment Necessary)
- Ethereum Ropsten (Uniswap)
- Ethereum Rinkeby (Uniswap)
- Ethereum Goerli (Uniswap)
- Ethereum Kovan (Uniswap)
- RSK Testnet (RSKSwap)

### Future Networks & Protocols
Below a list a potential future networks:
- Elastos
- Ethereum Classic
- Matic
- xDAI
- Binance SmartChain
- NEAR Protocol

Existing known Uniswap Forks:
- SushiSwap (Ethereum)
- BurgerSwap (Binance SmartChain)

## Git Submodules
Unlike other monorepos, this one relies on git submodules to reference other Multiswap git repos.
This makes it simple to keep track of the various forked repos we use while also giving the possibility of combining them as one in this repo.
See https://git-scm.com/book/en/v2/Git-Tools-Submodules on using git submodules.


## Repositories
* [default-token-list](https://github.com/multiswap/default-token-list): Fork of Uniswap Token List
* [assets](https://github.com/multiswap/assets): Fork of TrustWallet token logos
* [sdk](https://github.com/multiswap/sdk): Fork of Uniswap SDK
* [contracts](https://github.com/multiswap/contracts): Uniswap contracts upgrade to Sol 0.6.0 with single-command deploy
* [interface](https://github.com/multiswap/interface): Fork of Uniswap Interface