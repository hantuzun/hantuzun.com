+++
title = "The Science of Blockchains"
series = "🔭 The Science of Blockchains"
date = 2020-10-31T23:26:59+03:00
draft = false
og_title = "🔭 The Science of Blockchains"
og_description = "A blog series based around fundamental papers."
og_image = "https://hantuzun.com/images/posts/the-science-of-blockchains/cover.jpg"
og_image_type = "image/jpg"
og_image_width = 1400
og_image_height = 600
[twitter]
  card = "summary_large_image"
  creator = "@hantuzn"
  title = "🔭 The Science of Blockchains"
  description = "A blog series based around fundamental papers."
  image = "https://hantuzun.com/images/posts/the-science-of-blockchains/cover.jpg"
+++

![Cover](/images/posts/the-science-of-blockchains/cover.jpg)

I'm starting my blog with a blog series to celebrate the 12th anniversary of the Bitcoin white paper. 🎂

I'll introduce an extensive technical foundation to comprehend Bitcoin, Ethereum, and the future of blockchains.

The series is based on selected fundamental papers.

 <!--more--> 
 -----------

## Why I Start This Series?

I like to have a comprehension of the primary sources when learning about a subject.

When I've been teaching at [@BlockchainOkulu](https://twitter.com/blockchainokulu), I structured my lessons around primary sources such as the Bitcoin white paper and the Ethereum yellow paper.

This way, my students learned not only what I know, but also what's the source of the knowledge. Now that they're graduated, they know where to look for when they have questions.

Even though the course was four weeks long for each batch I could not answer some excellent questions in detail. Instead, I had to resort to black boxes many times.

How do digital signatures work? A black box. 

What about ZK-STARKs? Another black box.

Black boxes help to teach a subject. Not so much for understanding in detail.

To understand Bitcoin, Ethereum, and more on a deeper level, one should know the pillars they are built on.

You understand the strength of the Bitcoin network when you know how does SHA-256 work.

You understand how your contracts run once you know the inner-working of the EVM.

You understand the security of the protocols you invest in when you, well, know a lot.

One must have a comprehensive understanding of these technologies to take part in the conversations on their governance.

We have *some* highly meritocratic communities in the blockchain space.

What should be the block size?

What're your opinions on various layer 2 protocols?

How can you help us approaching the open questions on scalability?

All you need to do is to join the conversations, as long as you know about the subject in depth.

Here comes a problem: I realized the most technical questions are getting little to no attention.

My ultimate goal is to have new voices on the future of blockchain governances. New voices that understand the contemporary subjects about blockchains inside and out.

This is one of the best things I can do for crypto.

{{< tweet 1299500501604667396 >}}

## Intended Audience

The series will require the reader to be comfortable with computer science papers. In fact, the content will be the papers.

My job is to curate the papers, explain their contexts in the blockchain space, and clarify them with my reading notes.

Ultimately, the series will offer a fundamental understanding of blockchain technologies to eager readers, be it economics students or CS professors.

## The Papers

I'm proud to present you 67 primary sources on the science of blockchains. Wish me plenty of free time for covering some of them in this blog series!

### Cryptography

