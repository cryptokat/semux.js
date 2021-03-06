# Semux Javascript SDK

[![NPM Status](https://img.shields.io/npm/v/semux.svg)](https://www.npmjs.com/package/semux)
[![Travis Build Status](https://travis-ci.org/semuxproject/semux-js-sdk.svg?branch=master)](https://travis-ci.org/semuxproject/semux-js-sdk)
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=eEVtNGR5NjNKcGdaMVp6N1RldVJsTmRpTTNQeGtQbVlvNER1R2dLWjlyST0tLTlQeG9WSlpJam8xOUIvYUc5NlBNN2c9PQ==--05e005a64351ce1375536b9931466c99c023ac13)](https://www.browserstack.com/automate/public-build/eEVtNGR5NjNKcGdaMVp6N1RldVJsTmRpTTNQeGtQbVlvNER1R2dLWjlyST0tLTlQeG9WSlpJam8xOUIvYUc5NlBNN2c9PQ==--05e005a64351ce1375536b9931466c99c023ac13)
[![Coverage Status](https://coveralls.io/repos/github/semuxproject/semux-js-sdk/badge.svg?branch=master)](https://coveralls.io/github/semuxproject/semux-js-sdk?branch=master)

This library aims to providing javascript utilities for Semux client-side applications, such as web wallet.

Visit [issues](https://github.com/semuxproject/semux-js-sdk/issues) page to see planned features or propose a feature request.

# Install

```
npm install --save semux
```

# Usage

- [Hash](https://github.com/semuxproject/semux-js-sdk/blob/master/lib/Hash.spec.ts)
- [Key & Signature](https://github.com/semuxproject/semux-js-sdk/blob/master/lib/Key.spec.ts)
- [Transaction Signing, Encoding or Decoding](https://github.com/semuxproject/semux-js-sdk/blob/master/lib/Transaction.spec.ts)
- [Byte Encoder](https://github.com/semuxproject/semux-js-sdk/blob/master/lib/SimpleDecoder.spec.ts) / [Byte Decoder](https://github.com/semuxproject/semux-js-sdk/blob/master/lib/SimpleDecoder.spec.ts)
- [API Client](https://github.com/semuxproject/semux-js-sdk/blob/master/lib/api/api.spec.ts)

# Browser Compatibility

- Chrome >= 65
- Firefox >= 59
- IE >= 11
- Edge >= 16
- Safari >= 6

# Development

## Install Modules

```
npm install
```

## Run Unit Tests

```
npm test
``` 

## Run Browser Tests

Browser testing requires Chrome and Firefox installed.

```
npm run-script test:browser
```

## Format Source Code

```
npm run format
```

## Check Source Code Formatting

```
npm run format:check
```

# Special Thanks

This project is supported by [BrowserStack](https://www.browserstack.com/) to test cross-browser compatibility:

[![BrowserStack Logo](https://ipfs.io/ipfs/QmSjhNTsswVWtxfkWup2XdTcFhhQrbw2Bdxajr1w7XM4Hh)](https://www.browserstack.com/)