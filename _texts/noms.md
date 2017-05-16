---
layout: narrative
title: "Blockchain: Ethereum and Noms"
author: Michael Angerman
editor: Michael Angerman
rights: Public Domain
source: Arcadian Group
publication-date: 2017
toc:
- Title Page
- Section I
- References
---

---

## Note

My background is in data [retrieval, search, storage, and visualization].  When the blockchain was invented by
[Satoshi Nakamoto](https://en.wikipedia.org/wiki/Satoshi_Nakamoto) in 2008
it was mainly used as a new accounting methodology to guarantee that the transactions
that were listed was a public ledger for all to see.  Now the concept has branched out
to many other interesting areas of research. The products that are evolving from
there are fascinating and relevant, I will attempt to outline a few of those in this post.

---

<a id="title-page" />

<p class="centered large">Ethereum</p>
<p class="centered medium">The Future of P2P Blockchain Systems</p>

---

## Section I


My career has been wide and varied but over the past couple of years I have been focusing on Golang programming in P2P systems like Ethereum and Bitcoin.  I am also working on new ways to search, store and retrieve data structures embedded in blockchains most recently with a new system called Noms.

My main focus for the past couple of years has been in the golang bitcoin world namely decred and btcsuite and for the past year in the world of ethereum focusing on backend P2P system and on front end Solidity contracts and tools associated with compiling, deploying and debugging namely web3.js and Truffle.

One of the very cool things about writing and debugging the Solidity contracts is that one can simulate the Ethereum client with Testrpc which gives one the ability to use the Web3 provider interface namely handleRequest to simulate all of the Web3 calls that need to be instantiated and simulated. Testrpc in concert with Truffle is an invaluable resource for quickly testing all of the code paths that need to be checked when prototyping new Ethereum contracts using Solidity.

My interest in blockchains goes deeper as I am delving into newer blockchain like Merkle DAG systems such as Noms.  From an information storage and retrieval architecture one can think of Noms as a new style of database that tracks individual inserts / commits but enables one to have complete control over their local data similar to the way git works.  Tying back into Ethereum one can think of running your own Ethereum private network that gives you the ability to use the power of Etheruem but in your own company where accounting for things no matter what it may be is very important.  The currency aspect of Ethereum is at the top of the stack so there are many other types of applications that are relevant to blockchain type systems that lend themselves well to systems like Noms.

My other main area of technical interest is distributed computing where consensus in blockchain systems and proof of stake can act as  a nice model, it is also relevant in distributed computing for solving fault tolerance. It is interesting to note that consensus is a hot topic in today's cloud computing world where people are starting to realize how challenging it is to solve these problems correctly.

Consensus in Etcd, which is used by the popular deployment package Kubernetes, is based on a recent Stanford PhD thesis called Raft which enables replicated state machines to come to agreement on values you deem as important. Likewise, P2P systems in blockchain based systems use Proof of Stake like voting systems to agree on values that need to be persisted long term.

---

## References

[Btcsuite](https://github.com/btcsuite)  
[Decred](https://github.com/decred)  
[Etcd](https://coreos.com/etcd/docs/latest/)  
[Noms](https://github.com/attic-labs/noms)  
[Noms Intro](https://medium.com/@aboodman/noms-init-98b7f0c3566)  
[Raft](https://raft.github.io/)  
[Solidity](http://solidity.readthedocs.io/en/develop/)  
[Testrpc](https://github.com/ethereumjs/testrpc)  
[Truffle](http://truffleframework.com/)  
[Web3.js](https://github.com/ethereum/wiki/wiki/JavaScript-API)  
