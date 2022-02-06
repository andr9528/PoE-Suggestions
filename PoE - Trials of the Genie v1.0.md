# Trials of the Genie
## Headsup
Any numbers and many effects written in the suggestion is up for discussion.
## Premis
Genies are magical creatues who fulfill wishes, however they also attemt to twist wishes to not be entirely possitive for the wisher.
## Pitch
A Genie has washed ashore of Wraeclast, and somehow escaped his/her eternal confinement of the Lamp. Impress him/her with your skills at fighting and surviving, and be rewarded.
## Description
The Genie will appear somewhere on the map close-ish to the center. Upon interacting with him/her, he/she will ask if you are willing to try and impress him/her. 
If agreed upon, he/she creates a large bubble/zone (larger than the largest during Ultimatum), wherein he/she will begin to spawn enemies. Enemies and projectiles outside the bubble are frozen in time. Going near the edge of the bubble slows the player down gradually until they move at 30% of their normal speed. Leaving the bubble for more than 5 seconds, counts as abandoning the trial.

To win the Trial, the player has to survive for a set amount of time. The rate at which the Genie summons enemies increases the longer the player survives. By deafault they player has to live 30 seconds, but increases by 5 seconds for each concecutive win. Upon a loss, when dieing or abandoning the bubble, the time needed is reset.
The Genie is a sore loser, and as such will begin to 'cheat' after 3 concecutive wins, and increase his rate of 'cheating' for every 3 concecutive win after that. When he/she cheats, he/she spawns different hazards throughtout the bubble. Hazards include, but is not limited to:
- Traps / Mines
- Projectiles
- Descructable Terrain

Killing enemies during the Trial increases the odds of getting a rarer reward from the Genie afterward. Enemies during the Trial still drop normal loot, which will appear by the Genie, ones the Trial is over, Win or Loss.
If the player wins the Trial the Genie will offer 3 buff of the same rarity to chose from. The player can then chose a buff or decline, in which case the Genie will reward the player with some currency depending on how well they did during the Trial.
If the player choses a buff, a matching 3 debuffs of the same rarity or rarer will be presented. For the player to keep the selected buff, they have to accept one of the debuffs, but can again decline, reciving less currency than if they had declined before.
If both a positive and negative buff has been chosen, the buff is granted to the player, that last for 30 minutes, even between instances.

Every 10 levels (1, 11, 21 etc.) the player earns a slot where he/she can lock in a buff/debuff to retain it, until the player choses to unlock the slot again, in which case the buff/debuff vanishes immediately.

## Buffs / Debuffs
Not all buffs and debuffs has all rarities. There are three rarities, Magic, Rare and Unique. As the name suggest only one of each Unique buffs/debuffs can be applied at a time. The magic and rare rarity buffs/debuffs stacks with itself, of the same or other rarities, but are not equally good to stack.
When chosing a debuff to allow the player to chose from, it does so by looking at the Tags on the buff, and selecting amoung debuffs who has atleat one Tag in common with the buff. i.e if a buff has a 'Frost' tag, debuffs with a 'Frost' tag can be shown.  
### Reactive Ward
- Type: Positive
- Magic: Ward recharges 1 second faster.
- Rare: Ward recharges 2 seconds faster.
- Unique: Ward never depletes. 
- Tags: Ward; Defence;
- Notes
	- When ward recharge is 0 seconds or less, any damage is lowered by amount of Ward.
	-  "Ward never depletes" means it has a recharge time of 0 seconds.
### Adaptive Defences
- Type: Positive
- Magic: ---
- Rare: Elemental Resistances are Equal. +10% to Elemental Resistances.
- Unique: All Resistances are Equal. Cap is equal to the highest amount All Resistances.
- Tags: Resistance; Defence; Frost; Fire; Lightning; Chaos; Physical
- Notes
	- If something sets a resistance to 0, which is part of being equal to others, the others are also set to 0.
	- 'Elemental Resistances' refers to Fire, Frost and Lightning.
	- 'All Resistances' refers to Fire, Frost, Lightning, Chaos and Physical.
	- With the Unique, increasing Armor, increases All Resistances.
