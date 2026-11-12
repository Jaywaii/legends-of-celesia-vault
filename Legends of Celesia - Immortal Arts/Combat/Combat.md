---
template: "article"
category: "[[Legends of Celesia - Immortal Arts]]"
state: "public"
wip: true
created: "2024-05-04"
updated: "2026-09-24"
worldanvil_url: "https://www.worldanvil.com/w/legends-of-celesia-jaywaii/a/combat-article-1"
type: "category"
---

# Combat

# Initiative

Initiative represents how quick you are to ready yourself for combat and determines your turn order.

- Base initiative roll is 1d20.
- Initiative rolls are modified by one attribute, known as the **initiative attribute**. By default, this is your Dexterity.
- Combatants take turns in descending order of their initiative rolls.
- Initiative groups are formed when allied combatants are adjacent to each other in the initiative order. Initiative groups are bordered by the start of the turn, the end of the turn, and when an enemy combatant's position in the turn order.
- Allies within an initiative group may freely arrange who takes their turn first among them. However, they cannot change their position before or after an enemy's position in the turn order.
- When combatants are already aware and ready for each other before the start of combat, everyone involved uses their Dexterity as their initiative attribute.
- When one side is hiding to ambush the other party, the hiding combatants roll Stealth checks as their initiative while the unaware combatants roll Perception checks as their initiative.
- Until a combatant makes their first turn, they are unaware and cannot make any reactions.

# Attack Roll

An attack roll represents your attempt to strike a target. Making an attack roll requires you to roll 1d20 and add your martial bonus and your attack attribute modifier. Other modifier may apply. See the **Attack** action further below for what uses you can perform with an attack roll.

## Martial Bonus

Martial bonus (MB) is a measure of your basic combat ability. You start with a martial bonus of +0. You can increase your martial bonus by taking the [[Martial Bonus Increase]] talent.

## Attack Attribute Modifier

Attack rolls require you to add the modifier of one attribute as its **attack attribute**. Which attribute is used depends on the type of attack you are making. See the **Attack** action further below to know which attribute each type of attack roll uses.

# Defence Value

Defence value (DV) is a measure of your ability to defend yourself and avoid getting injured.

- You add your Dexterity modifier to your DV as its **defence attribute**. Certain talents allow you to change which attribute you can use as your ADM.
- Armour that you wear as its armour bonus to your DV.
- **Touch DV** does not add your armour bonus. Attacks target your touch DV when they have effects that only require to touch you, and ignore the presence of armour.
- **Unaware DV** does not add your defence attribute unless it is a penalty. Attacks target your unaware DV when you are unable to react against the attack, such as being caught unaware or unable to dodge.

**Unaware Touch DV** refers to when you are both caught unaware and the attack ignores your armour, meaning you do not apply your defence attribute nor your armour bonus to your DV.

# Attribute Save Checks

When you are subjected to an unusual effect such as a magical explosion, a poison, or an environmental hazard, you will be asked to make an ability save check against the effect's DC to avoid or reduce the effect.

A **mental save check** requires you to roll 1d20 and add the lowest modifier between your mental attributes (Intelligence, Wisdom, and Charisma) and its save bonus.

# Stamina and Exhaustion

Stamina is a pool of points that represent how long your character can remain conscious and perform strenuous activities.

- Stamina pool can be increased by training.
- You gain a modifier to your Stamina pool equal to your current Constitution modifier times your level.
- Your maximum Stamina pool can never go below 1.
- Certain actions will cost Stamina points to perform.
- Certain effects inflict Stamina damage which will reduce your current Stamina points.
- Creatures with no Constitution modifier do not have a Stamina pool. They cannot use actions that use Stamina, and are immune to effects that target Stamina.

When you reach 0 stamina, you become [[Exhausted|exhausted]].

# Injuries

Damage inflicts injuries. Injuries damage body parts, each with their own effect.

