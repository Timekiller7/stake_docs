---
# Page settings
layout: default
keywords: staking, cardano
comments: false

# Micro navigation
micro_nav: true

---

A single window has the following stages
* Staking/Withdrawal Period
* Rewards distribution Period
  
As the staking pool starts, the staking/withdrawal period begins and users can send tokens to pool in order to stake them. Tokens aren’t locked in the on-chain script, users can withdraw their deposited amount plus earned rewards in any time during staking/withdrawal period.

Tokens must be deposited <b> before </b> the start of the staking/withdrawal period for which user want to receive a reward.

After the staking/withdrawal period is over, then comes rewards distribution period. For past staking/wintdrawal period in current window the staking rewards are accrued to users, proportionally to their share of the overall staked pool in that period.
  
  Example:
  * Window 1: User deposits 5 AGIX
    * New deposit = 5 AGIX
    * Rewards = 0 AGIX
  * Window 2: User deposits 10 AGIX
    * Confirmed stake  = 5 AGIX
    * New deposit = 10 AGIX
    * Rewards (1) are accrued to user for 5 AGIX stake
  * Window 3: User doesn’t deposit anything
    * Confirmed stake = 15 AGIX
    * Rewards (2) are accrued to user for 15 AGIX stake + rewards(1)
  * Window 4:
    * User’s final (confirmed) stake = 15 AGIX
    * Rewards are accrued to user for 15 AGIX stake + rewards(2)

The diagram below shows the timeline (with sample time periods) of the key events (staking/withdrawal, rewards distribution)