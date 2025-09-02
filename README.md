# Hi there, I'm Tereza
I'm a cybersecurity graduate from VUT FIT. This is my GitHub portfolio where you'll find a collection of my projects. My main interests are in blockchain security, mainly Ethereum so far, although I am open to explore new directions. 

`cybersec` `blockchains` `research` `development`

## Experience
During the [cohort four](https://github.com/eth-protocol-fellows/cohort-four) of the Ethereum Protocol Fellowship, I worked on the implementation of Ephemery testnet in [Lighthouse](https://github.com/terezaburianova/lighthouse) and [reth](https://github.com/terezaburianova/reth). I also helped to review, finalize and polish the proposal and the tooling, becoming a co-author of [EIP-6916](https://eips.ethereum.org/EIPS/eip-6916). The project was [presented at Devconnect Istanbul](https://streameth.org/65a90bf27932ebe436ba9348/watch?session=65b8f8cca5b2d09b88ec0f02).

I also worked at SAP Labs Brno as Developer Associate. My tasks included developing and maintaining testing tools and implementing small tasks in ABAP.

## Publications
*(Click a publication name below to expand and see details.)*
<details>
<summary>
<img alt="Static Badge" src="https://img.shields.io/badge/Featured-08872B">
<b>Master's Thesis</b>: 
Safeguarding PoS Consensus: A Comparative Analysis of Proposer Protection Mechanisms Against Various Attack Vectors
</summary>

- `English` `Rust`
- [Thesis](https://www.vut.cz/en/students/final-thesis/detail/164846) | [Implementation](https://github.com/terezaburianova/leader-election-sim)
- Presented at [Excel@FIT](https://excel.fit.vutbr.cz/sbornik/) and [ETHPrague](https://ethprague.com/schedule?talk=1207-poster-session)
- Dean's Award for Excellent Master's Thesis
- **Abstract:** The thesis deals with proposer protection mechanisms in the Ethereum Proof-of-Stake consensus. The aim is to introduce the principles and possible weaknesses of the consensus mechanism, identify and investigate potential attack vectors targeting proposers, evaluate various proposer protection mechanisms and further investigate two selected mechanisms, Whisk and homomorphic sortition, by simulating their behaviour under different circumstances. For this purpose, a simulation framework was designed and several scenarios were proposed to test the security effectiveness of the mechanisms during the attack. Measurements were conducted to estimate the computational demand of both mechanisms. Finally, the results were discussed, the feasibility of the mechanisms was determined and topics for future research and improvements were suggested.

</details>

<details><summary><b>Master's Thesis Survey Article:</b> Preventing Attacks Leveraging the Publicly Known List of Upcoming Proposers in Ethereum</summary>

- `English`
- [Article](https://github.com/terezaburianova/terezaburianova/blob/390d19e9a0acc3fd6d5e9e49d22d01e12ad403d4/publications/DP_survey.pdf)
- **Abstract:** In the Ethereum PoS, the block proposers are known in advance and it is possible to obtain their IP addresses. This can lead to attacks like DoS, which can have negative impact on the network. The paper provides an overview of proposed and researched measures. The measures implemented partially or completely on the consensus layer include SSLE, like Whisk or Swap-or-Not SSLE, which generally manipulate a set of validators to hide the proposer’s identity. These solutions are feasible based on the concluded research but are too complex. SnSLE,
including the solution implemented in Algorand and the proposal adapted to Ethereum, select several proposers and choose one of them after their proposals. The anonymity set in these cases corresponds to the validator set, but fork-choice complications are introduced. The proposal for Polkadot is partially implemented on the network layer. It utilizes a construct called ring-VRF, which combines VRF and SNARKs. A solution implemented solely on the network layer, utilizing Dandelion++ and RLN to add a private pre-network, has also been included. Network layer solutions have too high latency based on an existing analysis and also are susceptible to attacks. The last solution is the distributed validators technology, where the obligations of one validator are distributed among several nodes. This solution is complex but increases the costs and requires a new type of client. The paper further describes the principle of each method, their drawbacks and points of further research, the methods are also
briefly compared based on various properties.
</details>

<details>
<summary>
<b>Game Theory Course Project:</b> How Ethereum Utilizes Auctions to Mitigate Negative MEV Impact
</summary>

- `English`
- [Article](https://github.com/terezaburianova/terezaburianova/blob/38f0a98f03d3632e1cfc295fe191b01e3decdb3f/publications/THE.pdf)
- In Ethereum, MEV allows block proposers to increase their reward by ordering, including and excluding the transactions in the block. The profit gained from MEV can be significant. While MEV is an important part of many mechanisms, it can also have negative impact on the
consensus of PoS Ethereum. One of the mechanisms that has been proposed to mitigate these negative effects is the Proposer-Builder Separation (PBS). This project aims to generally describe the PBS mechanism and then take
a closer look at how the mechanism utilizes auctions. It describes the architecture of the PBS, analyses the blockspace auction of the MEV-Boost implementation and shortly introduces the Order Flow Auctions.
</details>

<details>
<summary>
<b>Bachelor's Thesis</b>:
Modeling and Simulation of Incentive Mechanisms in Ethereum
</summary>

- `English` `Jupyter Notebook`
- [Thesis](https://www.vut.cz/en/students/final-thesis/detail/145085) | [Implementation](https://github.com/terezaburianova/incentive-mechanism-analysis/)
- **Abstract:** The topic of this thesis is the Ethereum incentive mechanism, in particular the changes introduced in EIP-1559. The aim of the thesis is to investigate the behaviour and propose any potential improvements in case of discovered flaws. The previously used first price auction mechanism required users to choose the incentive arbitrarily, which led to overpaying and high fee volatility. These problems occurred mainly due to higher network utilization after the popularization of projects such as decentralized finance, NFT collections, and the metaverse. The new incentive mechanism introduced the variable block size, which can adapt to the current network usage. Base fee, a value that indicates the minimum fee needed to include the transaction in the block, is then calculated based on the utilization of the previous block, making the fees more predictable. Several simulation experiments were proposed to investigate the typical behaviour and possible weaknesses of the mechanism. Finally, a possible improvement was found, and future research was proposed. The goals of the thesis were achieved, and the results were presented in the thesis.
</details>

<details>
<summary>
<b>Secure Hardware Devices Course Project:</b> Relay Attack Survey
</summary>

- `English`
- [Article](https://github.com/terezaburianova/terezaburianova/blob/390d19e9a0acc3fd6d5e9e49d22d01e12ad403d4/publications/BZA.pdf)
- **Abstract:** This survey summarizes interesting research regarding relay attacks with focus on the most affected areas - Passive Keyless Entry and Start vehicles, contactless payments and NTLM. Implementations of the attack and possible countermeasures are presented, with one of the most universal measures being distance bounding protocols.
</details>

## University Projects
*(Click a name or category below to expand and see details.)*
<details>
<summary>
Monitoring of BitTorrent Traffic in LAN
</summary>

- `English` `Python` `Networks` `Protocols`
- [Repository](https://github.com/terezaburianova/VUT-PDS) | [Protocol](https://github.com/terezaburianova/VUT-PDS/blob/562de0105c096a5dcb1f846b1ec08ec6b4db0b32/xburia28.pdf)
- In this project, the behaviour of protocols used in the BitTorrent architecture and communication was analysed and the findings were further described in detail. Methods for protocol detection were proposed and finally, the implementation of the chosen methods was presented.
</details>

<details>
<summary>
Hybrid RSA–AES Secure Communication System
</summary>

- `Python` `Cryptography` 
- [Repository](https://github.com/terezaburianova/VUT-KRY-AES-RSA/)
- This project implements a secure client–server messaging system where messages are encrypted with AES, the AES key is securely exchanged with RSA, and message integrity/authenticity is verified with RSA-signed hashes.
</details>

<details>
<summary>
Implementation and Breaking of Affine Cipher
</summary>

- `Czech` `C++` `Python` `Cryptography` `Frequency analysis`
- [Repository](https://github.com/terezaburianova/VUT-KRY-cipher-breaking) | [Documentation](https://github.com/terezaburianova/VUT-KRY-cipher-breaking/blob/f26b9c02d27db852dcc1ad3fce59a2f09f0836e3/doc.pdf)
- This project implements cryptanalysis tools for breaking and analyzing simple substitution ciphers, focusing on the Affine cipher. It provides functionality for encryption, decryption (with or without keys), and automated key recovery using frequency analysis, with special support for Czech language detection.
</details>

<details>
<summary>
Applied Information Security Project
</summary>

- `Czech` `Security`
- [Documentation](https://github.com/terezaburianova/terezaburianova/blob/da5666e1e2c190869840f70e4372ad8f18f39f9d/publications/BIS.pdf)
- An information security project based on a narrative case study that involved uncovering hidden data and solving cryptographic challenges. The project combined practical cryptography, secure communication, and investigative analysis to simulate a real-world security problem.
</details>

<details>
<summary>
Assessment of Retinal Image Quality Based on General Characteristics
</summary>

- `Czech` `Security` `Biometry`
- [Repository](https://github.com/terezaburianova/VUT-BIO) | [Documentation](https://github.com/terezaburianova/VUT-BIO/blob/ef082c211e5e3721b4d4240c59c13810f06c6e5d/docs/docs.pdf)
- The work deals with evaluating the quality of retinal images based on sharpness and illumination. The goal is to implement algorithms that can quantitatively express the quality of images based on various properties, as well as to conduct experiments and analyze the achieved results. The resulting metrics can then be used for further classification of other images, for example using the k-nearest neighbors method or the support vector machine method.
</details>

<details>
<summary>
Other Master's Projects
</summary>

- **Parallel and Distributed Algorithms**
  - `C++`
  - [Parallel Splitting Algorithm](https://github.com/terezaburianova/VUT-PRL-splitting/) | [K-Means algorithm](https://github.com/terezaburianova/VUT-PRL-Kmeans)
- **Functional and Logic Programming**
  - `Haskell` `Prolog`
  - [Decision Trees Classification and Training](https://github.com/terezaburianova/VUT-FLP-FP/) | [Hamiltonian Cycles](https://github.com/terezaburianova/VUT-FLP-LP/)
- **Computation Systems Architectures**
  - `C++`
  - [Parallelization](https://github.com/terezaburianova/VUT-AVS-paralelizace/) | [Vectorization](https://github.com/terezaburianova/VUT-AVS-vektorizace/)
- **Artificial Intelligence and Machine Learning**
  - `C++` `Python`
  - [Freecell](https://github.com/terezaburianova/VUT-SUI-freecell) | [Neural Networks](https://github.com/terezaburianova/VUT-SUI-neural)
- **Data Storage and Preparation**
  - `Jupyter Notebook` `Python` `Shell`
  - [Repository](https://github.com/terezaburianova/VUT-UPA)
</details>

<details>
<summary>
Other Bachelor's Projects
</summary>

- **Introduction to Programming Systems**
  - `C`
  - [Repository](https://github.com/terezaburianova/VUT-IZP)
- **Operating Systems**
  - `C`
  - [Repository](https://github.com/terezaburianova/VUT-IOS/tree/master/proj2)
- **Computer Communications and Networks**
  - `Python`
  - [Repository](https://github.com/terezaburianova/VUT-IPK/tree/main/proj1)
- **Network Applications and Network Administration**
  - `C++` `Lua`
  - [Repository](https://github.com/terezaburianova/VUT-ISA)
- **Signals and Systems**
  - `Jupyter Notebook`
  - [Repository](https://github.com/terezaburianova/VUT-ISS/)
- **Principles of Programming Languages**
  - `Python` `PHP`
  - [Repository](https://github.com/terezaburianova/VUT-IPP/)
- **Database Systems**
  - `SQL`
  - [Repository](https://github.com/terezaburianova/VUT-IDS)
</details>
