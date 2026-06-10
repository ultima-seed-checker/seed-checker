<a href="https://gifyu.com/image/bIfvZ"><img src="https://s13.gifyu.com/images/bIfvZ.png" alt="ultima" border="0" /></a>

Ultima Multi-Chain Wallet Checker is a tool for checking
cryptocurrency wallet balances across 70+ blockchain networks.
Supports two modes: seed phrase (mnemonic) checking and
private key checking.

  OPERATING MODES

[MNEMONIC MODE]
  • Generate random BIP39 phrases (12 or 24 words)
  • Check phrases from a text file (one per line)
  • Address derivation via standard BIP44 paths
  • Multiple addresses per phrase (1–5, configurable)

[PRIVKEY MODE]
  • Generate random 256-bit private keys
  • Check keys from file (HEX or WIF format)
  • Addresses for all supported UTXO and EVM networks

  SUPPORTED NETWORKS (70+)

EVM-compatible:
  Ethereum, BNB Chain, Polygon, Arbitrum, Avalanche,
  Optimism, Base, Fantom, zkSync Era, Linea, Cronos,
  Celo, Gnosis, Moonbeam, Moonriver, Harmony, Klaytn,
  Aurora, Ronin, Mantle, Scroll, VeChain, Filecoin EVM,
  Conflux, Oasis Emerald

Ethereum Classic (ETC):
  Separate derivation m/44'/61' — different address from ETH,
  same as Trust Wallet / MetaMask

Bitcoin / UTXO:
  Bitcoin (Legacy + P2SH + Bech32 bc1...)
  Litecoin (Legacy + P2SH + Bech32 ltc1...)
  Dogecoin, Dash, Bitcoin Cash, Zcash, Bitcoin SV,
  Ravencoin, Vertcoin, Groestlcoin

Layer-1 / Alternative:
  Tron, Solana, TON, XRP, Stellar, Algorand, Cardano,
  Polkadot, NEAR, Aptos, Sui, Hedera, Tezos, MultiversX,
  Kaspa, Nano, Stacks, Zilliqa, Waves, Mina Protocol

Cosmos ecosystem:
  Cosmos (ATOM), Osmosis, Injective, Sei, Celestia,
  Kava, dYdX, Secret Network, Band Protocol

Avalanche X-Chain (avax1...)

  TOKEN SUPPORT

  Ethereum/EVM  — USDT, USDC, DAI, SHIB, WBTC, LINK,
                  UNI, AAVE, PEPE, FET
  BNB Chain     — USDT, USDC, BUSD, CAKE
  Polygon       — USDT, USDC, DAI, WETH, LINK
  Arbitrum      — USDT, USDC, DAI, WBTC, ARB
  Avalanche     — USDT, USDC
  Tron          — USDT, USDC, WIN, BTT, JST, SUN
  Solana        — USDT, USDC, BONK, RAY, JUP, WIF
  TON           — USDT (Jetton)

  SETTINGS & FEATURES

  Proxy: none / HTTP / HTTPS / SOCKS5 / load from file

  Network selection — by number, coin name (btc, eth, sol...)
  or letter presets:
    a — Bitcoin family  (BTC LTC DOGE DASH BCH ZEC BSV GRS VTC RVN)
    b — EVM main        (ETH BNB MATIC ARB AVAX OP BASE)
    c — EVM extra       (FTM zkSync Linea VeChain ETC etc.)
    d — Tron + Solana with tokens
    e — TON + USDT
    f — Cosmos          (ATOM OSMO INJ SEI TIA KAVA DYDX SCRT BAND)
    g — Layer-1 alts    (XRP XLM ALGO NEAR APT SUI ADA DOT etc.)
    h — Quick scan of top assets
    i — All networks

  History: skip already-checked phrases/keys
  Resume: continue from where you stopped
  Pause delay: configurable between checks
  RPC diagnostics: check EVM node availability
