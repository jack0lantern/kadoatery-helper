# Features

## Feed highlighting

**You can see inventory feedable kads highlighted in red.** In order to use this function, you need to visit your inventory to allow the script to sync with your inventory.

**You can see SDB feedable kads highlighted in blue.** In order to use this function, you need to visit each page in your SDB under the "Food" search to sync with the script. It may be a little time consuming but you'll save a lot of trouble ;)

Clicking a kad will automatically copy the food name to your clipboard. Just paste into your already-open shop wizard!

Use this script in conjunction with diceroll's [search helper](https://github.com/diceroll123/NeoSearchHelper) to get the best results with SDB feeding.

## Timekeeping

If you refresh the [kadoatery](http://www.neopets.com/games/kadoatery/index.phtml) when new hungry kads show, **the script automatically registers the refresh** as either a "main" (all the kads refreshed) or a "mini" (only the last 1-3 refreshed). It grabs the time from the NST clock and computes the next refresh time. You can see the time of the next refresh by clicking the "Kad Food List" button, as well as the foods that showed on the refresh.

If a refresh might have happened, but didn't, **you can see the refresh pending time below the Kad Food List button.**

As of now, this only tracks the latest main and mini that refreshed. 

## Future features

* Manual input of refresh times (from neoboards or something)
* Multiple mini clocks
* Timing alarms (some sound when it's time to refresh)
* Reset late refreshes (kads that refresh 30s or more past the expected time usually reset to the expected time, so the next expected refresh would be 28 min from the old expected time)
* Lots of bug fixes... not really a feature but eh

# Installation

1. Install the Tampermonkey extension or addon
2. [Click here.](https://greasyfork.org/en/scripts/423914-kad-helper) Install the script. Keep in mind there may be updates available!

If you're feeling iffy about feed highlighting, you can get a version of the script that only has timekeeping capabilities. [https://greasyfork.org/en/scripts/423920-kad-timekeeper](https://greasyfork.org/en/scripts/423920-kad-timekeeper)


# Contribute
I'm not sure I'll have time to implement all the above future features. I have opened up each corresponding issue. If you want to develop them, just assign the issue to yourself and raise a pull request ^^
