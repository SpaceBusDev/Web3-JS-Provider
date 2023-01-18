# Web3-JS-Provider


### Make sure you have the following ready:

- [Node.js](https://nodejs.org/) installed LTS v16
- [Typescript](https://www.typescriptlang.org/)  v4.9.4
- [MetaMask](https://metamask.io/) installed in your browser


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