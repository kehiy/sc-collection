# TON contracts

This directory contains TON Blockchain and TVM smart contracts. contracts on TON behave like `actors` on [actor paradigm](https://en.wikipedia.org/wiki/Actor_model) and we call it actors too. everything on TON is contract or actor even accounts (they are waller contracts).

Contract calls and execution are handled by ton virtual machine ot TVM. (they run the TVM [byte codes](https://docs.ton.org/learn/archive/tvm-instructions))

> Some more interesting info about TON blockchain: https://docs.ton.org/learn/overviews/ton-blockchain#single-actor

## languages

There is 3 different smart contract language for TVM.

### Fift

The Fift is so close to machine code and it's  TVM byte codes. they are not useful for large projects.

### FunC

The FunC is another language for TVM contracts that's have a similar syntax to C. it's not useful for large projects too but it useful to write wallet, multi-sig wallets contracts.

### Tact

The Tact is a language similar with TypeScript fot TVM contracts which is compiled to FunC and then byte codes at the end. Tact is more useful for large projects such as market-places and ...
