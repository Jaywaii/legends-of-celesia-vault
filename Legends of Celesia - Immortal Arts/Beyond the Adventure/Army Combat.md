---
template: "article"
category: "[[Beyond the Adventure]]"
state: "public"
wip: true
created: "2024-05-10"
updated: "2026-04-13"
worldanvil_url: "https://www.worldanvil.com/w/legends-of-celesia-jaywaii/a/army-combat-article"
---

# Army Combat

# Units

Units are the components of an army. Each unit is composed of soldiers of the same lineage traits, the same talents, and the same level.

## Basics

**Attack Roll** is the roll made for your unit's attacks. It is equal to 1d20 + UL + ULM + equipment modifiers + miscellaneous modifiers. A natural 20 increases the total number of casualties inflicted by 50%. A natural 1 reduces the total number of casualties by 50%.

**Casualties** are the number of troops that are wounded or killed when the unit is attacked. This is a temporary number that is updated during the turn. At the end of the turn, the unit makes a **Casualties save** to determine how many troops of the casualties are wounded and how many are killed. See the **Casualties Phase** below.

**Creature Size** of the unit is based on the creature size category of its troops. A unit's melee attacks gains +1 bonus for every creature size category it is larger compared to its target.

**Fatigue** is the DC that the unit needs to beat in order to not gain a level of fatigue. Each time the unit performs a tiring activity, it must make Morale check against the Fatigue DC, or take one level of the fatigue condition. Each level of fatigue inflicts a -1 penalty to attack rolls, the unit's DV, to Morale checks, and reduces speed by one size category. Regardless of success, the tiring activity increases the DC by 5. The unit's Fatigue DC resets to 0 each time the unit fails its Morale check against Fatigue, and a full rest.

**Killed** tracks the number of troops killed. Troops that are killed no longer count towards the unit's size, and if the number of living troops drops down to the next size category at the end of the Casualties phase, the unit's size modifier changes to that category. A unit with no living troops remaining is considered to be **destroyed**.

**Morale** is a score that represents your unit's willingness to keep fighting and its cohesion. A newly created unit starts with a morale score of 10. Certain events modify morale. When morale reaches 0 or lower, make a DC 10 Morale check each time morale is lowered; failure results in the unit disbanding. A Morale check is 1d20 + the morale score + your ULM. A natural 20 on a Morale check is an automatic success, and a natural 1 is an automatic failure.

### Table : Morale Event Modifiers

| Event | Modifier |
|---|---|
| Winning a battle. | 4 + 1 per enemy army's size category greater |
| Enemy unit is destroyed. | +1 |
| Enemy unit retreats from the battle. | +1 |
| Pay double Wealth consumption. | +1 |
| Each time Wealth consumption is not paid. | -1 |
| Every 1/10 of the unit'scurrent size of troops killed. | -1 |
| Retreats from battle. | -1 |
| Taking friendly fire damage. | -1 |
| An allied unit is destroyed. | -2 |

**Supply** is the collection of capital that your unit is carrying. For every 10 times a unit's size modifier worth of total capital (Food, Goods, Magic, and Wealth combined), the unit's base speed is reduced by 1 size.

**Unit Defense Value (UDV)** tracks your unit's defense. Attack rolls must match or exceed this value to inflict damage. It is equal to 10 + ULM + equipment modifiers + miscellaneous modifiers.

**Unit Leader** is the person who commands the unit. Every unit needs a unit leader in order to perform actions. The unit leader can be of different level or lineage than the composition of their unit.

**Unit Leader Modifier (ULM)** represents how the unit leader leads their unit. The leader uses her highest modifier between Intelligence, Wisdom, and Charisma, and adds a bonus based on her proficiency in her Soldier skill: -1 for untrained, +0 for skilled, +1 for expert, +2 for master, and +3 for legendary.

**Unit Level (UL)** represents the unit's overall strength. It is equal to the troops' level.

