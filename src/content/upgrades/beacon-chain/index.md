---
title: The Beacon Chain
description: Learn about the Beacon Chain - the upgrade that introduced proof-of-stake Ethereum.
lang: en
template: upgrade
sidebar: true
image: ../../../assets/upgrades/core.png
summaryPoint1: The Beacon Chain introduced proof-of-stake to the Ethereum ecosystem.
summaryPoint2: It was merged with the original Ethereum proof-of-work chain in September 2022.
summaryPoint3: The Beacon Chain introduced the consensus logic and block gossip protocol which now secures Ethereum.
---

<UpgradeStatus isShipped dateKey="page-upgrades-beacon-date">
  The Beacon Chain shipped on December 1, 2020, and formalized proof-of-stake as Ethereum's consensus mechanism with The Merge upgrade on September 15, 2022.
</UpgradeStatus>

## What was the Beacon Chain? {#what-is-the-beacon-chain}

The Beacon Chain was the name of the original proof-of-stake blockchain that was launched in 2020. It was created to ensure the proof-of-stake consensus logic was sound and sustainable before enabling it on Ethereum Mainnet. Therefore, it ran alongside the original proof-of-work Ethereum. Switching off proof-of-work and switching on proof-of-stake on Ethereum required instructing the Beacon Chain to accept transactions from the original Ethereum chain, bundle them into blocks and then organize them into a blockchain using a proof-of-stake based consensus mechanism. At the same moment, the original Ethereum clients turned off their mining, block propagation and consensus logic, handing that all over to the Beacon Chain. This event was known as [The Merge](/upgrades/merge/). Once The Merge happened, there were no longer two blockchains; there was just one proof-of-stake Ethereum chain.

## What did the Beacon Chain do? {#what-does-the-beacon-chain-do}

The Beacon Chain was the name given to a ledger of accounts that conducted and coordinated the network of Ethereum [stakers](/staking/) before those stakers started validating real Ethereum transactions. It did not process transactions or handle smart contract interactions.

It introduced the consensus engine (or "consensus layer") that took the place of proof-of-work mining on Ethereum and brought many significant improvements with it.

The Beacon Chain was a foundational component for [the secure, environmentally friendly and scalable Ethereum we have now](/upgrades/vision/).

## Beacon Chain impact {#beacon-chain-features}

### Introducing staking {#introducing-staking}

The Beacon Chain introduced [proof-of-stake](/developers/docs/consensus-mechanisms/pos/) to Ethereum. This keeps Ethereum secure and earns validators more ETH in the process. In practice, staking involves staking ETH in order to activate validator software. As a staker, you run the software that creates and validates new blocks in the chain.

Staking serves a similar purpose that [mining](/developers/docs/mining/) used to, but is different in many ways. Mining required large up-front expenditures in the form of powerful hardware and energy consumption, resulting in economies of scale, and promoting centralization. Mining also did not come with any requirement to lock up assets as collateral, limiting the protocol's ability to punish bad actors after an attack.

The transition to proof-of-stake made Ethereum significantly more secure and decentralized by comparison to proof-of-work. The more people that participate in the network, the more decentralized and safe from attacks it becomes.

<InfoBanner emoji=":money_bag:">
  If you're interested in becoming a validator and helping secure the Ethereum, <a href="/staking/">learn more about staking</a>.
</InfoBanner>

### Setting up for sharding {#setting-up-for-sharding}

Since the Beacon Chain merged with the original Ethereum Mainnet, the Ethereum community started looking to scaling the network.

Proof-of-stake has the advantage of having a registry of all approved block producers at any given time, each with ETH at stake. This registry sets the stage for the ability to divide and conquer but reliably split up specific network responsibilities.

This responsibility is in contrast to proof-of-work, where miners have no obligation to the network and could stop mining and turn their node software off permanently in an instant without repercussion. There is also no registry of known block proposers and no reliable way to split network responsibilities safely.

[More on sharding](/upgrades/sharding/)

## Relationship between upgrades {#relationship-between-upgrades}

The Ethereum upgrades are all somewhat interrelated. So let’s recap how the Beacon Chain affects the other upgrades.

### Beacon Chain and The Merge {#merge-and-beacon-chain}

At first, The Beacon Chain existed separately from Ethereum Mainnet, but they were merged in 2022.

<ButtonLink to="/upgrades/merge/">
  The Merge
</ButtonLink>

### Shards and the Beacon Chain {#shards-and-beacon-chain}

Sharding can only safely enter the Ethereum ecosystem with a proof-of-stake consensus mechanism in place. The Beacon Chain introduced staking, which 'merged' with Mainnet, paving the way for sharding to help further scale Ethereum.

<ButtonLink to="/upgrades/sharding/">
  Shard chains
</ButtonLink>

## Further Reading

- [More on Ethereum's future upgrades](/upgrades/vision)
- [More of proof-of-stake](/developers/docs/consensus-mechanisms/pos)
