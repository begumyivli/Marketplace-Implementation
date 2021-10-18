# -Marketplace-Implementation
Economy is an indispensable fact of our lives. In real life, for buying and selling
things, we use some printed or virtual assets, called money. However, your money
does not have any difference with paper in your pocket. It gains its value only in a
marketplace.
In this project, I implemented a basic marketplace model. This model
consists of traders, wallets, transactions, currencies, and the market. For simplicity
we have two currencies in the market: dollar and PQoin (Priority Queue Coin).
Traders can give buying or selling orders to the market, if they can afford.
In our market model, there are two priority queues for storing orders. In a priority
queue, elements having highest priority serve before. The priority rules are written in
the next sections. With these rules, your market implementation should make
transactions if these two priority queues’ tops overlap.