**Unit Size** is equal to the number of troops in the unit.

**Wounded** tracks the number of troops that are wounded severely enough that they cannot be healed during the battle. When the number of wounded reaches or exceeds 50%  of the number of remaining troops in the unit, the unit incurs a +1 hindrance on all d20 rolls. Wounded troops can still fight and still count towards the unit's size.

## Unit Sizes

A unit's size refers to its number of troops.

**Size Modifer:**

**Travel Time Multiplier:** The larger the number of soldiers in a unit or army has, the more time it takes to travel overland. The extra time comes from the time needed to keep the soldiers organized as a workable, cohesive unit, and from the delays that arise from units slowing down and making space for each other as they all move forward.

### Table: Army Unit Sizes

| Designation | Number of Soldiers | Size Modifier | Travel Time Multiplier |
|---|---|---|---|
| Solo* | 1 | +0 | x1 |
| Squad | 2-10 | +1 | x1 |
| Platoon | 11-50 | +2 | x1.25 |
| Company | 51-200 | +4 | x1.5 |
| Battalion | 201-500 | +8 | x2 |
| Regiment | 501-2,000 | +16 | x2.5 |
| Brigade | 2,001-5,000 | +32 | x3 |
| Legion | 5,001-10,000 | +64 | x4 |
| Corps | 10,001-25,000 | +128 | x5 |
| Army | 25,001-50,000 | +256 | x6 |

## Consumption

**Food:** A unit's Food consumption is equal to its unit size modifier + the troops' lineage size modifier. Failure to pay Food consumption increases the unit's Fatigue and Morale DCs by 5.

**Goods:** A unit's Good consumption depends on what equipment it is equipped with which generally scales with its unit size modifier. Failure to pay Goods consumption means that certain equipment can no longer be used.

**Wealth:** A unit must be paid Wealth equal to its size modifier plus its level. Failure to pay Wealth consumption increases the unit's Morale DC by 10. If the unit's troops are followers of a realm leader, the Wealth consumption is halved.

**Garrisoned:** A unit that is in a hex with enough garrison capacity for it is considered to be **garrisoned**, meaning it can acquire food and shelter as any other inhabitant. The unit only needs to be in the appropriate hex by the time the Upkeep phase comes around; it can travel freely any time before then. A garrisoned unit needs only its Wealth consumption paid during the Upkeep phase.

**Deployed:** A unit that is not in a hex with enough garrison capacity for its size is considered to be **deployed**. A deployed unit's consumption increases to Food and Goods in addition to Wealth, which must be paid with supplies it is carrying.

### Military Capacity

Your realm can maintain a number of units without any additional costs as long as the sum total of their size modifiers do not exceed your realm's total Population level. Exceeding the Population level does not prevent you from creating and maintaining more units. However, doing so increases your government upkeep costs by an amount of Wealth equal to how much the total size modifiers of all of your units exceed your realm's Population level, in addition to their base costs. The point limit of all hirelings except for Soldiers is reduced by the same amount. If your Development edict is set to "Free", reduce the percentage of Wealth allotted to developing hirelings except for Soldiers by the same amount.

## Equipment

Some equipment can be acquired at higher quality levels. Expert quality is 10 times the cost and grants a +1 quality bonus, master quality is 25 times and grants a +2 quality bonus, and legendary is 100 times and grants a +3 quality bonus. Weapons gain an enhancement bonus to attack rolls equal to their quality bonus. Armors gain an enhancement bonus to their armor bonus to UDV equal to their quality bonus.

Some equipment can be magical enchanted with enhancement bonuses which cost Magic capital. Enhancement bonuses can be exchanged for the equivalent magic properties. Multiply the Magic cost by the unit's size modifier. Weapons apply their enhancement bonus to attack rolls. Armors apply their enhancement bonus to their armor bonus to UDV.

Solo units (which have a +0 unit size modifier) do not use the mass combat equipment costs, instead they buy their equipment with gp as normal.

