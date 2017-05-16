---
layout: narrative
title: "Blockchain: Ethereum and Noms"
author: Michael Angerman
editor: Storm
rights: Public Domain
source: Arcadian Group
publication-date: 2017
toc:
- Title Page
- Chapter I
- Chapter II
- Chapter III
- Appendix
- A Parody
---

---

## Note

witness was used in making their digital edition. The edition below is only a slightly modified version of the Guttenberg text, and therefore should not be taken too seriously as an edition. I use the text mostly to show a few affordances of using Ed for long form narrative.

---

<a id="title-page" />

<p class="centered large">Ethereum</p>
<br>
<p class="centered medium">The Future of P2P Blockchain Systems</p>

---

## FREDERICK DOUGLASS.


Frederick Douglass was born in slavery as Frederick Augustus Washington Bailey near Easton in Talbot County, Maryland. He was not sure of the exact year of his birth, but he knew that it was 1817 or 1818. As a young boy he was sent to Baltimore, to be a house servant, where he learned to read and write, with the assistance of his master's wife. In 1838 he escaped from Frederick Douglass*, published in 1855 and 1881 respectively. He died in 1895.

---

## CHAPTER I


My career has been wide and varied but over the past couple of years I have been focusing on Golang programming in P2P systems like Ethereum and Bitcoin.  I am also working on new ways to search, store and retrieve data structures embedded in blockchains most recently with a new system called Noms.

My main focus for the past couple of years has been in the golang bitcoin world namely decred and btcsuite and for the past year in the world of ethereum focusing on backend P2P system and on front end Solidity contracts and tools associated with compiling, deploying and debugging namely web3.js and Truffle.

One of the very cool things about writing and debugging the Solidity contracts is that one can simulate the Ethereum client with Testrpc which gives one the ability to use the Web3 provider interface namely handleRequest to simulate all of the Web3 calls that need to be instantiated and simulated. Testrpc in concert with Truffle is an invaluable resource for quickly testing all of the code paths that need to be checked when prototyping new Ethereum contracts using Solidity.

My interest in blockchains goes deeper as I am delving into newer blockchain like Merkle DAG systems such as Noms.  From an information storage and retrieval architecture one can think of Noms as a new style of database that tracks individual inserts / commits but enables one to have complete control over their local data similar to the way git works.  Tying back into Ethereum one can think of running your own Ethereum private network that gives you the ability to use the power of Etheruem but in your own company where accounting for things no matter what it may be is very important.  The currency aspect of Ethereum is at the top of the stack so there are many other types of applications that are relevant to blockchain type systems that lend themselves well to systems like Noms.

My other main area of technical interest is distributed computing where consensus in blockchain systems and proof of stake can act as  a nice model, it is also relevant in distributed computing for solving fault tolerance. It is interesting to note that consensus is a hot topic in today's cloud computing world where people are starting to realize how challenging it is to solve these problems correctly.

Consensus in Etcd, which is used by the popular deployment package Kubernetes, is based on a recent Stanford PhD thesis called Raft which enables replicated state machines to come to agreement on values you deem as important. Likewise, P2P systems in blockchain based systems use Proof of Stake like voting systems to agree on values that need to be persisted long term.


---

## APPENDIX

I find, since reading over the foregoing Narrative, that I have, in several instances, spoken in such a tone and manner, respecting religion, as may possibly lead those unacquainted with my religious views to suppose me an opponent of all religion. To remove the liability of such misapprehension, I deem it proper to append the following brief explanation. What I have said

> - Just God! and these are they,
> - Who minister at thine altar, God of right!
> - Men who their hands, with prayer and blessing, lay
> - On Israel's ark of light.
{:.poetry}
> - What! preach, and kidnap men?
> - Give thanks, and rob thy own afflicted poor?
> - Talk of thy glorious liberty, and then
> - Bolt hard the captive's door?
{:.poetry}

The Christianity of America is a Christianity, of whose votaries it may be as truly said, as it was of the ancient scribes and Pharisees, "They bind heavy burdens, and grievous to be borne, and lay them on men's shoulders, but they themselves will not move them with one of

---

## A PARODY

> - Come, saints and sinners, hear me tell
> - How pious priests whip Jack and Nell,
> - And women buy and children sell,
> - And preach all sinners down to hell,
> - And sing of heavenly union.
> ^
> - All good from Jack another takes,
> - And entertains their flirts and rakes,
> - Who dress as sleek as glossy snakes,
> - And cram their mouths with sweetened cakes;
> - And this goes down for union.
{:.poetry}


Sincerely and earnestly hoping that this little book may do something toward throwing light on the American slave system, and hastening the glad day of deliverance to the millions of my brethren in bonds—faithfully relying upon the power of truth, love, and justice, for success in my humble efforts—and solemnly pledging my self anew to the sacred cause,—I subscribe myself,

FREDERICK DOUGLASS.
LYNN, *Mass., April* 28, 1845.

THE END

---

[References to **Concepts** mentioned above...]

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
