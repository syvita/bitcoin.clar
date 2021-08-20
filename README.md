<img src="bitcoin.clar.png"></img>

---

### Welcome! 👋

`bitcoin.clar` is a Clarity library that you can use in your smart contracts to do various operations that involve Bitcoin.

### Features:

- [x] Verify Bitcoin transactions in a Stacks smart contract
   - [x] Support P2PKH (legacy) addresses
   - [x] Support P2SH (SegWit) addresses
   - [ ] Support Bech32 (native SegWit) addresses
- [ ] Create a Bitcoin address from a `secp256k1` public key **(WIP)**
- [ ] Verify a `secp256k1` signature originated from a certain Bitcoin address **(WIP)**

`bitcoin.clar`'s primary feature currently is cross-chain transaction verification. This means you can verify that Bitcoin transactions happened in a trustless smart contract on the [::Stacks blockchain::](https://stacks.co/).

It currently powers [::Catamaran swaps::](https://www.catamaranswaps.org/) & [::Sypool::](https://sypool.co/)'s transaction verification. We built `bitcoin.clar` specifically for Sypool, but the applications of verifying Bitcoin transactions through smart contracts are far more than that. We're trying to build docs and make this a library that other developers in the ecosystem can use too!

[Continue reading...](https://www.craft.do/s/9YyJfqjBBWiIU3)