- An attack roll's degree of success is also called an injury degree.
- The effects of injuries on multiple same body parts stack with each other unless otherwise stated.
- Injured body parts have four levels of severity. Each injury taken on the same body part increases the severity by one step. Unless otherwise noted, a higher severity injury inflicts the effects of lower severity injuries in addition to its own effects.
	1. Light
	2. Severe
	3. Crippled
	4. Destroyed: Unless otherwise noted, a destroyed body part cannot be healed naturally, and needs to be regenerated.
- Upon a successful attack, you inflict one injury. Each successful degree of your result allows you to inflict one additional injury on the target of your attack. These additional injuries can be inflicted upon the same body part or spread out to a different one in the same category. Extra injuries can also be spent to inflict another extra injury on a body part. For example, if you succeeded an attack roll at the target's DV with 2 successful degrees, you inflict one injury on one arm, and spend the extra injury degree to worsen the same arm's condition by one step or inflict an injury on another body part.
- If left untreated, an injured body part's condition risks worsening. Every day that a injury goes untreated, make a Constitution check at DC 20 for a light injury or a DC 30 for severe injury to not have it worsen. If you fail, increase the injury's severity by one step up to severe.
- Damaged body parts can be healed mundanely over time:
	- Each injury must first be treated with a Heal check. The DC starts at 15 for light injuries, and increases by 10 for each severity higher.
	- After being treated, the injury takes one week per severity level to fully recover. Until then, the injury's effect remains active.
- Some magical spells and techniques can instantly heal damaged body parts.
- Destroyed body parts cannot be healed mundanely. Some magical spells and techniques can regrow destroyed body parts. Some items can be used as prosthetics to replace destroyed body parts.
- TODO: what happens when no body parts left

## Area of Effect Damage

When you are caught in an area of effect that inflicts injuries, you roll an ability save check against the effects DC. Failing to beat the effect's DC results in you taking its full effects, with every degree of failure being treated as a degree of success when applying injuries. However, unlike an attack, you instead get to decide which of your body parts gets injured and how the effect's number of degrees are spent.

For example, if you are caught in the area of effect of a *fireball* spell with a DC 30 that inflicts 2 degrees of injuries, you roll a Dexterity save check. Your result is 19, so you take one additional injury degree. You can choose any combination of injured body parts and severity, such as gaining a light injury on both your arms and one leg, a light injury on your body and one arm, a severe injury on one arm and a light injury on your other arm, or suffer a destroyed leg.

## Fighting Against Larger Creatures

When you are fighting most tall creatures that are at least two size categories larger than you, you are unable to target their heads with melee attacks as long as you are on the same elevation. Long creatures need to be at least three size categories larger than you to have their heads out of reach. Every 5 feet increase to your reach or every 5 feet of elevation you are above your opponent's feet increases the number of size categories of how much larger your opponent needs to be for their head to be out of reach of you.

# Extremities

## Arm

Tentacles count at arms.

**Light:** You take a +1 hindrance on Acrobatics, Athletics, Beast Handling, Dance, Escape Artist, Musical Instrument, Thievery, and all craft skill checks.

**Severe:** You take a +1 hindrance on attack rolls made with weapons wielded or natural attacks attached with this arm.

**Crippling:** You drop anything being held with this arm. You cannot make any natural attack with this arm.

## Fin

**Light:** You take a +1 hindrance on Athletics checks when swimming with your fins.

**Severe:** Your swim speed using your fins is reduced by 1 size category.

**Crippling:** When all of your fins are crippled, you can no longer swim using fins.

## Leg

**Light:** You take a +1 hindrance on Acrobatics, Athletics, Dance, Ride, and Stealth checks.

**Severe:** You take a +1 hindrance on natural attacks attached with this leg. Your land speed is reduced by 1 size category and cannot charge or run. Trip attacks gain a +1 edge against you.

**Crippling:** When all of your legs are crippled, you immediately fall prone and cannot stand up. You cannot make any natural attack with this leg.

## Tail

**Light:** Your tail no longer provides an edge to Acrobatics checks.

**Severe:** You take a +1 hindrance on attack rolls on tail attacks and weapons and tools wielded with this tail. If you use your tail for movement, your speed is reduced by one size category.

**Crippling:** You take a +1 hindrance on Acrobatics checks. You cannot make tail attacks with this tail.

