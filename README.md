# Hot Cross Audits

This repository contains a public-facing list of audits that have been performed on the [Hot Cross](https://hotcross.com/) codebase and select Hot Cross products. We attempt to adhere to [Semantic Versioning](https://semver.org/) at all times but aren't anywhere near perfect in this regard. If multiple audits take place on the same codebase at the same time then we sometimes adjust versioning on the fly to accomodate for that. 

We have thus far conducted audits with [Beosin](https://lianantech.com/), [SlowMist](https://www.slowmist.com/), [Omniscia](https://omniscia.io/), [Zokyo](https://www.zokyo.io/), [CertiK](https://www.certik.org/), and [PeckShield](https://peckshield.com/en).

Thorough documentation of these audits can also be found [here](https://docs.hotcross.com/oink/guides/audits).

## [Hot Cross Token and Vesting](cross-token/)

### General Information

- Token Name: `NFC Token`
- Token Symbol: `$NFCT`
- Token Decimals: `10`
- Total Supply: `200,000,000`
- Initial Circulating Supply: `85,750,000` (The full token emission schedule is [here](https://hotcross.link/hotcross-economy).)
- Current Supply: https://api.hotcross.com/supply
- Current Circulating Supply: https://api.hotcross.com/circulating
- [Ethereum](https://ethereum.org/) Contract Address: [0x4297394c20800E8a38A619A243E9BbE7681Ff24E](https://etherscan.io/address/0x4297394c20800e8a38a619a243e9bbe7681ff24e) (Canonical)
- [Binance Smart Chain](https://www.binance.org/en/smartChain) Contract Address: [0x4FA7163E153419E0E1064e418dd7A99314Ed27b6](https://bscscan.com/address/0x4FA7163E153419E0E1064e418dd7A99314Ed27b6) (Bridge) ([link](https://bridge.hotcross.com/))
- [Avalanche C-Chain](https://www.avax.network/) Contract Address: [0x2f86508f41310D8D974B76deb3D246c0caa71cf5](https://snowtrace.io/token/0x2f86508f41310d8d974b76deb3d246c0caa71cf5) (Bridge) ([link](https://bridge.hotcross.com/))
- [Polygon](https://polygon.technology/) Contract Address: [0x3b737a181f7d2532cF49864f8050b3465a310593](https://polygonscan.com/token/0x3b737a181f7d2532cF49864f8050b3465a310593) (3rd-Party Mapped) ([link](https://mapper.matic.today/))
- [Harmony](https://www.harmony.one/) Contract Address: [one1u0tuw46yh9m09kkxs7znwjtwwhm754h3lp0jzn](https://explorer.harmony.one/address/0xe3d7c75744b976f2dac6878537496e75f7ea56f1) (3rd-Party Bridge) ([link](https://bridge.harmony.one/))
- [Solana](https://solana.com/) Contract Address: [64LRWE7xXGzJnNdr7mdKKjajqWxMScRaoSnArS4hj4Tu](https://explorer.solana.com/address/64LRWE7xXGzJnNdr7mdKKjajqWxMScRaoSnArS4hj4Tu/) (3rd-Party Bridge) ([link](https://wormholebridge.com/#/))

Canonical (and thus its EVM audits) resides on Ethereum. The Binance Smart Chain BEP20 is an ever-fluctuating supply that relies on the inflow and outflow of [Cross Bridge](https://bridge.hotcross.com/), and 3rd-party mapped assets rely on those bridge technologies. Supply for the asset is always updated at the following API endpoint: https://api.hotcross.com/supply.

---

