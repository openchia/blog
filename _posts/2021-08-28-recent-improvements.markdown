---
layout: post
title:  "Recent Improvements"
date:   2021-08-28 14:40:01 -0300
---

Sometimes it may seen that our team has their arms crossed and is not doing anything!

We are often working on a lot of things, not always these things are features that we can see easily or notice at all because it may be work happening on the backend.

We would like to keep all our farmers updated on our latest developments no matter what, so here are a few of the things that we have worked on recently.

# Extra stats for farmers in explorer

We have added "Utilization Space" and "Estimated Space" to the main farmers table.

![Explorer](/assets/2021-aug-28-improvements/space.png)

# XCH Price

The current XCH price is now available at the top of our explorer.

The Discord also advertises the price via nickname.

![Explorer](/assets/2021-aug-28-improvements/xchprice.png)

# Increase width of size for large screens

It now has better space utilization and reads better on other languages.

# Better graph colors for pool space and farmer partials

They are now more aligned to the website theme.

# Website translation

We have received more contributions for translation and now we have Simplified Chinese (prelimiar), German, French, Polish and Portuguese.

Special thanks to Aidan, DJΞRFY and l080 for the contributions.

# Support for 24 hours PPLNS in backend

The pool now has improved support for PPLNS over last 24 hours. For now its a disabled feature but its ready as soon as the pool starts having rewards more often.

# Harverster ID

Haverster ID is now being collected from partials and will soon be made available under Farmer Details.

# Bug in Blocks and Payouts in Farmer Details

These two tabs were being shown within Farmer Details but they were not working properly. We were able to fix that bug thanks to Whuza78 for reporting it.

# Delay in partials

Confirmed partials were being registered in the website using a timestamp with a delay. Partials takes time to be processed and thats by design but they should be registered using the timestamp it was sent by the farmer. Thanks to _atomsymbol_ for reporting the bug.

Special thanks to DJΞRFY for contributing on many of these features and embracing the open source spirit.

As always, please let us know of any issues that may arise or any feature you would like to see through our [GitHub][2].

[1]: https://openchia.io/api/doc/
[2]: https://github.com/openchia/web/issues