#### Table: Enhancement Bonus Costs

| Bonus | Cost |
|---|---|
| +1 | 2 Magic |
| +2 | 8 Magic |
| +3 | 18 Magic |
| +4 | 32 Magic |
| +5 | 50 Magic |
| +6 | 72 Magic |
| +7 | 98 Magic |
| +8 | 128 Magic |
| +9 | 162 Magic |
| +10 | 200 Magic |

### Armor

**Cost** Goods or Magic (see text).

Units hqve a default armor bonus to their UDV equal to +0. This can be increased by equipping your unit with armor and shields. This costs Goods equal to the total armor bonus squared times the unit's size modifier. The cost can be reduced by having the armor reduce the unit's speed. Each step of speed reduction reduces the armor cost by Goods equal to the total armor bonus times the unit's size modifier. An enhancement bonus can be added to the armor bonus by spending Magic equal to the squared total of the bonus. Some or all of the enhancement bonus can be exchanged for the equivalent magical armor traits.

### Banner of Chaos/Evil/Good/Law

**Cost** Magic equal to 4 times the unit's size modifier.

### Catapult

**Cost** 2 Goods.

A unit with one or more catapults gain a range attack that can inflict damage to a fortiication. Catapults are indirect fire weapons, meaning its projectiles can arc over obstacles. However, if the catapult's unit does not have line of sigh of the target, the attack targets at a random unit within the target zone, and the attack roll has a -20 penalty.

### Melee Weapons

**Cost** Goods or Magic (see text).

Units are always able to make melee attacks, even if it means they use their bare hands, and begin with an attack modifier of +0 on melee attacks. Better weapons can be equipped by the unit by spending Goods equal to the squared total of the desired attack modifier times the unit's size modifier. An enhancement bonus can be added to the unit's melee attack modifier by spending Magic equal to the squared total of the enhancement bonus. Some or all of the enhancement bonus can be exchanged for the equivalent melee magical weapon traits.

### Mounts

**Cost** Goods and Food equal to the mounts size modifier times the unit's size modifier (minimum Goods and Food equal to the unit's size modifier).

