---
layout: post
title:  "How-to set name in Explorer"
date:   2021-07-27 01:10:08 -0000
---

Launcher ID is how a farmer is identified for each Plot NFT.
That is a long hexadecimal string and not user friendly.

For easier identification in our pool we allow users to set a friendly name for the explorer, an alias for your launcher ID.

### Using the command line

Grab your launcher id:

    chia plotnft show

With your launcher id get the link:

    chia plotnft get_login_link -l <launcher_id>

Open the link with your browser, set the name and click Save.

### Using Chia UI

Under Pools menu select your Plot NFT, click the 3 dot menu and then View pool login link.

Copy the the link and open in your browser, set the name and click Save.
