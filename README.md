# awesome-sse [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated list of resources about **Searchable Symmetric Enryption (SSE)**. It is designed to have a central place where everyone can find open-source implementation of SSE schemes as well as introductory material to this topic.

## Contents

- [Theory](#theory)
	- [Introductory Papers](#introductory-papers)
	- [Surveys](#surveys)
	- [Different Aspects](#different-aspects)
	- [Blogs](#blogs)
	- [Videos](#videos)
	- [Attacks](#attacks)
- [Implementations](#implementations)  
  	- [Constructions](#constructions)
	- [Systems](#systems)


## Theory

### Introductory Papers

- [Curtmola et al. 2006], [Searchable symmetric encryption: improved definitions and efficient constructions](https://eprint.iacr.org/2006/210.pdf)
- [Chase et al. 2010], [Structured Encryption and Controlled Disclosure](https://www.iacr.org/archive/asiacrypt2010/6477581/6477581.pdf)
- [Cash et al. 2013], [Highly-Scalable Searchable Symmetric Encryption with Support for Boolean Queries](https://eprint.iacr.org/2013/169.pdf)
- [Cash et al. 2014], [Dynamic Searchable Encryption in Very-Large Databases: Data Structures and Implementation](https://eprint.iacr.org/2014/853.pdf)

### Surveys

- [Bösch et al. 2015], [A Survey of Provably Secure Searchable Encryption](https://dl.acm.org/citation.cfm?id=2636328)
- [Poh et al. 2017], [Searchable Symmetric Encryption: Designs and Challenges](https://dl.acm.org/citation.cfm?id=3064005)
- [Fuller et al. 2017], [SoK: Cryptographically Protected Database Search](https://arxiv.org/abs/1703.02014)

### Different Aspects
#### Forward & Backward Privacy
- [Chang et al. 2005], [Privacy Preserving Keyword Searches on Remote Encrypted Data.](https://pdfs.semanticscholar.org/62b0/603324e12755abeba2602ffdecb23937e7e0.pdf)
- [Stefanov et al. 2014], [Practical Dynamic Searchable Encryption with Small Leakage](https://eprint.iacr.org/2013/832.pdf)
- [Rafaël Bost. 2016], [Σoφoς – Forward Secure Searchable Encryption](https://eprint.iacr.org/2016/728.pdf)
- [Bost et al. 2017], [Forward and Backward Private Searchable Encryption from Constrained Cryptographic Primitives](https://eprint.iacr.org/2017/805.pdf)
- [Chamani et al. 2018], [New Constructions for Forward and Backward Private
Symmetric Searchable Encryption](http://home.cse.ust.hk/~jgc/Index_files/New-Constructions-for-Forward-and-Backward-Private-Symmetric-Searchable-Encryption.pdf)
- [Sun et al 2018], [Practical Backward-Secure Searchable Encryption from Symmetric Puncturable Encryption](https://dl.acm.org/citation.cfm?id=3243782)


#### Multiple Keywords Search
- [Cashe et al. 2013], [Highly-Scalable Searchable Symmetric Encryption with Support for Boolean Queries](https://eprint.iacr.org/2013/169.pdf)
- [Kamara et al. 2017], [Boolean Searchable Symmetric Encryption with Worst-Case Sub-Linear](https://eprint.iacr.org/2017/126.pdf)

#### Data Locality
- [Cash et al. 2014], [The Locality of Searchable Symmetric Encryption](https://www.iacr.org/archive/eurocrypt2014/84410155/84410155.pdf)
- [Asharov et al. 2016], [Searchable symmetric encryption: optimal locality in linear space via two-dimensional balanced allocations](https://eprint.iacr.org/2016/251)
- [Demertzis et al. 2017], [Fast Searchable Encryption With Tunable Locality](https://dl.acm.org/doi/10.1145/3035918.3064057)

#### Verfiability
- [Kurosowa et al. 2012], [UC-Secure Searchable Symmetric Encryption](https://ifca.ai/pub/fc12/73970279.pdf)
- [Bost et al. 2016], [Verifiable Dynamic Symmetric Searchable Encryption: Optimality and Forward Security](https://eprint.iacr.org/2016/062)

### Blogs
- [Mattew Green, 2019],  [Attack of the week: searchable encryption and the ever-expanding leakage function](https://blog.cryptographyengineering.com/2019/02/11/attack-of-the-week-searchable-encryption-and-the-ever-expanding-leakage-function/)


### Videos


### Attacks

- [Islam et al. 2012], [Access Pattern disclosure on Searchable Encryption: Ramification, Attack and Mitigation](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2017/09/06_1.pdf)
- [Liu et al. 2013], [Search Pattern Leakage in Searchable Encryption: Attacks and New Construction](https://eprint.iacr.org/2013/163.pdf)
- [Naveed et al. 2015], [Inference Attacks on Property-Preserving Encrypted Databases](https://cs.brown.edu/~seny/pubs/edb.pdf), ([slides](https://rwc.iacr.org/2016/Slides/rwc16-wright.pdf))
- [Cash et al. 2015], [Leakage-Abuse Attacks Against Searchable Encryption](https://eprint.iacr.org/2016/718)
- [Grubbs et al. 2016], [Breaking Web Applications Built On Top of Encrypted Data](https://eprint.iacr.org/2016/920)
- [Zhang et al. 2016], [All Your Queries Are Belong to Us: The Power of File-Injection Attacks on Searchable Encryption](https://eprint.iacr.org/2016/172)
- [Kellaris et al. 2016], [Generic Attacks on Secure Outsourced Databases](https://scholar.harvard.edu/files/gkellaris/files/genericattacks.pdf)
- [Grubbs et al. 2017], [Why Your Encrypted Database Is Not Secure](https://eprint.iacr.org/2017/468.pdf)
- [Giraud et al. 2017], [Practical Passive Leakage-Abuse Attacks Against Symmetric Searchable Encryption](https://eprint.iacr.org/2017/046.pdf)
- [Bost et al. 2017], [Thwarting Leakage Abuse Attacks against Searchable Encryption -- A Formal Approach and Applications to Database Padding](https://eprint.iacr.org/2017/1060)
- [Lacharité et al. 2017], [Improved Reconstruction Attacks on Encrypted Data Using Range Query Leakage](https://eprint.iacr.org/2017/701)
- [Ning et al. 2018], [Passive Attacks Against Searchable Encryption](https://ieeexplore.ieee.org/abstract/document/8443434/)
- [Grubbs et al. 2019], [Learning to Reconstruct: Statistical Learning Theory and Encrypted Database Attacks](https://eprint.iacr.org/2019/011.pdf)



## Implementations

### Constructions
- [Clusion](https://github.com/encryptedsystems/Clusion)
- [OpenSSE](https://opensse.github.io/)

### Systems

- [CryptDB](https://css.csail.mit.edu/cryptdb/)
- [StealthDB](https://github.com/cryptograph/stealthdb)
- [Arx](https://eprint.iacr.org/2016/591.pdf)
- [Monomi](https://dspace.mit.edu/bitstream/handle/1721.1/87023/tu-monomi-cr-vldb13.pdf?sequence=1&isAllowed=y)
- [Opaque](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/zheng)
- [ZeroDB](https://github.com/zerodb/zerodb)
- [HardINDX](https://link.springer.com/chapter/10.1007/978-3-319-61176-1_22)
- [DataBlinder](https://dl.acm.org/doi/10.1145/3366626.3368132)
- [CryptDICE](https://www.sciencedirect.com/science/article/abs/pii/S0306437920301289)

## Acknowledgements
I would like to thank all the smart people who have started this exciting field of security and cryptography, and those who have contributed to this relatively young research area. We thank [Fuller et al. 2017](https://arxiv.org/abs/1703.02014) and Raphael Bost ([his website](https://raphael.bost.fyi/se_references/)) whose work has motivated us to make this list.

