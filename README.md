# Web3-JS-Provider


### Make sure you have the following ready:

- [Node.js](https://nodejs.org/) installed LTS v16
- [Typescript](https://www.typescriptlang.org/)  v4.9.4
- [MetaMask](https://metamask.io/) installed in your browser.

To run this project connecting to a local chain download Ganache utilize chain ID 1337

[Download Ganache](https://www.trufflesuite.com/ganache)

Otherwise in order to show the Account info you'll need to connect the app to a valid Account on the chain ID you are choosing inside the component/wallet/connector.js file.

To test with a Testnet please visit Infura: [Infura.io](https://infura.io/) and drop your endpoint into the Web3 Provider

---

### Install all package dependancies by running:

```
npm install
```

## Features:

- [x] Web3 Wallet (Metamask / Wallet connect / Coinbase)
- [x] Chain selector
- [ ] Hooks to query user's Native Balance / Token Balances
- [ ] Hook to query user's NFTs


# How to use?
Wrap your **App** in `<MetamaskProvider></MetamaskProvider>`

**App.tsx**
```
import { MetamaskProvider } from ". /metamask";
import Main from "./components/Main";

export default function App() {
  return (
    <MetamaskProvider>
      <Main />
    </MetamaskProvider>
  );
}
```