**Fundementals**
- Bloom, B. 1970. Space/Time Trade-offs in Hash Coding with Allowable Errors. [📃](http://crystal.uta.edu/~mcguigan/cse6350/papers/Bloom.pdf)

- Rivest R. L., Shamir A., Adleman L. 1978. A Method for Obtaining Digital Signatures and Public-Key Cryptosystems. [📃](https://people.csail.mit.edu/rivest/Rsapaper.pdf)

- Merkle, R. C. 1980. Protocols for public key cryptosystems. IEEE Symposium on Security and Privacy. [📃](http://www.merkle.com/papers/Protocols.pdf)

- Penard W., van Werkhoven, T. 2001. On the Secure Hash Algorithm family. [📃](https://web.archive.org/web/20160330153520/http://www.staff.science.uu.nl/~werkh108/docs/study/Y5_07_08/infocry/project/Cryp08.pdf)


**Elliptic-curve Cryptography**
- Koblitz, N. 1987. Elliptic curve cryptosystems. [📃](https://www.ams.org/journals/mcom/1987-48-177/S0025-5718-1987-0866109-5/S0025-5718-1987-0866109-5.pdf)

- Miller, V. 1985. Use of elliptic curves in cryptography. [📃](https://link.springer.com/content/pdf/10.1007%2F3-540-39799-X_31.pdf)

- Boneh, D., Lynn, B., Shacham, H. 2004. Short signatures from the Weil pairing. [📃](https://www.iacr.org/archive/asiacrypt2001/22480516.pdf)

- ANSI. 2005. Public Key Cryptography for the Financial Services Industry: The Elliptic Curve Digital Signature Algorithm (ECDSA). [📃](https://webstore.ansi.org/Standards/ASCX9/ANSIX91422020)

- Bernstein D. J. 2006. Curve25519: new Diffie-Hellman speed records. [📃](https://cr.yp.to/ecdh/curve25519-20060209.pdf)

- Brown D. R. L. 2010. SEC 2: Recommended Elliptic Curve Domain Parameters. [📃](https://www.secg.org/sec2-v2.pdf)

- Kate, A. et al. 2010. Constant-Size Commitments to Polynomials and Their Applications. [📃](https://www.iacr.org/archive/asiacrypt2010/6477178/6477178.pdf)

- Wang D. 2014. Secure Implementation of ECDSA Signatures in Bitcoin. [📃](http://www.nicolascourtois.com/bitcoin/thesis_Di_Wang.pdf)

- Schnorr, C. 1990. Efficient identification and signatures for smart cards. [📃](https://link.springer.com/chapter/10.1007/0-387-34805-0_22)

**Quantum Cryptography**
- Shor, P. W. 1996. Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer. [📃](https://arxiv.org/pdf/quant-ph/9508027.pdf)

- Aggarwal, D. et al. 2017. Quantum attacks on Bitcoin, and how to protect against them. [📃](https://arxiv.org/pdf/1710.10377.pdf)

**Zero Knowledge**
- Goldreich O. 1991. Proofs that Yield Nothing But Their Validity All Languages in NP Have Zero-Knowledge Proof Systems. [📃](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Zero%20Knowledge/Proofs_That_Yield_Nothing_But_Their_Validity_or_All_Languages_in_NP_Have_Zero-Knowledge_Proof_Systems.pdf)

- Reitwiessner, C. 2016. zkSNARKs in a Nutshell. [📃](https://chriseth.github.io/notes/articles/zksnarks/zksnarks.pdf)

- Bunz, B. et al. 2017. Bulletproofs: Short Proofs for Confidential Transactions and More. [📃](https://eprint.iacr.org/2017/1066.pdf)

- Ben-Sasson, E. et al. 2018. Scalable, transparent, and post-quantum secure computational integrity. [📃](https://eprint.iacr.org/2018/046.pdf)

- Gabizon, A. et al. 2020. PLONK: Permutations over Lagrange-bases for Oecumenical Noninteractive arguments of Knowledge. [📃](https://eprint.iacr.org/2019/953.pdf)


### Distributed Computing and Consensus
- Schneider F. B. 1990. Implementing Fault-Tolerant Services Using the State Machine Approach: A Tutorial. [📃](https://nakamotoinstitute.org/static/docs/implementing-fault-tolerant-services.pdf)

- Lamport, L., et al. 1982. The Byzantine Generals Problem. ACM Transactions on Programming Languages and Systems 4(3): 382-401. [📃](https://dl.acm.org/citation.cfm?id=357176)

- Castro, M., Liskov, B. 1999. Practical Byzantine fault tolerance. Proceedings of the Third Symposium on Operating Systems Design and Implementation. [📃](http://pmg.csail.mit.edu/papers/osdi99.pdf)

- Lamport, L. 2001. Paxos made simple. [📃](http://lamport.azurewebsites.net/pubs/paxos-simple.pdf)

- Szabo, N. 2003. Advances in Distributed Security. [📃](https://nakamotoinstitute.org/advances-in-distributed-security/)

- Aspnes, J., et al. 2005. Exposing computationally challenged Byzantine imposters. Yale University Department of Computer Science. [📃](http://cs.yale.edu/publications/techreports/tr1332.pdf)
 
- Stutzbach, D., Rejaie, R. 2006. Understanding Churn in Peer-to-Peer Networks; [📃](http://www.barsoom.org/papers/imc-2006-churn.pdf)

- Berman, P., Juan A. 1993. Cloture Votes: n/4-resilient Distributed Consensus in t + 1 rounds. [📃](https://link.springer.com/article/10.1007%2FBF01187072)


### Timestamping
- Haber, S., Stornetta, W. S. 1997. Secure names for bit-strings. [📃](http://dl.acm.org/citation.cfm?id=266430)

- Massias, H., Avila X. S.,  Quisquater, J.-J. 1999. Design of a secure timestamping service with minimal trust requirements. [📃](https://nakamotoinstitute.org/static/docs/secure-timestamping-service.pdf)

- Just, M. 1998. Some timestamping protocol failures. [📃](https://www.ndss-symposium.org/wp-content/uploads/2017/09/Some-Timestamping-Protocol-Failures_0.pdf)

- Bonnecaze, A. et al. 2002. Improving Time Stamping Schemes: A Distributed Point of View. [📃](http://pages.upf.pf/Alban.Gabillon/articles/AnnalTelecom.pdf)


### Digital Money
- Chaum, D., et al. 1988. Untraceable electronic cash. Advances in Cryptology: 319-327. [📃](https://dl.acm.org/citation.cfm?id=88969)

- Dai, W. 1998. [📃](http://www.weidai.com/bmoney.txt)

- Szabo, N. 2008. Bit gold. [📃](https://unenumerated.blogspot.com/2005/12/bit-gold.html)


### Proof of Work
- Back, A. 2002. Hashcash—a denial of service counter measure. [📃](http://www.hashcash.org/papers/hashcash.pdf)

-  Douceur, J. R. 2002. The Sybil attack. [📃](https://dl.acm.org/citation.cfm?id=687813)

- Szabo, N. 1999. Intrapolynomial Cryptography. [📃](https://nakamotoinstitute.org/intrapolynomial-cryptography/)


### Bitcoin
- Nakamoto, S. 2008. Bitcoin: a peer-to-peer electronic cash system. [📃](https://bitcoin.org/bitcoin.pdf)
 
- Wuille, P. 2012. BIP 32: Hierarchical Deterministic Wallets. [📃](https://en.bitcoin.it/wiki/BIP_0032)

- Rosenfeld M. 2012. Overview of Colored Coins. [📃](https://bitcoil.co.il/BitcoinX.pdf)

- Biryukov, A. et al. 2014 Deanonymisation of clients in Bitcoin P2P network. [📃](https://arxiv.org/pdf/1405.7418.pdf)

- Poon, J., Dryja, T. 2016. The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments. [📃](https://lightning.network/lightning-network-paper.pdf)

- Pass, R., et al. 2017. Analysis of the blockchain protocol in asynchronous networks. [📃](https://link.springer.com/chapter/10.1007/978-3-319-56614-6_22)


### Smart Contracts
- Turing, A. M. 1937. On Computable Numbers, with an Application to the Entscheidungsproblem. [📃](https://londmathsoc.onlinelibrary.wiley.com/doi/abs/10.1112/plms/s2-42.1.230)

- Szabo, N. 1994. Smart contracts. [📃](http://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart.contracts.html)

- Bhargavan, K. et al. 2016. Short Paper: Formal Verification of Smart Contracts. [📃](https://www.cs.umd.edu/~aseem/solidetherplas.pdf)


### Proof of Stake
- Poelstra, A. 2015. On Stake and Consensus. [📃](https://download.wpsoftware.net/bitcoin/pos.pdf)

- Bentov, I. 2017. Cryptocurrencies without Proof of Work. [📃](https://arxiv.org/pdf/1406.5694.pdf)


### Ethereum
- Sompolinsky, Y.,  Zohar, A. 2013. Secure High-Rate Transaction Processing in Bitcoin. [📃](https://web.archive.org/web/20150402122229/https://eprint.iacr.org/2013/881.pdf)

- Eth Wiki. Modified Merkle Patricia Trie Specification. [📃](https://eth.wiki/fundamentals/patricia-tree)

- Buterin, V. 2013. Ethereum White Paper: A Next Generation Smart Contract & Decentralized Application Platform. [📃](https://ethereum.org/en/whitepaper/)

- Dameron, M. 2019. Beigepaper: An Ethereum Technical Specification. [📃](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf)

- Wood, G. 2020. Ethereum: A Secure Decentralised Generalised Transaction Ledger. [📃](https://ethereum.github.io/yellowpaper/paper.pdf)

- Solidity Documentation. [📃](https://buildmedia.readthedocs.org/media/pdf/solidity/develop/solidity.pdf)

### Scaling

- Croman, K. et al. 2016. On Scaling Decentralized Blockchains. [📃](https://www.comp.nus.edu.sg/~prateeks/papers/Bitcoin-scaling.pdf)

- Kalonde, H. et al. 2018. Arbitrum: Scalable, private smart contracts. [📃](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf)

- Dang H. et al. 2019. Towards Scaling Blockchain Systems via Sharding. [📃](https://arxiv.org/pdf/1804.00399.pdf)

- Buterin, V. Serenity Design Rationale. [📃](https://notes.ethereum.org/s/rkhCgQteN)

- Buterin, V. et al. 2020. Combining GHOST and Casper. [📃](https://arxiv.org/pdf/2003.03052.pdf)

- Adler, J., Quintyne-Collins, M. 2020. Building Scalable Decentralized Payment Systems. [📃](https://arxiv.org/pdf/1904.06441.pdf)

### Other Blockchains

- Namecoin. 2011. Merged mining. [📃](https://en.bitcoin.it/wiki/Merged_mining_specification)

- Van Saberhagen, N. 2013. CryptoNote v 2.0 (Annotated by the Monero Team). [📃](https://web.getmonero.org/resources/research-lab/pubs/whitepaper_annotated.pdf)

- Ben-Sasson, E. et al. 2014. Zerocash: Decentralized Anonymous Payments from Bitcoin. [📃](http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf)

- Poelstra, A. 2016. Mimblewimble. [📃](https://download.wpsoftware.net/bitcoin/wizardry/mimblewimble.pdf)

- Team Rocket et al. 2019. Scalable and Probabilistic Leaderless BFT Consensus through Metastability. [📃](https://arxiv.org/pdf/1906.08936v1.pdf)

- Bonneau, J. et al. 2020. Mina: Decentralized Cryptocurrency at Scale. [📃](https://minaprotocol.com/static/pdf/technicalWhitepaper.pdf)


## Help Me Prioritize

Let me know which papers do you want to read first in Twitter! I may built some kind of voting for this later on.

Reply to this thread: 