![Status Badge](https://img.shields.io/badge/Status-archived-red)

**NOTE:** This lab has been archived and is no longer being maintained.

# [NEFERTI](https://wiki.hyperledger.org/display/CP/NEFERTI)

## Description 
**NEFERTI**  plans a low-code and highly secure implementation to issue and trade NFTs, in a **protocol agnostic way**. NEFERTI code will address market place utilities for issuance and trading of NFTs. NEFERTI implementation will allow for extensibility and openness. An initial reference Hyperledger Fabric implementation is planned.

## Motivation
An NFT, as many already know, is an acronym for **N**on **F**ungible **T**oken. A token is a digital or physical object that stands for something else. Tokens must be issued following a strict process, there must be easy ways to verify that a token is a legitimate representation of value. The object that a token stands for can be digital or analog. Key to the definition of an NFT, is fungibility. Fungibility is a property for units of commodity or a good to be interchangeable. USD is fungible, gold of the same purity and composition is fungible. Fungibility needs a measure, a unit of currency, a gram of gold, a barrel of oil, one share of IBM. Fungibility hinges on the indistinguishability of such units. When examined closely Fungibility itself is a spectrum, sometimes limited by taint, by geography, by the number of units.

In NFT, the definition of fungibility is negated; that is, each token is unique and one cannot be exchanged for another. 

A software system for the **creation** and **trading** for NFTs has to account for a way to **tie the NFT to the unique object at issuance (Identity, authorization and a global registry)**; a marketplace for trading NFTs, which means **establishing a price** for the NFT as well as to **transfer ownership**. This means an implementation of these actions through interfaces supported by NFT token attributes and metadata.

As reuse is one of the defining characteristics of human endeavor, the following is proposed. 

* Adopt a token standard (a combination of the TTF and ERC- inspired standards)  
* Implement a marketplace (recode samples )
* Use Hyperledger Fabric as the underlying utility. See how ERC standards have been implemented in Fabric.
* A complex systems view (Identity, distribution, decentralization, fairness, payment systems, cross-border, multi-protocol, interoperability of tokens, standards)- See under extensions.



## What is the Vision of NEFERTI?
* General philosophy drivers [Moxie Marlinspike](https://moxie.org/2022/01/07/web3-first-impressions.html), [Vitalik Buterin](https://np.reddit.com/r/ethereum/comments/ryk3it/my_first_impressions_of_web3/hrrz15r/) and O'Reilly, [Wrapped Tokens](https://www.wraptokens.com/)
* Existing code in fabric [ERC-721](https://github.com/hyperledger/fabric-samples/tree/main/token-erc-721), [ERC-1155](https://eips.ethereum.org/EIPS/eip-1155) and newer standards. 
* Smart Contract Generators using a framework: Generators
* Identity solutions (Aries, Indy)
* Storage solutions (storj, ipfs, private data collections etc.)
* Integrating with payments (tokens etc.)
*Standards
* Decentralize infrastructure (middleware and contact points)
* UX / UI - wallets
* What can we reuse
* Testnet or sandboxes incorporating protocols and middleware.
* Interoperability using HL solutions
* Security- more than just cryptography