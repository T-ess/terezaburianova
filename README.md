# Hi, I'm Tereza

- 🎓 I graduated with an M.Sc. in Computer Science from the Brno University of Technology.
- 💻 My specialization is cybersecurity, but I have broad knowledge and a strong passion for coding.
- 💹 I’m passionate about blockchain technologies, though I’m also open to roles in other areas, especially FinTech.
- ❓ I work with Rust and Python lately, I also have some experience with other languages (C, C++, Haskell...), I'm now exploring Java.
- 💼 I’m open to discuss interesting projects. Feel free to reach out via [email](mailto:tess.burianova@gmail.com) or [LinkedIn](https://www.linkedin.com/in/tereza-burianova/) if you’d like to chat.

## 📖 Research & Writing
*(Click a publication name below to expand and see details.)*
<details>
<summary>
<b>Paper</b>:
Secret Leader Election in Ethereum PoS: An Empirical Security Analysis of Whisk and Homomorphic Sortition under DoS on the Leader and Censorship Attacks
</summary>
  
- [Preprint on arXiv](https://arxiv.org/abs/2509.24955)
- **Abstract:** Proposer anonymity in Proof-of-Stake (PoS) blockchains is a critical concern due to the risk of targeted attacks such as malicious denial-of-service (DoS) and censorship attacks. While several Secret Single Leader Election (SSLE) mechanisms have been proposed to address these threats, their practical impact and trade-offs remain insufficiently explored. In this work, we present a unified experimental framework for evaluating SSLE mechanisms under adversarial conditions, grounded in a simplified yet representative model of Ethereum's PoS consensus layer. The framework includes configurable adversaries capable of launching targeted DoS and censorship attacks, including coordinated strategies that simultaneously compromise groups of validators. We simulate and compare key protection mechanisms - Whisk, and homomorphic sortition. To the best of our knowledge, this is the first comparative study to examine adversarial DoS scenarios involving multiple attackers under diverse protection mechanisms. Our results show that while both designs offer strong protection against targeted DoS attacks on the leader, neither defends effectively against coordinated attacks on validator groups. Moreover, Whisk simplifies a DoS attack by narrowing the target set from all validators to a smaller list of known candidates. Homomorphic sortition, despite its theoretical strength, remains impractical due to the complexity of cryptographic operations over large validator sets.
  
</details>

<details>
<summary>
<b>Master's Thesis</b>:
Safeguarding PoS Consensus: A Comparative Analysis of Proposer Protection Mechanisms Against Various Attack Vectors
</summary>

- [Thesis](https://www.vut.cz/en/students/final-thesis/detail/164846) | [Implementation](https://github.com/terezaburianova/leader-election-sim) | [Survey Paper](https://github.com/terezaburianova/terezaburianova/blob/390d19e9a0acc3fd6d5e9e49d22d01e12ad403d4/publications/DP_survey.pdf)
- Presented at [Excel@FIT](https://excel.fit.vutbr.cz/sbornik/) and [ETHPrague](https://ethprague.com/schedule?talk=1207-poster-session), Dean's Award for Excellent Master's Thesis
- **Abstract:** The thesis deals with proposer protection mechanisms in the Ethereum Proof-of-Stake consensus. The aim is to introduce the principles and possible weaknesses of the consensus mechanism, identify and investigate potential attack vectors targeting proposers, evaluate various proposer protection mechanisms and further investigate two selected mechanisms, Whisk and homomorphic sortition, by simulating their behaviour under different circumstances. For this purpose, a simulation framework was designed and several scenarios were proposed to test the security effectiveness of the mechanisms during the attack. Measurements were conducted to estimate the computational demand of both mechanisms. Finally, the results were discussed, the feasibility of the mechanisms was determined and topics for future research and improvements were suggested.
</details>

<details>
<summary>
<b>Specification</b>: 
 EIP-6916
</summary>

 - [Specification](https://eips.ethereum.org/EIPS/eip-6916)
 - I am a co-author of the “EIP-6916: Automatically Reset Testnet” specification. I analysed protocol-level feasibility and identified discrepancies in relation to integration with the current implementation. I also partially implemented this specification in Rust-based Ethereum clients.
</details>

<details>
<summary>
<b>Game Theory Course Project:</b> How Ethereum Utilizes Auctions to Mitigate Negative MEV Impact
</summary>

- [Paper](https://github.com/terezaburianova/terezaburianova/blob/38f0a98f03d3632e1cfc295fe191b01e3decdb3f/publications/THE.pdf)
- In Ethereum, MEV allows block proposers to increase their reward by ordering, including and excluding the transactions in the block. The profit gained from MEV can be significant. While MEV is an important part of many mechanisms, it can also have negative impact on the
consensus of PoS Ethereum. One of the mechanisms that has been proposed to mitigate these negative effects is the Proposer-Builder Separation (PBS). This project aims to generally describe the PBS mechanism and then take
a closer look at how the mechanism utilizes auctions. It describes the architecture of the PBS, analyses the blockspace auction of the MEV-Boost implementation and shortly introduces the Order Flow Auctions.
</details>

<details>
<summary>
<b>Bachelor's Thesis</b>:
Modeling and Simulation of Incentive Mechanisms in Ethereum
</summary>

- [Thesis](https://www.vut.cz/en/students/final-thesis/detail/145085) | [Implementation](https://github.com/terezaburianova/incentive-mechanism-analysis/)
- **Abstract:** The topic of this thesis is the Ethereum incentive mechanism, in particular the changes introduced in EIP-1559. The aim of the thesis is to investigate the behaviour and propose any potential improvements in case of discovered flaws. The previously used first price auction mechanism required users to choose the incentive arbitrarily, which led to overpaying and high fee volatility. These problems occurred mainly due to higher network utilization after the popularization of projects such as decentralized finance, NFT collections, and the metaverse. The new incentive mechanism introduced the variable block size, which can adapt to the current network usage. Base fee, a value that indicates the minimum fee needed to include the transaction in the block, is then calculated based on the utilization of the previous block, making the fees more predictable. Several simulation experiments were proposed to investigate the typical behaviour and possible weaknesses of the mechanism. Finally, a possible improvement was found, and future research was proposed. The goals of the thesis were achieved, and the results were presented in the thesis.
</details>

<details>
<summary>
<b>Secure Hardware Devices Course Project:</b> Relay Attack Survey
</summary>

- [Paper](https://github.com/terezaburianova/terezaburianova/blob/390d19e9a0acc3fd6d5e9e49d22d01e12ad403d4/publications/BZA.pdf)
- **Abstract:** This survey summarizes interesting research regarding relay attacks with focus on the most affected areas - Passive Keyless Entry and Start vehicles, contactless payments and NTLM. Implementations of the attack and possible countermeasures are presented, with one of the most universal measures being distance bounding protocols.
</details>

## 🎓 University Projects
*(Click a category below to expand and see details.)*

<details>
<summary>
<b>Selected Master's Projects</b>
</summary>

- Data Communications, Computer Networks and Protocols: [Monitoring of BitTorrent Traffic in LAN](https://github.com/terezaburianova/VUT-PDS)
- Cryptography: [Hybrid RSA–AES Secure Communication System](https://github.com/terezaburianova/VUT-KRY-AES-RSA/) | [Implementation and Breaking of Affine Cipher](https://github.com/terezaburianova/VUT-KRY-cipher-breaking)
- Information System Security: [Internal Network Security Audit (Capture-The-Flag style)](https://github.com/terezaburianova/terezaburianova/blob/da5666e1e2c190869840f70e4372ad8f18f39f9d/publications/BIS.pdf)
- Biometry: [Assessment of Retinal Image Quality Based on General Characteristics](https://github.com/terezaburianova/VUT-BIO)
- Artificial Intelligence and Machine Learning: [Freecell](https://github.com/terezaburianova/VUT-SUI-freecell) | [Neural Networks](https://github.com/terezaburianova/VUT-SUI-neural)
- Parallel and Distributed Algorithms: [Parallel Splitting Algorithm](https://github.com/terezaburianova/VUT-PRL-splitting/) | [K-Means algorithm](https://github.com/terezaburianova/VUT-PRL-Kmeans)
- Functional and Logic Programming: [Decision Trees Classification and Training](https://github.com/terezaburianova/VUT-FLP-FP/) | [Hamiltonian Cycles](https://github.com/terezaburianova/VUT-FLP-LP/)
- Computation Systems Architectures: [Parallelization](https://github.com/terezaburianova/VUT-AVS-paralelizace/) | [Vectorization](https://github.com/terezaburianova/VUT-AVS-vektorizace/)
- Data Storage and Preparation: [Big Data in NoSQL](https://github.com/terezaburianova/VUT-UPA/blob/main/project1/doc.pdf) | [Data preparation and their descriptive characteristics](https://github.com/terezaburianova/VUT-UPA/tree/main/project2) | [Data extraction from the web](https://github.com/terezaburianova/VUT-UPA/tree/main/project3)
</details>

<details>
<summary>
<b>Selected Bachelor's Projects</b>
</summary>
  
- [Network Applications and Network Administration](https://github.com/terezaburianova/VUT-ISA)
- [Operating Systems](https://github.com/terezaburianova/VUT-IOS/tree/master/proj2)
- [Computer Communications and Networks](https://github.com/terezaburianova/VUT-IPK/tree/main/proj1)
- [Signals and Systems](https://github.com/terezaburianova/VUT-ISS/)
- [Principles of Programming Languages](https://github.com/terezaburianova/VUT-IPP/)
- [Introduction to Programming Systems](https://github.com/terezaburianova/VUT-IZP)
- [Database Systems](https://github.com/terezaburianova/VUT-IDS)
</details>
