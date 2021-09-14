---
layout: post
title:  "Farmer Partials"
date:   2021-09-14 17:40:01 -0300
---

We have been out of the news here for a little while but we have kept ourselves busy!

We have made a bunch of improvements to our pool server code which are invisible to the end user but greatly improves its reliability.

Now for the website side of things we have recently introduce a few changes to the Farmer Details page.

# Harverster ID

Most farmers have only one harverster set up for their farm, however some of them choose to have multiple of these, harvesting from multiple locations. For that reason we have started tracking the harvester id and showing it in the partials table.

![](/assets/2021-sept/harvester.png)

# Extra Overall Details

Now that we are tracking harversters we now show a count of total harversters we have for the farmer that were seen in the last day.
Additionally to that we have the performance of the farmer, which is essentially the rate of successful partials.

![](/assets/2021-sept/extra.png)

# Failed Partials Filter

Most of the times the farmer may be only interested to see the failed partials in the table, thats why we have added a checkbox where you can now filter for these failed partials.

![](/assets/2021-sept/failed.png)

Special thanks DJΞRFY for some of the contributions.

As always, please let us know of any issues that may arise or any feature you would like to see through our [GitHub][1].

[1]: https://github.com/openchia/web/issues
