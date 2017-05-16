---
layout: narrative
title: "Devops: Docker, Kubernetes, Hashicorp"
author: Michael Angerman
editor: Michael Angerman
rights: Public Domain
source: Arcadian Group
publication-date: 2017
toc:
- Title Page
- Chapter I
- References
---

---

## Note

Ever since Docker was released, developers have realized how important it is to be
able to easily manage cloud infrastructure.  I have been working in this area
since that time.  Initially, my motivation was to better understand the Go Programming
Language as Docker was one of the first major applications to be written in Go.  In fact,
I would claim that
[Solomon Hykes](https://www.forbes.com/sites/alexkonrad/2015/07/01/meet-docker-founder-solomon-hykes)
decision to choose Go as his language for developing Docker might have been the catalyst that launched Go on its path as one of the most popular systems programming languages today.

---

<a id="title-page" />

<p class="centered large">Devops</p>
<p class="centered medium">Managing the Cloud</p>

---

## CHAPTER I

My career has been wide and varied but over the past couple of years I have been focusing on Golang programming in the area of products that uses the Raft algorithm as their underlying infrastructure for distributed computing and fault tolerance. Both Kubernetes and Consul use Raft to allow for individual node failures while still maintaining state of the cluster system.  Kubernetes underlying distributed storage system uses Etcd.

Consensus in Etcd is based on a recent Stanford PhD thesis called Raft which enables replicated state machines to come to agreement on values you deem as important. Likewise, P2P systems in blockchain based systems use Proof of Stake like voting systems and also Proof of Work to agree on values that need to be persisted long term in both the Bitcoin and Ethereum blockchains.

In the past, I worked on the
[Rkt spec](https://github.com/rkt/rkt) 
which has integrations with Hashicorp's Nomad and Kubernetes.  I am also familiar in my past work with the internal workings of Docker via Systemd.

---

## References

[Docker](https://www.docker.com/)  
[Creating Containers](http://crosbymichael.com/creating-containers-part-1.html)  
[Kubernetes](https://kubernetes.io/)  
[Hashicorp](https://www.hashicorp.com/)  
