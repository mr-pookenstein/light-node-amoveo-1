Amoveo light node vStablecoin
========

This is a light node for the Amoveo cryptocurrency and is meant to be used to try out testnet BTC stablecoins. The idea is that you can effectively convert VEO into BTC using this market. This is meant to test out functionality and there may be significant bugs. In fact there is a high chance of something going wrong, so lower your expectations.

You can either download the light node from this repository, or you can just access it from here: http://18.222.121.248:8070/stablecoin.html

INSTRUCTIONS:

First time users:
1. open link http://18.222.121.248:8070/stablecoin.html
2. click the "account settings" button at the top and either load your private key or create a new one.
3. click the "stablecoin market" button at the top. enter how much veo you want to lock into a channel, then hit "open channel" and wait for a block to be mined.
4. in the stablecoin market, fill out the fields with a veo/btc price, an amount of veo, and click long or short. short means you want a stablecoin, long means you want to go long veobtc. hit "Place order".
5. you can click "check positions" to see if your order has been filled yet. "check balance" checks your channel balance.
              
              An order to short 0.045 VEO at 0.025 veobtc that has been filled looks like this:
                    Value: -0.045 VEO, Entry Price: 0.025
              
              If this same order wasn't filled, it would look like this:
                    Value: -0.045 VEO, Order Price: 0.025

note: users should save their channel state before exiting the page by clicking "channel settings" at the top and downloading their channel state.

If you've already opened a channel but exited the webpage, only steps 1-3 are different:

1. open link http://18.222.121.248:8070/stablecoin.html
2. click the "account settings" button at the top and load your private key.
3. either click the "stablecoin market" button at the top and hit "trusted channel sync" (warning: this is trusted), or click "channel settings" and load your channel state that was saved previously.
