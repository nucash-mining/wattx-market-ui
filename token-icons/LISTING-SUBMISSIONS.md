# WATT v2 — icon & listing submissions (staged 2026-08-17)

Everything below is paste-ready. Fields marked `⚠ FILL` need your input (socials I
couldn't verify). Icon files live in this folder: `watt-32.png` (Polygonscan),
`watt-256.png` / `watt-512.png` (CoinGecko & aggregators).

---

## 1. Polygonscan "Update Token Info" — do this FIRST (free, no pool needed)

**Steps**
1. Sign in / register at https://polygonscan.com (use nucash.mining@gmail.com).
2. Verify address ownership: https://polygonscan.com/verifyAddress — sign the
   challenge with the **deployer wallet `0xd7eC194F0CD35CB2f67B92D63C6D73B99567B7dd`**
   (token admin is the multisig, so ownership is proven via the deployer signature;
   if rejected, sign from a multisig owner wallet `0x8324FA24…` instead and note the
   2-of-2 admin structure in the comments box).
3. Open https://polygonscan.com/token/0x387693eCEC037C61943404F03c097d2ADA15ae3f
   → "Update Token Info" → fill the form:

| Field | Value |
|---|---|
| Token contract | `0x387693eCEC037C61943404F03c097d2ADA15ae3f` |
| Token name | WATT (The Mining Game) |
| Symbol | WATT |
| Decimals | 18 |
| Logo (32×32 PNG) | `watt-32.png` from this folder |
| Official site | https://wattxchange.app |
| Email | nucash.mining@gmail.com |
| Project description | see block below |
| Marketplace / dApp | https://nft.wattxchange.app |
| GitHub | ⚠ FILL (The-Mining-Game org or nucash-mining repo link) |
| Twitter/X | ⚠ FILL |
| Discord/Telegram | ⚠ FILL |

**Description (short version, for length-limited fields):**
> WATT is the energy token of The Mining Game — a multi-chain NFT mining
> simulation. Players stake mining-rig NFTs to generate WATT and spend it on
> in-game power, items, and cross-chain gameplay on Polygon, Altcoinchain, and
> WATTxchain. WATT v2 is a burn-and-mint upgrade of the original 2021 token.

**Longer version (if the form allows):**
> WATT powers The Mining Game, an NFT-based mining simulation live on Polygon,
> Altcoinchain (chainId 2330) and WATTxchain (chainId 22356). Mining-rig NFTs
> staked in the game's engines generate WATT; the token is consumed for power,
> item crafting, pool hosting, and marketplace activity. WATT v2 replaces the
> 2021 legacy token via WattSwap, a 1:1 burn-and-mint migrator (v1 is burned to
> 0xdEaD). Supply is governed by a 2-of-2 multisig; current Polygon supply
> ~196,582 WATT. Canonical deployments: Polygon
> 0x387693eCEC037C61943404F03c097d2ADA15ae3f · Altcoinchain
> 0xB7635E386283CAE6FB1A710f19CaA8220beF630D · WATTxchain
> 0xc4603E2582aE320857379819123dFbFd3093dcfa.

---

## 2. CoinGecko application — AFTER a WATT v2 pool exists

**Prerequisite (hard requirement):** a live, trading pool on a tracked DEX.
Recommended: QuickSwap or Uniswap v3 WATT/WPOL on Polygon, seeded at your
intended price. Without ≥ some days of organic trades the application bounces.

Form: https://www.coingecko.com/request-form (choose "New cryptocurrency").

| Field | Value |
|---|---|
| Coin name | WATT (The Mining Game) |
| Ticker | WATT |
| Contract (Polygon) | `0x387693eCEC037C61943404F03c097d2ADA15ae3f` |
| Additional contracts | ALT 2330: `0xB7635E38…630D` · WATTx 22356: `0xc4603E25…dcfa` (CG won't track these chains but list them as official deployments) |
| Logo 200×200 | use `watt-256.png` (CG accepts ≥200px square PNG) |
| Website | https://wattxchange.app |
| Block explorer | https://polygonscan.com/token/0x387693eCEC037C61943404F03c097d2ADA15ae3f (+ https://alt-exp.wattxchange.app/token/0xB7635E386283CAE6FB1A710f19CaA8220beF630D) |
| Launch date | 2026-08 (v2); original WATT v1 2021 |
| Description | use the longer description above |
| Note to reviewer | "Not affiliated with QoWatt (QWT) or POWERCITY WATT — distinct project, The Mining Game, migrated v1→v2 via on-chain burn-and-mint (WattSwap 0x90a0906a7e01a65f48bd35741681088E3FA6729c)." |
| Email | nucash.mining@gmail.com |
| Socials | ⚠ FILL |

**Why CoinGecko matters:** DexScreener, Rabby, MetaMask, TrustWallet and most
aggregators auto-pull the CoinGecko logo — one approval propagates everywhere.

---

## 3. DexScreener (optional fast-lane, paid)

Once the pool exists the pair appears automatically (unbranded). For instant
branding without waiting on CoinGecko: connect a wallet on the pair page →
"Enhanced Token Info" (~$299 one-time) → upload `watt-512.png`, links,
description. Skip if you're patient — the CoinGecko route is free.

---

## 4. Order of operations

1. Polygonscan token update (today — no dependencies).
2. Create + seed the WATT v2 pool on QuickSwap (needs your call on depth/price;
   this is also what makes DexScreener list the token at all).
3. Let it trade a few days → CoinGecko application.
4. (Optional) DexScreener Enhanced Token Info for instant branding.
