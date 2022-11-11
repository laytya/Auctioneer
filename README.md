### From Norganna's AddOns

Jump to: [navigation](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#column-one), [search](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#searchInput)

-   [What is auctioneer](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#what_is_auctioneer)

-   [An example tooltip](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#an_example_tooltip)

-   [So what does this tell th…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#so_what_does_this_tell_the_user_)

-   [What is this scanning abo…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#what_is_this_scanning_about_)
-   [What can Auctioneer do to…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#what_can_auctioneer_do_to_help_me_)

-   [Another example tooltip](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#another_example_tooltip)

-   [Ok, what is this new data…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#ok_what_is_this_new_data_telling_the_user_)
-   [Ok, but what do these num…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#ok_but_what_do_these_numbers_actually_mean)

-   [Selecting the prices to s…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#selecting_the_prices_to_sell_for)

-   [An example auction - 1](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#an_example_auction_1)
-   [An example auction - 2](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#an_example_auction_2)

-   [What's all this mean then?](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#what_s_all_this_mean_then_)

-   [What are the available pr…](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#what_are_the_available_pricing_models_)
-   [Conclusion](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/BasicAucUsage#conclusion)

For help on the Interface Usage look in [Interface Usage](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/Interface_Usage "Auctioneer/Interface Usage")

Updated to version: _3.6.0.0930_

_The following is an edited copy of a post to the forums + an update to mentioned version_

## What is auctioneer

Auctioneer is an addon that allows you to view information about an item that may be useful in helping you determine what it's worth.

Straight out of the box, Auctioneer knows much about many items in the game, and will tell you many things about the item when you move your mouse over the item in the game.

Right at the start, the information that is provided (via the [Informant](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Informant "Informant") addon) to the user is:

```
Linen Cloth
Buy 3 (0.55 each)                   1s65c
Sell 3 (0.13 each)                    39c
Stacks in lots of 20
Class: Trade Goods
Used for: Smithing, First Aid,
        Engineering
Quest items in 4 quests

```

### So what does this tell the user?

-   It tells the user that they are looking at the item "Linen Cloth".
-   The buy price (that you can buy this item from vendors for) for three of these items is 1 silver and 65 coppers. (which is 55 coppers each)
-   The sell price (that you can sell this item back to the vendors for) for three of these items is 39 coppers. (which is 13 coppers each)
-   This item can be stacked together up to a maximum stack size of 20 items
-   Blacksmithing , First aid and Engineering professions all use this item in their trades. (_Note editor: I'm very sure it is also used for tailoring, but the current Informant information does not say this_)
-   It is a quest-item in 4 quests.

_**Note'**: Items that you may not actually be able to buy from vendors still have a value in the game. This value determines things like deposit price and starting price at the auction house and repair costs for durability damage._

## What is this scanning about?

Once a user moves to the auction house and beyond just buying and selling from/to vendors, the whole game changes. No longer is the user dealing with the static prices of the vendor to support their character's income. We are now dealing with the fluid and hectic nature of a dog-eat-dog market economy.

In such an economy, which is in a constant state of flux, it can be difficult to select the correct pricing points for your item at the auction house. Sometimes the prices and value of your items can be wildly different to the vendor price due to many factors, the value of items that can be made from your item, the use of a particular item in a quest, the suitability of a particular weapon or armor to specific classes, and the disenchantability of an item to enchanters.

Primarily, the driving factor of the price fluctuations, as in the real world is supply versus demand. When supply is high, but demand is low, competition drives the prices down, and conversly then supply is low, but demand is high, the market is driven into a sellers market.

## What can Auctioneer do to help me?

Auctioneer can help you alleviate this lack of market knowledge over time by watching the market evolve. When you go to the auction house for the first time after installing auctioneer, you will see a new button marked "Scan" at the bottom of the Auction window's browse pane. Clicking on this button will put the Auction window into an automatic scanning process which will look at the current market **_snapshot_** and record statistical data about the prices and quantities of items at the auction house. (There are many reports that can be run from this snapshot, but they will be covered in a more advanced manual)

Once the market analysis has completed, you will notice additional information about the items in the tooltips when you mouse over them:

```
Linen Cloth
Seen 4062 times at auction total
Averages for 3 items:
Starting bid (1.63 ea)              4s89c
Bids (10% 0.52 ea)                  1s56c     
Buyout (92%, 3.40 ea)              10s20c
Buyout median                       7s35c
Last 35, median BO (ea)             2s50c
Scanned 20, median BO (ea)          2s45c
Suggested price for your 3 stack: 3.40 min / 4.26 BO
Undercutting by 5%
Buy 3 (0.55 each)                   1s65c
Sell 3 (0.13 each)                    39c
Stacks in lots of 20
Class: Trade Goods
Used for: Smithing, First Aid,
        Engineering
Quest items in 4 quests

```

### Ok, what is this new data telling the user?

The new data is displaying the market statistics from all auction scans (in this case there has only been one scan). It is telling the user that:

-   The item linen cloth has been seen 4062 times in total due to scans of the auction house.
-   The average values for the current stack of three items is:
-   An average starting bid for 3 items of 4 silver and 89 coppers (1 silver and 63 coppers for one item)
-   An average bid rate of 10% (that is 10% of the 4062 items had bids) and an average bid of 1 silver and 56 coppers (52 coppers for one item)
-   An average buyout value of 10 silver and 20 coppers (3 silver and 40 coppers for one) was set on 92% of the 4062 auctions (Not all auctions need to have a buyout set, that is why the percentage is only 92%)
-   The most accurate median buyout (for 3 items) is 7 silver and 35 coppers
-   For the last 35 of these items seen, the per item median buyout was 2 silver and 50 coppers
-   The most recent scan of the auction house saw 20 of these items, and the per item median buyout was 2 silver and 45 coppers
-   Auctioneer suggests that the minimum bid for the 3 stack is set to 3 silver and 40 coppers and that the buyout price is set to 4 silver and 26 coppers
-   Auctioneer has determined the previous values by undercutting the market with 5% (for explanation see below)

### Ok, but what do these numbers actually mean

Understanding of what the numbers are telling you can be the most difficult part of understanding this addon. Let me tell you what this data tells me.

-   The sample size is high. 4062 items, which means that we have a lot of information about the item.
-   The auction house has some nibblers who are taking bids on the lower priced items in the auction house. 10% of the items have bids, however they are not coming close to the average starting bid (even lower than halfway towards it). This indicates that there are people looking for bargains on this item (likely to try and buy and resell it at a better price)
-   The buyout rate being at 92% indicates that people are fairly confident that they know the value of this item.
-   The Average buyout being about 2 silver 85 copper higher than the average median (around 40% of the median) indicates a varying price for these item, but still fair. When the difference between the average and the median is high, this indicates a market that is unstable, unsure of it's pricing point.
-   The last median (historical median) shows the median value of up to the last 35 items, whereas the scanned median (snapshot median) shows the median buyout of only those items currently for sale on the auction house. The difference between these two values indicate a temporary market shift. The historical data being higher than the snapshot data means that the market is in a low for this item (buyers market) and conversely the snapshot being higher than the historical indicates the market booming for this item (sellers market)
-   The other points are explained already in the previous section.

## Selecting the prices to sell for

If auctioneer has enough data, when you try to put an auction up for sale, it will attempt to provide you with intelligent pricing points based upon the market data it has accumulated through scanning.

When you drag your item from your inventory window into the Create Auction item slot, Auctioneer will set a minimum price, a buyout price and display relevant data about it's decision making process underneath in the market analysis pane, as well as telling you how it arrived at it's prices.

## An example auction - 1

Based upon the Auction-tab description (for more information see [Interface Usage](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/Interface_Usage "Auctioneer/Interface Usage"))

```
[ 3 ] Linen Cloth

Starting price
3s 40c
Buyout price (optional)
4s 26c
Auction duration
[ ] 2 [ ] 8 [x] 24 hour
Deposit: 12c

-----------------------------
35 historical 7s 50c
20 last scan  7s 35c
Snapshot low  4s 50c
Market price  7s 35c
Original bid 1s
 
-----------------------------
Undercutting by 5%

```

## An example auction - 2

Based upon the Post Auction-tab description (for more information see [Interface Usage](http://web.archive.org/web/20070104093310/http://norganna.org/wiki/Auctioneer/Interface_Usage "Auctioneer/Interface Usage"))

```
[ 3 ] Linen Cloth

Undercutting by 5%

Starting price
3s 40c
Buyout price
4s 26c
Auction duration
[ ] 2 [ ] 8 [x] 24 hour
Deposit: 12c

```

### What's all this mean then?

Ok, well the starting and buyout prices, the duration and the deposit are all self explanitory. The rest of the data means this (Explanation based upon example 1):

-   This item has been seen 35 times historically (that is in the last 35 times) with a median of 7 silver and 50 coppers
-   This item has been seen 20 times the last scan (snapshot) with a median of 7 silver and 35 coppers
-   The lowest price for this item in the last scan was 4 silver and 50 coppers
-   The calculated market price for this item os 7 silver and 35 coppers
-   The original starting bid, suggested by blizzard for this item is 1 silver
-   The pricing algorithm decided that the current lowest bid (4s50c) could be undercut by 5% and still not deviate too far from the market price.

## What are the available pricing models?

The pricing algorithm may select one of:

-   **Marking up vendor by 300%**: This item has not been seen at auction. We are estimating that it will be worth 3 times more than what you could sell it to the vendor for.
-   **Undercutting by x%**: This item has competition on the market, but it's not so bad that we'd be cutting our throats by matching them.
-   **No competition**: This item is not on the market, you have a monopoly on this item at this point in time.
-   **Competiton above market**: The prices for this item are no threat to you as they are all over prices (you could afford to bump your prices up a little too, if you felt like it)
-   **Cannot match lowest price**: The lowest price is too far below the market value. Selling at this point in time is not recommended. Either bide your time until this item is gone, risk it and put your item up any way at a higher price, manually reduce your price to match it, or buy out the cheap items, and relist them and your items for proper market value.
-   **Using my current price**: You have the most competitive price on the market, so we are relisting at your current price.
-   **No data for HSP**: No data exists to work out what the highest sellable price for this item is.

## Conclusion

I hope this helps people to understand Auctioneer a bit better.

More advanced topics such as playing the market to make bulk **GOLD** will be covered in future documentation.