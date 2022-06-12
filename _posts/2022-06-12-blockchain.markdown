---
layout: post
title: Blockchain
date: 2022-06-12 00:00:00 -0300
tags: [Blockchain]
---

## What is a blockchain?
Blockchain is a database, shared and distributed. It records data in a chain of blocks (in a probabilistically impossible way to edit or hack it), each block built grouping a set of transactions that, in the end, are updating the global state of the network.

## State
Each blockchain start with a "genesis" state, each following transacion updates that global state and in turn it is replicated across all nodes of the network.

All transactions agre grouped in blocks and chained together in a cryptographycally verifiable way (therefore, state is traceable and reproducible by starting from the genesis -or any other block- and transitioning each block's information until now).

## Nodes
The blockchain is a distributed P2P network of nodes. Simply put, each node is keeping a copy of the global transaction ledger, so each node idividually can verify and audit transactions on the network and ensure no ilicit is being made. Another type of node (mining node) is responsible of grouping transactions to create a block and propose it to be included  in the global ledger by eveyone else. This mining work is computationally expensive, so miner whose block are accepted, get rewarded with a token. 

Using a blockchain ensures that each unit of value was transferred only once, solving the  [double-spending](https://en.wikipedia.org/wiki/Double-spending) problem.

## Decentralization
Storing data in a P2P network means the blockchain is a decentralized network.
This has significant benefits over storing data in a centralized manner. There are significant problems with centralization:

* Data breaches in centralized systems expose lot of data
* Centralized authorities can censor and shut down speech
* Reliance on a central authority means upstream problems affect downstream consumers (e.g. AWS going down means most of the internet goes down with it)

On the other hand, decentralization brings about the opposite benefits.

* No censorship as there is no single authority or middleman that can censor you
* No downtime as the overall network is running across 1000's of nodes across the globe
* Highly attack resistant making it infeasible to manipulate or destroy data

Thanks for reading!
