<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://static.ringsnetwork.io/ringsnetwork_logo.png">
  <img alt="Rings Network" src="https://raw.githubusercontent.com/RingsNetwork/asserts/main/logo/rings_network_red.png">
</picture>

Rings Whitepaper
===============

This repo is about whitepapers of rings network, you can find tex source and compiled files here.

The Rings Paper
---------------

The [Rings Paper](https://raw.githubusercontent.com/RingsNetwork/whitepaper/master/rings.pdf) provides an overview of the Rings Network architecture, explaining the design principles, the operating mechanisms, and the core features that distinguish it from other blockchain systems. It delves into the network's efficient consensus protocol, improved scalability, and security measures that make it ideal for a wide range of applications.

```bib
@misc{RingsNetwork,
    author = "Ryan J. Kung",
    title = "Rings: A peer-to-peer network for sovereign age",
    year = "2023",
    url = "https://github.com/RingsNetwork/whitepaper/rings.pdf"
}
```


The DRank Paper
---------------

The [DRank Paper](https://raw.githubusercontent.com/RingsNetwork/whitepaper/master/pos.pdf) presents a comprehensive reputation system for monitoring and evaluating the performance of nodes in a structured peer-to-peer (P2P) network. The system aims to foster responsible behavior and deter cheating among network participants. The reputation system is comprised of two main components: local rankings and global rankings. Local rankings reflect the behavior of each node within its own network, while global rankings provide a comprehensive view of the behavior of all nodes in the entire network. To ensure the system's reliability, it utilizes reward proofs and punishment proofs. Nodes exhibiting good behavior are rewarded, while nodes engaging in undesirable actions are penalized, thus creating an environment where nodes are motivated to act ethically and cheating is discouraged.

```bib
@misc{RankingProtocol,
    author = "Ryan J. Kung",
    title = "The Ranking Protocol",
    year = "2023",
    url = "https://github.com/RingsNetwork/whitepaper/ranking_protocol.pdf",
    note = "(accessed on July 13, 2023)"
}
```


The BNS Paper
-------------

The [BNS Paper](https://raw.githubusercontent.com/RingsNetwork/whitepaper/master/bns.pdf), BNS is a proposed system that aims to enhance the Bitcoin network by introducing a structured peer-to-peer network based on Distributed Hash Tables (DHTs), providing DHT storage capabilities and DID services. BNS is developed using Rings, a modern browser-native P2P network that implements the Chord algorithm, which can provide extendable DNS services and secure network traffic for web2 and web3 applications on blockchains. Rings Network can be run on servers and browsers using WebAssembly, with both nodes being functionally equivalent.

```bib
@misc{BNSNetwork,
    author = "Rings Network Dev Team",
    title = "BNS - A Segregated Network System for Bitcoin",
    year = "2023",
    url = "https://github.com/RingsNetwork/whitepaper/bns.pdf",
    note = "(accessed on July 13, 2023)"
}
```
