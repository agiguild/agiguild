# $AGI token

Open Source AI Guild will steward the funding of research and rewarding of contributors with a cryptographic token, $AGI. 

There are two primary users/holders of $AGI: 
 - Open Source contributors are given $AGI for their work. Initial distribution will be based on past contributions to Open Source AI.
 - Companies with over $1m in revenue who are using software under the COL license must acquire and stake $AGI to use the software. Through staking $AGI, value will accrue to all $AGI holders.

## Token distribution

Total supply: 10B

| Role | Percentage | Vesting |
| - | - | - |
| Initial distribution | 20% | 6 months |
| DAO | 80% | 4 years |

## Initial distribution

Initial distribution of $AGI is proposed to retroactively reward open source contributors and authors of papers weighted by citations.

There will be mistakes by automated process, so we encourage people who think they were omitted to apply for retroactive funding via DAO software.

The exact calculations are specified in (technical specification document)[./tech-spec.md].

## Staking & voting escrow

To become a member of Guild and have voting power, holder of $AGI must stake their token with selected duration. The goal is to have long term aligned members who are in turn rewarded both by governance power and additional token rewards.

## Commercial use members

For commercial use of the Work associated to Guild, the organization must become a member of the Guild.

This does not apply to companies that have less than $1M in annual revenue. Guild believes in enabling startups to use all of it's work to build a successful business.

Past $1M in annual revenue, organization must acquire and stake $AGI for at least 1 year proportionally to the annual revenue.

The exact formula is `X * min(0, AnnualRevenue - 1,000,000)`, where `X` is specified by the Guild, but suggesting to start at `0.001`. 

For example, a company that makes $2m in ARR must stake $2k of $AGI that year in order to use all of IP licensed by Open Source AI Guild.

The flip side, is that these commercial organizations become voting members of the Guild and are able to direct funding to develop more valuable software, dataset or other work.

It's also not an expense, as it goes to the balance sheet of the organization (albeit with some illiquidity discount due to staking).