## Wing

**Light:** You take a +1 hindrance on Fly checks using your wings.

**Severe:** You take a +1 hindrance on wing attacks made with this wing. Your fly speed with your wings is reduced by one size category.

**Crippling:** You can no longer fly when you have less than 2 wings not crippled. If you are currently flying, you immediately fall. You cannot make wing attacks with this wing.

# Body

## Heart

**Light:** You take a -1 penalty to your Constitution modifier.

**Severe:** You take an additional -2 penalty to your Constitution modifier.

**Crippling:** You take an additional -3 penalty to your Constitution modifier.

**Destroyed:** When all of your hearts are destroyed, you die.

## Lungs

**Light:** You take a -1 penalty to your Constitution modifier.

**Severe:** You take one degree of [[Staggered|staggered]].

**Crippling:** When all of your lungs are crippled, you begin suffocating.

## Stomach

**Light:** You take one degree of [[Sickened|sickened]].

**Severe:** You take one degree of [[Staggered|staggered]].

**Crippling:**  You take one degree of [[Bleeding|bleeding]].

# Head

## Brain

**Light:** You take one degree of [[Stunned|stunned]].

**Severe:** You become [[Stupefied|stupefied]]. You can attempt a save at the start of your next turn to remove the condition, and at the start of every following turn until you succeed. The DC is equal to 30, and is reduced by 1 every round after.

**Crippling:** You fall unconscious.

**Destroyed:** Unless otherwise stated, you are killed when all of your heads are destroyed.

## Ear

**Light:** You take a +1 hindrance on Perception checks with an audio component.

**Severe:** In addition to the light injury effects, you take 1 level of sickened.

**Crippling:** You become deafened when all ears are crippled.

## Eye

**Light:** You take a +1 hindrance on Perception checks with a visual component.

**Severe:** You take a +1 hindrance on attack rolls unless you have the Blind-Fight feat.

**Crippling:** You become blind when all eyes are crippled.

## Mouth

**Light:** You take +1 hindrance on Deception, Diplomacy, and Intimidation checks.

**Severe:** You take a +1 hindrance on bite attacks with this mouth.

**Crippling:** You cannot make bite or breath weapon attacks with this mouth. You cannot speak with this mouth.

## Neck

**Light:** You are [[Frightened|frightened]] for 1 round.

**Severe:** You cannot speak with the mouth attached to this neck. You are unable to breathe; at the end of your turn, you can make a Constitution save against a DC equal to the attack roll's result until you succeed.

**Crippling:** You lose the swallow whole ability. You are unable to breathe; at the end of your turn, you can make a Constitution save against a DC equal to the attack roll's result + 10 until you succeed. Your bleed increases by 1.

**Destroyed:** Any head attached to a destroyed neck is not longer attached to the body. You are killed when are of your necks are destroyed.

## Nose

**Light:** You take a +1 hindrance on Perception and Survival checks with a scent component.

**Severe:** You lose the scent ability if you possessed it.

**Crippling:** You lose the scent ability if you possessed it.

**Destroyed:** You take a +1 hindrance on Diplomacy and Oratory checks, and edge on Intimidate checks.

> DESIGN NOTES: attackers always aim to kill, disable, or specifically hamper their opponent; if a body part does not inflict a condition or effect that immediately benefits the attacker in combat for any circumstances, then there is no point in targeting it, and thus no point in listing.

> DESIGN NOTES: When assigning a severity of a body part, consider the following:
>
>
>
>
> - how hard is it to hit the part in relation to the body as a whole?
> - how harmful is the effect of the damaged part?
> - is this body part overlapped by a larger one?

# Critical Hits and Misses

A natural 20 on an attack roll is a critical hit. If the attack roll result is still less than the target's DV, the attack deals a minor injury instead of being unsuccessful. Otherwise, the critical hit adds another degree and applies the weapon's critical effect (see Weapons).

Some weapons have an increased critical range. A natural roll on that number in that range threatens a critical hit, but does not automatically hit if the d20 does not land on a 20. Natural rolls in the rest of the critical range only threaten if the result is a successful hit.

