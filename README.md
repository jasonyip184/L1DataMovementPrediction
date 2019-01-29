# L1DataMovementPrediction

## Task
Task is to predict the type of the first event that will happen in the next 1/3/5 seconds.

0 -- No price change

1 -- Bid price decreased

2 -- Ask price increased

## Features
timestamp  str  datetime string
bid_price  float  price of current bid in the market
bid_qty  float  quantity currently available at the bid price
bid_price  float  price of current ask in the market
ask_qty  float  quantity currently available at the ask price
trade_price  float  last traded price
sum_trade_1s  float  sum of quantity traded over the last second
bid_advance_time  float  seconds since bid price last advanced
ask_advance_time  float seconds since ask price last advanced
last_trade_time  float  seconds since last trade
