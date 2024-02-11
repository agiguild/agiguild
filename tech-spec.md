# Technical specification

## Smart contracts



### Token smart contract
The token $AGI will be deployed on Ethereum, and comply with the ERC-20 standard. 

### Voting escrow



### DAO

DAO is the smart contract is coordinating distribution of assets to the.


## Initial distribution snapshot
The initial snapshot distribution technique relies on a mechanism to accurately attribute a user's impact on open-source AGI. 
It is important that the snapshot distribution can't be gamed. A couple metrics by which the snapshot can be calculated are outlined below:

### Open-source metrics 
The primary two metrics available include:
- h-index measures the total sum of contribution of an author.
- github metrics: forks/stars on open-source model repositories

The h-index does not account for time-frame or research field, and over-correlates with number of papers published as opposed to quality.
Github metrics are harder to source.

### Confererence-based weights

The top ML conferences engage in an intense peer-review mechanism to determine paper quality and acceptance.
The initial snapshot relies on this vetting mechanism to judge research quality and contribution to AGI. 
Conferences infclude ICML, NeurIPS, and CVPR.

The snapshot process looks like this:
- $C$ = weight of ML conference, based on reputation and quality, where  $\sum C = 1$ 
- $P$ = Assign a weight to each paper type 
    - Example for NeurIPS
        - Outstanding: $P = 10$
        - Runner-up: $P = 5$
        - Accepted: $P = 1$
- $A$ = Assign a weight to each author. use geometric reducing formula so first-author doesn't get diluted
    - first author: $A_1 = 10$
    - second author: $A_2 = 5$
    - third-author: $A_3 = 2.5$

To calculate the weight attributed to a single author for a single paper, the following formula can be used.
$W = C * P * A$

Note that weights must first be normalized across papers, and across conferences.