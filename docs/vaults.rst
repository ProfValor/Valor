************************
Vaults
************************

VALOR Staking Farm
================================================

In this farm, users can stake using their VALOR tokens, while getting back WBNB. The APR for this farm is dependent on the performance of all the other farms, since the 30% performance fee on other farms are what is collected and given out as the reward/roi for the VALOR staking pool. VALOR Pool has no withdrawal fee and no performance fee.

VALOR/BNB Farm
================================================

In this farm, users can deposit VALOR/BNB and earn even more VALOR tokens. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours, but there will be no fee during the migration to v2.

CAKE Auto Compounding Farm
================================================

The CAKE farm is where you can reap the benefits of automating compounding and the high APY. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours, but there will be no fee during the migration to v2. The 30% performance fee is collected but for every 1BNB in fees collected, we give 25 VALOR, so you’re getting free money.

Rest of PancakeSwap Farms
================================================

Currently we have CAKE-BNB, BUSD-BNB, USDT-BNB, DAI-BNB, USDC-BNB, VAI-BUSD, USDT-BUSD pools, which exist on Pancakeswap. Our smart contracts automatically compound your investments, giving you a higher APY. For these pools, as profit you will be getting the respective LP Token of the pool, as well as VALOR tokens. 40% of profits will be collected and given as VALOR tokens. For every 1BNB collected, we give 25 VALOR. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours, but there will be no fee during the migration to v2. Currently you can only claim your profits, if you claim & exit the pool. We may change this in the future.

Maximizer PancakeSwap Farms
================================================

The Maximizer farms takes the profits that come out of the original compounded Pancakeswap farm, and puts it into the CAKE auto-compounding farm, in order to give you a higher apy, while protecting your principal. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours, but there will be no fee during the migration to v2. With the Maximizer Farms, users can claim their profits, without exiting the farm.

According to our test calculations, assuming that CAKE price stays constant, USDT-BNB Farm APY is 30%, and CAKE APR is 300%, then the APY of someone who deposits into the “Yield Maximizing USDT-BNB Farm” would be 189.9%. This is much higher than the 30% achieved by simply compounding USDT-BNB, yet the risk is very minimal. The only risks would be if CAKE price drops significantly, or if the CAKE APR drops as well. That being said even if the CAKE price drops significantly the principal amount invested in USDT and BNB would still be the same. Similar to our regular farms, in order to fully benefit from the compounding effect, a user must have the patience to sit back and watch their money grow exponentially over time. One small complication is that because of the way the new yield maximized farms are coded through back end development, the yields earned daily (24 hour period) get distributed the next day on a rolling cycle. This means that users who deposit from day 0 to day 1 would be at a slight disadvantage as they would not be able to receive their fair share of yields for the first 24 hours. To mitigate this effect we plan on giving these early users some VALOR to compensate for the lost yields.
