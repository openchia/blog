---
layout: post
title:  "Change Pool in Chia"
date:   2021-07-27 06:10:08 -0300
---

For many reasons users may want to change from one pool to another.
Some people prefer bigger pools, some prefer smaller, others prefer a different interface, etc.

In Chia the new plots (NFT) are tied to a Plot NFT. A single Plot NFT can change pools very easily.

What will happen to the points you accumulated in the previous pool depends on each pool. Some will pay your accumulated points, some will ignore them.

Changing pool costs 1 mojo (0.000000000001 XCH). If you don't have 1 mojo grab one [here][1]. See below how you can change pools.

### Using Chia UI

Open the Chia UI, go to Pool menu and then click on the Change Pool button:

![Plot NFT](/assets/changepool/plotnft.png "Plot NFT")

Select Connect to pool and enter "https://pool.openchia.io".

![Change Pool](/assets/changepool/nftchange.png "Change Pool")

Click Change and you're done.

### Using Command Line

Check your plotnft and copy your wallet id (usually 2, if you have only one Plot NFT).

    chia plotnft show

Join another pool

    chia plotnft join -i 2 -u https://pool.openchia.io

Confirm and you're done.

Thanks for joining us!

[1]: https://faucet.chia.net/