A natural 1 on an attack roll is a critical miss, and decreases the severity of the inflicted injury by one step. If the injury would have been a minor one, then no injury is inflicted. If the attack roll result is less than the target's DV, then the attacker loses their grip on their weapon and drops it. If the attack was made with a natural weapon, the attacker cannot use that natural attack until the end of their next turn. If the attack was a spell, the spell fizzles without any effects and its cooldown is increased by 1 round.

# Maneuvers

Skills that are used for maneuvers require:

- the target opponent is within reach
- roll the skill check and add your martial bonus to the result
- if the result is equal or greater than the target's Touch DV, the maneuver is a success
- maneuvers provoke from the target if you are untrained with the skill

# Size Differences

- Injuries that you inflict with weapon attacks are reduced by 1 degree for each size the target is larger than you, and are increased by 1 degree for each size the target is smaller than you.
- You gain a +1 size bonus on maneuver attack rolls against a target one size category smaller than you, and a -1 penalty against a target one size category larger than you. Double the bonus and penalty for every size category step away from your size.

# Positioning

# Cover

An enemy combatant takes a +1 hindrance on attack rolls against you when you have cover between the both of you.

## Total Cover

An enemy combatant takes a +2 hindrance on attack rolls against you when you have total cover between the both of you.

# Flanking

When you and an ally are adjacent to the same enemy on opposing sides or corners and you are both threatening, you both gain +1 edge on melee attack rolls against that enemy.

# Rounds and Actions

Combat is divided into rounds lasting 6 seconds.

During each round, each participant has a turn.

During their turn, a participant has 3 beats and one reaction.

### Table: Action Beats

| Action | Number of Beats |
|---|---|
| Free action | 0 beats, but only once per turn. |
| Simple action | 1 beat. |
| Standard action | 2 beats. |
| Greater action | 3 beats. |
| Reaction | usable only when triggered by specific circumstances. |
| Full-round action | all beats and reactions for that turn until the start of the next turn. |

> DESIGN NOTE: all full-round actions should have bonus or scaling effects if the participant has more than 3 beats during their turn (such as being under the effects of a haste effect).

# Actions

# Simple Actions

## Attack

Attacks require at least one target, and make an attack roll or skill check against the target's DV to determine success or failure.

#### Multiple Attacks

When you use the same type of attack against the same foe during your turn, your foe becomes more adept at defending themselves. You take a number of hindrances on your attack roll equal to the number of times you have already used this type of attack on this foe.

The different types of attacks are: melee, ranged, disarm, grapple, shove, sunder, trick, trip, multiweapon.

### Maneuver Attack

Maneuvers are special melee attacks that apply a specific effect instead of inflicting injuries. Each type of maneuver attack is associated with a skill, and you make a skill check in place of an attack roll.

**Disarm** ([[Acrobatics]])

**Grapple** ([[Athletics]])

**Shove** ([[Athletics]])

**Sunder** ([[Athletics]])

**Trick** ([[Thievery]])

**Trip** ([[Acrobatics]])

### Melee Attack

Your target must be within your melee reach for you to make a melee attack against them. Use either your Strength or your Dexterity as your attack attribute.

#### Cleave

After landing a successful melee attack on your opponent, you may spend 1 stamina as a free action to continue your attack into another opponent that is adjacent to the first and within your reach. Doing so opens up your defences, and you become [[Off-Guarded|off-guarded]] until the start of your next turn.

#### Lunge

You may spend 1 stamina as a free action to increase your next melee attack to increase your reach by 5 feet. Doing so opens up your defences, and you become [[Off-Guarded|off-guarded]] until the start of your next turn. You must make this decision before you make your attack roll.

#### Power Attack

As a free action as part of a melee attack, you can spend an amount of stamina up to your martial bonus to gain a +2 bonus to your attack roll for each point of stamina spent. You must make this decision before you make your attack roll.

#### Reckless Attack

As a free action as part of a melee attack, you can increase the injury inflicted by a successful attack by 1 degree for every 2 stamina spent. Doing so opens up your defences, and you become [[Off-Guarded|off-guarded]] until the start of your next turn. You must make this decision before you make your attack roll.

