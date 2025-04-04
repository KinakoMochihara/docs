---
id: quick-start
title: SDK Quick start
---

The Uniswap SDK exists to help developers build on top of Uniswap. It's designed to run in any environment that can execute JavaScript (think websites, node scripts, etc.). While simple enough to use in a hackathon project, it's also robust enough to power production applications.

# Installation

The easiest way to consume the SDK is via [npm](https://github.com/Uniswap/uniswap-v2-sdk). To install it in your project, simply run `yarn add @uniswap/v2-sdk` (or `npm install @uniswap/v2-sdk`). This also installs the sdk-core package that is used by both the V2 and V3 SDK and ethers as dependencies.

# Usage

To run code from the SDK in your application, use an `import` or `require` statement, depending on which your environment supports. Note that the guides following this page will use ES6 syntax.

## ES6 (import)

```typescript
import { ChainId } from '@uniswap/sdk-core'
import {Pair} from '@uniswap/v2-sdk'
console.log(`The chainId of mainnet is ${ChainId.MAINNET}.`)
```

## CommonJS (require)

```typescript
const CORE = require('@uniswap/sdk-core')
const V2_SDK = require('@uniswap/v2-sdk')
console.log(`The chainId of mainnet is ${CORE.ChainId.MAINNET}.`)
```

# Reference

Comprehensive reference material for the SDK is publicly available on the [Uniswap Labs GitHub](https://github.com/Uniswap).
