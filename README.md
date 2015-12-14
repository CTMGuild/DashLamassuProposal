# Dash Lamassu Integration

Dash desires to exchange local cash with Dash tokens using the Lamassu BTM.

##### Requirements

 * Enable a Lamassu BTM to be software-upgraded to buy and sell Dash side-by-side with Bitcoin.
 * Lamassu operators can enable/disable Dash from the admin site.
   * If enabled, a new screen to choose currency will appear before the buy/sell lander, and other 'BTC' reference in the UI will be changed.
   * If disabled, the default Lamassu UI has to be exactly as before.
 * A complete plugin set (ticker, trade, and wallet) will be created for Dash
   * Ticker will stream the Dash price from the exchange of choice.
   * Trade will convert to Dash as the user buys, using the exchange of choice. (Chain fiat->BTC->Dash if necessary)
   * Wallet will plug in to Dashd via RPC for use as a hot wallet. (or wallet API if preferred)
 * Easy to use installation and deployment instructions will be provided.
 * The code has to be maintained, with a 2 year guarantee of functionality.

## About Deginner

[Deginner](http://deginner.com) was founded in early 2015 by former Coinapult CEO and CTO, [isysd](https://github.com/isysd) and [g-p-g](https://github.com/g-p-g). The Deginner team has built many cryptocurrency services and apps in the past, and now focuses entirely on open source tools. They developed the [lamassu-coinapult](https://github.com/coinapult/lamassu-coinapult) trade, wallet, and ticker plugins, and have good relationships with the Lamassu team, as well as many of their operators. If this project is approved, Deginner will ensure it is deployed on at least one network of BTMs, starting with the one in [Panama City, Panama](http://coinatmradar.com/bitcoin_atm/509/bitcoin-atm-lamassu-panama-virtual-mallbox/).

In line with the open source, collaborative spirit, Deginner usually offers startups a deep discount in return for revenue sharing or similar. This ensures clients properly incentivized support for years to come. To read more about Deginner's philosophy, please visit [rdov.co](http://rdov.co).

By spreading the majority (80%) of the development cost out across 2 years, and accepting Dash at the price at time of signing, the payment value will fluctuate with the long term success or failure of Dash. In this way, the network gets new, valuable, infrastructure at low up front cost, and the long-term support from of a team of open source developers.