### Ranged Attack

You take a number of disadvantages on your ranged attack roll equal to the distance of your target from you divided by your attack's range increment. Use either your Dexterity or Wisdom as your attack attribute.

When making a ranged attack at an enemy engaged in melee with an ally, you take a +1 hindrance on your ranged attack roll as you try not to hit your ally unless your target is two or more size categories larger than your ally or is 10 or more feet away from them.

Each creature of the same size as your target that is standing in the path of your projectile between you and your target provides a cumulative +2 bonus to your target's DV. The target's bonus increases by 2 for every size category larger.

#### Deadly Aim

As a free action as part of a ranged attack, you can gain a +2 bonus to your attack roll for each point of stamina spent. You must make this decision before you make your attack roll.

#### Rapid Shot

If you have a ranged weapon that you can reload as a free action or are able to draw thrown weapons as a free action, you can perform multiple ranged attacks with one attack action with a +1 hindrance on each attack roll for each attack beyond the first. You must make this decision before you make your attack.

#### Throw

You can throw an object at a target as a ranged attack. You may use Strength as your attack attribute instead of those normally used for ranged attacks. By default, thrown objects have a range increment of 10 feet, but weapons with the Thrown trait may have longer increments. For every +1 Strength bonus you possess, increase your thrown object's range increment by 5 feet.

Objects that hit the target land in the same square as the target.

When you miss your target, roll 1d8. Starting from the square adjacent to the target that is nearest towards you and going clockwise, count the squares around the target to your roll's result to determine a direction away from the target. From that square, count a number of squares away from the target in that direction equal to the number of range increments between you and your target. Your object lands in that final square unless an obstacle blocks its path.

### Multiweapon Fighting

When you wield more than one weapon, you can spend a simple action to attack with each weapon. You can do this with just melee, natural, or ranged weapons, or a mix of them as long as you have enough appendages to wield them all at once and attack with them. When you choose this attack, you make an attack roll for each weapon with a -2 penalty for each weapon you are using as part of this action. You must make this decision before you attack.

## Careful Step

You can move 5 feet without provoking from moving out of a threatened square. You cannot make a careful step when your speed is 5 feet or less.

## Command Companion

Command your animal companion, eidolon, familiar, or summoned creature. The target of your command has 2 beats per command.

## Defend

You focus on defending yourself. Add a dodge bonus to your DV and a circumstance bonus to Block attack rolls both equal to your martial bonus until the start of your next turn. You cannot use the Attack action or Reactive Attack reaction until the start of your next turn.

## Draw of Sheathe a Weapon

You draw or sheath a weapon with a free hand. When your martial bonus is +1 or higher, you can draw or sheath a weapon as part of a Move action (see **Move Your Speed**).

## Move Your Speed (provoke)

Upon selecting this action, choose a type of movement you possess. For the rest of your turn, you can move a number of feet up to that movement's speed. This movement does not need to be continuous, but each time you stop and move again, you provoke again. When you move out of a square that is threatened by an opponent, you provoke from this opponent, but not for moving from any other squares the opponent threatens as long as this is one contiguous movement.

## Ready Shield

When you wield one or more shields, you can spend a simple action to grant all of your shields' bonuses to your DV until the start of your next turn. Unless otherwise stated, you cannot use your shields for any other action other than the Block reaction until the start of your next turn.

# Standard Actions

Standard actions require you to spend 2 beats.

## Reload Cross of Your Size of Smaller (provoke)

You reload a crossbow for your size or smaller.

## Charge

Charge is a special attack that combines movement to deliver a more powerful attack. However, there are some drawback and restrictions on your movement.

### Movement

You may move up to twice your speed towards your opponent. This movement provokes. You need to move at least 10 feet in order to perform a charge. The movement of your charge must come before your attack, and not after.

You must travel in an unobstructed straight line. Obstacles that prevent charges include conscious creatures (including allies), helpless creatures and bodies that are at least one size smaller than you or larger, and objects that occupy at least a square. You cannot charge on difficult terrain. Your movement must end in the closest square to your starting location from which you can attack your enemy.

