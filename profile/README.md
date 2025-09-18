# Leviathan — Web3 Game Launchpad
<p align="center">
  <img width="102" height="156" alt="image" src="https://github.com/user-attachments/assets/fabda521-ab84-4926-b030-5fd56a07fcc5" />
</p>

Creators build. Players play. The chain pays.
A sleek, creator-first web3 game launchpad on Sui — where UGC, fair finance, and awesome gameplay meet.

🚀 TL;DR

Leviathan is a Sui-native web3 game launchpad that empowers creators to build, customize, publish, and monetize on-chain-ready games — while protecting users from SUI volatility via Hermit Finance (hSui).
This repo contains the MVP blueprint: hSui swap, Salmon Launchpad (5×5 Yut-style board editor), Splash Zone (game browser + PvP), and the lightweight off-chain systems to make gameplay smooth.

✨ What makes it dope

Creator-first: No deep Move knowledge required — low-code / no-code game editor and templates.

Hybrid architecture: responsive, low-latency off-chain gameplay + on-chain financial settlement & verifiable game registration.

Reliable finance: delta-neutral hSui LST protects players from raw SUI volatility while keeping composability.

One-click publish: package game metadata to Walrus/IPFS and register on-chain with hSui fees.

MVP focus: ship fast, look polished, scale later.

🧭 # Key Features (MVP)

# Hermit Finance 
<img width="102.4" height="102.4" alt="Gemini_Generated_Image_a13bvga13bvga13b" src="https://github.com/user-attachments/assets/8b8850d3-ae19-49d7-a5d2-b7ab906bae5e" />

SUI ↔ hSui swap (deposit / mint / burn / withdraw).

# Salmon Launchpad
No-code game builder with templates (incl. 5×5 customizable Yut-like board): drag & drop, tile properties, rule editor, testplay.

# Splash Zone 
Game gallery, matchmaking, PvP with SUI staking and on-chain settlement (Match contract).

Off-chain truth + on-chain settlement — gameplay runs off-chain; signed final states submitted for trustful settlement.

Walrus/IPFS storage for game assets and immutable metadata.
