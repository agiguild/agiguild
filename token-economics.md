# $AGI token

Open Source AI Guild will steward the funding of research and rewarding of contributors with a cryptographic token, $AGI. 

There are two primary users/holders of $AGI: 
 - Open Source contributors are given $AGI for their work. Initial distribution will be based on past contributions to Open Source AI, using a transparent programmatic
formula taking into account github contributions and relevant publications. On-going distribution will be based on contribution submission and a review by the community of $AGI holders. 

 - Companies with over $1m in revenue who are using software under the COL license must acquire and stake $AGI to use the software. Through staking $AGI, value will accrue to all $AGI holders.

## Token distribution

Total supply: 10B

| Role | Percentage | Vesting |
| - | - | - |
| Initial distribution | 20% | 6 months |
| DAO | 80% | 4 years |

## Initial distribution

Initial distribution of $AGI is proposed to retroactively reward open source contributors weighted by github metrics and authors of papers weighted by citations. The contributions will have to be made before the initial distribution deadline to avoid gaming. For example, the cutoff could be Feb 01 2024. 

Even if prepared with careful calibration, the automated process will inevitably lead to mistakes and omissions, so we encourage people who think they were omitted to apply for retroactive funding via the DAO software (see "On-going" distribution section). 

The exact calculations are specified in (technical specification document)[./tech-spec.md].

## Staking & voting escrow

To become a member of Guild and have voting power, holders of $AGI must stake their token with selected duration. The goal is to have long-term aligned members who are in turn rewarded both by governance power and additional token rewards.

## On-going distribution
i. To open source contributors
The objective is to incentivize on-going open source contribution. Contributors are encouraged to appeal if their contributions before the deadline were not included in the initial $AGI distribution. Past the initial distribution, the review process will be manually done by reviewers yet assisted by github/citation metrics.

Before being reviewed, contribution proposals will need to pass a set of criteria. e.g., 
- be posterior to a certain date (otherwise assessing the impact of the work might be challenging)
- be under the OSAI license
- be categorized under a pre-defined category (e.g., model, dataset, tooling etc ...)
- propose an optional allocation split between contributors if it's a multi-contributor proposal

The manual review process will be improved and approved by governance vote. For example it could be such that: 
- K reviewers are assigned to each proposal based on their expertise (and their lack of conflict)
- reviewers assess the proposal according to a publicly shared and governance-voted template designed to neutrally assess the importance of the contribution 
- a formula assigns a contribution score to the proposal based on the templates filled in by the K reviewers

ii. To reviewers
$AGI holders will be volunteering to be reviewers, and will earn rewards for participating in the review process. The allocation process of proposals to reviewers will be improved over time and based on feedback from reviewers and applicants. The process will be designed to avoid bias, conflicts, and assure that the reviewers have adequate expertise.

iii. To DAO operators
DAO operators are ensuring that the DAO runs properly (e.g., governance operations, commercial use enforcement). AI agents will be experimented to reduce overhead. 


## Commercial use members

For commercial use of the Work associated to Guild, the organization must become a member of the Guild.

This does not apply to companies that have less than $1M in annual revenue. Guild believes in enabling startups to use all of their resources to build a successful business.

Past $1M in annual revenue, organizations must acquire and stake $AGI for at least 1 year proportionally to the annual revenue. 

The exact formula is `X * min(0, AnnualRevenue - 1,000,000)`, where `X` is specified by the Guild, but suggesting to start at `0.001`. 

For example, a company that makes $2m in ARR must stake $2k of $AGI that year in order to use all of IP licensed by Open Source AI Guild. 

The flip side, is that these commercial organizations become voting members of the Guild and are able to influence funding decisions to develop software, dataset or other work that will be in their interest.

$AGI investment is not an expense, as it is booked on the balance sheet of the organization (albeit with some illiquidity discount due to staking).
