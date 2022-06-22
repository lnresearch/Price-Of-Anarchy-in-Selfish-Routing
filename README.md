This is a collection of notebooks and scripts that tries to understand the Price of Anarchy of selfish routing strategies on the Lightning Network.

This is related to the [Summer of Bitcoin Project](https://www.summerofbitcoin.org/project-ideas-details?recordId=recJchpFa9tqSZkQ4)

Read more about why this is important [on the mailinglist](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-May/003590.html) and in [this blog article](https://blog.bitmex.com/price-of-anarchy-from-selfish-routing-strategies/)

Currently it contains:
* one notebook that describes how selfish behavior produces drain which produces failure rate. This notebook also suggests measuring the price of anarachy can be modelled by looking at the distribution of drain
* another notebook showing, via simulation in the simplest case, how we expect the liquidity to be distributed in a channel after it has seen sufficiently many routing attempts.

## Acknowledgements 
This notebook was created by Rene Pickhardt and is a result of very helpful discussions with Krystal Maughan and Sebastian Alscher who are Rene's mentees during the 2022 Summer of Bitcoin. We expect this to be extended to a mathematically more sound theoretical and empirical work during the Summer of Bitcoin 2022.

Rene Pickhardt's research is funded through NTNU & BitMEX and various donors at https://donation.rene-pickhardt.de and https://www.patreon.com/renepickhardt While the mentees are sponsored by Summer of Bitcoin.