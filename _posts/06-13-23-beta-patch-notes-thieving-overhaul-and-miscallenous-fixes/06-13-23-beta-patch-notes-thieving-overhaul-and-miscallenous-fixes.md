---
title: 06/13/23 | Beta Patch Notes - Thieving Overhaul and Miscellaneous Fixes
date: 2023-06-13
tags: [beta, patch-notes]
description: Neox updates from 06/13/23.
---

***
<em>Hey there, everyone! As I'm sure everyone can agree, there's certain skills among the game that just aren't that enjoyable to train, or are egregiously unapologetic in how input intensive they are for the payout. With this in mind, it's always going to be a goal of our to take the very baseline content of the game and modify it in ways that make for an enjoyable experience. We'll always be looking to kind of adapt the game in that regard without altering it too drastically as to veer off from the original identity. As with our mining changes from before, we're now tackling thieving to remove some of the lesser enjoyable mass clicking and grinding aspects from the skill and have resultingly introduced some pretty drastic changes that we think will be for the better. Alongside the thieving overhaul, we also have a ton of smaller fixes and adjustments to share with you all. As always, we welcome any and all feedback through the appropriate channels.

<em>Thanks!

<em>Neox Staff<br>

***

<div class="spacer-large"></div>
<div class="changes-body">
    <div class="changes-body changes-row features">
        <div class="changes-row-header">
            <span class="icon">
                <span class="material-symbols-outlined">arrow_circle_up</span>
            </span>
            <h3>Features</h3>
        </div>
    </div>
</div>
<div class="spacer-small"></div>

- Added 30 new thieving tasks to go along with the thieving overhaul.
- Pickpocketing actions are now repeated with no input necessary, if successful. Repeat pickpockets happen every 3 ticks, while manual pickpocketing can be performed once every 2 ticks.
- Pickpocketing will be interrupted if players get caught by the NPC, or if they pickpocket over a certain number of times in a row.
- Most thieving actions now reward the player with one of 4 different tiers of a new item called 'Bag of Riches'.
- These bags are stackable and can be looted for coins and gems. The highest tier of bag can even contain Onyxes. They also have a right-click option to loot up to 300 of them at a time, to reduce the amount of clicking required.
- Added a new achievement: 'Renowned Thief'. Rewards the gloves of silence, which improve pickpocket success rate, and a new 'Thief' title.
- Added map labels describing areas of the new Home Island.
- Added Agility Pyramind & Pyramid Plunder to the minigame teleports.
- Added a cows teleport to the teleport portal. 

<div class="spacer-medium"></div>
<div class="changes-body">
    <div class="changes-body changes-row improvements">
        <div class="changes-row-header">
            <span class="icon">
                <span class="material-symbols-outlined">arrow_circle_up</span>
            </span>
            <h3>Improvements</h3>
        </div>
    </div>
</div>
<div class="spacer-small"></div>

- Renamed the 'Steal X coins from Ardougne inhabitants' task variants to 'Steal X coins from Ardougne citizens'.
- Reduced the amount of coins required to complete the elite and master variants of the 'Steal X coins from Ardougne citizens' tasks.
- Pyramid Plunder access doors are no longer randomized. Any of the 4 pyramid doors will now take you to the room containing the Guardian Mummy.
- Pyramid Plunder objects can now contain bags of riches in addition to artefacts; the Grand Golden chests in each room are guaranteed to contain 2-6 bags of riches.
- Pyramid Plunder artefacts can now be stored in the resource bag, and will automatically be deposited in the bag if you are carrying an open one.
- Run energy is no longer consumed while in the Home Island.
- Made visual improvements to the title selection interface.
- Changed the 'Home Island' map label to 'Neox Island'.
- Rebalanced shop prices and converted more shops to use the new shop interface.
- Added a hammer item spawn to the smithing area in Neox Island.

<div class="spacer-medium"></div>
<div class="changes-body">
    <div class="changes-body changes-row fixed">
        <div class="changes-row-header">
            <span class="icon">
                <span class="material-symbols-outlined">handyman</span>
            </span>
            <h3>Fixed</h3>
        </div>
    </div>
</div>
<div class="spacer-small"></div>

