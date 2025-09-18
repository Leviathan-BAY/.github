# Leviathan — Web3 Game Launchpad
<p align="center">
  <img width="306" height="468" alt="image" src="https://github.com/user-attachments/assets/fabda521-ab84-4926-b030-5fd56a07fcc5" />
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
<p align="center">
<img width="306" height="306" alt="Hermit" src="https://github.com/user-attachments/assets/00719eef-c05f-4976-b165-b32e7adefb07" />
</p>  

SUI ↔ hSui swap (deposit / mint / burn / withdraw).

# Humpback Launchpad
<p align="center">
<img width="306" height="306" alt="Humpback" src="https://github.com/user-attachments/assets/3e3bc0e0-6125-4f37-8ad3-8cf84ca1f04f" />
</p>  

No-code game builder with templates (incl. 5×5 customizable Yut-like board): drag & drop, tile properties, rule editor, testplay.

# Splash Zone 
<p align="center">
<img width="500" height="500" alt="Splash Zone" src="https://github.com/user-attachments/assets/79504009-e349-4a84-b873-aeb8a6a87cfe" />
</p>  

Game gallery, matchmaking, PvP with SUI staking and on-chain settlement (Match contract).

Off-chain truth + on-chain settlement — gameplay runs off-chain; signed final states submitted for trustful settlement.

Walrus/IPFS storage for game assets and immutable metadata.