The unit becomes a mounted unit. The mounts must be creatures that are at least one lineage size larger than the troops' lineage size. The unit gains the movement types and speeds of the mounts, and can traverse up to two zones instead of one with the Move action. The unit gains a +1 edge on melee attacks against unmounted units. The unit's Food consumption increases by twice the mount's size modifier times the unit's size modifier (minimum Food equal to the unit's size modifier).

### Ranged Weapons

**Cost** Goods or Magic (see text).

Equip your unit with weapons that allow it to make ranged attacks. This costs Goods equal to the squared total number of zones the ranged weapons possess times the unit's size modifier. Default ranged weapons grant a +0 attack modifier to ranged attacks. This can be increased by spending additional Goods equal to the squared total of the attack modifier set times the unit's size modifier. An enhancement bonus can be added to the ranged weapons' attack modifier by spending Magic equal to the squared total of the bonus. Some or all of the enhancement bonus can be exchanged for the equivalent ranged magical weapon traits.

## Abilities

Types of abilities a unit can get depends on hireling type.

Number of abilities a unit can get depends on unit level. 2 levels = 1 ability.

### Deceptive Tactics (Scoundrels)

### Dirty Fighting (Scoundrels, Thugs)

### Enchanted Defenses (Mages, Priests)

As a standard action, your unit can grant an enhancement bonus equal to its level to the target unit's DV. This bonus lasts until start of your next turn.

### Gunslinger (Soldiers)

Your unit starts with simple firearms for free. Its ranged attack still requires Goods to be spent.

### Healing Magic

As a standard action, you grants healing points equal to 1 + your unit's size modifier to a target unit. At 3rd level, and every 2 levels after, increase the amount of points by 1 + the unit's size modifier again. Before making the target unit makes its Casualties save, it can spend the healing points to reduce its casualties by 1d4 troopers per point spent. Any leftover healing points can be used to heal 1 current wounded trooper per point.

### Inspire Courage (Performers)

As a standard action, your unit can grant a +1 morale bonus to the target unit's attack rolls and Morale checks. At 3rd level, and every 2 levels after, the bonus increases by +1. This bonus lasts until start of your next turn.

### Magical Blast (Mages)

Your unit can make magical melee or ranged attacks with a +1 bonus to attack roll. At 3rd level, and every 2 levels after, the bonus increases by +1. Choose the attack's energy type upon using this action: acid, cold, electricity, fire, force, or sonic.

### Sneak Attack (Thugs)

### Stealth (Scoundrels, Thugs)

### Tracking (Soldiers, Thugs)

## Tactics

Tactics allow a unit to perform special actions. A unit can learn one tactic per level. Tactics become part of the unit's institutional knowledge, even if there is only one trooper left. They are only lost when the unit is destroyed or disbanded.

### Aggressive

Gain +1 edge on all melee attack rolls. Attacks against you gain +1 edge. Increase your speed by one step. Incur +1 hindrance on your Fatigue save.

### Balanced

No benefits or drawbacks.

### Defensive

Attack rolls against you incur -10 penalty. You incur +1 hindrance on melee attack rolls. Reduce your speed by one step.

### Pincer

Your unit focuses on surrounding enemy units.

### Skirmish

Your unit focuses on moving and striking fast. When your unit uses the disengage action, enemy units gain no bonus to their morale check for having a higher speed than yours, and incur a -5 penalty for every step in speed lower than yours. Enemies that succeed on their Morale check gain +1 edge on their free melee attack roll against you.

## Traits

A unit gets the effect of a trait if all of its troops possess it and if it has a constant duration. An art can also apply the effects of a trait as long all of the unit's troops can perform it. The effect of the art must be either constant, or have a duration measured at least in hours (in which case, the unit only benefits from the trait in battle for its duration). Arts with shorter durations cannot apply as there is no guarantee that the troops can consistently execute them repeatedly during a round of mass combat.

### Incorporeal

An incorporeal unit ignores its target bonuses to UDV from nonmagical equipment. It also takes no damage from nonmagical attacks, while only taking half the number of casualties inflicted from magical attacks or attacks with magical weapons.

### Invisiblity

An invisible unit gains a +10 bonus to attack rolls against units that cannot see them. The unit also cannot be targeted by ranged attacks by units that cannot see them. Units engaged with an invisible unit reduce their casualties by 50% if they cannot see it.

### Mindless

A mindless unit does not possess a Morale score. Your unit automatically succeeds at all Morale checks except for its Fatigue check. Fatigue checks are treated as if the unit rolled a 10 on its check.

### Natural Armor

Your unit gains a +10 natural armor to UDV if all of its troops possess a +7 natural armor bonus or higher. At +17 natural armor bonus, and every +10 after, you unit's natural armor bonus to UDV increases by 10.

### Undead

cannot gain fatigue

no Food consumption

## Training

### Healing Arts

# Armies

Multiple units come together to form an army. An army is led by an **Army Commander**. An army commander can be a solo unit or be a leader of their own unit.

An army commander grants their ULM to morale checks of all units of the army.

# Mass Combat

## Analyze Unit

Once per turn, a unit leader can target another unit within line of sight to learn what is its current tactic or its active boon (but not both). To do so, your unit's leader makes a unit leader check against a DC equal to 10 + the target unit's ULM.

## Inflicting Damage

When the attack roll is equal or higher than the target's UDV, the target receives **damage** equal to a number of d6s equal to attacking unit's size modifier. Each degree of success adds additional d6s equal to the unit's level.

## Actions

Units has 3 beats per turn. Simple actions consume 1 beat, standard actions consume 2 beats, and greater actions consume 3 beats. They can also make one reaction per turn. Reaction are actions that are triggered by other actions or effects.

### Simple Actions

#### Change Tactics

Change your unit's current tactic. Changing tactics allows units engaged with you to make an opportunity attack. Make a DC 20 Morale check; increase the DC by 5 for each enemy unit making an opportunity attack beyond the first. On success, reduce the number of casualties from the opportunity attacks to half; on a critical success, you changed tactics in such good order that all opportunity attacks failed.

#### Disengage

Your unit tries to escape from all enemy units engaged with it. Any units currently engaged with yours may make a Morale check against your Disengage DC; any unit may choose to not make the check, automatically allowing you to disengage. Enemy units gain a +2 bonus to their check for every 5 ft. of speed above yours, and a -2 penalty for every 5 ft. under. If all of the enemy checks fail, your unit is no longer engaged. If only some are successful, your unit is no longer engaged, but enemy units that succeed may make a free melee attack against you. If all of the enemy checks succeed, you remain engaged with the attacking units and all engaged units may may make a free melee attack against you.

> **Disengage DC** = your UCR + your ULM + your Morale score

#### Move

The unit moves from one zone to another. You cannot use the move action if your unit is currently engaged with enemy units.

#### Resupply

A unit in its Camp zone can resupply its capital from the army's reserves. Alternatively, it can transfer supplies to another unit in any zone as long as they are both in it.

### Standard Actions

#### Charge

As a standard action, you use the Move action towards the zone of your target unit, then make a Melee Attack action against it with a +1 edge for that attack. All attacks against you gain a +1 edge until the start of your next turn. You must not be engaged to use this action.

#### Melee Attack

Your unit makes a melee attack against another unit in the same zone, and becomes engaged with it. If your unit is already engaged, then the attack is against one of the units you are engaged with of your choice.

*Engaged:* When a unit attacks another in melee, the units both become engaged even if the attack fails. Engaged units are caught up in the fighting, and cannot leave the zone until all opposing units are defeated, destroyed, or routed from the field, or until one side performs a successful Disengage or Retreat.

*Flanking:* Your unit flanks an enemy unit when it attacks the enemy that is already engaged with an ally unit. Your unit must be in the same zone as the enemy unit. Flanking grants your unit a +1 edge on its melee attack roll. Both your unit and your ally unit gain the flanking on the same enemy unit once you are both engaged with it.

#### Ranged Attack

If your unit has a ranged ability and is not currently engaged, then it can make a ranged attack against another unit up to a number of zones away limited by that ability. However, you incur a cumulative -2 penalty on ranged attack rolls for each zone away. Diagonal zones count as two zones away when calculating range. If your ranged attack consumes Goods as projectiles, your unit must be carrying enough Goods in their supply to make the attack.

### Greater Actions

#### Rest

Your unit spends the turn to rest, reducing their Fatigue DC by 5, and increase their morale score by 1. During this turn, you cannot make reactions, and attacks against you gain a +1 edge. When you take this action in your Camp zone, you can make the Resupply action for free at the same time.

#### Retreat

Your unit leaves the battlefield and the battle completely, and reappears in a valid adjacent hex. You can only take this action if your unit is in your army's Command or Camp zone and not currently engaged. If you are engaged, you can make a Disengage action for free as part of the Retreat, but failing to disengage cancels the Retreat and the rest of your turn. When your unit successfully retreats from the battle, your unit loses 1 Morale, and all allied units remaining in the battle reduce their Morale score by 2, while enemy units increase their Morale by 1. If your unit is led by the army's commander, allied units reduce their Morale score by 5 instead.

### Reactions

#### Brace Charge

As a reaction against an enemy unit charging you, your unit can brace for the charge as long as it has polearms. You gain a free melee attack against the charging unit.

## The Battlefield

Mass combat takes place on a battlefield covering an entire hex, and it is split into different zones.

Each separate side involved in the battle has the same set of zones.

### Engagement Zones

These are listed below, starting from furthest away from the center of the battle, to the nearest.

- **Camp:** This represents an army’s base of operations, which may be a temporary bivouac or a permanent fortification. Goods and limited use Magic capital are stored here. Units must enter this zone to resupply on capital.
- **Command:** This is the area where the army’s leader directs the flow of battle. The army's leader must be at least this far in order to issue commands to the rest of the army in the Rear and Front zones.
- **Rear:** This represents the back lines of an army on the field, with forces usually arrayed to engage in ranged combat.
- **Front:** This represents the front lines of any battle, where forces meet in close and brutal combat.

It is easier to visualize these zones as concentric circles with an army's Camp zone at the center. Each army has their own set of engagement zones, and if you want your forces to reach the enemy's Command zone, you must advance your army through your own Front zone into the enemy's Front zone, then through their Rear zone, and finally into their Command zone.

A unit that is within an army's Front zone (including its own army) can advance into the Front zone of any other army on the field of battle. However, if the unit moves deeper in such as the Rear or Command zones, it cannot move to another army's zone until it returns to the Front zone of the army it is in.

At the beginning of the battle, unless otherwise stated, all units begin either in the Camp, Command, or Rear zones, as decided by the army commander.

### Lateral Zones

The Command, Rear, and Front zones are laterally split along three columns: the left and right flanks on either side, and the center column in the middle. Camp zones do not have lateral zones.

- **Left Flank**: Your army's left flank is opposed by the enemy army's right.
- **Center Column:** The middle area of your army and is opposed by the enemy's center column
- **Right Flank:** Your army's right flank is opposed by the enemy's left.

### Altitude Zones

Similar to engagement zones, altitude zones are areas of the battlefield on a vertical axis, either above or below the surface. These zones exist only in relation to the standard ground or naval battle; battles that occur solely in the air or under water use only the standard battle zones and special elevation rules.

*Seafloor:* This is a special depth zone that applies whenever there is a submerged structure or terrain that is relevant to the course of a battle. The Seafloor can exist in the Abyssal, Deep or Shallow zones, depending on the depth of the water. A battle on the Seafloor works similarly to a second Surface depth level, in that creatures on the Seafloor and creatures in the adjoining Shallows or Deep can engage in ranged combat but cannot engage in melee unless either the swimming creatures come down to the Seafloor or the creatures on the Seafloor leave it and swim up into the open water.

*Deep:* Units in this depth zone cannot effectively see units on the surface or be seen by them, and are too far away to effectively attack or be attacked by them.

*Shallow:* Units in this depth zone are beyond the reach of melee attacks, except by other creatures that are also swimming in the shallows. However, they can still see creatures and vessels on the surface and can be seen themselves, though with some difficulty. Creatures in the shallows can attack with or be attacked by ranged attacks, though such attacks are made at a substantial penalty.

*Surface:* The zone represents the stable area that divides between the depths and altitudes, being either solid ground or the surface of water. Units in this zone are neither flying nor burrowing or diving, though they may be swimming upon the surface.

*Low Altitude:* Units in this altitude zone are well out of range of melee attacks but can attack with (and be attacked by) ordinary ranged attacks. Aerial units can attack at this range with dropped items with reasonable accuracy.

*Medium Altitude:* Units in this altitude zone fly on the fringes of the battle zone, able to attack with (and be attacked by) siege weapons, but otherwise out of reach of standard ranged attacks. Aerial units at this altitude can attack ground units with dropped items but with +1 hindrance on their attack roll.

*High Altitude:* Units in this altitude zone are too far away to effectively attack units on the ground or be attacked by them.

### Fortifications

#### Walls

Walls are tall and thick enough to allow units to stand and battle atop of. Units occupying a wall gains +20 to their UDV. Units cannot pass through a zone without first occupying the wall. Occupying units also gain a +1 edge on attacks rolls against non-occupying units. A wall has 2,000 hp and a DV of 100.

## Sequence

Each round of a battle lasts 1 hour, and is split into several phases.

1. **Tactical Phase**—This phase is the start of a new round of mass combat.
	- **Boons:** Each unit leader can decide which boon to make active. These choices must be made before the tactical initiative is determined.
	- **Tactics:** Each unit leader can decide what special tactics their unit will use to implement that strategy. These choices must be made before tactical initiative is determined.
	- **Tactical Initiative:** After selecting their boon and tactic, each unit leader makes their initiative check by rolling 1d20 + their ULM.
2. **Action Phase**—During this phase, each army commander chooses one unit to act in turn in the order determined by the Tactical Initiative.
	- Army units have 3 beats to spend on actions. See **Actions** for a list of actions a unit can execute.
	- Keep track of how many Casualties each unit receives, but do not deduct them from the unit's section just yet.
3. **Fatigue Phase**—After resolving Action phase, each unit then makes a **Fatigue** save which is a morale check against its Fatigue DC.
	- If the check fails, the unit gains 1 level of fatigue, and its Fatigue DC resets to 0.
	- On success, no fatigue is gained, but the unit's Fatigue DC increases by 5.
	- On a critical success, the unit gains a second wind which reduces its Fatigue DC by 5 instead of increasing it.
4. **Casualties Phase**—After the Fatigue phase, each unit applies its casualties score. Make a **Casualties save** which is morale check against a DC equal to 10 + 1/10 of the unit's casualties.
	- On success, half of the casualties are counted as wounded with the remainder counted as killed.
	- On a critical success, all casualties are counted as wounded.
	- On failure, all casualties are counted as killed. Every 1/10 of the unit's troops that is killed during this turn reduces the unit's Morale score by 1.
	- Each unit that is destroyed reduces the Morale score of all surviving allied units by 2.
	- Each enemy unit destroyed increases the opposing units' Morale by 1.
5. **Rout Phase**—After calculating casualties, each surviving unit makes a **Rout save** which is a morale check against DC 10.
	- If the check fails, the unit gains the **routed** condition and begins to rout from the battlefield, no longer follows its leader's orders.
	- A routed unit automatically spends its Action phase to perform the Retreat action, the Disengage action if currently engaged, or the Move action to get into a valid zone to retreat. It can no longer use the Melee or Ranged Attack actions or any reactions.
	- When the routed unit fails its Morale check to disengage, the free attack from the enemy unit gains a +1 edge on their attack roll, with a +5 bonus.
	- If a routed unit is still on the battlefield on the next turn, the unit reduced their Morale by 1 before the Action phase. However, it can attempt to rally back under control as a greater action by making a DC 10 morale check with a +1 hindrance.
	- On success, the unit loses the Routed condition and can act normally on its next turn; on a critical success, the unit regains 1 point of Morale. On a critical failure, the unit loses an additional point of Morale.

# Strategic Battle

When you have multiple armies engaged in multiple locations, it may be easier to play mass combat on a strategic level. Strategic battles play directly on the hex map, and not on the battlefield. Army units are not played individually, but are instead treated as parts of a whole.

An army is commanded by an army commander who is selected from its units' leaders. Use the chosen unit leader's ULM for the army as a whole.

Add troops from all units in the army together, and use the total to determine army's size modifier.

Each army uses the highest level among their units as their UL.

Army units are like equipment/feats, granting the army the ability to use their abilities. When using a unit's ability, use that unit's size modifier and level for any calculations. Only one ability per unit can be used per turn. However, when you use a unit's ability, you take a penalty equal to its size modifier to your army's attack rolls. For example, if your army includes a 9th-level company of mages, you can choose to use its Enchanted Defenses ability to gain a +9 to your army's UDV for one turn, but your army takes a -4 penalty to attack rolls.

Traits only apply to the army if more than half of its troops have the same trait.

Only the best equipment bonuses among all units are used.