### Reinforcing Gems
- Type: Positive
- Magic: A level 7 X supports Links in Y.
- Rare: A level 14 X supports Links in Y.
- Unique: Two different level 20 X supports Links in Y.
- Tags: Gems; Support
- Notes
	- X is any Support gem.
	- Y is any gear slot, which can have sockets, including Rings.
	- Empower, Enlighten and Enhance support gems are not among the valid gems for X.
### Ragnarök Comes
- Type: Positive
- Magic: You deal 100% more Frost damage.
- Rare: You deal 200% more Frost damage.
- Unique: You deal 300% more Frost damage. Cold Ailments are 100% more effective.
- Tags: Frost; Attacks; Spells
- Notes
	- 'More Effective' means it inceases both intensity and duration.
### Helfire's Release
- Type: Positive
- Magic: You deal 100% more Fire damage.
- Rare: You deal 200% more Fire damage.
- Unique: You deal 300% more Fire damage. Ignite lasts until death, and stacks.
- Tags: Fire; Attacks; Spells
- Notes
### Eternal Storm
- Type: Positive
- Magic: You deal 100% more Lightning damage.
- Rare: You deal 200% more Lightning damage.
- Unique: You deal 300% more Lightning damage. Lightning Ailments are 100% more effective.
- Tags: Lightning; Attacks; Spells
- Notes
	- 'More Effective' means it inceases both intensity and duration.
### Swiftfooted
- Type: Positive
- Magic: Increase Evasion rating by 0.75x of bonus movement speed.
- Rare: Increase Evasion rating by 1.5x of bonus movement speed.
- Unique: Increase Evasion rating by 2.25x of bonus movement speed. On evading an attack, increase movement speed by 5% for 4 seconds, stacking.
- Tags: Movement Speed; Evasion; Defence
- Notes
### Cursed Actions
- Type: Negative
- Magic: Get cursed by a level 7 X when you activate a gem in Y for 4 seconds.
- Rare: Get cursed by a level 14 X when you activate a gem in Y for 4 seconds.
- Unique: Get cursed by a level 20 X when you activate a gem in Y for 4 seconds. Hey Curses on you are 50% more potent.
- Tags: Hex; Curse; Gems; Attacks; Spells;
- Notes
	- X is any gem with both Curse and Hex tags.
	- Y is any gear slot, which can have sockets, including Rings
	- If multiple of the same debuff is gained, stack the duration.
	- If the activating gem is an Aura, continuesly apply the curse, intil the aura is disabled.

### Slow Reactions
- Type: Negative
- Magic: On getting hit, reduce bonus movement speed by 3% for 4 seconds.
- Rare: On getting hit, reduce bonus movement speed by 6% for 4 seconds.
- Unique: On getting hit, reduce bonus movement speed by 12% for 4 seconds. If hit with 0% bonus movement speed, get stunned for 0.25 seconds.
- Tags: Movement Speed;
- Notes
	- Can never go below the player default movement speed.
	- Gives 0.5 seconds of immunity to stuns from this, after being stunned by this, preventing stunlocks.
	- 'Getting Hit' refers to both hits from attacks and spells.

### Decaying Nature
- Type: Negative
- Magic: Reduce X Resistance by 4 when hit, for 4 seconds.
- Rare: Reduce X Resistance by 8 when hit, for 4 seconds.
- Unique: Reduce X Resistance by 16 when hit, for 6 seconds.
- Tags: Fire; Frost; Lightning;
- Notes
	- X is the Elemental tag of the buff, that this is the negative part of.
	- X is only one Element, even if the buff has multiple Elemental tags.
	- 'Elemental' refers to Fire, Frost and Lightning.




> Written with [StackEdit](https://stackedit.io/).
