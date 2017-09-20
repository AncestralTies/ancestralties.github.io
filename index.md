# Ancestral Ties - Legion EPGP

## Overview

* Minor, Crossgrade, and Offspec loot options have been removed to greatly simplify the loot process
* All loot will be assigned at the full GP value (with 1 exception)
* Weapon Drop rules have been removed because everyone has Artifacts
* Relic drops are assigned a GP value of 1/3 of a 2H weapon
* Raid EP is now rewarded at a rate of 40EP/15m on both Heroic and Mythic difficulties
* Loot items awarded for Transmog now cost 1 Chaos Crystal to the guild
	* Crystals should be mailed in-game to **Rour**

Additionally:

* Bonus EP per week is now attainable through material contributions to the guild. ([Details](#contribs))

	* 20 EP per 60 Starlight Rose or Leylight Shards	* 20 EP per 20 Felwort	* 20 EP per 20 Chaos Crystals
	* 20 EP per 20 Bacon	* 20 EP per 100 Felslate	* 20 EP per 200 Leystone Ore, Arkhana, or Legion Meat/Fish/Herbs
	* Mats should be mailed in-game to **Zaestha**.

## Notes

By far the biggest change is the change from Major/Minor/Crossgrade/Offspec/Transmog to the new Normal/Others First/Transmog loot options. 

A great deal of discussion went into considering these options. Over the course of WoD, our loot system evolved in a manner that served to continuously reduce the average GP cost of loot, reducing the effectiveness of the EPGP system by greatly reducing GP costs and reducing the impact to PR of looting an item. Eventually, being charged the full GP value of an item felt like a punishment. Additionally, a great deal of confusion existed regarding what qualified as Minor upgrade, Crossgrade, or Offspec loot. The intended purpose of Offspec (to allow raiders to maintain a healer or tank gear set to serve as a backup) was forgotten, and Offspec relaxed to the point that it was invoked simply for use with a different set of talents within the same spec. 

For Legion, we're reverting to full GP values. An item's full GP value will be credited to the loot winner (with one notable exception, see below). By starting with a clean slate and 0 EP/GP, everyone is working within the same constraints and within a fair system. Doing this allows us to remove confusion regarding what qualifies as a major upgrade/minor upgrade/crossgrade, and simplify loot distribution greatly. While those who obtain a piece of loot for use with a secondary loot spec will be assigned the full GP value, this is true of all raiders evenly, and we expect the PR numbers to generally balance out.

The exception to full-cost GP is that trinkets and relics (the remaining 2 slots that are still role-specific) that are taken for an Off-__role__ purpose (such as a DPS player looting a tanking/healing trinket), will be assigned 75% of the item's GP cost (a 25% discount). This encourages the continuation of off-role gearing.

***Note 1***: A raider who loots a trinket or relic for a secondary spec of the same role (ie Off-spec but not Off-role) will still be charged the full GP cost. Off-role discounting only applies to trinkets and relics assigned by “Others First” priority for use in a different DPS/Healer/Tank role category. 

***Note 2***: Relics will not be eligible for off-role discounting unless they cannot be equipped in the player’s main spec artifact

We have simplified standard loot distributions down to 2 options: "Normal" and "Others First". 

* ***"Normal"*** effectively replaces the Major/Minor/Crossgrade options, and indicates that you wish to be included in the first priority tier, within which winners are still determined by the highest PR. 

* ***"Others First"***, as the name suggests, should be used when you want to loot an item, but only as a secondary priority. This is effectively "I want it if no one else needs it more than I do”. PR determines the winner within "Others First", and full GP will still be assigned for loot taken in this manner, but it allows players to specify whether they want others to have first crack at it if it's not as important an upgrade for them. 

While we understand that some may be put off by these changes, we’re confident that this will be an improvement for the guild as a whole, and encourage everyone to work with us as we adapt to these changes. The expansion of Warforged/Titanforged gear and the addition of Mythic+ dungeons also gives additional gearing avenues to those who are concerned about obtaining viable gear for secondary specs without incurring large GP debts. We look forward to making sure that everyone is able to gear up and contribute to the best of their abilities.

## Addons

* [epgp-dkp-reloaded](https://mods.curse.com/addons/wow/epgp-dkp-reloaded)
* [epgp_lootmaster](https://mods.curse.com/addons/wow/epgp_lootmaster)
 
Go Download these, you will need them. 

## The Nerdy Details
EP stands for Effort Points, they are points awarded for contributing to the guild’s raids. Unlike DKP, you don’t “spend” your EP points.
 
GP stands for Gear Points and are credited to a player's total when an item of raid loot is distributed to them. The overall GP cost of an item is determined by its item level and item slot. Like EP, your GP isn’t spent.
 
PR is the player's loot priority. PR is calculated as EP divided by GP. This number determines who wins a piece of loot over others asking for the same item. Whoever has the highest PR in a given roll wins the item. 

### Effort Points and Sources
EP is distributed for participating in heroic and mythic guild raids, EPGP is not used in our alt/friend casual raids. The following EP awards are available:
 
* On-time and Ready at start time: 100EP/raid
* During raids: 40EP/15mins in Mythic and Heroic raids
* Boss kills: 40EP/kill for guild's first 5 kills (inclusive)
* Boss wipes: 5EP/wipe for guild's first 5 kills (inclusive)

<a name="contribs"></a>(__NEW__) Optional material contributions: 

* 20 EP per 60 Starlight Rose or Leylight Shards* 20 EP per 20 Felwort* 20 EP per 20 Chaos Crystals
* 20 EP per 20 Bacon* 20 EP per 100 Felslate* 20 EP per 200 Leystone Ore, Arkhana, or Legion Meat/Fish/Herbs
* Up to 200EP max per week

Material contributions must be in multiples of the above quantities, and will not be prorated. Contributions should be mailed to Zaestha, and all contributions during a week will be credited to players following the next Decay.

### Gear Points and Loot Options
GP is assigned to a player when items are looted to them. Loot will be assigned according to the following priority, and an item's winner will be assigned GP according to its cost. The EPGP addon shows the GP value for an item on the item’s tooltip.
 
1. Normal (100% of item GP)
2. Others First (100% of item GP, 75% for off-role trinkets and relics)
3. Transmog (0% GP, 1 Chaos Crystal to Guild Bank)

#### Decay
The EP and GP of the entire guild is decayed by 10% every week. This serves both to reduce the effect of hoarding EP and reduce the impact of the GP you have gathered over time. If you attend raids and never spend EP, it will eventually get to the point where you decay as much as you earn. Additionally, if you receive a large amount of GP in a short period of time, decay reduces the severity of that GP hit over time.

### Cosmetic and Offspec Items
Any items that are not taken for GP will be random-rolled for transmog amongst those who selected the Transmog loot option. The winning player is responsible for reimbursing the guild with a Chaos Crystal.
 
### Extra Mathy Stuff
The EPGP addon presents two extra values, “BaseGP” gives the entire guild a non-zero GP value that is always present. For our guild, this is set at 100GP.
 
The other, “MinEP”, is a threshold that a new player must reach in order to be eligible to use their PR against players that have more EP than the MinEP. This provides a short-lived barrier ensure that fresh raiders cannot immediately win loot on their first night. We use a MinEP of 750EP, just more than one night of farm content.
 
***Note***: Raiders below MinEP can still win uncontested items, or items that have only been rolled on by other raiders that are also below MinEP.