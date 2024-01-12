# Technology Guide

This section attempts to convert all the supplementary material to the Iron Gods adventure path that still need to be included to actually run it within 2e. Most of it will be entries from the *[Technology Guide](https://paizo.com/products/btpy98i0?Pathfinder-Campaign-Setting-Technology-Guide)* but some may be homebrewed extras to help with the conversion.

Please note that there will be **MAJOR SWEEPING CHANGES** to many items.

## Looking for Items?

This document covers general concepts and mechanics for an adventure in Numeria. For individual item lists, please check out the following:

* [Weapons](Weapons/README.md)
* [Armor](Armor/README.md)
* [Pharmaceuticals](Pharmaceuticals/README.md)
* [Gear](Gear/README.md)
* [Cybertech](Cybertech/README.md)

## New Traits

To see an overview of the traits that were added, please click [here](/Traits/README.md).

## Table of Contents

* [Silverdisks](#silverdisks)
* [New Actions](#new-actions)
  * [Identify Technology](#identify-technology)
  * [Identify Pharmaceutical](#identify-pharmaceutical)
* [New Feats](#new-feats)
  * [Craft Cybernetics](#craft-cybernetics)
  * [Scavenger's Luck](#scavengers-luck)
* [New Spells](#new-spells)
  * [Antitech Field](#antitech-field)
  * [Detect Radiation](#detect-radiation)
  * [Discharge](#discharge)
  * [Irradiate](#irradiate)
  * [Memory of Function](#memory-of-function)
  * [Rebuke Technology](#rebuke-technology)
  * [Recharge](#recharge)
  * [Remove Radioactivity](#remove-radioactivity)
  * [Technomancy](#technomancy)
* [Color Grading](#color-grading)
* [Technological Radiation](#technological-radiation)
* [Numerian Fluids](#numerian-fluids)
* [Skymetals](#skymetals)
  * [Glaucite](#glaucite)

## Silverdisks

Silverdisks are [batteries^](Gear/README.md#battery) that no longer function. They are often used as a secondary currency in Numeria.

One silverdisk is worth 1 gp.

## New Actions

### Identify Technology

**Traits:** Concentrate, Exploration, Secret

You can identify the nature of a technological item with 10 minutes of testing. If your attempt is interrupted in any way, you must start over. Attempt a Engineering Lore check. You may instead make Crafting check at a -5 penalty.

If you have a [zipstick^](Gear/README.md#zipstick) on hand you can expend a use to gain a +2 item bonus to your check.

The DC of the item being identified is the same as its listed Craft DC.

* **Success** You identify the item and the means of activating it.
* **Failure** You fail to identify the item, but can try again.
* **Critical Failure** You misidentify the item as another item of the GM's choice.

### Identify Pharmaceutical

**Traits:** Concentrate, Exploration, Secret

**Requirements:** You have alchemist's tools.

You can identify the nature of a pharmaceutical item with 10 minutes of testing. If your attempt is interrupted in any way, you must start over. Attempt a Medicine check. You may instead make Crafting check at a -5 penalty.

The DC of the item being identified is the same as its listed Craft DC.

* **Success** You identify the item and the means of activating it.
* **Failure** You fail to identify the item, but can try again.
* **Critical Failure** You misidentify the item as another item of the GM's choice.

## New Feats

### Craft Cybernetics

**Level:** 9

**Traits:** Rare, General, Skill

**Prerequisites:** master in Medicine, expert in Engineering Lore

You can use the Craft activity to create cybernetic items, though many have additional requirements. Selecting this feat immediately gives you the formula of 1 [cybertech^](Cybertech/) item.

You also gain access to the [Install Cybertech^](Cybertech/README.md#install-cybertech) and [Remove Cybertech^](Cybertech/README.md#remove-cybertech) activities.

### Scavenger's Luck

**Level:** 1

**Traits:** Rare, General, Skill

**Prerequisites:** trained in Crafting

When your check for using a piece of timeworn technology results in a failure or critical failure, you can roll again. You must take the second result, even if it’s worse.

## New Spells

### Antitech Field

**Rank** 7

**Traits** Concentration, Manipulate

**Traditions** arcane, primal

**Cast** three actions

**Area** 10-foot emanation, which affects you

**Duration** sustained up to 1 minute

You repel all technology from the target area, preventing technological items and creatures from functioning. Energy and laser weapons can't penetrate the area, technological items cease to function within it, and no one inside can use technological items. Technological items resume to function the moment they pass outside the field. Invested technological items cease to function, but they remain invested and resume functioning when they exit the field. Technological items twice the level as the antitech field's rank and higher overcome its effects, and can even be used by a creature within the field.

The field disrupts only powered technology, so pharmaceuticals still function. A chainsaw could still be swung like an axe, but cannot be Activated and a grenade detonated outside of the field can still affect a creature within the field. Cybertech ceases to function within the field. Technologically created creatures (such as robots) must attempt a Fortitude saving throw when within the field. Androids and automatons are treated as technologically created creatures for the purposes of this spell, but instead receive a success on a failure or a critical failure.

**Critical Success** The creature can function normally.

**Success** The creature is slowed 1 while within the field.

**Failure** The creature is slowed 2 while within the field.

**Critical Failure** The creature is stunned while within the field.

### Detect Radiation

**Rank** 2

**Traits** Concentrate, Detection, Manipulate

**Traditions** arcane, divine, occult, primal

**Cast** two actions

**Duration** 10 minutes

You can see radiation and its intensity. This spell can penetrate barriers, but 3 feet of dirt or wood, 1 foot of stone, 1 inch of common metal, or a sheet of lead blocks it - but radiation can seep into the barriers and eventually make them radioactive - and thus visible.

**Heightened (5th)** The spell's duration is extended to 8 hours.

### Discharge

**Rank** 3

**Traits** Concentrate, Electricity, Manipulate

**Traditions** arcane, primal

**Cast** two actions

**Range** 30 feet; **Targets** 1 creature or object with the [Tech^](/Traits/README.md#tech) trait

**Defense** basic Will

You depower an item with the tech trait or disrupt a creature with the tech trait, with effects based on choosing creature or object.
  * **Creature** If your target is a creature with the tech trait, it attempts a Will Save. On a failure, the creature is glitching 1; On a critical failure, the creature is glitching 2.
  * **Object** If you target an attended object, the creature that has the object attempts a Will save. On a failure, the object loses half of its maximum charges. On a critical failure, or if you target an unattended object, the object loses all its remaining charges.

### Irradiate

**Rank** 3

**Traits** Concentrate, Manipulate, Radiation, Poison

**Traditions** arcane, divine, occult, primal

**Cast** two actions

**Range** 150 feet; **Area** 10-foot burst

**Defense** Fortitude

You flood the area with a sudden burst of dangerous radiation. Creatures in the area who fail their save are affected as if they entered an area of low intensity radiation - becoming drained 1 and afflicted with stage 1 of [Radiation Poisoning^](/Technology%20Guide/README.md#radiation-poisoning).

While the DC for the saving throw is based on the spellcaster, the DC for recovering from Radiation Poisoning is determined by the intensity of radiation affecting the creature.

**Heightened (5th)** The area of the spell increases to a 20-foot burst, with the central 10-foot burst affecting creatures that fail the saving throw as if they entered an area of medium intensity radiation - becoming drained 2 and afflicted with stage 2 of Radiation Poisoning, and the next 10 feet as low intensity radiation.

**Heightened (7th)** The area of the spell increases to a 30-foot burst, with the central 10-foot burst affecting creatures that fail the saving throw as if they entered an area of high intensity radiation - becoming drained 3 and afflicted with stage 3 of Radiation Poisoning, and the next 10 feet as medium intensity radiation, and the last 10 feet as low intensity radiation.

**Heightened (9th)** The area of the spell increases to a 40-foot burst, with the central 10-foot burst affecting creatures that fail the saving throw as if they entered an area of severe intensity radiation - becoming drained 4 and afflicted with stage 5 of Radiation Poisoning, and the next 10 feet as high intensity radiation, and the next 10 feet as medium intensity radiation, and the last 10 feet as low intensity radiation.

### Memory of Function

**Rank** 7

**Traits** Concentration, Manipulation

**Traditions** arcane, occult

**Cast** one action

**Range** touch; **Targets** one object or creature with the construct trait touched

You restore a broken object or damaged construct to a functional state, as if it were new and intact. Any pieces missing from the object or construct remain missing. Significant missing pieces may prevent proper functioning. If the object uses charges, the object becomes fully charged. A timeworn object becomes fully charged, but doesn’t lose the timeworn trait (this spell is one of the few ways a timeworn item can be recharged). For 1 hour after this spell is cast on a timeworn object, that object is treated as if it does not have the glitching condition. Other consumables such as ammunition are not restored.

When this spell is cast upon a damaged construct, all damage dealt to that construct is restored. When this spell is cast upon a destroyed construct, it is restored to full functionality and full hit points, provided no significant portion of the destroyed construct (such as an entire limb) is missing. Constructs brought back in this fashion regain their memories up to the moment of their destruction and have no particular inclination to serve the caster.

If you attempt to cast this spell on an object or a construct that has been destroyed for more than 100 years, the spell fails.

### Rebuke Technology

**Rank** 4

**Traits** Concentration, Incapacitation, Manipulation

**Traditions** arcane, primal

**Cast** two actions

**Range** 120 feet; **Targets** 1 unattended technological object or technological creature

**Defense** Fortitude; **Duration** sustained up to 1 minute

You shroud the target technological object or creature with magical energy. It has to make a Fortitude saving throw.
    
**Critical Success** The target is unaffected and if the target was deactivated, it may activate at the GM's discretion.

**Success** The target creature or object is glitching 1 as it attempts to shake off the effect.

**Failure** The target is glitching 2. The target creature is powered down and is unconscious. The target object is deactivated and any attempts to activate it fail. When the spell is sustained, the target can attempt another Fortitude saving throw.

**Critical Failure** As failure, but the glitching condition has a value of 3, and if the target is an object, it loses 2 charges worth of power if applicable

### Recharge

**Rank** 3

**Traits** Electricity, Manipulate

**Traditions** arcane, divine, occult

**Cast** one action

**Range** touch; **Targets** 1 [battery^](/Technology%20Guide/Gear#battery) or technological item that is powered by batteries

You attempt to restore power to a battery or a powered device. Declare how many charges you wish to restore and make a skill check based on your spellcasting tradition (Arcana for arcane, Religion for divine, and Occultism for occult). The DC for the check is dependent on how many charges you declared to restore.

   * **DC 15** - You restore 2 charges.
   * **DC 20** - You restore 3 charges.
   * **DC 30** - You restore 4 charges.
   * **DC 40** - You restore 5 charges.

   **Critical Success** The device regains the charges you declared, as well as an extra additional charge, up to the maximum capacity the device can withhold.
     
   **Success** The device regains the charges you declared up to the maximum capacity the device can withhold.
   
   **Failure** The device regains half as many charges as declared up to the maximum capacity the device can withhold.
   
   **Critical Failure** The device is overcharged and takes 8d4 electricity damage. This damage ignores hardness. If the target was a battery it is instantly destroyed.

Regardless of the result, the device becomes immune to further castings of recharge for the next hour; it can still be recharged via batteries or other technological means.

Attempting to cast this spell on a device that is fully charged automatically critically fails. Recharging batteries via this spell incurs the same chance for destruction as one would recharging it via a generator - on a DC 4 flat check, the battery is destroyed.

**Heightened (+2)** The amount of charges you restore at each DC increases by 1.

Recharge now works similarly to [Treat Wounds](https://2e.aonprd.com/Actions.aspx?ID=57), where it's possible to gamble with the amount recharged, but without penalising the player for "doing too well."

### Remove Radioactivity

**Rank** 8

**Traits** Concentration, Healing, Manipulate

**Traditions** divine, occult, primal

**Cast** two actions

**Range** 30 feet; **Targets** 1 creature or object

You attempt a counteract check against a source of radiation. Counteracting the target renders the source of radiation inert - it no longer emits radiation and depletes all of its charges if it had any remaining.

This spell has been simplified to just that of the greater version as the effects of radiation can both be alleviated with *[neutralize poison](https://2e.aonprd.com/Spells.aspx?ID=207)* and *[restoration](https://2e.aonprd.com/Spells.aspx?ID=258)*

### Technomancy

**Rank** 1

**Traits** Concentrate, Detection, Manipulate

**Traditions** arcane, occult

**Cast** two actions

**Area** 30-foot emanation

You send out a pulse that registers the existence of a technological object. You receive no information beyond the presence or absence of an object. You can choose to ignore technology you're fully aware of, such as the ones on you and your allies.

**Heightened (4th)** You're able to pinpoint the source of the highest level technological object. Like for an imprecise sense, you don't learn the exact location, but can narrow down the source to within a 5-foot cube (or nearest if larger than that).

## Color Grading

Technology with various grades sometimes use a color-based grading scale. The mapping is as follows.

Color Grade | Level
------------|------
Brown       | 1
Black       | 3
White       | 5
Gray        | 7
Green       | 9
Red         | 11
Blue        | 13
Orange      | 15
Prismatic   | 17

## Technological Radiation

Technological radiation is a mostly invisible hazard that suffuses a spherical area and can extend into objects. Each area of radiation has an associated intensity stepping up from Low to Medium to High to Severe, and the areas work the same way as listed on *[Technology Guide, pg. 55-56](https://www.d20pfsrd.com/gamemastering/traps-hazards-and-special-terrains/hazards/environmental-hazards/radiation/)*.

Whenever a creature enters or starts their turn in an area of technological radiation, they make a single Fortitude save. On a failure, they become drained and afflicted with Radiation Poisoning, with the value and stage dependent on the intensity of radiation they were exposed to. This drained condition cannot be lowered by a full-night's rest.

Intensity | Fort DC | Drained value | Radiation Poisoning
----------|---------|---------------|--------------------
Low       | 20      | 1             | Stage 1
Medium    | 25      | 2             | Stage 2
High      | 30      | 3             | Stage 3
Severe    | 35      | 4             | Stage 5

### Radiation Poisoning

**Traits** Poison, Radiation

**Saving Throw** see table above; **Onset** 1 day; **Stage 1** enfeebled 1 (1 day); **Stage 2** enfeebled 2 (1 day); **Stage 3** enfeebled 3 (1 day); **Stage 4** enfeebled 4 (1 day); **Stage 5** 12d10 poison damage and enfeebled 5 (1 day)

## Numerian Fluids

This is a section from *[Numeria, Land of Fallen Stars, pg. 28-29](https://paizo.com/products/btpy978l?Pathfinder-Campaign-Setting-Numeria-Land-of-Fallen-Stars)* that can come up in this adventure path.

**Traits** Rare, Alchemical, Drug, Ingested

**Level** 5 **Identify Alchemy DC** 25 (20 for level 5, +5 for rarity)

**Saving Throw** DC 20 Fortitude; **Stage 1** +2 item bonus to Perception and a side effect on the Numberian Fluids table (see below) (1 hours); **Stage 2** fascinated and stupefied 2 (6 hours);

d%    | Result
------|-------
01    | The drinker's cellular structure breaks down, and their flesh dissolves off their bones. The victim dies in 1 round unless the *[regenerate](http://2e.aonprd.com/Spells.aspx?ID=248)* or *[wish](http://2e.aonprd.com/Spells.aspx?ID=377)* spell is administered.
02-04 | The drinker permanently loses a random sense (roll 1d4: 1 - hearing, 2 - sight, 3 - smell, 4 - taste). A *[regenerate](http://2e.aonprd.com/Spells.aspx?ID=248)* spell can restore it.
05-07 | The drinker ages 2d10 years.
08-10 | The drinker becomes sickened 6 and gains another side effect on this table. Reroll any result less than 15.
11-15 | The drinker becomes drained 2.
16-20 | The drinker becomes stupefied 4 and loses the ability to speak or write for 1 day.
21-30 | The drinker becomes confused.
31-35 | The drinker becomes enfeebled 2 and clumsy 2
36-40 | The drinker becomes unconscious.
41-50 | The drinker becomes stupefied 1.
51-60 | The drinker becomes sickened 1.
61-65 | The drinker becomes fascinated. Any attempts to disrupt the fascination causes the drinker to become confused.
66-70 | The drinker exudes an unpleasant stench (aura, olfactory). A creature entering this aura must succeed at a DC 20 Fortitude save or be sickened 1 (plus slowed 1 for the same duration on a critical failure).
71-75 | The drinker gains increased empathy with mechanical minds. It gains a +10 item bonus on Deception, Diplomacy and Perception checks against androids and robots, but a -5 item penalty against anyone else.
76-80 | The drinker becomes healed by a random energy type (acid, cold, fire, electricity or sonic) instead of harmed, but being healed this way inflicts stunned 1.
81-85 | The drinker's skin thickens into armor-like plates. This gives a +2 bonus to AC but they become clumsy 2. It takes 1d4 months for the skin to slough off.
86-90 | Roll twice. If the first result is below 20, add 20 to the result. If the second result is above 80, deduct 20 from the result. If it's the same roll twice, apply it once.
91-92 | The drinker gains fast healing 5 for 24 hours, but must consume twice as much food and water as normal.
93-94 | The drinker gains a +6 status bonus to a random ability score for the next 2d4 days.
95-96 | The drinker gains telepathy with a range of 100 feet for 2d4 days.
97    | The drinker gains the ability to see possible futures a few seconds ahead for 24 hours. They become fascinated. When they perform an attack roll, a skill check or a saving throw, they may declare to use the vision's guidance to reroll and take the better result. This ends the fascinated condition and the visions.
98    | The drinker becomes 1d6 years younger.
99    | The drinker foresees their death in a cryptic and disjointed vision. The next time an effect would cause their death, they can take an extra action just before they die.
100   | Roll on the exceptional Numerian Fluid Effects table below for a permanent effect!

d10 | Result
----|-------
1   | The drinker no longer dies of old age.
2   | The drinker permanently becomes under the effect of a mutagen that suits their personality.
3   | The drinker gains the ability to become incorporeal for 1d4 rounds as an action by becoming drained 1. Coming out of a phase while inside of a solid object is instantly fatal.
4   | The drinker gains either scent or echolocation as an imprecise sense of 30 feet.
5   | The drinker grows a pair of batlike wings that grant a fly speed of 25 feet.
6   | The drinker gains a +2 untyped bonus to a random ability score.
7   | The drinker's body begins to produce its own Numerian fluids, save for the fact it cannot produce exceptional effects (reroll rolls of 100).
8   | The drinker grows a metal mesh surrounding their skin which grants electricity resistance 10.
9   | The drinker's body constantly emits as much light as a hooded lantern. They may use a concentrate sustained action to suppress this effect.
10  | For 24 hours, the drinker falls into a coma and cannot be awakened. During this time, they dream of living an entire lifetime on a different planet in an alien body. The drinker gains the Bardic Lore skill at Master proficiency when they wake.

## Skymetals

Most skymetals have now been converted to second edition with the release of *[Pathfinder Lost Omens: The Grand Bazaar](https://paizo.com/products/btq027kc)*.

### Glaucite

Glaucite is an alloy of adamantine and steel that's 1.5x as heavy as steel but not much better than it. Glaucite is what the *Divinity*'s hull is made from, which is why scavengers leave these ships mostly in tact. For the sake of determining Hardness and HP for objects (likely structures if you're looking here), glaucite performs the same as steel.

Item       | Level | Hardness | HP | BT
-----------|-------|----------|----|----
Thin item  | 1     | 5        | 20 | 10
Item       | 1     | 9        | 36 | 18
Structure  | 1     | 18       | 72 | 36
