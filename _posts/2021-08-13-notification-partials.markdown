---
layout: post
title:  "Notification of Missing Partials"
date:   2021-08-13 08:20:01 -0300
---

Farmers need to make sure their farm is running smoothly at all times.

The way pools perceive the contribution of farmers is through submission of partial proof of space.

On a difficulty of 1 a farmer is supposed to send 10 partials per day per K32 plot, which means with 30 plots (roughly 3TiB) the farmer will be sending 300 partials per day.

That said, in that scenario, if the pool does not receive in average 12 partials per hour there is something wrong with his farm. For that reason we have implemented a notification system to inform farmers in case the pool stops receiving partials.

How does it work?

First the farmer needs to configure his email and enable the checkbox for notification in the login page. This is the same page used to [set a display name][1].

![Notification](/assets/2021-aug-notification/details.png "Notification")

Once you have that configured you will receive one email if you stop sending partials for a reasonable amount of time, depending on your estimated farm size.

This should help identify a number of issues with the farm in a timely manner.

As always, please let us know of any issues that may arise or any feature you would like to see through our [GitHub][2].

[1]: https://blog.openchia.io/2021/07/27/howto-set-name.html
[2]: https://github.com/openchia/web/issues