You can incorporate a jump in your movement, but you can no longer move as part of your charge upon landing.

You can incorporate swinging from a rope or similar tool as part of your movement. You can attack at any point during the swing, but your charge and its benefits end upon your first attack or when you land, whichever comes first.

Charging throws off your balance, and you become [[Off-Guarded|off-guarded]] until the start of your next turn.

### Attacking

At the end of your charge movement, you gain a +1 edge on all attacks until you move again or the end of your current turn, whichever comes first.

Your first attack must be made against the target of your charge, but if you are able to make multiple attacks during your turn, you can attack other targets  with the benefits of your charge as long as you do not move from the square where you ended your charge until the end of your turn.

# Greater Actions

Greater actions require you to spend 3 beats.

## Reload Larger Crossbow (provoke) You reload a crossbow that is one size larger than you. Increase the action by 1 beat for each size larger.

# Round Actions

Round actions start at the start of your turn, and end only at the start of your next turn. You must spend all 3 beats and cannot use any reactions until the action has ended. If you have more than 3 beats during your turn, your extra beats often grants additional bonuses.

# Free Actions

Free actions do not cost any beats. You can only perform free actions during your turn, but theoretically, you can take as many free actions as you want, up to what the GM judges can fit inside 6 seconds.

## Fighting Defensively

When you choose to fight defensively, you can gain a +2 bonus to DV for each -1 penalty to all attack rolls you are willing to take. The bonus and the penalty both lasts until the start of your next turn. You must make this decision only once on your turn before you make any attack rolls.

# Reactions

Reactions do not cost any beats, but can only be performed in response to specific triggers.

You cannot perform reactions when you are [[Off-Guarded|off-guarded]].

You have 1 reaction per turn. Talents may increase the number of reactions per turn. You regain your reactions at the start of your next turn.

When you use up all of your reactions, you may spend 1 stamina to perform a reaction. Each extra reaction cost 1 more point of stamina than the previous, so your first extra reaction costs 1 stamina, your second costs 2 stamina, your third costs 3 stamina, and so on.

Reactions occur after their trigger starts, but before the trigger's effects are resolved.

You can perform only one reaction against a single trigger.

## Block

Blocking also includes parrying, and can be performed with a shield, a weapon, or a natural weapon. After an opponent confirms their attack roll against you, you can spend a reaction to make an opposed attack roll with your blocking instrument, applying any other valid modifiers to attack rolls as normal. If your result exceeds the opponent's, you reduce their damage by one injury plus one additional injury for each successful degree. For each block reaction you have taken this turn, you take a +1 hindrance on attack rolls with that shield or weapon used until the end of your next turn.

You may also block an attack against an ally if they are within your reach. However, you become [[Off-Guarded|off-guarded]] until the start of your next turn.

You cannot block a critical hit or a touch attack.

## Reactive Attack

You can spend a reaction to perform an attack action against an opponent that commits an action that provokes you.

## Redirect Injury

You can spend a reaction to double your DAM to DV in response to an attack roll that would succeed against you. If your new DV beats the attack roll, you can choose which body part gets targeted instead of the opponent choosing.

# GM-Specific Actions

Here are optional actions GMs can have NPCs use in order to run combat encounters faster

## Aid Ally

Allied combatants within an initiative group can grant an the ally in the same initiative group a +1 bonus per action given up for that turn. The bonus per action given up increases by 1 at 6th-level and every 5 levels after. These bonuses last until the start of the next turn of this initiative group. Bonuses from multiple allies stack when they target the same ally and effect.

- **Attack:** The ally gains the bonus to one attack roll.
- **Defence:** the ally gains the bonus to their DV.
- **Saves:** The ally gains the bonus one attribute save. The combatant granting the bonus chooses which attribute the bonus is applied to.
- **DC:** The ally adds the aid bonus to the DC of one

## Child Articles

- [[Acid Injury]]
- [[Cold Injury]]
- [[Electric Injury]]
- [[Fire Injury]]
- [[Sonic Injury]]
