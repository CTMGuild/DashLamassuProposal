<img src="https://www.dash.org/wp-content/uploads/2015/03/dash_logo_s.png" height="25px" align="middle">
<img src="http://i.imgur.com/8FvXjib.png" height="42px" align="middle">

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

## BTM Overview

<p align="center"><img src="http://i.imgur.com/wF7HhaN.png" width="65%"></p>

## Deliverables

##### Plugins

The ticker, wallet, and trader plugins will be delivered as JavaScript
and will include tests for achieving 100% code coverage. The timely
delivery of these assume that a stable API for ticker usage exists, as
well a RPC or similar interface for wallet operations, and a stable Dash
exchange for testing the trader is present.

##### Lamassu admin

lamassu-admin will be delivered as a fork in order to list the new
plugins and also to add a new option for installing a different initial
screen. Initially, operators will need to install this version in place
of the official one if they desire to use this new functionally. We're
coordinating with Lamassu so the list of new plugins is included on
their own release, as well this new option. When such release happens,
then operators will no longer need to install this forked version.

##### Lamassu machine

lamassu-machine will be delivered as a fork under the conditions
mentioned for lamassu-admin. This repository needs to be updated in
order to 1) remove the interface restrictions that limit it to 'BTC' and
2) display a different initial optional screen that allows user to
select between BTC and Dash.

<p align="center"><img src="http://i.imgur.com/36RQvfj.png" width="65%"></p>

## Estimates

Item     | Days
-------- | ----------------------
Plugins  | 7.5 (2.5 for each one)
Admin    | 3
Machine  | 9
Installer  | 1

Total: 20.5 days

Work can begin immediately upon receiving the initial payment and a proof of concept transaction on a live machine could be as
soon as 4 weeks later. A more conservative estimate to allow for quality
assurance is 8 weeks.

## About Deginner

[Deginner](http://deginner.com) was founded in early 2015 by former Coinapult CEO and CTO, [isysd](https://github.com/isysd) and [g-p-g](https://github.com/g-p-g). The Deginner team has built many cryptocurrency services and apps in the past, and now focuses entirely on open source tools. They developed the [lamassu-coinapult](https://github.com/coinapult/lamassu-coinapult) trade, wallet, and ticker plugins, and have good relationships with the Lamassu team, as well as many of their operators. If this project is approved, Deginner will ensure it is deployed on at least one network of BTMs, starting with the one in [Panama City, Panama](http://coinatmradar.com/bitcoin_atm/509/bitcoin-atm-lamassu-panama-virtual-mallbox/).
