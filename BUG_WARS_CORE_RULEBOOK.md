# BUG WARS
## Core Rulebook
### A Year Zero Engine Military Science-Fiction Roleplaying Game

**Playtest Edition 0.2 — aligned with the approved BWzye v0.12.8 MVP**

This edition uses the project design/build specifications, approved phase defaults and Phase 11 reference content as its baseline. Provisional values remain playtest values. Text marked **Optional tabletop proposal** is an unapproved extension from the original draft; agree on it with the GM before using it. A numerical rule appearing here does not by itself make it part of the approved MVP.

Fantasy Grounds notes identify implementation limits separately from tabletop adjudication. The current build covers Phases 0–12, including the separate [Outpost Defense: Relay K-17 module](notes/phase-12-acceptance.md). Chapter 18 remains an optional written variant; use the delivered module's own guide for its scenario settings. Live scenario validation remains pending. This review establishes consistency with the local project; it does not certify balance, official Year Zero Engine compatibility or distribution rights.

---

## Table of Contents

1. [What Is BUG Wars?](#1-what-is-bug-wars)
2. [The Core Rules](#2-the-core-rules)
3. [Creating a Trooper](#3-creating-a-trooper)
4. [Attributes and Skills](#4-attributes-and-skills)
5. [Archetypes and Specialties](#5-archetypes-and-specialties)
6. [Equipment and Loadout](#6-equipment-and-loadout)
7. [Combat](#7-combat)
8. [Weapons and Ammunition](#8-weapons-and-ammunition)
9. [Damage, Armor, and Critical Injuries](#9-damage-armor-and-critical-injuries)
10. [Suppression, Resolve, and Panic](#10-suppression-resolve-and-panic)
11. [Command and Squad Tactics](#11-command-and-squad-tactics)
12. [Hordes](#12-hordes)
13. [NPC Squads](#13-npc-squads)
14. [The Bugs](#14-the-bugs)
15. [Missions and Campaigns](#15-missions-and-campaigns)
16. [Advancement and Promotion](#16-advancement-and-promotion)
17. [Game Master Rules](#17-game-master-rules)
18. [Sample Mission: Hold the Line](#18-sample-mission-hold-the-line)
19. [Quick Reference](#19-quick-reference)
20. [Playtest Notes](#20-playtest-notes)

- [Appendix A: Character Sheet Summary](#appendix-a-rules-summary-for-character-sheets)
- [Appendix B: Future Modules](#appendix-b-future-modules)
- [Appendix C: Distribution Note](#appendix-c-development-and-distribution-note)
- [Appendix D: Accuracy Baseline](#appendix-d-edition-02-accuracy-baseline)

---

# 1. What Is BUG Wars?

**BUG Wars** is a military science-fiction roleplaying game about infantry soldiers fighting an enemy that does not think like a human army, does not fear casualties, and can attack in numbers too large to represent one creature at a time.

The player characters are trained troopers deployed to hostile worlds, besieged colonies, underground nests, isolated installations, and collapsing front lines. A mission may begin as a patrol and end as a desperate extraction with ammunition running low and hundreds of Bugs pouring through a breached perimeter.

BUG Wars is built around six ideas:

- **The squad matters.** Characters are soldiers operating as a team.
- **Ammunition matters.** Automatic fire is powerful, but sustained fire burns through magazines.
- **Suppression matters.** A trooper can still be physically capable while becoming pinned, shaken, or overwhelmed.
- **Command matters.** Leaders can rally troops, coordinate attacks, and keep a position from collapsing.
- **Mass combat must remain fast.** Large Bug attacks use Horde rules instead of dozens of individual turns.
- **Mission success matters more than kill count.** Objectives, extraction, casualties, and strategic consequences drive the campaign.

The game is intentionally setting-light. A campaign can be a hard military survival story, a pulpy bug hunt, a grim colonial war, or a dark satire about institutions that keep sending young soldiers into impossible battles.

## 1.1 What You Need

To play you need:

- this rulebook;
- one character sheet per player;
- polyhedral dice: d6, d8, d10, and d12;
- tokens or miniatures if desired;
- a map or simple Zone sketch for tactical encounters;
- a Game Master.

Fantasy Grounds or another VTT can automate many procedures, but the tabletop rules do not require one.

## 1.2 The Mission Loop

A typical session follows this structure:

1. **Briefing** — Command provides objectives and intelligence.
2. **Loadout** — The squad selects weapons, ammunition, and equipment.
3. **Deployment** — Dropship, vehicle, tunnel insertion, patrol, or defensive assignment.
4. **Contact** — The first threat appears.
5. **Escalation** — More Bugs, equipment failure, casualties, or changing orders.
6. **Objective** — The squad completes, changes, or abandons the mission goal.
7. **Extraction** — Surviving the mission is often an objective of its own.
8. **Debrief** — Experience, casualties, promotions, and campaign consequences are recorded.

---

# 2. The Core Rules

BUG Wars uses **step dice**.

## 2.1 Ratings and Dice

Attributes and trained Skills use the following ladder:

| Rating | Die |
|---:|---|
| 0 | No die |
| 1 | d6 |
| 2 | d8 |
| 3 | d10 |
| 4 | d12 |

Attributes normally range from 1 to 4.

Skills range from 0 to 4.

A normal test rolls:

> **Attribute Die + Skill Die**

If the character has Skill 0, roll only the Attribute Die.

### Example

A trooper with **Agility 3** and **Ranged Combat 2** rolls:

> **d10 + d8**

## 2.2 Counting Successes

Each die can generate successes.

| Die Result | Successes |
|---:|---:|
| 1-5 | 0 |
| 6-9 | 1 |
| 10-11 | 2 |
| 12 | 3 |

A d6 can therefore produce at most 1 success.

A d10 can produce up to 2.

A d12 can produce up to 3.

Add the successes from every die rolled.

## 2.3 Difficulty

Most dangerous actions require **1 success**.

| Difficulty | Required Successes |
|---|---:|
| Routine under pressure | 1 |
| Difficult | 2 |
| Severe | 3 |
| Extreme | 4+ |

Do not roll for ordinary actions that have no meaningful pressure or consequence.

## 2.4 Opposed Tests

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

When two characters directly oppose one another, both roll.

The side with more successes wins.

A tie favors:

1. the defender;
2. the character maintaining the current situation;
3. GM adjudication if neither applies.

## 2.5 Bonus Dice

A **Bonus Die** is a d6. Each 6 adds one success.

Bonuses may come from specialties, commands, firing modes or GM-adjudicated advantages. There is no approved universal three-Bonus-Die cap. The current ruleset accepts up to ten Bonus Dice on a test; this is an implementation limit, not a new balancing rule. Apply each source's own restrictions and do not duplicate the same benefit.

## 2.6 Step Modifiers

In the approved MVP, step modifiers adjust the **Attribute die**, or the base Attack/Firepower die for a Horde or Squad. A trained Skill die remains unchanged.

> d6 <-> d8 <-> d10 <-> d12

The modified base die is bounded at d6 and d12. Penalties do not remove it, and bonuses beyond d12 do not convert into Bonus Dice. Skill 0 still means no Skill die; modifiers do not create one.

Cover and Suppression use this same rule. For example, Agility d10 + Ranged Combat d8 with a -1 step modifier becomes **d8 + d8**.

## 2.7 Helping

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

One character may help another when it makes sense.

Each effective helper adds **1 Bonus Die**, to a maximum of 2 helpers.

Helping normally requires the helper to spend the same kind of action as the acting character.

## 2.8 Pushing a Roll

An eligible failed or disappointing test may be **Pushed once**.

1. Keep all dice showing **1** and all dice that scored successes.
2. Reroll only dice showing **2–5**.
3. Keep the existing successes and add any new successes; accept the new roll.
4. Gain **1 Stress**, not Suppression.
5. If this attack requires an Ammo Check, it owes a second check after application, provided ammunition remains.

A roll with no eligible dice cannot be pushed. Resolve/Panic, independent Squad Morale and injury treatment rolls cannot be pushed in this MVP. Stress is recorded separately; additional Stress effects have not been specified.

The Combat Tracker displays the current amount as a public **STRESS: N** effect, including zero. It follows Stress changes, including Push, and is only a visual reminder; the effect itself applies no penalty.

For attacks, Rally and commands, finish **Roll → optional Push → Apply Last Result** before starting another test. An ordinary Single attack requires no Ammo Check even after Push; Fire at Will can change that exception.

## 2.9 Extended Tests

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Some tasks require accumulated successes over time.

Examples:

- repairing a damaged transmitter;
- cutting through a blast door;
- treating several casualties;
- planting charges along a defensive line.

The GM sets a total:

| Task | Required Total |
|---|---:|
| Short | 3 successes |
| Significant | 5 successes |
| Major | 8 successes |
| Extreme | 10+ successes |

Each roll consumes time and may trigger complications.

---

# 3. Creating a Trooper

Character creation follows eight steps.

## 3.1 Step One: Concept

Choose:

- name;
- call sign;
- home or colony;
- military background;
- personality;
- reason for serving.

These details have no required mechanical effects, but they help define the trooper outside combat.

## 3.2 Step Two: Choose an Archetype

Choose one:

- Rifleman
- Squad Leader
- Heavy Weapons Specialist
- Combat Medic
- Scout
- Combat Engineer

Archetypes define battlefield emphasis, not rigid classes.

Any trooper may attempt any action.

## 3.3 Step Three: Assign Attributes

Assign:

> **4, 3, 2, 2**

among:

- Strength
- Agility
- Wits
- Empathy

The archetype does not force a specific arrangement.

## 3.4 Step Four: Assign Skills

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Choose:

- one Skill at **3**;
- two Skills at **2**;
- three Skills at **1**;
- all remaining Skills at **0**.

Under this optional allocation, one archetype Key Skill must be rated 3.

A second archetype Key Skill must be rated at least 2.

## 3.5 Step Five: Choose a Specialty

**Optional starting-choice proposal:** choose one of the three Specialties listed for the archetype. The approved reference module supplies those choices but does not establish a character-creation purchase budget.

Additional Specialties may be learned later.

## 3.6 Step Six: Calculate Derived Values

### Health

> **Health = 3 + Strength Rating**

### Resolve

> **Resolve = 2 + Empathy Rating**

Resolve is a recorded derived score. The current MVP triggers Panic at **5+ Suppression**, not at this score; Resolve tests use the provisional dice rule in §10.6.

### Carry

> **Carry = 4 + Strength Rating**

Carry is the amount of Bulk that can be carried without penalty.

## 3.7 Step Seven: Choose Rank

Most new characters begin as:

> **Private**

A Squad Leader may begin as:

> **Corporal**

or, in a veteran campaign:

> **Sergeant**

Rank is primarily authority and responsibility, not a direct combat bonus.

## 3.8 Step Eight: Choose Loadout

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

A standard infantry deployment normally provides:

- Standard Infantry Armor;
- one primary weapon;
- Service Pistol;
- four primary-weapon reloads;
- two pistol reloads;
- two fragmentation grenades;
- tactical radio;
- basic field kit.

The GM may alter equipment by mission. This suggested kit is not automatically issued by the ruleset. Grenades and reload quantities are manually adjudicated; use the approved reference entries in §6 for stocked gear.

## 3.9 Optional Character Details

For stronger roleplaying, record:

**Drive** — Why does the trooper keep fighting?

**Buddy** — Which squad member does the trooper trust most?

**Line They Will Not Cross** — What order or action would seriously test their loyalty?

These are narrative hooks. They may be used when awarding XP.

---

# 4. Attributes and Skills

## 4.1 Strength

Strength covers:

- physical power;
- stamina;
- resisting exhaustion;
- carrying heavy loads;
- close combat.

## 4.2 Agility

Agility covers:

- coordination;
- movement;
- shooting;
- reaction speed;
- balance.

## 4.3 Wits

Wits covers:

- awareness;
- technical knowledge;
- navigation;
- fieldcraft;
- battlefield interpretation.

## 4.4 Empathy

Empathy covers:

- leadership;
- morale;
- communication;
- influence;
- emotional control.

---

## 4.5 Skills

### Athletics — Strength

Use for:

- climbing;
- jumping;
- forced marches;
- swimming;
- carrying casualties;
- physical endurance.

### Close Combat — Strength

Use for:

- knives;
- bayonets;
- rifle strikes;
- grappling;
- Bug melee.

### Mobility — Agility

Use for:

- dodging;
- crossing exposed ground;
- scrambling;
- maintaining balance;
- rapid repositioning.

### Ranged Combat — Agility

Use for:

- rifles;
- carbines;
- pistols;
- shotguns;
- sniper rifles.

### Heavy Weapons — Agility

Use for:

- squad automatic weapons;
- grenade launchers;
- rocket launchers;
- mounted weapons;
- crew-served weapons.

### Recon — Wits

Use for:

- spotting ambushes;
- detecting movement;
- tracking;
- identifying Bug activity;
- reading a battlefield.

### Survival — Wits

Use for:

- navigation;
- hostile environments;
- finding shelter;
- recognizing environmental hazards;
- long-range field operations.

### Tech — Wits

Use for:

- electronics;
- computers;
- sensors;
- communications;
- field repairs.

### Demolitions — Wits

Use for:

- explosives;
- mines;
- breaching;
- demolition charges;
- explosive disposal.

### Medical — Wits

Use for:

- first aid;
- stabilization;
- trauma treatment;
- field surgery.

### Command — Empathy

Use for:

- rallying;
- battlefield orders;
- morale;
- unit coordination;
- maintaining discipline.

### Influence — Empathy

Use for:

- persuasion;
- interrogation;
- negotiation;
- deception;
- dealing with civilians and command personnel.

---

# 5. Archetypes and Specialties

The following eighteen specialty effects match the design specification and Phase 11 reference module. They are **GM-adjudicated**; copying a specialty does not automate its modifier or action. Specialty Rally is a once-per-round direct reduction, distinct from a rolled Rally command.

## 5.1 Rifleman

The Rifleman is the flexible core of an infantry squad.

**Key Skills**

- Ranged Combat
- Athletics
- Mobility

### Controlled Burst

**Trigger:** Burst fire.

Burst Ammo Depletion risk is reduced by one step.

### Bug Hunter

**Trigger:** Attack known Arachnid infantry at Close or Medium range.

Gain +1 Bonus Die on the attack.

### Bayonet Training

**Trigger:** Enter melee with rifle equipped.

Ignore the improvised-weapon penalty.

## 5.2 Squad Leader

The Squad Leader keeps the unit functioning under pressure.

**Key Skills**

- Command
- Ranged Combat
- Recon

### Rally

**Trigger:** Once per round; Fast Action.

Reduce Suppression by 1 for one ally in the same or an adjacent Zone.

### Coordinated Fire

**Trigger:** Slow Action; designate a target.

Up to three allies gain +1 Bonus Die when attacking that target before your next turn.

### Hold the Line

**Trigger:** Leader is active and unsuppressed.

Allies in your Zone gain +1 Bonus Die to Resolve tests.

## 5.3 Heavy Weapons Specialist

The Heavy Weapons Specialist controls lanes, kills large organisms, and breaks swarms.

**Key Skills**

- Heavy Weapons
- Athletics
- Demolitions

### Walking Fire

**Trigger:** Move while using Suppressive Fire.

Move one Zone without the normal attack penalty.

### Brace

**Trigger:** Recoil, Bulk or unstable position would impose a penalty.

Ignore the first such penalty.

### Explosives Expert

**Trigger:** Use prepared charges, mines or grenades.

Gain +1 Bonus Die to Demolitions tests.

## 5.4 Combat Medic

The Combat Medic keeps casualties alive long enough to extract them.

**Key Skills**

- Medical
- Ranged Combat
- Mobility

### Combat Triage

**Trigger:** Once per round.

Stabilization can be performed as a Fast Action.

### Get Him Moving

**Trigger:** After stabilizing an ally.

Remove 1 Suppression from that ally.

### Field Surgeon

**Trigger:** Treat a critical injury during a rest.

Gain +1 Bonus Die on the treatment test.

## 5.5 Scout

The Scout finds the enemy before the enemy finds the squad.

**Key Skills**

- Recon
- Mobility
- Survival

### Stay Low

**Trigger:** Cross exposed terrain.

Gain +1 Bonus Die to Mobility tests.

### Forward Observer

**Trigger:** Direct indirect fire or provide target coordinates.

Gain +1 Bonus Die.

### Ambush

**Trigger:** Begin combat undetected.

Gain +1 Bonus Die on your first attack.

## 5.6 Combat Engineer

The Combat Engineer builds, destroys, repairs, and opens routes.

**Key Skills**

- Demolitions
- Tech
- Heavy Weapons

### Breacher

**Trigger:** Use prepared charges against structures or armor.

Prepared charges gain +1 base Damage.

### Field Repairs

**Trigger:** Spare parts are available.

Repair mission equipment without a full workshop.

### Defensive Works

**Trigger:** Time and materials are available.

Improve a Zone cover rating by one level.

# 6. Equipment and Loadout

## 6.1 Bulk

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Equipment uses abstract **Bulk**. Carry = 4 + Strength is approved. **Carried Bulk** automatically totals weapons on the Combat tab, armor in Equipment & Specialties, and field gear Bulk multiplied by quantity. Each listed weapon and armor item counts once, whether equipped or not; unequipped equipment is still carried. Remove an item from the loadout when it is no longer carried, or reduce a gear stack's quantity (zero contributes no Bulk). Specialties, skills and archetypes add no Bulk. The total refreshes when the loadout changes and when existing characters are loaded. Generic CoreRPG Inventory weights are separate and are not converted into BW Bulk; use BW gear records for physical equipment. The penalties below are optional proposals; the MVP does not calculate or enforce them.

A character can carry Bulk up to their **Carry** value without penalty.

The Combat Tracker automatically displays a public **ENCUMBERED** effect while Carried Bulk is greater than Carry Limit, and removes it at or below the limit. This effect is only a visual reminder and applies none of the optional penalties below. These automatic status effects are visible to players on Friendly entries under the normal effect-visibility rules.

### Encumbered

If total Bulk exceeds Carry:

- step Athletics down once;
- step Mobility down once;
- the character cannot Sprint.

If Bulk exceeds Carry by more than 2, the character cannot move more than one Zone per round without dropping equipment.

## 6.2 Ammunition Reloads

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

A reload is a magazine, belt, shell carrier, battery, or equivalent ammunition package.

Two standard reloads normally equal:

> **Bulk 1**

Heavy ammunition may count differently.

## 6.3 General Equipment

The approved **provisional** field-gear set is:

| Item | Bulk | Use |
|---|---:|---|
| Helmet Comms | 0 | Short-range squad communication; the GM determines interference and range. |
| Medkit | 1 | Supplies for first aid and stabilization with Medical; track supplies manually. |
| Field Toolkit | 1 | Portable tools for Tech repairs when materials and access permit. |
| Demolition Kit | 2 | Tools and components for prepared Demolitions; charge damage and quantities require GM approval. |
| Binoculars | 0 | Magnified observation; the GM judges visibility and Recon conditions. |
| Motion Scanner | 1 | Detect nearby motion when conditions permit; no automatic target discovery. |
| Ration Pack | 1 | Field food supplies; track days and consumption manually. |
| Water Canteen | 1 | Portable drinking water; track supply manually. |
| Climbing Kit | 1 | Rope and anchors for climbs; use Athletics with GM-set difficulty. |
| Spare Parts | 1 | Repair materials for field equipment; suitability and expenditure require GM adjudication. |

Bulk is per item. Gear copies start at quantity one. Supplies, charge damage, depletion and situational benefits require GM adjudication; no automatic scanner Bonus Die or medkit prerequisite has been approved.

## 6.4 Grenades

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

A proposed fragmentation grenade has Damage 3, Blast and Close/Medium throwing range, with individual grenades tracked manually.

For consistency with the fixed Skill list, a proposed Athletics throwing test uses **Strength + Athletics**. Mobility uses Agility for movement; do not silently change Athletics' linked Attribute to Agility.

Thrown grenades are not one of the eight approved weapon records. Their damage, range, targeting and supply rules require a GM decision. The approved **Grenade Launcher** is a different weapon: Heavy Weapons, Damage 4, Medium range, d6 Ammo.

# 7. Combat

Combat is divided into rounds.

A round represents several seconds of intense action.

## 7.1 Initiative

The design specification uses the following encounter-start roll, with initiative cards as an optional faster alternative:

> **Agility + Recon**

Count successes.

Highest success total acts first.

Ties are broken by:

1. larger Agility die;
2. player choice.

The GM settles any remaining NPC tie. In Fantasy Grounds, **Roll Initiative** in the lower-right corner of a PC's Combat tab or NPC's BW Combat tab rolls Agility + Recon publicly, shows each die and the success total, and updates that actor's existing tracker entry. The tracker orders higher successes first, then larger rolled Agility dice; remaining ties still require player choice or GM adjudication. If the actor is not on the tracker, the chat result can be entered after adding it. Recon 0 rolls only Agility. NPCs, including squads and Hordes, use their stored Agility/Recon; missing values use the existing NPC defaults of Agility 2 (d8) and untrained Recon. The normal Recon Suppression penalty applies. Initiative is a separate roll with no Push or Apply step and does not replace a pending attack result. Keeping that order for the encounter is a GM convention.

The host Combat Tracker's Initiative menu uses the same public Agility + Recon rolls for **All**, **PCs**, or **NPCs**. The NPC option includes Individuals, Squads and Hordes. Each actor rolls independently, including NPCs with matching names; the generic CoreRPG d20/group initiative option does not apply to these BW rolls.

## 7.2 Actions

Each character receives:

- **1 Slow Action**
- **1 Fast Action**

A Slow Action may be exchanged for another Fast Action.

## 7.3 Common Slow Actions

- Fire a weapon
- Full Auto
- Suppressive Fire
- Close Combat attack
- Sprint (optional §7.5 proposal)
- Treat a casualty
- Use Demolitions
- Perform a major Tech action
- Coordinated Fire (specialty)
- Reload a heavy weapon

Treating Focus Fire, Hold Position or Fire at Will as Slow Actions is an optional action-cost convention; those commands' costs are not numerically fixed by the approved MVP. Agree on them with the GM.

## 7.4 Common Fast Actions

- Move one Zone
- Aim
- Take Cover
- Reload a standard weapon
- Draw or stow equipment
- Stand from Prone
- Rally
- Interact with a simple object

## 7.5 Zones

BUG Wars uses **Zones**.

A Zone is a meaningful tactical area such as:

- command bunker;
- western barricade;
- killing field;
- rocky rise;
- tunnel chamber;
- dropship pad.

A character normally moves one adjacent Zone with a Fast Action.

### Sprint

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Spend a Slow Action to move up to two Zones.

Difficult terrain may require Athletics or Mobility.

## 7.6 Range Bands

| Range | Meaning |
|---|---|
| Engaged | close enough for melee |
| Close | same Zone |
| Medium | adjacent Zone |
| Long | two Zones away |
| Extreme | three or more Zones away |

A weapon's listed range guides GM adjudication. The current MVP uses a manually selected range band and has no approved numeric range-penalty table or automatic maximum-range enforcement.

## 7.7 Cover

| Cover | Effect |
|---|---|
| Light | Step the attack Attribute/base die down once |
| Solid | Step the attack Attribute/base die down once; Armor +1 |
| Fortified | Step the attack Attribute/base die down once; Armor +2 |

Examples:

**Light**
- brush;
- scattered debris;
- shallow trench.

**Solid**
- stone wall;
- vehicle engine block;
- reinforced barricade.

**Fortified**
- prepared bunker;
- heavy firing position;
- hardened defensive wall.

## 7.8 Aim

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Spend a Fast Action.

Gain **1 Bonus Die** on the next Single or Burst attack made before the end of the current turn.

An Accurate weapon may improve this benefit.

## 7.9 Prone

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Going Prone is a Fast Action.

While Prone:

- ranged attacks from Medium or farther step the attack Attribute die down once unless the attacker has elevation;
- melee attacks against the Prone character gain 1 Bonus Die;
- standing is a Fast Action.

## 7.10 Dodge and Block

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

A character may react to an attack if aware of it.

Spend a Fast Action to:

**Dodge**
> Agility + Mobility

or

**Block**
> Strength + Close Combat

Each success cancels one attacker success under this proposed reaction rule. In Fantasy Grounds, make the opposed roll manually and enter its success count in **Defense**. A hit must meet the selected difficulty and exceed Defense.

If the character has already spent their Fast Action this round, the reaction consumes the Fast Action from their next turn.

A character may make only one Dodge or Block reaction per round unless a Specialty says otherwise.

## 7.11 Ranged Attacks

Roll:

> **Agility + Ranged Combat**

or:

> **Agility + Heavy Weapons**

depending on weapon.

One uncancelled success hits.

Extra successes may improve the result.

## 7.12 Close Combat

Roll:

> **Strength + Close Combat**

The defender may use the optional Block or Dodge procedure if the group adopts it.

One remaining success hits.

## 7.13 Extra Successes

After achieving the success needed to hit, spend extra successes on:

- +1 Damage per success;
- +1 Suppression per success;
- knock target Prone;
- force target from Cover;
- create a positional advantage;
- activate a weapon trait if required.

The GM must approve narrative effects.

## 7.14 Called Shots

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

A Called Shot requires **2 successes** to hit.

Examples:

- exposed sensor organ;
- weapon arm;
- weak armor plate;
- Tanker underside;
- control mechanism.

If successful, apply the specific effect established by the target or GM.

---

# 8. Weapons and Ammunition

## 8.1 Weapon Statistics

Weapons use:

- Damage
- Range
- ROF
- Ammo
- Bulk
- Traits

### ROF

ROF is stored descriptively in the MVP. The following mode restrictions are an optional tabletop proposal, not automatically enforced.

| ROF | Available Modes |
|---:|---|
| 1 | Single |
| 3 | Single, Burst |
| 5 | Single, Burst, Full Auto, Suppressive Fire |

## 8.2 Core Weapons

These are the **provisional design-spec values** shipped in Phase 11.

| Weapon | Damage | Range | ROF | Ammo | Bulk | Traits |
|---|---:|---|---:|---|---:|---|
| Service Pistol | 1 | Medium | 1 | d8 | 1 | Sidearm |
| Morita-style Rifle | 2 | Long | 3 | d10 | 2 | Burst |
| Carbine | 2 | Medium | 3 | d10 | 2 | Compact |
| Squad Automatic Weapon | 2 | Long | 5 | d12 | 3 | Suppressive, Heavy |
| Sniper Rifle | 3 | Extreme | 1 | d8 | 3 | Accurate |
| Shotgun | 3 | Close | 1 | d8 | 2 | Scatter |
| Grenade Launcher | 4 | Medium | 1 | d6 | 2 | Blast |
| Rocket Launcher | 6 | Long | 1 | d6 | 4 | Anti-Armor, Blast |

“Service Rifle” in narrative examples refers to the module’s Morita-style Rifle. SAW and both launchers use Heavy Weapons; the other five use Ranged Combat. Shotgun and Grenade Launcher do not have Limited in the approved set. Rocket Launcher uses d6 Ammo, not an automatic single-use rule.

## 8.3 Firing Modes

### Single

No attack Bonus Dice and **no ordinary Ammo Check**.

### Burst

Gain **1 Bonus Die**. Make one Ammo Check; depletion occurs on **1–2**.

### Full Auto

Gain **2 Bonus Dice**. Make one Ammo Check; depletion occurs on **1–3**.

The automated attack uses one primary target. Distribution among multiple targets is GM-adjudicated; use Finish Manually after resolving such a distribution to settle Ammo without applying the primary-target result again.

### Suppressive Fire

Roll an attack with no firing-mode Bonus Dice. On success, each explicitly selected target makes a **Resolve test**. Each failure adds **1 Suppression**; a Horde that fails also loses **1 Momentum**. A successful resistance test prevents those effects.

Suppressive Fire inflicts no direct Damage or automatic Strength loss, regardless of attack successes. The GM selects eligible exposed targets; Zone geometry does not select them automatically. Make one Ammo Check, depleting on **1–2**.

These are the normal thresholds. Fire at Will changes them as described in §11.6.

## 8.4 Ammo Checks

Burst, Full Auto and Suppressive Fire require an Ammo Check after target effects are applied, including on a miss. Ordinary Single fire does not. Pushing an attack that requires a check adds a second sequential check if ammunition remains. Horde mass attacks, Squad attacks and the creature Acid Spray action do not use weapon Ammo.

Roll the weapon's current Ammo Die.

If the result falls within the depletion range for the firing mode, step the Ammo Die down:

> d12 -> d10 -> d8 -> d6 -> Empty

When Empty, the weapon cannot fire.

### Example

A Service Rifle is at d10 Ammo.

The trooper fires Burst.

The attack gains 1 Bonus Die.

The Ammo Die rolls 2.

Because Burst depletes on 1-2:

> d10 becomes d8.

## 8.5 Reloading

Reloading a standard weapon is a Fast Action.

Restore the weapon to its listed maximum Ammo die. Availability and expenditure of carried reloads are GM-adjudicated; the ruleset does not track a reload inventory automatically.

A Heavy or awkward weapon may require a Slow Action.

## 8.6 Limited

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

The original draft proposed increasing depletion thresholds by one for Limited weapons. This trait is not assigned to the approved Shotgun or Grenade Launcher and has no automated effect. Establish both the affected weapons and the check triggers before adopting it; increasing a threshold does not turn ordinary Single fire into a check under the approved baseline.

## 8.7 Single-Use Weapons

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Tracking individual rockets and emptying a launcher after every shot is an alternative ammunition system. It is not the approved Rocket Launcher default, which uses d6 Ammo. If the GM adopts a single-use variant, track rockets, Empty state and reload timing manually.

## 8.8 Weapon Traits

### Accurate

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

When Aiming, gain **2 Bonus Dice** instead of 1.

### Anti-Armor

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Reduce target Armor by **3** before Armor Dice are rolled.

### Blast

When at least one Damage remains after Armor, a Horde loses **1 additional Strength** after the normal conversion. If Armor cancels all Damage, Blast causes no Strength loss and no Momentum loss.

The MVP does not automatically damage nearby individual targets or select everyone in a Zone. Additional area targets and their attack results require GM adjudication.

### Burst

The weapon supports Burst fire.

### Compact

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Ignore the first penalty for cramped spaces or firing from restricted positions.

### Heavy

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

If not Braced or properly supported, step the attack Attribute die down once.

### Scatter

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

The original draft proposed +1 Bonus Die at Close range and a -1 Attribute step at Medium. The approved Shotgun is listed at **Close** range. A Medium-range Scatter option would require the GM to approve a range extension as well as the modifier. Scatter currently has no automatic numerical effect.

### Sidearm

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

May be fired while Engaged without the normal close-quarters penalty.

### Suppressive

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Gain 1 Bonus Die when using Suppressive Fire.

---

# 9. Damage, Armor, and Critical Injuries

## 9.1 Damage

A successful attack inflicts:

> **Weapon Damage + purchased extra Damage**

Damage is reduced by Armor.

Remaining Damage reduces Health.

## 9.2 Armor

Armor is rated in **Armor Dice**.

Roll a number of d6 equal to the effective Armor rating.

Each **6** cancels 1 Damage.

### Example

A trooper in Armor 3 is hit for 3 Damage.

The player rolls:

> 3d6

and scores one 6.

Armor cancels 1 Damage.

The trooper loses:

> 2 Health.

## 9.3 Armor Types

The approved **provisional infantry armor** is:

| Armor | Rating | Bulk |
|---|---:|---:|
| Light Infantry Armor | 1 | 1 |
| Standard Infantry Armor | 2 | 2 |
| Heavy Infantry Armor | 3 | 3 |

On PCs, the manual **Base Armor** value adds to one equipped armor item's rating. Do not enter the same suit in both places. Armor copies start unequipped; choosing another suit unequips the previous one. The tracker shows their combined total.

Powered Armor remains future work. The original draft's Armor 3/4/6 tier table is not an approved MVP default.

## 9.4 Armor-Piercing Effects

Armor cannot fall below zero. Approved Acid Spray records persistent Armor loss as described in §14.1. The original draft's **Anti-Armor −3** rule is an optional proposal; it is not automated or numerically specified by the approved weapon table.

For PCs or NPCs damaged by Acid, the GM opens **Traits** from the host tracker entry and reduces **Armor loss** after adjudicating repairs. Changing the armor record itself is not required.

## 9.5 Broken

When an individual actor's Health first reaches zero, set **Broken** and roll one Critical Injury immediately. Repeated updates at zero do not create duplicate injuries. Horde and Squad defeat uses Strength instead and does not cause individual Critical Injuries.

The GM can delete one injury or use **Delete All** on a PC or NPC's Injuries tab. This also permits cleanup of existing injuries on Horde/Squad records, including their separate tracker instances. Deletion does not restore Health or Strength, and clearing injuries cancels pending injury jobs for that actor.

A Broken actor needs a successful **Resolve: Broken** check before attempting another action. The permission is consumed by starting that action; pushing the same test does not require a new permission. No extra Suppression is automatically charged for using it. See §10.6 for the provisional Resolve roll.

Falling Prone and other physical consequences are GM-adjudicated. Restoring positive Health clears Broken but does not erase injuries.

## 9.6 Taking Damage While Broken

Further injury, worsening or death while already Broken is **GM-adjudicated**. Additional damage at zero Health does not automatically roll another Critical Injury in the approved MVP. The GM may use **Roll Critical** to assign an additional injury. Recovering above zero and later becoming Broken again triggers a new injury normally.

## 9.7 First Aid

Use the active healer's **Wits + Medical** against the selected injury's treatment difficulty. Untrained Medical uses Wits alone. The approved provisional difficulty is **one success** for every initial injury entry.

Success marks that injury **Stabilized**, stops its optional fatal timer and retains its history. Failure leaves both unchanged. Treatment cannot be pushed in this MVP. A Broken healer first needs permission from Resolve: Broken.

Stabilization does **not** automatically restore Health or clear Broken. Health restoration, repeat treatment opportunities and other recovery effects are GM decisions.

## 9.8 Critical Injuries

Roll **1d12** when an individual becomes Broken. The approved **provisional** table is:

| d12 | Injury | Descriptive effect | Potentially fatal |
|---:|---|---|---|
| 1 | Bleeding | Active bleeding; describe its location and impact with the GM. | No |
| 2 | Concussion | Head injury; GM adjudicates confusion and exertion. | No |
| 3 | Broken Arm | Arm injury; GM adjudicates use of the affected arm. | No |
| 4 | Broken Leg | Leg injury; GM adjudicates mobility. | No |
| 5 | Internal Injury | Internal trauma; GM determines urgency and consequences. | Yes |
| 6 | Crushed Hand | Hand injury; GM adjudicates grip and fine work. | No |
| 7 | Severe Burn | Burn injury; GM determines affected area and consequences. | No |
| 8 | Punctured Lung | Chest injury; GM adjudicates breathing and exertion. | Yes |
| 9 | Severed Limb | Limb loss; GM adjudicates bleeding and permanent consequences. | Yes |
| 10 | Massive Trauma | Extensive trauma; GM determines affected systems and urgency. | Yes |
| 11 | Mortal Wound | Life-threatening injury; GM sets the deadline and outcome. | Yes |
| 12 | GM Choice | GM selects or edits an injury appropriate to the attack. | GM decides |

All twelve entries initially require **one treatment success**; healing time is **GM determines**. Descriptive effects do not automatically impose Attribute penalties, disable equipment or kill the actor. The GM may customize the campaign table.

**Fatal timers are disabled by default**, including on potentially fatal injuries. To use one, the GM explicitly sets the remaining time and unit and enables it. Advance timers is a manual action, not an automatic round countdown. Reaching zero records a deadline and prompts GM adjudication; it does not automatically kill the actor. Stabilization stops further ticking.

The original draft's random 1d6-round deadlines and treatment difficulties 2–3 are not approved defaults.

## 9.9 Recovery

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

Recovery time and Health restoration remain GM-controlled in the approved MVP. The following durations and amounts are optional proposals, not automated effects. Mark healed retains an injury in history and does not itself restore Health.

### Short Rest

After 10 minutes in relative safety:

- remove 1 Suppression;
- reload and reorganize equipment if ammunition is available.

### Full Rest

After at least 6 hours of safe rest:

- restore 2 Health;
- reduce Suppression to 0.

Critical Injuries may limit healing.

### Medical Care

A successful Medical treatment during a Full Rest restores:

> +1 additional Health.

Serious injuries may require days, surgery, prosthetics, or evacuation.

---

# 10. Suppression, Resolve, and Panic

A soldier does not need to be wounded to become combat ineffective.

**Suppression** measures:

- fear;
- shock;
- disorientation;
- exhaustion under fire;
- battlefield overload.

## 10.1 Gaining Suppression

Common sources:

- explosions;
- friendly casualties;
- sudden Bug charges;
- being surrounded;
- heavy incoming fire;
- Plasma bombardment;
- terrifying organisms;
- an explicitly adjudicated stress event (Push itself adds Stress, not Suppression);
- failed morale effects.

## 10.2 Suppression States

| Suppression | State |
|---:|---|
| 0–1 | Effective |
| 2 | Shaken |
| 3 | Suppressed |
| 4 | Pinned |
| 5+ | Panic test |

The approved Panic threshold is **5**, independent of the recorded Resolve score. Higher levels retain the relevant lower-state penalties until Suppression is reduced.

## 10.3 Shaken

At Suppression 2 or higher, apply a **−1 Attribute step** to Command and Recon tests. The trained Skill die remains unchanged.

## 10.4 Suppressed

At Suppression 3 or higher, keep Shaken's relevant penalties and apply a **−1 Attribute/base die step** to combat tests. These are skill-specific penalties, not two automatic penalties on every roll.

Advancing toward the source of Suppression requires a Resolve: Advance test; the GM adjudicates movement.

## 10.5 Pinned

At Suppression 4 or higher, retain applicable penalties and seek Cover if possible. Movement restrictions are GM-enforced.

**Offensive Full Auto is unavailable until rallied below 4 Suppression.** A successful Advance/Composure test does not bypass that restriction.

## 10.6 Composure Test

“Composure” in the original draft refers to a **Resolve test**. The approved provisional roll is:

> **Empathy die alone; one success required**

For a Squad, use its **Morale die** instead. Do not add Command, ordinary Suppression penalties or Stress. Resolve rolls cannot be pushed. Hold Position may improve the base die by one step.

Use Resolve for resisting Suppressive Fire, Panic, acting while Broken and advancing under Suppression. The derived score **2 + Empathy** remains recorded, but does not set the Panic threshold or supply a dice pool in this MVP.

## 10.7 Panic Test

At **5+ Suppression**, make one Resolve test. On success, record that Panic was resisted. On failure, the GM chooses a consequence from §10.8.

After either outcome, reduce Suppression to **4**. If an intervening Rally already reduced it below 4, retain the lower value. Panic consequences and their execution remain GM-adjudicated.

## 10.8 Panic Table

There is no approved random Panic table. On a failed test, the GM selects an appropriate consequence:

- freeze;
- retreat;
- drop prone;
- empty magazine;
- abandon position;
- follow nearest leader.

Record the choice and adjudicate timing, movement and ammunition manually. The original draft's compulsory d6 table, action losses and Wild Fire attack are not MVP rules.

## 10.9 Rallying

A rolled Rally uses **Empathy + Command** and is a **Fast Action** in the design-spec action list. Action costs remain GM-enforced.

At the default one-success difficulty, each success removes **1 Suppression** from one chosen ally. More generally, remove one plus the successes above the required difficulty. The MVP applies all of that reduction to one allied recipient; distributing it requires GM adjudication.

Roll, optionally Push, then Apply Last Result. Push adds 1 Stress. Range, communication and self-rally eligibility require GM adjudication. The separate **Rally specialty** grants its written once-per-round Fast Action reduction; do not double-apply it with a rolled command.

## 10.10 Bugs and Suppression

The approved creatures and Hordes use the existing Suppression states and Resolve/Panic rules. They are **not automatically Fearless**, and Momentum does not replace Horde Suppression.

Fearless is an optional narrative trait with no supported immunity effect in the MVP. If the GM adopts immunity for a particular creature, adjudicate it explicitly rather than assuming the ruleset will ignore Suppression.

# 11. Command and Squad Tactics

Commands use **Empathy + Command**, normally requiring **one success**, followed by optional Push and Apply Last Result. A Push adds 1 Stress. The following numerical effects are approved **provisional MVP defaults**.

A living PC or individual/elite NPC leader issues an order to one allied PC, individual/elite NPC or Squad in the tracker. Hordes and monsters do not receive these allied orders. Recipients must have the leader's non-neutral faction. Reorganize requires two depleted Squads instead of one recipient.

Temporary orders expire at the **start of the next round**, not the leader's next turn and not automatically after one attack. Reissuing the same order refreshes it without stacking. Extra successes improve Rally only; other commands have fixed benefits. Communication, action costs and Zone positioning remain GM-adjudicated. Rally is listed as Fast in the design spec; the other command action costs need GM agreement.

## 11.1 Rally

Remove **1 Suppression plus one per success above the required difficulty** from one ally. See §10.9.

## 11.2 Focus Fire

Designate an enemy and choose an allied recipient. The recipient gains **+1 Attribute/Firepower die step** on Ranged Combat, Heavy Weapons and Squad attacks against that enemy until the next round. It does not benefit melee or area Suppressive Fire.

In Fantasy Grounds, target the enemy and issue Focus Fire to save the designation, then target the ally and issue it again to roll the command. The enemy receives no allied effect.

## 11.3 Fall Back

Grant the recipient **+1 step to Mobility tests** for retreat/disengagement. The GM handles movement and pursuit. No automatic Suppression reduction or immunity to reaction attacks is granted.

## 11.4 Hold Position

Grant **+1 step to Resolve tests only**, including a Squad's Morale-based Resolve. This does not improve attacks, Defense, Armor, Command tests or the separate Squad Morale Check.

## 11.5 Covering Fire

Grant the recipient **+1 step to Mobility tests** for protected movement. This is a command, not a Suppressive Fire attack. The GM handles the movement.

## 11.6 Fire at Will

Grant **+1 Bonus Die** to ranged/heavy/Squad attacks. While the order applies, weapon Ammo checks use these depletion thresholds:

| Mode | Depletes on |
|---|---|
| Single | 1–2 (a check is now required) |
| Burst | 1–3 |
| Full Auto | 1–4 |
| Suppressive | 1–3 |

A pushed weapon attack owes two checks, stopping if Empty. Squad supplies remain abstract and are adjudicated by the GM. The attack captures the order's bonus and Ammo risk when rolled, so later expiry does not erase its costs.

## 11.7 Move! Move! Move!

Grant **+1 step to Mobility tests** and a coordinated-movement order marker. The GM decides movement distance and action expenditure; no automatic extra Zone is granted.

Fall Back, Covering Fire and Move do not stack their Mobility modifiers with one another. Focus Fire can combine with Fire at Will.

## 11.8 Reorganize

Choose two living, idle, depleted allied Squads and designate the receiving Squad. Transfer surviving Strength into that Squad **up to its existing maximum**. Keep excess Strength in the donor; never create personnel or delete either record.

The receiver keeps its own Firepower, Damage, Armor, Morale, Specialty and Leader. Its Suppression becomes the higher of the two values. Both maxima remain unchanged.

- 4/10 + 3/10 becomes **7/10 + 0/10**.
- 7/10 + 6/10 becomes **10/10 + 3/10**.

Full-strength, defeated, enemy, duplicate or busy Squads cannot reorganize. A donor at zero cannot contribute personnel again. The GM adjudicates proximity and whether battlefield conditions permit the order.

---

# 12. Hordes

A Horde represents a mass of similar enemies.

Do not place or track every creature.

A Horde uses:

- Strength
- Armor
- Attack Die
- Damage
- Suppression
- Speed
- Momentum
- Traits

## 12.1 Horde Strength

| Strength | Approximate Number |
|---:|---|
| 2 | 3-5 |
| 4 | 6-10 |
| 6 | 11-20 |
| 8 | 21-40 |
| 10 | 40-80 |
| 12+ | Massive wave |

These numbers are descriptive.

**Fantasy Grounds NPC sizing:** When added to the tracker, Individuals, Elites and Monsters start with Space equal to half their current Health. Fresh deployments start at full Health, so Health 5 gives Space 2.5. Hordes and Squads both use Strength pools and start with half their current group Strength. This initializes before native map placement, preserves fractions, and uses Space 1 when the relevant pool is zero. Later Health changes do not automatically resize Individuals, Elites or Monsters. **Options → Combat → Squad/Horde tokens resize with Strength** defaults to **No**, preserving the current Size as Strength changes, including at zero. With **Yes**, existing groups immediately resize to current Strength/2, then resize with damage, recovery and manual Strength edits; zero Strength uses Size 1. Switching back to No keeps the current size and allows GM Size edits to persist. With a map grid and native token auto-scaling enabled, the linked token follows Size changes. The GM's grid/scaling settings remain in force; Fantasy Grounds can round the occupied footprint independently of the stored Size. Regardless of this option, the host receives "[Name] is down." once when a living group reaches zero. Reopening or reloading does not repeat it; recovery permits a new down transition.

The host can edit every numeric/text field in the Horde/Squad tracker panel even when the original NPC record is locked. Tracker edits affect that instance. Calculated fields (such as Attack Bonus, State and Morale Due) remain subject to normal rules recalculation; editing them does not create a permanent override. Source-sheet locks and client restrictions still apply.

## 12.2 Horde Attacks

A Horde rolls:

> **Attack Die + Strength Bonus Dice**

| Current Strength | Bonus Dice |
|---:|---:|
| 1-3 | 0 |
| 4-6 | 1 |
| 7-9 | 2 |
| 10+ | 3 |

One success hits.

Extra successes may buy Damage or Suppression. Automated mass attacks use one target; additional targets require GM adjudication.

## 12.3 Damaging a Horde

After Armor and other defenses, convert Damage into Strength loss.

| Damage | Horde Strength Loss |
|---:|---:|
| 1-2 | 1 |
| 3-4 | 2 |
| 5+ | 3 |

**Blast** increases Strength loss by 1 only if at least one Damage remains after Armor. Zero remaining Damage means zero Strength loss.

A Horde at Strength 0 is:

- destroyed;
- dispersed;
- routed;
- no longer combat effective.

## 12.4 Momentum

Momentum ranges from **0 to 3**: Stalled, Pressing, Charging, Overrunning.

Approved automatic changes are:

- A successful targeted mass attack gains **1 Momentum** when applied, even if Armor cancels the Damage.
- A failed Suppressive Fire resistance check adds 1 Suppression and loses **1 Momentum**.
- A failed Resolve: Advance check while suppressed loses **1 Momentum**.
- A Blast attack that actually removes Strength loses **1 Momentum**.

Misses, untargeted attacks and Finish Manually do not grant attack Momentum. Reaching a defended Zone, command-organism support and other narrative changes are GM adjustments.

## 12.5 Overrun

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

At Momentum 3, a Horde may:

- enter defended Zones more easily;
- ignore one movement obstruction;
- make an immediate melee attack after breaching a position if the GM judges it appropriate.

## 12.6 Horde Movement

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

A Horde normally moves a number of Zones equal to Speed.

Most Warrior Hordes have:

> **Speed 1**

Fast swarms may have more.

## 12.7 Hordes in Melee

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

When a Horde occupies the same Zone as defenders:

- the defenders are Engaged;
- leaving normally requires Mobility or a successful Fall Back order;
- the Horde may spread attacks among multiple targets.

The GM should describe individual Bugs without creating individual turns.

---

# 13. NPC Squads

Friendly military units use simplified Squad rules.

A Squad has:

- Strength
- Firepower
- Damage
- Armor
- Morale
- Suppression
- Specialty
- Leader

## 13.1 Example Rifle Squad

Approved **provisional MVP** default:

- Strength: **10/10**
- Firepower: **d10**
- Damage: **2**
- Armor: **2**
- Morale: **d8**
- Suppression: **0**
- Specialty: **Rifle**
- Leader: unassigned descriptive field

## 13.2 Squad Attacks

Roll the **Firepower die** with applicable combat Step modifiers, Bonus Dice, Cover and Defense. Squads **do not receive Horde Strength Bonus Dice**.

One success at the normal difficulty hits. Apply Damage 2 by default plus extra successes spent on Damage, or allocate extras to Suppression. Resolve target Armor and then use that target type's damage conversion.

Use **Attack → optional Push → Apply Last Result**. Push follows the normal eligible-dice rule and adds 1 Stress. Squad attacks have no per-weapon Ammo Check and do not gain Horde Momentum.

## 13.3 Squad Casualties

Roll Squad Armor first. Each uncancelled Damage removes **one Squad Strength**, to a minimum of zero. This is the approved provisional conversion; do not use the Horde damage bands or Horde Blast bonus.

At zero Strength, the Squad is defeated and cannot launch, push or apply attacks. Strength loss does not cause Broken or individual Critical Injuries.

## 13.4 Squad Condition

Use exact current/maximum Strength ratios:

| Remaining Strength | State |
|---|---|
| At least 75% | Effective |
| At least 50%, below 75% | Reduced Firepower |
| At least 25%, below 50% | Shaken |
| Above zero, below 25% | Morale Check |
| Zero | Defeated |

The state names do **not** automatically reduce stored Firepower or Morale. Numerical casualty penalties remain GM-adjudicated using explicit modifiers.

At each round start, a surviving Squad below 25% checks its **Morale die**, requiring one success. This check cannot be pushed. Failure records a pending GM consequence; it does not automatically move, surrender or destroy the Squad. The GM may also request a manual Morale check.

## 13.5 Squad Suppression

Squads use the standard Suppression states and combat penalties in §10. Their Resolve tests use the **Morale die** instead of Empathy. At 5+ Suppression, resolve Panic through that procedure; this is distinct from the below-25% Strength Morale check.

Rally can remove Squad Suppression. Advance and failed-check consequences remain GM-adjudicated; a successful Rally is not the only way to attempt an Advance check.

## 13.6 Player Squad Control

On the host Combat Tracker, right-click a Squad and choose **Assign Control → PC name (username)**. Only PCs with a player owner appear; long lists are grouped into submenus. The assignment belongs to that player, independently of their active PC, and persists across sessions. The menu shows the current controller. Selecting another PC transfers control; **Remove Player Control** revokes it. Assignment makes the Squad visible in the client tracker.

The assigned player can double-click the Squad's tracker name or right-click and choose **Open Squad Sheet**. Use **Attack → optional Push → Apply Last Result**, **Finish Manually**, **Morale Check**, and **Roll Initiative**. The Squad's targeting reticle and Clear Targets controls manage its own targets. Its target summary is visible to its controller. All players can see active public effects on any tracker entry marked **Friendly**, including PCs, Individuals, Squads and Hordes. A Squad's controller also retains public effect visibility regardless of its faction. GM-only effects remain hidden, and effects visibility grants no editing or targeting permissions. The host performs requested rolls and applies results; assigned Squad attack, Push, Morale and initiative rolls are public.

The linked map token also belongs to the assigned player, subject to the GM's normal movement locks. The GM retains control of statistics, modifiers, extra-success choices and consequences. Assignment grants action control rather than editing ownership of the NPC or its source template. The player does not need to unlock the sheet. Revoking control closes the former controller's open Squad sheet, removes token control and rejects further requests. Dice already accepted by the host can finish; the GM or a new controller can finish an outstanding attack review. Ordinary public tracker information remains visible after control is removed.

# 14. The Bugs

Bugs are not required to use the same rules as human characters.

The GM should favor:

- clear battlefield roles;
- simple traits;
- strong tactical identities;
- minimal bookkeeping.

## 14.1 Common Bug Traits

The following numerical effects are approved **provisional Phase 10 defaults**. Creature trait bonuses apply to individual/elite/monster/Horde creatures, not PCs or Squads.

### Chitin

Add **1 effective Armor** to the base rating. Do not count this bonus twice in creature stat blocks.

### Fearless

**Optional narrative trait; no MVP immunity automation.** The approved roster does not receive automatic Suppression or Panic immunity.

### Scuttler

Ignore minor difficult ground on a **GM-confirmed movement action**.

### Wall Crawler

Climb vertical surfaces freely on a **GM-confirmed movement action**. Additional ceiling movement requires GM adjudication.

### Burrower

Use a designated underground Zone and GM-confirmed enter/emerge actions. Map terrain is not detected automatically.

### Pincer

Add **1 Damage to melee attacks**. This is not Armor penetration.

### Swarm

Gain **1 Bonus Die** while a different living allied creature with a supported creature trait is in the same manually named Zone. Both must be in the tracker with matching non-neutral factions.

### Acid Spray

Use a separate **Agility + Ranged Combat** attack with provisional **Damage 2**, optional Push and Apply Last Result. A successful applied hit reduces remaining effective Armor by **1**, recording that as persistent Armor loss, including if Armor cancels the Health damage. It cannot accumulate further loss once that Armor is zero, and it does not remove Cover's separate Armor dice. The hit's Armor roll uses the rating before this new loss. It uses no weapon Ammo. A Horde's Acid attack uses its configured base Attack die.

The GM repairs the loss through the target's **Traits → Armor loss** setting. Zone range and special area effects require adjudication; no automatic Acid cone or Blast is implied.

### Winged

Use GM-confirmed flight to bypass ground obstacles; the GM determines route and distance.

### Siege Organism

Add **2 Damage** against an explicitly designated fortification/vehicle/structure target.

### Fearsome

A GM-confirmed Zone entry adds **1 Suppression** to selected living enemies in the same or an explicitly adjacent named Zone. Each target is affected once per entry identifier. Increment the entry identifier for a new entry. There is no extra Composure resistance roll for this effect.

### Neural

Narrative biological command or coordination; psychic effects have **no MVP automation or approved numerical defaults**.

## 14.2 Warrior Bug

**Provisional Phase 11 reference statistics.**

**Type:** Individual\
**Role:** Close-combat infantry

**Attributes**

- Strength: d10
- Agility: d8
- Wits: d6
- Empathy: d6

**Skills**

- Close Combat: d8

Unlisted skills are untrained.

**Health:** 5

**Base Armor:** 0; **effective Armor 1 with Chitin**

**Claws**

- Damage 2 +1 from Pincer = **3 melee Damage**
- Close Combat
- Engaged range

Use Single mode for natural attacks; no Ammo Check.

**Traits:** Chitin, Scuttler, Pincer, Swarm

Provisional MVP content; subject to playtest and GM adjustment. Health 5. Base Armor 0 plus Chitin 1. Claws Damage 2 plus Pincer 1. Swarm needs a living ally in the same named Zone. Movement requires GM confirmation.

Individual movement distances, special weaknesses and unlisted powers are GM-adjudicated.

---

## 14.3 Warrior Horde

**Provisional Phase 11 reference statistics.**

**Type:** Horde\
**Role:** Mass infantry threat

**Strength:** 8/8\
**Attack Die:** d8 plus Strength Bonus Dice\
**Damage:** 2\
**Suppression:** 0\
**Resolve:** Empathy d8\
**Speed:** 1 (GM adjudicates movement)\
**Momentum:** 0

**Base Armor:** 0; **effective Armor 1 with Chitin**

**Traits:** Chitin, Swarm

Provisional MVP content; subject to playtest and GM adjustment. Strength 8; attack step 2 (d8), Damage 2, base Armor 0 plus Chitin 1. Use Mass Attack, optional Push, Apply Last Result. Strength adds the established Horde Bonus Dice. Swarm uses the existing named-Zone check. Relentless advances remain GM adjudication.

Individual movement distances, special weaknesses and unlisted powers are GM-adjudicated.

---

## 14.4 Hopper

**Provisional Phase 11 reference statistics.**

**Type:** Individual\
**Role:** Flying assault creature

**Attributes**

- Strength: d8
- Agility: d12
- Wits: d8
- Empathy: d6

**Skills**

- Close Combat: d8

Unlisted skills are untrained.

**Health:** 6

**Base Armor:** 0

**Talons**

- Damage 2
- Close Combat
- Engaged range

Use Single mode for natural attacks; no Ammo Check.

**Traits:** Winged, Fearsome

Provisional MVP content; subject to playtest and GM adjustment. Health 6; Armor 0; talons Damage 2. Flight uses GM-confirmed Winged movement. Fearsome requires GM-confirmed Zone entry and selected enemies. Dive attacks have no additional automatic bonus.

Individual movement distances, special weaknesses and unlisted powers are GM-adjudicated.

---

## 14.5 Tanker

**Provisional Phase 11 reference statistics.**

**Type:** Monster\
**Role:** Armored siege creature

**Attributes**

- Strength: d12
- Agility: d6
- Wits: d6
- Empathy: d8

**Skills**

- Close Combat: d10
- Ranged Combat: d8

Unlisted skills are untrained.

**Health:** 20

**Base Armor:** 3; **effective Armor 4 with Chitin**

**Crushing Limbs**

- Damage 4
- Close Combat
- Engaged range

Use Single mode for natural attacks; no Ammo Check.

**Traits:** Chitin, Siege Organism, Acid Spray

Provisional MVP content; subject to playtest and GM adjustment. Health 20; base Armor 3 plus Chitin 1. Crushing limbs Damage 4. Siege adds 2 Damage against a designated structure/vehicle. Use the Traits Acid Spray action for its separate provisional Damage 2 and Armor loss effect.

Individual movement distances, special weaknesses and unlisted powers are GM-adjudicated.

---

## 14.6 Plasma Bug

**Provisional Phase 11 reference statistics.**

**Type:** Monster\
**Role:** Living artillery

**Attributes**

- Strength: d10
- Agility: d8
- Wits: d8
- Empathy: d8

**Skills**

- Heavy Weapons: d10

Unlisted skills are untrained.

**Health:** 15

**Base Armor:** 2

**Plasma Discharge**

- Damage 6
- Heavy Weapons
- Extreme range
- Blast

Use Single mode for natural attacks; no Ammo Check.

**Traits:** Siege Organism

Provisional MVP content; subject to playtest and GM adjustment. Health 15; Armor 2; Plasma discharge Damage 6, Extreme range, Blast. Siege adds 2 Damage against a designated structure/vehicle. The GM adjudicates indirect fire, minimum range, setup and firing cadence. Choose affected CT targets explicitly.

Individual movement distances, special weaknesses and unlisted powers are GM-adjudicated.

---

## 14.7 Brain Bug

**Provisional Phase 11 reference statistics.**

**Type:** Monster\
**Role:** Command and intelligence creature

**Attributes**

- Strength: d6
- Agility: d6
- Wits: d12
- Empathy: d12

**Skills**

- Close Combat: d6
- Command: d10
- Influence: d10

Unlisted skills are untrained.

**Health:** 10

**Base Armor:** 0

**Feeding Tendrils**

- Damage 1
- Close Combat
- Engaged range

Use Single mode for natural attacks; no Ammo Check.

**Traits:** Neural, Fearsome

Provisional MVP content; subject to playtest and GM adjustment. Health 10; Armor 0; feeding tendrils Damage 1. Neural is a narrative GM-adjudicated trait; psychic effects and control are not automated. Fearsome uses the existing confirmed Zone-entry action.

Individual movement distances, special weaknesses and unlisted powers are GM-adjudicated.

---

# 15. Missions and Campaigns

A BUG Wars campaign is built from missions.

## 15.1 Mission Template

Each mission should define:

### Briefing

What does Command claim is happening?

### Primary Objective

What must be accomplished?

### Secondary Objective

What would improve the strategic outcome?

### Deployment

How does the squad enter?

### Known Enemy

What intelligence is available?

### Unknown Threat

What is Command wrong about?

### Escalation

How does the situation worsen?

### Extraction

How does the squad leave?

### Consequences

What changes if the mission succeeds or fails?

---

## 15.2 Escalation Clock

Use a six-step clock.

| Level | State |
|---:|---|
| 0 | Quiet |
| 1 | Contact |
| 2 | Reinforcements |
| 3 | Swarm Pressure |
| 4 | Heavy Organism |
| 5 | Position Overrun |
| 6 | Catastrophic Escalation |

Advance Escalation when:

- the squad delays;
- loud actions attract Bugs;
- an objective fails;
- a scripted event occurs;
- the GM needs to increase pressure.

The clock is not required to advance every round.

It measures the overall deterioration of the mission.

---

## 15.3 Extraction

Extraction should be treated as a real objective.

Common requirements:

- hold an LZ for a number of rounds;
- activate a beacon;
- restore communications;
- reach a tunnel exit;
- recover a vehicle;
- survive until dropship arrival.

Do not assume victory ends combat.

Sometimes the hardest part of a mission is getting out.

---

## 15.4 Campaign War Track

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

For a longer campaign, track:

**Human War Position:** 0-10\
**Bug War Position:** 0-10

Mission outcomes can shift one or both values.

Examples of Human War advantages:

- more reinforcements;
- better intelligence;
- orbital support;
- improved equipment.

Examples of Bug War advantages:

- stronger Hordes;
- new castes;
- deeper infestations;
- lost colonies;
- biological artillery.

The War Track is optional.

---

# 16. Advancement and Promotion

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

The design specification establishes XP categories and possible purchases, but supplies no numerical award schedule or purchase costs. The numbers below remain proposals; the MVP records XP and ratings without automatically enforcing advancement. Rank itself remains separate from XP.

## 16.1 Experience

At debrief, award 1 XP for each "yes."

- Did the squad complete the primary objective?
- Did the character materially contribute using their role or Specialty?
- Did the character protect another person at meaningful risk?
- Did the character survive or overcome a major threat?
- Did the character's Drive, Buddy, or personal conflict matter during the mission?

Typical award:

> **2-5 XP**

## 16.2 Improving Skills

Cost equals:

> **New Rating x 3 XP**

| Improvement | Cost |
|---|---:|
| 0 -> 1 | 3 XP |
| 1 -> 2 | 6 XP |
| 2 -> 3 | 9 XP |
| 3 -> 4 | 12 XP |

Training and narrative justification may be required for Ratings 3 and 4.

## 16.3 Learning Specialties

A new Specialty costs:

> **6 XP**

The GM may require training or field experience.

## 16.4 Improving Attributes

Attributes are difficult to improve.

Increasing an Attribute by one step costs:

> **20 XP**

Maximum Rating:

> **4**

The GM should require significant training or campaign downtime.

## 16.5 Rank

Rank is separate from XP.

Suggested ladder:

1. Private
2. Private First Class
3. Corporal
4. Sergeant
5. Staff Sergeant
6. Lieutenant

Promotion should reflect:

- battlefield leadership;
- mission performance;
- vacancies;
- Command decisions;
- campaign events.

A higher rank brings authority, access, and responsibility.

It does not automatically increase Attributes or Skills.

---

# 17. Game Master Rules

## 17.1 Keep the Objective Visible

Players should usually understand what they are trying to accomplish even when they do not know the full situation.

Good objectives:

- recover the black box;
- hold the transmitter for six rounds;
- destroy the nest entrance;
- escort the engineer;
- locate survivors;
- mark the Plasma Bug;
- reach extraction.

"Kill everything" should be rare.

## 17.2 Use Bugs as Battlefield Problems

A Bug should change what the players must do.

Examples:

**Warriors**
- close distance and overwhelm.

**Hoppers**
- bypass walls and hit support personnel.

**Tankers**
- break fortified positions.

**Plasma Bugs**
- make staying in one place dangerous.

**Brain Bugs**
- strengthen the swarm and become strategic targets.

## 17.3 Use Hordes Early

If there are more enemies than the GM wants to track individually:

> use a Horde.

The game is designed around that choice.

## 17.4 Separate Threat from Body Count

A Strength 8 Horde might represent:

- 25 large Bugs;
- 40 smaller Bugs;
- 70 immature attackers.

Strength measures battlefield effectiveness, not exact population.

## 17.5 Starting Encounter Guidelines

For four starting PCs:

### Light

- 4-6 individual Warriors;
or
- one Strength 4 Horde.

### Standard

- one Strength 6 Horde;
or
- 4 Warriors plus one Hopper.

### Hard

- one Strength 8 Horde plus a specialist Bug;
or
- two Strength 4 Hordes.

### Severe

- two Strength 6 Hordes;
or
- one Tanker with supporting Warriors.

These are playtest guidelines, not fixed balance formulas.

## 17.6 Keep Ammunition Relevant

Ammunition should influence decisions without becoming accounting.

Use:

- long defensive fights;
- uncertain resupply;
- Full Auto temptation;
- mission loadout choices.

Do not arbitrarily remove ammunition just to punish players.

## 17.7 Apply Suppression Fictionally

Suppression is not only gunfire.

Examples:

- a squadmate is torn apart;
- a Tanker breaches the wall;
- a tunnel collapses;
- the dropship is destroyed;
- Bugs emerge behind the squad.

If the event would make trained soldiers lose focus, Suppression may be appropriate.

## 17.8 Casualties Should Change the Battlefield

When friendly NPC Squads lose Strength:

- reduce firepower;
- create wounded;
- open defensive gaps;
- force players into leadership roles;
- threaten mission objectives.

Casualties should matter beyond a number.

## 17.9 Failure Should Escalate

A failed roll should not always mean "nothing happens."

Good consequences:

- lose time;
- gain Suppression;
- Ammo depletes;
- attract Bugs;
- damage equipment;
- increase Escalation;
- expose a position;
- complete the task at a cost.

## 17.10 Major Monsters

A Monster should usually have:

- one obvious strength;
- one exploitable weakness;
- one battlefield-changing action.

Do not make a Monster simply a large pile of Health.

---

# 18. Sample Mission: Hold the Line

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

This written scenario sketches an optional Outpost Defense variant. Its clocks, force strengths and escalation events have not been validated. The delivered Phase 12 [Outpost Defense: Relay K-17 module](notes/phase-12-acceptance.md) supplies its own guide, pregens and staged encounters; this chapter does not override that module's scenario settings. Use the corrected provisional creature statistics in §14; any special weakness or target-underbelly benefit needs explicit GM adjudication.

## 18.1 Situation

**Relay Outpost K-17** sits on the edge of a recently abandoned mining settlement.

Long-range communications failed six hours ago.

The player squad has been ordered to:

1. reach the outpost;
2. restore the relay;
3. hold the site until evacuation.

Command expects scattered Bug activity.

Command is wrong.

## 18.2 Battlefield Zones

Use five Zones:

1. **Command Bunker**
2. **Defensive Wall**
3. **Killing Field**
4. **Rocky Approach**
5. **Tunnel Mouth**

The Command Bunker has Fortified Cover.

The Defensive Wall has Solid Cover.

The Killing Field has Light Cover.

## 18.3 Friendly Forces

In addition to the PCs:

### Alpha Squad

- Strength 10
- Firepower d10
- Damage 2
- Armor 2
- Morale d8
- Suppression 0

### Bravo Squad

- Strength 8
- Firepower d8
- Damage 2
- Armor 2
- Morale d8
- Suppression 0

## 18.4 Mission Clock

The relay requires:

> **5 total Tech successes**

to repair.

Each repair attempt is a Slow Action.

Once activated, extraction arrives after:

> **6 rounds**

if the beacon remains operational.

## 18.5 Initial Contact

Begin with:

> Warrior Horde, Strength 4

at the Rocky Approach.

## 18.6 Escalation

### Escalation 1

Initial Horde attacks.

### Escalation 2

A second Warrior Horde, Strength 4, emerges from the Tunnel Mouth.

### Escalation 3

The larger Horde increases to Strength 6 or receives reinforcements.

### Escalation 4

A Hopper attacks the Command Bunker or rear position.

### Escalation 5

A Tanker appears at the Rocky Approach.

### Escalation 6

The defensive line collapses unless extraction is already inbound.

## 18.7 Tanker Objective

The Tanker does not need to be killed.

Possible solutions:

- heavy weapons;
- demolitions;
- lure it into a prepared charge;
- target the underside;
- delay it until extraction.

## 18.8 Extraction

When the timer reaches zero, a dropship arrives.

The squad must reach the designated extraction Zone.

Any character or Squad left behind is a casualty unless another plan has been established.

## 18.9 What This Mission Tests

The scenario is successful as a playtest if it meaningfully uses:

- ammunition;
- Suppression;
- Rally;
- command actions;
- NPC Squad losses;
- Horde Strength;
- Momentum;
- heavy weapons;
- Critical Injuries;
- extraction pressure.

The GM should record which systems feel slow.

---

# 19. Quick Reference

## Core Test

Attribute die + trained Skill die; Skill 0 adds no die. Step modifiers affect the Attribute/base die, bounded d6–d12. Bonus Dice are d6s.

| Result | Successes |
|---|---:|
| 1–5 | 0 |
| 6–9 | 1 |
| 10–11 | 2 |
| 12 | 3 |

Difficulty: 1 routine under pressure; 2 difficult; 3 severe; 4+ extreme.

## Push

Once per eligible test: keep ones and successes; reroll only 2–5; gain **1 Stress**. An attack that requires an Ammo Check owes a second check after Push if ammunition remains. Resolve, injury treatment and independent Squad Morale checks cannot be pushed.

## Actions and Movement

One Slow and one Fast Action; exchange Slow for Fast if desired. A Fast move covers one Zone. Rally is Fast in the design-spec list. Sprint, reactions and other optional action details require GM agreement; action use and movement are not automatically enforced.

## Normal Firing Modes

| Mode | Attack benefit | Ammo depletion |
|---|---|---|
| Single | None | No check |
| Burst | +1 Bonus Die | 1–2 |
| Full Auto | +2 Bonus Dice | 1–3 |
| Suppressive | Resolve resistance for each selected target | 1–2 |

Failed Suppressive resistance adds 1 Suppression and, for a Horde, loses 1 Momentum. No direct Damage. Fire at Will changes thresholds to Single 1–2, Burst/Suppressive 1–3, Full Auto 1–4.

Ammo: **d12 → d10 → d8 → d6 → Empty**. Reload restores the listed maximum; supplies are manual.

## Suppression and Resolve

| Value | State |
|---:|---|
| 0–1 | Effective |
| 2 | Shaken: −1 Attribute step on Command/Recon |
| 3 | Suppressed: also −1 base step on combat tests |
| 4 | Pinned: no offensive Full Auto until rallied below 4 |
| 5+ | Panic test |

Resolve: **Empathy die alone**, or Squad Morale die; one success. Panic resolves to Suppression 4 after either outcome, preserving any lower intervening value. Failed consequences are GM-selected. The recorded Resolve score is not the trigger.

## Hordes

| Strength | Attack Bonus Dice |
|---:|---:|
| 1–3 | 0 |
| 4–6 | 1d6 |
| 7–9 | 2d6 |
| 10+ | 3d6 |

| Damage after Armor | Strength loss |
|---:|---:|
| 0 | 0 |
| 1–2 | 1 |
| 3–4 | 2 |
| 5+ | 3 |

Blast adds 1 Strength loss only when Damage remains. Momentum: 0 Stalled, 1 Pressing, 2 Charging, 3 Overrunning. See §12.4 for triggers.

## Squads

Attack uses Firepower, without Horde Strength Bonus Dice. Default Damage 2, Armor 2, Strength 10, Firepower d10, Morale d8. Each uncancelled Damage removes **one Strength**. Below 25% surviving Strength: a Morale check each round; failure is GM-adjudicated. Zero Strength defeats a group without individual Critical Injuries.

## Armor, Broken and Treatment

Each 6 on an Armor d6 cancels 1 Damage. Light/Standard/Heavy Infantry Armor: rating and Bulk **1/2/3**. Equipped armor adds to manual Base Armor once.

An individual first reaching 0 Health becomes Broken and rolls one d12 Critical Injury. Repeated zero updates do not roll again. Resolve: Broken grants one attempted action. Treatment is **Wits + Medical**, one success for the initial table, no Push; it stabilizes the selected injury without automatically restoring Health. Fatal timers start disabled.

## Rally and Commands

Rally: Empathy + Command; at difficulty 1, remove one Suppression per success from one ally. Other commands have fixed benefits. Temporary orders last until the **next round starts**. See §11 for recipients and effects.

---

# 20. Playtest Notes

BUG Wars is intended to be tested before rules expansion.

The first major milestone is not a large equipment catalog or vehicle chapter.

It is this encounter:

> Four to six troopers and a small friendly unit defend an isolated position against approximately one hundred Bugs while ammunition declines, Suppression rises, the line takes casualties, a heavy organism breaches the perimeter, and extraction becomes the final objective.

The core system is working when:

- the GM does not track individual swarm creatures;
- a Horde turn takes less than one minute;
- players voluntarily use Suppressive Fire;
- leaders voluntarily use Command actions;
- ammunition changes player decisions;
- Heavy Weapons have a distinct role;
- Suppression changes tactics without removing players from the game too often;
- Critical Injuries create urgency;
- a large battle takes about as long as a normal medium-sized RPG combat.

## 20.1 Recommended Test Sequence

### Test A — Fire Team

4 PCs vs. 8 individual Warriors.

Test:

- core attacks;
- Armor;
- Damage;
- optional reactions, if adopted;
- Critical Injuries.

### Test B — Horde

4 PCs plus one friendly Squad vs. a Strength 8 Warrior Horde.

Test:

- Horde Damage;
- Momentum;
- Suppressive Fire;
- NPC Squad rules.

### Test C — Tanker

4-6 PCs vs. one Tanker with limited support.

Test:

- optional Anti-Armor, if adopted;
- optional Called Shots and any GM-approved weakness;
- heavy weapons;
- Monster pacing.

### Test D — Outpost

Run **Hold the Line**.

Test everything together.

## 20.2 Record These Metrics

During testing, record:

- average rounds per encounter;
- average attacks before a weapon reaches Empty;
- PC Health lost;
- number of Critical Injuries;
- Suppression gained;
- Rally actions used;
- Horde turns per battle;
- Horde survival time;
- NPC Squad losses;
- Tanker survival time;
- total session combat time.

Change rules from evidence rather than intuition.

---

# Appendix A: Rules Summary for Character Sheets

## Derived Values

**Health**
> 3 + Strength

**Resolve**
> 2 + Empathy

**Carry**
> 4 + Strength

## Step Dice

| Rating | Die |
|---:|---|
| 0 | — |
| 1 | d6 |
| 2 | d8 |
| 3 | d10 |
| 4 | d12 |

## Character Creation Skills

**Optional tabletop proposal — requires GM agreement; not an approved MVP default.**

The approved software initializes skills at 0 and does not assign a trained-skill budget. If the group adopts §3.4:

- one Skill 3;
- two Skills 2;
- three Skills 1;
- remaining Skills 0.

## Starting Attributes

> 4, 3, 2, 2

## Starting Specialty

Optional §3.5 proposal: **1 archetype Specialty**. The approved reference module supplies choices but does not issue one automatically.

---

# Appendix B: Future Modules

The following are intentionally outside the core playtest rules:

- full Powered Armor system;
- Marauder-style assault suits;
- vehicles;
- dropships;
- starship combat;
- orbital support rules;
- Fleet player characters;
- psionics;
- advanced Bug castes;
- strategic logistics;
- colony management;
- campaign generation;
- detailed prosthetics;
- military awards.

These systems should be added only after the infantry, Horde, Suppression, and Command rules are stable.

---

# Appendix C: Development and Distribution Note

BUG Wars is written as an original military science-fiction game framework.

For private campaigns, groups may adapt the game to their preferred setting.

Before public or commercial distribution:

- verify the current Year Zero Engine licensing requirements;
- include any required attribution;
- use original setting text and artwork;
- avoid unlicensed names, characters, factions, equipment, creatures, or text from other properties;
- keep game mechanics and setting-specific presentation separated where practical.

---

# Appendix D: Edition 0.2 Accuracy Baseline

Fantasy Grounds Manual Roll cancellation releases the unfinished test. Cancelling a Push preserves the previous completed result and its Push availability, and refunds the Stress added by that cancelled Push. An attack already awaiting Apply remains available. Use `/bwcancel` to abandon a test interrupted by a reload: on the host this acts on the current Combat Tracker turn; on a player client it acts on the active character. This does not cancel committed damage or Ammo jobs. For tests left unfinished by builds before v0.12.6, the command conservatively keeps existing Stress and Push availability; the GM should check those values. `/bwresume` continues to resume combat jobs and points an active actor with an unfinished test to `/bwcancel`.

Reviewed against the local [design specification](BW_YZE_DESIGN_SPEC.md), [build specification](BW_FG_BUILD_SPEC.md), approved phase decisions, production managers in `BWyze/scripts`, and [Phase 11 reference content](reference-module/content.json).

Key implementation/default references:

- [Dice, Push and Ammo defaults](notes/phase-0-3-acceptance.md)
- [Combat, Resolve and Suppression](notes/phase-4-5-acceptance.md)
- [Critical Injury defaults](notes/phase-6-acceptance.md)
- [Hordes](notes/phase-7-acceptance.md) and [Squads](notes/phase-8-acceptance.md)
- [Commands](notes/phase-9-acceptance.md)
- [Creature traits](notes/phase-10-acceptance.md) and [reference roster/equipment](notes/phase-11-acceptance.md)

Older acceptance documents describe the build at that phase. Later approved decisions and current source take precedence where they add or correct behavior. Full findings and remaining proposal decisions are in the [accuracy review](notes/rulebook-accuracy-review.md).

---

# End of Core Rulebook

**BUG Wars — Playtest Edition 0.2**