- Implings and birds can no longer fly into indoors areas.
- Fixed the 'Mix a super combat potion in Varrock's west bank' not completing correctly if you used a torstol herb instead of a torstol potion.
- Fixed the 'Kill a Mithril Dragon in the Ancient Cavern' task and its higher tier variants not completing correctly.
- Fixed the smithing step of the 'Make 10 rune darts in Varrock' task not progressing correctly.
- Fixed the 'Mine some Runite ore in the Fremennik Isles' task not requiring you to be in the correct area to be completed.
- Fixed an issue preventing the spirit tree in the new home area from working correctly.
- Fixed the Ardougne cloak 2 incorrectly requiring 50 defence to be equipped.
- Fixed Patchy's dialogue showing Frincos as the NPC.
- Added locust meat to Locust droptable.
- Replaced Al kharid palace with guards and gave them combat defs.
- Removed Stonemasons from Taverly and added druids.
- Jatix now opens the correct store interface.
- Blocked the tiles that guide NPCs and the Fisherman stand on so that the players cannot walk on top of them.
- Fixed an issue causing attack options to be invisible for new players.
- Restored Land's end map to its original state.

<div class="spacer-medium"></div>
<div class="changes-body">
    <div class="changes-body changes-row removed">
        <div class="changes-row-header">
            <span class="icon">
                <span class="material-symbols-outlined">remove_circle</span>
            </span>
            <h3>Removed</h3>
        </div>
    </div>
</div>
<div class="spacer-small"></div>

- Removed clutter items from H.A.M. Members pickpocketing loot table, except for outfit pieces.
- Removed Zamorak Crafter spawn in the middle of lava lake at Ourania Altar.
- Removed ladder that sent player to void area in Sophanem.

<div class="spacer-medium"></div>

***

<h1 style="color:#885eac;">Thieving Overhaul - Expanded</h1>


Simply put, thieving, much like several other skills on the way to a maxed account, is not a fun skill. It's unapologetically click intensive, requires a ton of observation and player involvement, and the rewards have always been relatively miniscule if not outright worthless. With the changes we've made this patch, we wanted to giving thieving a bit more of a unique identity as well as removing some of the tedium involved in leveling it up. 

Beyond making very rudimentary changes to the skill's behavior, we've also added unique incentives and achievements based around improving the *quality of life* of the skill as well as giving it a bit more of a unique identity. Below, we'll sort of outline out train of thought going into each approach.

## Auto-Thieving

<img src="/assets/img/updates/061323/thieving.gif">

With the new design, thieving will be significantly less **attention demanding** in the sense that players will be able to click on their target and continue auto-thieving and generate profit without having to pay much attention. Though this might seem entirely AFK, we didn't want to completely remove involvement and the following actions will cause a player to cease auto-thieving:

  • The player is detected by the NPC they are thieving and stunned.<br>
  • The player is forced into the AFK state by Runelite's internal timer.<br>
  • If the player clicks to perform another action.<br>

In time, we might have to adjust some of these elements accordingly, however we're hoping the new system will be an improvement from the traditional thieving experience.

## Thieving Rewards

<img src="/assets/img/updates/061323/lootingbags.gif"> <img src="/assets/img/updates/061323/bagsofrichesloot.png">

Thieving rewards themselves have undergone some relatively drastic changes, but ones we hope will be for the better. Besides now compacting the cash reward into a stackable unique item referred to as a "bag of riches", players will also be able to receive items from their original looting tables at the same time. These bags will include a ranged cash pile depending on the tier of bag opened alongside a random gem; to add to this, it's even possible to get an onyx from the highest tier of bag!

<img src="/assets/img/updates/061323/thiefachievement.gif">

Besides modifying the thieving loot, we've also implemented a way in which players can obtain the <a href="[url](https://oldschool.runescape.wiki/w/Gloves_of_silence)">Gloves of Silence</a>, which will give a player an increased chance to successfully pickpocket; contrary to their original 62 failed pickpocket limit, we've completely removed the limit and players will be able to wear them for as long as they wish.

That's it from us for now! Thanks for taking the time to read everything, for those that have, and we'll see you in the next patch.






