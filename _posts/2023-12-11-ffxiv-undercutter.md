---
layout: post
title: "Final Fantasy XIV Undercutter"
---

![FFXIV Undercutter](https://oyster.ignimgs.com/mediawiki/apis.ign.com/final-fantasy-xiv/8/84/Ffxiv_12122021_000738_504.png?width=640)
*In-game FFXIV market board[^1].*

Final Fantasy XIV is an MMORPG with a market board system that allows players to buy and sell items. The market board is a place where players can list items for sale and purchase items from other players. The market board is a great way to make money in the game, but it can also be a competitive place. One of the ways players can compete on the market board is by undercutting.

I developed FFXIV Undercutter to automate the process of undercutting on the market board. The tool allows players to set a target price for an item and automatically undercut the lowest price by a specified amount. This can help players sell items quickly and efficiently on the market board, without having to constantly monitor prices and manually adjust their listings.

![FFXIV Undercutter](https://raw.githubusercontent.com/besplago/besplago.github.io/main/_images/ffxiv_undercutter_1.png)
*FFXIV Undercutter interface.*

The tool is implemented using PyQt5 and Python. Currently, the tool is in the early stages of development, and it relies on another addon to get the market board data. For now, the tool is hardcoded to undercut by 1 gil (the in-game currency), which is mostly wanted. Future plans include implementing independent market board data retrieval, friendlier user interface, and adding more features. It is currently only for personal use, and I do not plan to release it to the public anytime soon.

<!-- (insert video/gif)
*FFXIV Undercutter in action.* -->

---
{: data-content="Rings of Ragnarok"}

[^1]: Image credit: [How to Use the Market Board](https://www.ign.com/wikis/ffxiv/How_to_Use_the_Market_Board) by IGN.
