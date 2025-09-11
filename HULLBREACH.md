# HULLBREACH

## 0. Introduction

HULLBREACH is a rules-light sci‑fi RPG of armoured marines raiding derelict starships for salvage while surviving wounds, malfunctions, and rising panic.

## 1. Core Game Rules

### 1.1 Skill Tests

Each character has four attributes, each with a rating of 1 to 3.

| Attribute  | Description                                |
| ---------- | ------------------------------------------ |
| **Might**  | Melee, breaching, raw strength             |
| **Reflex** | Dodging, aiming, piloting                  |
| **Tech**   | Hacking, sensors, demolitions, interfacing |
| **Grit**   | Endurance, survival, pain threshold        |

When performing an action where the outcome is uncertain you will select a piece of gear to use: a weapon, a software module or your suit. Each piece of gear has a **Skill Rating** and a **Malfunction Rating**. When making a test:

1. **Assign Difficulty**
   - The **Mission Commander** determines how many successes are required to complete the action
     - **Easy** tasks require **1 Success**
     - **Normal** tasks require **2 Successes**
     - **Hard** tasks require **3 Successes** or more.

2. **Build the Dice Pool**
   - Roll a number of **d6 = Attribute + Gear Skill Rating**.
   - Minimum: 1 die is always rolled.

3. **Count Successes**
   - Each roll of **5 or 6** = **1 success**.
   - The skill test is successful as long as you have scored at least as many successes as the difficulty rating.

4. **Malfunctions**
   - If you roll a number of **1s** equal or greater than the **Malfunction Rating** a single test, a malfunction occurs.
   - If you roll fewer dice than the **Malfunction Rating**, a malfunction only occurs if **all dice are 1s**.
   - Malfunctions occur even if the test succeeds.
   - Roll on the relevant **Malfunction Table**.

### 1.2 Challenges

Some tests represent an ongoing activity rather than a simple pass fail. This includes things like clearing the jam from a gun, hacking a computer terminal or repairing a piece of machinery. In these cases the **Mission Commander** will assign a Challenge Rating - the total number of successes needed to complete the task.

The Dice Pool is assembled as before. Multiple Skill Tests can be attempted against the task with successes accumulating against the Challenge Rating. Each attempt takes a certain amount of time. Once a number of successes equal or greater to the Challenge Rating have been achieved the task has been completed successfully. If a Malfunction is rolled during the attempt then the task has failed and either the task can no longer be attempted or all successes against the challenge are lost and the task must be started over (Mission Commander's discretion).

## 2 Character Creation

### 2.1 Generate Attributes

Roll 1d4-1 each for **Might**, **Reflex**, **Tech** and **Grit** to determine your attribute ratings.

You may reduce an attribute by 2 points to increase another by 1 point. No attribute may start higher than 3 or lower than -2 (armour and gear may modify attributes beyond these limits later).

### 2.2 Cool Points

**Cool Points** represent your character's composure and ability to deal with stressful situations. These are reduced by stressful situations, such as equipment malfunctions and encountering horrors. At **0 Cool Points** your character **Freaks Out**.

### 2.3 Rank

Rank measures your experience and seniority within **HULLBREACH**. There are 4 ranks:

| Rank | Name       |
| ---- | ---------- |
| 1    | Trooper    |
| 2    | Sergeant   |
| 3    | Lieutenant |
| 4    | Captain    |

All characters start at Rank 1 (Trooper). You may only acquire and use gear of a tier equal to your rank or lower. You do not have the requisite training or security clearance to use gear of a higher tier. You may be awarded a promotion to a higher rank by your Mission Commander for successfully completing missions, displaying valour on the battlefield or posthumously.

### 2.4 Choose your Armour

You may choose your **Armour Model**. This determines how much gear you can carry and how good you are at basic physical tasks.

| Armour Model   | Hit Points | Armour Rating | Manoeuvre Rating | Power Rating | Carry Capacity | Computer Rating | Malfunction Rating | Notes                  |
| -------------- | ---------- | ------------- | ---------------- | ------------ | -------------- | --------------- | ------------------ | ---------------------- |
| **Wraith**     | 8          | 1             | 3                | 1            | 7              | 2               | 3                  | Fast and lightweight   |
| **Vindicator** | 10         | 1             | 2                | 2            | 9              | 1               | 3                  | Standard issue         |
| **Bastion**    | 12         | 2             | 1                | 3            | 8              | 1               | 3                  | Tough and lumbering    |
| **Guardian**   | 10         | 1             | 1                | 2            | 10             | 3               | 3                  | Good for support roles |

1. **Hit Points**: This is the total amount of damage you can sustain before your suit is destroyed.
2. **Armour Rating**: This is your Armour Rating. All incoming damage is reduced by this amount.
3. **Manoeuvre Rating**: This is your skill rating for running, jumping, dodging and other physical activities that require agility.
4. **Power Rating**: This is your skill rating for throwing, punching, lifting, pushing and crushing objects and other activities that require brute strength.
5. **Carry Capacity**: This is the number of Gear Slots you have to carry equipment. Regulations forbid exceeding this value.
6. **Computer Rating**: This is the total number of programs your onboard computer can store and run.
7. **Malfunction Rating**: This is the Malfunction Rating that applies when making skill tests with your armour's basic abilities.

Your armour has the following gear built in

| Item                | Slots | SR  | MR  | Cost | Description                                                                                           |
| ------------------- | ----- | --- | --- | ---- | ----------------------------------------------------------------------------------------------------- |
| **Basic Visor HUD** | 0     | 1   | 3   | 0    | What you can see. Comes with basic object identification and tagging. Requires light source.          |
| **Head Torch**      | 0     | 1   | 3   | 0    | Provides illumination within current zone.                                                            |
| **Comms Suite**     | 0     | 1   | 3   | 0    | Allows radio communication with the rest of your unit.                                                |
| **Life Support**    | 0     | 1   | 3   | 0    | Provides heat & air filtration and an internal reserve for 1 hour.                                    |
| **Medical Support** | 0     | 1   | 3   | 0    | Provides medical support to maintain trooper efficiency even in the face of extreme trauma.           |
| **Autopilot**       | 0     | 1   | 3   | 0    | In the event of loss of conciousness or ability to complete the mission the autopilot will take over. |

### 2.5 Choose Gear

You may select gear up to your carry capacity from a tier available to your Rank. You may install a number of software modules equal to your computer rating from a tier available to your Rank.

### 2.6 Define Your Marine

Give your marine a callsign. You may roll or choose from the following if you wish.

| d66 | 1      | 2      | 3         | 4       | 5        | 6       |
| --- | ------ | ------ | --------- | ------- | -------- | ------- |
| 1   | Raven  | Viper  | Ghost     | Titan   | Hammer   | Wraith  |
| 2   | Falcon | Cobra  | Shade     | Atlas   | Anvil    | Mirage  |
| 3   | Jackal | Raptor | Ember     | Goliath | Breaker  | Phantom |
| 4   | Nomad  | Vector | Aegis     | Banshee | Havoc    | Scythe  |
| 5   | Echo   | Apex   | Neon      | Kraken  | Forge    | Zero    |
| 6   | Oracle | Badger | Manticore | Thunder | Catalyst | Spectre |

Give your marine a trait. You may roll or choose from the following if you wish.

| d66 | 1 - 2           | 3 - 4            | 5 - 6                 |
| --- | --------------- | ---------------- | --------------------- |
| 1   | Wisecracker     | Cautious Planner | Twitchy Trigger       |
| 2   | Veteran Cynic   | Morale Booster   | Paranoid Scanner      |
| 3   | Rookie Optimist | Calm Under Fire  | Loyal to a Fault      |
| 4   | By-the-Book     | Superstitious    | Battlefield Tactician |
| 5   | Hot-Headed      | Mission-First    | Gallows Humour        |
| 6   | Profit-Minded   | Glory Hound      | Door-Kicker           |

## 3. Gear

### 3.1 Utility Gear

TBD:- I need to review these items and add Tiers. Include upgrades to the basic armour equipment.

| Tier | Item                       | Slots | SR  | MR  | Cost | Description                                                                           |
| ---- | -------------------------- | ----- | --- | --- | ---- | ------------------------------------------------------------------------------------- |
|      | **Armour Patch Foam**      | 1     | 1   | 4   | 2 RP | Seals breaches, restores 1 DRR for remainder of mission. Consumable (1 use).          |
|      | **Bioscanner**             | 1     | 2   | 3   | 3 RP | Picks up heat/life signs; range = 2 zones.                                            |
|      | **Black Ice Deck**         | 3     | 3   | 2   | 5 RP | Advanced hacking; can attack systems. On malfunction: feedback damage (d2).           |
|      | **Chameleon Mesh**         | 2     | 3   | 2   | 4 RP | Active camouflage. +2 dice to hide in cover. On malfunction: turns neon-bright.       |
|      | **Climbing Rig**           | 1     | 1   | 4   | 1 RP | Ropes & ascenders. Grants +2 SR on climb tests.                                       |
|      | **Cybernetic Spares**      | 2     | 2   | 3   | 4 RP | Emergency replacement limb/eye; restores function but may glitch (new flaw).          |
|      | **Data Spike**             | 1     | 1   | 2   | 2 RP | Brute-force breach tool. +2 SR vs electronic locks.                                   |
|      | **Field Surgery Kit**      | 2     | 2   | 3   | 3 RP | Stabilizes crippled limbs; restores Broken results 2 or 3.                            |
|      | **Grapple Gun**            | 2     | 2   | 3   | 3 RP | Fires line 2 zones. Move Reflex test auto-succeeds if grapple attached.               |
|      | **Industrial Cutter**      | 2     | 2   | 3   | 3 RP | Destroys crates, plating, alien bone; doubles as crude melee (Dmg 2, Unreliable).     |
|      | **Mag Boots**              | 1     | 1   | 4   | 2 RP | Walk in zero-G. On malfunction: stuck or release fails.                               |
|      | **Medi-Pack**              | 1     | 2   | 4   | 2 RP | Restores d6 HP with Tech test. Consumable (3 uses).                                   |
|      | **Monotool**               | 1     | 1   | 4   | 1 RP | Universal wrench/driver/saw; grants +1 die to basic repairs.                          |
|      | **Motion Tracker**         | 1     | 2   | 3   | 2 RP | Detects movement in adjacent zones. May reveal false positives on malfunction.        |
|      | **Nanite Injector**        | 1     | 2   | 2   | 3 RP | Restores 2d4 HP but adds “Corruption” (flaw roll at mission end).                     |
|      | **Override Chip**          | 1     | 0   | -   | 1 RP | Single-use passkey. Auto-unlocks a standard door/terminal.                            |
|      | **Plasma Welder**          | 2     | 2   | 3   | 3 RP | Cuts through bulkheads/doors (Task HP -1); can seal doors.                            |
|      | **Portable Breach Charge** | 2     | 2   | 2   | 3 RP | Blows open bulkhead/door (Task HP instantly 0). 1 use only.                           |
|      | **Repair Kit**             | 1     | 2   | 4   | 2 RP | Restores 1 DRR to armor/gear with Tech test. Consumable (3 uses).                     |
|      | **Seismic Probe**          | 2     | 3   | 3   | 4 RP | Maps weak points; reduces Task HP by 2 when breaching/cutting.                        |
|      | **Signal Scrambler**       | 1     | 1   | 3   | 2 RP | Jams comms in 1 zone; hostile AI lose 1 die to tests.                                 |
|      | **Spectral Analyzer**      | 1     | 2   | 2   | 3 RP | Detects cloaked/stealthed targets. On malfunction: ghost echoes.                      |
|      | **Standard Cyberdeck**     | 2     | 2   | 3   | 3 RP | Hack doors, turrets, terminals (Task HP -1).                                          |
|      | **Stasis Spray**           | 1     | 1   | 4   | 2 RP | Freezes corrosion/acid/bleeding. Restores 1d4 HP if applied immediately after injury. |
|      | **Survey Drone**           | 2     | 2   | 2   | 4 RP | Remote recon drone (range 3 zones). On malfunction: attracts attention.               |
|      | **Thruster Pack**          | 2     | 2   | 2   | 4 RP | Short burst (move 2 zones, vertical or zero-G). On malfunction: spin out.             |

### 3.2 Armour Enhancements

Ablative armour

### 3.3 Melee Weapons

| Tier | Weapon Name             | Hands | Slots | Range | SR  | MR  | Dmg | Cost | Special                                        |
| ---- | ----------------------- | ----- | ----- | ----- | --- | --- | --- | ---- | ---------------------------------------------- |
| 1    | **Combat Knife**        | 1H    | 1     | Short | 2   | 4   | 1   | 1 RP | Always ready; can be thrown (Short, Dmg 1)     |
| 1    | **Shock Baton**         | 1H    | 1     | Short | 2   | 3   | 1   | 2 RP | Stun: on 2+ successes, target loses 1 action   |
| 2    | **Chainsword**          | 1H    | 2     | Short | 3   | 3   | 2   | 3 RP | Brutal; Unreliable                             |
| 2    | **Power Axe**           | 2H    | 2     | Short | 3   | 2   | 3   | 4 RP | Armor-Piercing; Kickback                       |
| 3    | **Monomolecular Blade** | 1H    | 1     | Short | 4   | 3   | 2   | 5 RP | Ignores armor on a crit                        |
| 3    | **Chainfist**           | 2H    | 3     | Short | 4   | 2   | 3   | 6 RP | Counts as breaching tool (Task HP -1 per roll) |
| 4    | **Power Hammer**        | 2H    | 3     | Short | 5   | 2   | 4   | 8 RP | Stuns all enemies in same zone on crit         |
| 4    | **Void Scythe**         | 2H    | 2     | Short | 5   | 1   | 3   | 9 RP | Shredding; may sweep across 2 targets          |

### 3.4 Projectile Weapons

| Tier | Weapon Name              | Hands | Slots | Range  | SR  | MR  | Dmg | Reload | Cost  | Special                                                  |
| ---- | ------------------------ | ----- | ----- | ------ | --- | --- | --- | ------ | ----- | -------------------------------------------------------- |
| 1    | **Slugspitter 9mm**      | 1H    | 1     | Short  | 2   | 3   | 1   | 1      | 1 RP  | Reliable, cheap sidearm                                  |
| 1    | **Viper PDW**            | 2H    | 1     | Short  | 2   | 3   | 1   | 1      | 2 RP  | Burst capable                                            |
| 1    | **Ironclad Mk.12**       | 2H    | 2     | Medium | 3   | 4   | 1   | 2      | 2 RP  | Rugged; +1 MR (hard to break)                            |
| 1    | **Banshee .45**          | 1H    | 1     | Short  | 2   | 2   | 1   | 1      | 1 RP  | Deafening; +1 to Reaction rolls nearby                   |
| 2    | **Direwolf Carbine**     | 2H    | 1     | Medium | 3   | 3   | 1   | 1      | 3 RP  | Suppression capable                                      |
| 2    | **Havoc-10 Auto**        | 2H    | 1     | Short  | 3   | 2   | 1   | 1      | 3 RP  | Auto fire; reroll 1 die/attack; Unreliable               |
| 2    | **Gorgon Handcannon**    | 1H    | 2     | Short  | 2   | 2   | 2   | 1      | 4 RP  | Devastating; MR 2                                        |
| 2    | **Hammerjack**           | 2H    | 2     | Short  | 3   | 3   | 2   | 1      | 3 RP  | +1 die within Short range                                |
| 3    | **Hellkite DMR**         | 2H    | 2     | Long   | 4   | 3   | 2   | 2      | 5 RP  | Precision: convert 1 success to crit                     |
| 3    | **Maelstrom MG**         | 2H    | 2     | Medium | 4   | 2   | 1   | 2      | 6 RP  | Suppression & Full Suppression capable; Overheat         |
| 3    | **Cerberus Tri-Pistol**  | 1H    | 1     | Short  | 3   | 2   | 1   | 1      | 5 RP  | Triple Burst; MR check each use                          |
| 3    | **Tombstone Riotgun**    | 2H    | 2     | Short  | 4   | 3   | 2   | 2      | 5 RP  | Shredding shells: armor counts as -1 tier; Burst capable |
| 4    | **Oblivion Rail-Pistol** | 1H    | 1     | Medium | 4   | 2   | 2   | 2      | 8 RP  | Armor-Piercing                                           |
| 4    | **Hydra Rotary Cannon**  | 2H    | 3     | Medium | 5   | 2   | 1   | 3      | 10 RP | Auto fire (+2 SR); Full Suppression capable; Overheat    |
| 4    | **Eidolon Silent Rifle** | 2H    | 1     | Long   | 4   | 3   | 2   | 2      | 7 RP  | Silent; malfunctions only on 2 ones                      |
| 4    | **Colossus Breaker**     | 2H    | 3     | Long   | 5   | 1   | 3   | 3      | 10 RP | Each success = 3 dmg; recoil: -1 Reflex next round       |

### 3.5 Special Weapons

| Tier | Weapon Name            | Hands | Slots | Range  | SR  | MR  | Dmg | Reload | Cost  | Special                                            |
| ---- | ---------------------- | ----- | ----- | ------ | --- | --- | --- | ------ | ----- | -------------------------------------------------- |
| 1    | **Incendiary Thrower** | 2H    | 2     | Short  | 2   | 3   | 2   | 1      | 3 RP  | Area attack (all in zone); Unreliable              |
| 2    | **Flame Projector**    | 2H    | 2     | Short  | 3   | 2   | 2   | 2      | 4 RP  | Suppression capable; Shredding                     |
| 2    | **Plasma Torch**       | 1H    | 1     | Short  | 2   | 3   | 2   | 1      | 3 RP  | Dual-use: melee cutter or ranged blast (Short)     |
| 3    | **Heavy Flamer**       | 2H    | 3     | Medium | 4   | 2   | 3   | 2      | 6 RP  | Area attack (zone + adjacent); Overheat            |
| 3    | **Plasma Ejector**     | 2H    | 2     | Medium | 4   | 2   | 3   | 2      | 6 RP  | Armor-Piercing; Friendly Splash                    |
| 4    | **Inferno Cannon**     | 2H    | 3     | Long   | 5   | 2   | 4   | 3      | 9 RP  | Full Suppression capable; area burns for d3 rounds |
| 4    | **Plasma Incinerator** | 2H    | 3     | Medium | 5   | 1   | 4   | 3      | 10 RP | Catastrophic on crit fail (auto Malfunction)       |

### 3.5 Ammunition

| Tier | Gear Name              | Slots | Reloads / Effect                           | Cost   | Special                                                             |
| ---- | ---------------------- | ----- | ------------------------------------------ | ------ | ------------------------------------------------------------------- |
| 1    | **Ammo Pouch**         | 1     | 3 reloads (Reload 1 weapons only)          | 1 RP   | Standard issue. Simple reload action.                               |
| 1    | **Spare Magazine**     | 0.5   | 1 reload (handgun/SMG only)                | 0.5 RP | Can be stashed in pockets.                                          |
| 2    | **Bandolier Rig**      | 1     | 4 reloads (any weapon)                     | 2 RP   | May reload as free action once per mission.                         |
| 2    | **Drum Magazine**      | 1     | 2 reloads (LMG/SMG/Shotgun only)           | 2 RP   | Reload Rating reduced by 1.                                         |
| 2    | **Ammo Satchel**       | 2     | 6 reloads (mixed weapon types)             | 3 RP   | Bulky. Takes 2 hands to access in combat.                           |
| 3    | **Belt Feed Unit**     | 2     | Continuous feed: 5 reloads (LMG/MG only)   | 4 RP   | Ignore Reload Rating 2 once per combat.                             |
| 3    | **Quick-Loader Frame** | 1     | 3 reloads (any)                            | 4 RP   | Reduce Reload Rating by 1 (min 1).                                  |
| 4    | **Ammo Backpack**      | 3     | Continuous feed: 8 reloads (any 2H weapon) | 6 RP   | Can sustain Auto/Suppression for 3 turns before Ammo Die is rolled. |
| 4    | **Auto-Loader Module** | 2     | 4 reloads (any)                            | 7 RP   | Reloads occur automatically when weapon empties; no action needed.  |

### 3.6 Explosives & Grenades

Marines deploy a variety of grenades and demolitions:

- Frag grenades, incendiaries, stun grenades.
- Satchel charges and anti-armor rockets.

Explosives have:

- **Blast Radius** (zones).
- **Damage dice** applied to all in zone.
- **Malfunctions** (dud, misfire, dropped grenade, premature detonation).

### 3.7 Software Modules (Placeholder)

**Standard Operating Procedure Modules (SOPMODs):**
AI-driven computer modules installed in the suit. Provide “skills on a stick.”

Examples:

- **Negotiation SOPMOD** - for NPC interactions.
- **Interrogation SOPMOD** - bonus for extracting info.
- **Xenology SOPMOD** - knowledge of alien biology.
- **Command SOPMOD** - improves Rally actions and Panic reduction.

### 3.8 Combat Drugs

Combat stims enhance performance at a cost.

- **Adrenastim**: boost Reflex, cause HP loss after.
- **Pain-X**: ignore wound penalties, but collapse after.
- **Focusin**: boost Tech, but induce paranoia.
- **Regen Patch**: heal HP, but risk mutation.

Each drug has:

- **Boost Effect.**
- **Crash Effect.**
- **Overdose/Malfunction chance.**

### 3.9 Special Services

Drop Pods, resupplies, advanced recon. Mission pod - offline support: extra equipment / resupply.

## 4. Malfunction Tables

| d6  | Armour Malfunctions |
| --- | ------------------- |

| d6  | Utility Gear Malfunctions                                                        |
| --- | -------------------------------------------------------------------------------- |
| 1   | **Power Drain.** Gear flickers out, requires 1 action to reboot.                 |
| 2   | **Overheat.** Tool sears user - take **1 damage**.                               |
| 3   | **Misread.** Scanner gives false info (phantom blips, wrong life signs).         |
| 4   | **Lockout.** Gear locks; requires **Tech test (2 successes)** to restore.        |
| 5   | **Feedback.** Sparks/shock: user takes **d2 damage**, nearby electronics glitch. |
| 6   | **Catastrophic Short.** Tool fries itself. Destroyed in sparks and smoke.        |

When a melee weapon (chainsword, power axe, etc.) malfunctions, roll on this table:

| d6  | Melee Weapon Malfunctions                                                                                                                   |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Slipped Grip.** You fumble the weapon. Costs 1 action to recover.                                                                         |
| 2   | **Stuck Fast.** Weapon bites deep into wall, floor, or enemy. Requires a **Might test (2 successes)** to pull free. Until then, it’s stuck. |
| 3   | **Overload.** Power field or chain drive overheats. Take **d2 damage** from feedback; weapon is unusable until repaired (Tech 2).           |
| 4   | **Kickback.** Weapon recoils violently. You fall prone unless you pass a **Reflex test (2 successes)**.                                     |
| 5   | **Friendly Nick.** In the chaos, your swing clips an ally in the same zone for **d2 damage**.                                               |
| 6   | **Catastrophic Break.** Blade shatters / chain seizes. Weapon is destroyed in a spray of shards or sparks; you take **d3 damage**.          |

When a projectile weapon malfunctions, roll on the following table:

| d6  | Projectile Weapon Malfunctions                                                                                                                                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Accidental Ammo Ejection.** Mag or shells spill out. Weapon is empty and must be reloaded.                                                                              |
| 2   | **Jam (2).** Weapon locks. Requires a **Tech test using the weapon’s SR**, needing **2 successes** to clear. Until cleared, weapon cannot fire.                           |
| 3   | **Stuck on Full Auto.** Weapon goes wild, spraying uncontrollably. Requires a **Tech test (3 successes)** to repair. If failed, weapon becomes **Jam (3)** until cleared. |
| 4   | **Accidental Discharge.** Weapon fires into a random friendly in the same zone (ally must roll Reflex to avoid).                                                          |
| 5   | **Burst Pipe.** The shot ruptures old ship infrastructure. Roll on the Environmental Hazards Sub-Table.                                                                   |
| 6   | **Barrel Rupture.** Weapon explodes. It is destroyed. Holder takes **d3 damage**.                                                                                         |

Flamers, plasma throwers, and other volatile heavy weapons are powerful but risky. When they malfunction, roll on this table:

| d6  | Special Weapon Malfunctions                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Pilot Light Out.** Flamer fails to ignite. Spend 1 action to reignite.                                                                           |
| 2   | **Fuel Leak.** Tank or hose leaks. You are drenched in flammable liquid. Next fire source that hits you deals **+d6 damage**.                      |
| 3   | **Backwash.** Fuel vents backwards. Take **d3 damage** and armor degrades 1 tier.                                                                  |
| 4   | **Blowback.** Plasma vent or fuel line bursts. Everyone in same zone makes a **Reflex test (2 successes)** or takes **d2 damage**.                 |
| 5   | **Friendly Splash.** Flame jet arcs wide, catching an ally in the same zone for **d3 damage**.                                                     |
| 6   | **Catastrophic Explosion.** Tank or plasma coil detonates. You take **d6 damage**; all others in Short range take **d3 damage**. Weapon destroyed. |

## Setting (Draft)

The marines are survivors of the **HULLBREACH Incident**.
- Their mothership, the *Oath of Iron*, was lost in the **Graveyard**, a vast orbital field of wrecked warships, colony craft, and alien hulks.
- The Graveyard is a frontier where **multiple alien factions** lurk:
  - Hive predators.
  - Rogue AI war machines.
  - Parasitic infestations.
  - Opportunistic scavengers.
- The marines’ objective: **salvage, survival, and containment**.

The *Oath of Iron* still drifts somewhere in the Graveyard — damaged, cut off, crew scattered. Marines launch missions into derelicts using strike pods, hoping to regroup and survive.

## Exploring Derelicts and Running Missions

Missions revolve around exploring derelict spacecraft in the **graveyard zone**.

Key interactive elements:

- **Doors** — locked, welded, jammed. Require breaching, hacking, or explosives.
- **Computers** — may hold intel, control turrets, or be corrupted by alien code.
- **Bulkheads & Hazards** — collapsed corridors, breached hulls, radiation zones.
- **Environmental Events** — power surges, decompressions, shifting wreckage.

Rules will give these elements **Task HP, malfunctions, and risks**.

### Time & Movement

### Zones

### Doors, Terminals Etc

### Scanning

### Scanners & Blips (Placeholder)

Scanners detect “blips.” Each may be:

- A real enemy.
- A ghost image.
- Environmental noise.

Operators spend actions to interpret blips.

Scanner Malfunctions:

- False positives.
- Ghost echoes.
- Enemies appear in wrong zones.

---

### Stealth (Placeholder)

Stealth uses **Stealth Points (SP)** like hit points.

- A successful stealth roll = SP gained.
- Detection attempts reduce SP.
- At SP 0 = detected.

Rules:

- Firing ranged weapons ends stealth immediately.
- Melee (silent) weapons do not.
- Stealth gear provides limited uses per mission (battery cycles).

### Environmental Hazards Sub-Table (d6)

| d6  | Hazard                                                                                                                                                       |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1-2 | **Steam Vent.** Scalding steam fills the zone. Everyone takes **1 damage** unless in sealed armor. Visibility reduced until end of round.                    |
| 3-4 | **Toxic Gas.** Corrosive fumes spread. Anyone without respirators or sealed armor must succeed a **Grit test (2 successes)** or take **d2 damage**.          |
| 5   | **Acid Spray.** Pipes burst, spraying acid. Everyone in zone takes **d3 damage** and armor degrades 1 tier.                                                  |
| 6   | **Vacuum Breach.** Hull tears open slightly. Everyone must pass a **Reflex test (2 successes)** or be pulled into cover/ground; unanchored gear may be lost. |

### Panic & Rising Tension (Placeholder)

Marines track **Panic Points (PP)** like hit points. Panic rises when:

- Encountering horrors.
- Squadmates die.
- False scanner blips.

At max Panic, marines break: flee, freeze, scream, or snap.

When Panic Points max out, roll on the **Panicked Action Table**.

Examples:

- Freeze in place.
- Flee blindly into another zone.
- Fire weapon wildly (friendly fire risk).
- Drop gear and scream.
- Berserk charge.

### Post Mission Debrief

### Advancement

## Combat

### The Combat round

### Initiative

### Fire Modes

- **Full Auto** — Add +2 SR to the attack. Must reload immediately after firing.
- **Burst** — May split damage across multiple targets in a 120° arc in the same zone.
- **Suppression** — Targeted enemies’ movement is halved.
- **Full Suppression** — Targets are pinned; cannot move this round. Requires reload afterwards.

### Weapon Traits

- **Unreliable** — In Burst or Suppression, MR worsens by -1.
- **Armor-Piercing** — Ignores 1 tier of armor (or all armor for advanced/prototype weapons).
- **Shredding** — Targets struck without armor must make a morale check.
- **Tracer** — Allies firing at the same target this round gain +1 die.
- **Brutal** — On a crit (multiple 6s), deal +1 damage beyond normal.
- **Stable Mount** — If braced (mounted, prone, bipod), gain +1 SR.
- **Silent** — Does not trigger automatic Reaction checks.
- **Overheat** — Cannot fire in Full Auto two turns in a row without a malfunction check.

### Reloading

Reloading is a tense, risky process:

- **Takes an action.**
- Make a **Reflex test using the weapon’s Skill Rating**.
- You must roll a number of successes equal to the weapon’s **Reload Rating**.
- If you succeed, the weapon is reloaded.
- If you fail, the reload is incomplete, but progress is kept (Reload HP).
- Some gear makes this process easier (see Reload Gear).

### Clearing Jams

- Clearing a jam always requires a **Tech test with the weapon’s SR**.
- The number in parentheses = **successes needed**.
- While jammed, the weapon cannot fire.

### Initiative System (Placeholder)

At start of round:

- Everyone rolls **Reflex + d6** = Initiative.
- Combatants act in descending order.
- After acting, subtract -4.
- If still >0, act again.
- Repeat until all ≤0.

This creates dynamic rounds where faster marines act more often.

---

### Surprise (Placeholder)

Surprise attacks:
- Defenders cannot act during first cycle.
- Surprise always triggers Panic checks.
- Scanners and stealth interact heavily here.

### Damage & Wounds

**Broken (d4):**

1. Unconscious for d4 rounds, AI takes partial control.
2. Crippled (lose arm/eye/leg), AI keeps you functional.
3. Bleeding out: death in d2 hours unless treated; nanites slow the process.
4. Decapitated — but your suit keeps fighting until help arrives.

- **Damage** reduces your armour’s **HP** after applying Damage Reduction (DRR).
- At **0 HP**, your **suit is destroyed** — it no longer provides DRR or movement bonuses, but you may fight on if you survive wounds.
- **Wound Threshold (WT):** Any single attack that deals ≥ WT damage causes a **Wound** to the marine inside the armour.
- Wounds bypass armour and affect the **body** (limbs, organs, senses).

Whenever a Wound is inflicted, roll d20. Effects stack.

| d20 | Wound                                                                                                                                     |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Bruised Ribs.** Wind knocked out. -1 Reflex until end of mission.                                                                       |
| 2   | **Fractured Hand.** Drop whatever you’re holding. Using 2H weapons adds +1 DR to all rolls.                                               |
| 3   | **Shattered Foot.** Movement hobbled. Move DR +2.                                                                                         |
| 4   | **Eye Trauma.** Vision blurred or one eye lost. -1 die on ranged attacks.                                                                 |
| 5   | **Ear Rupture.** Deaf on one side. Surprise attacks from that flank gain +1 die.                                                          |
| 6   | **Broken Arm.** Can’t use that arm. Drop items, 2H weapons impossible.                                                                    |
| 7   | **Shoulder Dislocation.** -1 Might until repaired.                                                                                        |
| 8   | **Gut Puncture.** Bleeding internally. Take d3 Grit damage immediately.                                                                   |
| 9   | **Collapsed Lung.** Breathing assisted by suit. -1 Grit until cybernetic/vat replacement.                                                 |
| 10  | **Cracked Spine.** Neural feedback. -1 Tech and Reflex.                                                                                   |
| 11  | **Severed Hand.** Lose hand; can’t use 2H gear. Must be replaced.                                                                         |
| 12  | **Crushed Leg.** Can’t sprint. Move limited to 1 zone max.                                                                                |
| 13  | **Severed Arm.** -2 Might. All gear in that hand lost.                                                                                    |
| 14  | **Severed Leg.** Move DR increases by +4, sprinting impossible.                                                                           |
| 15  | **Severe Internal Trauma.** Suit’s nanites keep you alive, but you take d6 Grit damage.                                                   |
| 16  | **Organ Loss.** Kidney, spleen, liver, or equivalent. Immediate med treatment required or die at mission end.                             |
| 17  | **Massive Head Trauma.** Suit AI takes partial control. -2 Reflex and Tech until replaced (cybernetic or vat head).                       |
| 18  | **Catastrophic Bleed.** Artery ruptured. Lose d3 HP at end of each round until treated.                                                   |
| 19  | **Decapitation (Partial).** Head severed or crushed — but suit AI puppets the body for d3 rounds. Afterwards: dead without replacement.   |
| 20  | **Fatal Core Damage.** Heart or brain destroyed. Nanites keep you alive for 1 round. If not treated immediately (Med Task HP 3), you die. |

## Medical Treatment

Marines of the HULLBREACH Corps are designed to survive injuries that would instantly kill ordinary humans. Stabilizing nanites, automated suit systems, and battlefield medicine can keep them alive — but wounds often require cybernetics or vat-grown replacements.

### Stabilization (in the field)

- **Broken Marines** or those suffering severe **Wounds** must be stabilized to avoid death.
- Stabilization requires appropriate **Medical Gear** (Medi-Pack, Field Surgery Kit, Nanite Injector, etc.).
- Each item has a **Task HP** cost depending on severity:
  - Minor Wound: Task HP 1
  - Major Wound (limb loss, organ failure): Task HP 2
  - Critical Wound (head trauma, decapitation, heart/lung): Task HP 3+
- A **Tech test** is rolled with the medical gear’s **SR**. Each success reduces Task HP by 1.

If Task HP is not reduced to 0 before the mission ends, the marine dies.

### Replacement & Recovery (between missions)

Destroyed or crippled body parts can be replaced with **cybernetics** or **vat-grown organs/limbs**.
Higher Rank marines have access to higher-quality replacements.

| Replacement Type         | Effect                                                                                                                                  |
| ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Basic Cybernetic**     | Restores lost function, but roll on Flaw Table.                                                                                         |
| **Advanced Cybernetic**  | Restores function and grants a minor bonus (+1 die to relevant tests).                                                                  |
| **Vat-Grown Clone Part** | Identical replacement, no bonuses or flaws. Expensive.                                                                                  |
| **Experimental Graft**   | Restores function and grants unique perk (infrared eye, servo arm, toxin-filter lung) — but unstable. Roll on Experimental Graft Table. |

### Post-Mission Recovery

At the end of a mission:

- Roll **d6 for each Wound** you sustained.
  - On 1-3: it requires replacement (cybernetic or vat).
  - On 4-6: nanites + stasis pods repaired it. You recover without surgery.
- HP is restored fully after downtime, but attribute penalties from lost parts remain until treated.

### Death & Resurrection (optional rule)

Even death is not always the end. With enough **resources and Rank**, marines may be revived through:

- **Cerebral Core Backup** (upload into a cloned or cybernetic body).
- **Nanite Reanimation** (return to action, but permanently Flawed).
- **AI Puppetry** (the marine’s suit AI runs their body indefinitely… personality optional).

Each option carries heavy **costs and corruption risks**.

### Cybernetic Flaw Table (d20)

Roll whenever you receive a **basic cybernetic replacement** (limb, organ, sensory system). Higher-rank or advanced replacements may ignore this table.

| d20 | Flaw                                                                                                   |
| --- | ------------------------------------------------------------------------------------------------------ |
| 1   | **Glitch-Twitch.** Involuntary spasms. -1 die to Reflex tests requiring precision.                     |
| 2   | **Cold Grip.** Prosthetic hand lacks fine control. +1 DR to delicate tasks.                            |
| 3   | **Feedback Loop.** Occasional shocks. Take 1 damage after rolling a natural 1.                         |
| 4   | **Uncalibrated Optics.** Depth perception off. -1 die on ranged attacks.                               |
| 5   | **Phantom Pain.** Old nerves scream. Lose 1 action on a roll of triple 1s.                             |
| 6   | **Noise Bleed.** Audio implant picks up static. Surprise attacks gain +1 die against you.              |
| 7   | **Drain Hog.** Cybernetics siphon suit power. Reduce Carry Capacity by -2.                             |
| 8   | **Overheats.** Implant runs hot. On long missions, take d2 damage unless cooled.                       |
| 9   | **Patchwork Code.** Tech tests suffer +1 DR when using hacking gear.                                   |
| 10  | **Magnet Weakness.** Strong fields mess with you. On malfunction nearby, drop items in hand.           |
| 11  | **Servo Lag.** Movements delayed. Initiative rolls suffer -1.                                          |
| 12  | **Uncanny Face.** Vat-grown or synthetic features creep others out. NPC Reactions at -2.               |
| 13  | **Nanite Addiction.** You require an injector every mission or lose 1 Grit.                            |
| 14  | **Horrible Scar Tissue.** -1 HP permanently. Looks metal as hell.                                      |
| 15  | **AI Ghost.** Replacement part whispers in your dreams. Once per mission, it acts on its own.          |
| 16  | **Obvious Mod.** Everyone knows you’re patched up. Enemies prioritize you in combat.                   |
| 17  | **Paranoid Subroutines.** You mistrust allies. Reaction rolls with squadmates are one step worse.      |
| 18  | **Corrupted Nanites.** 1-in-6 chance per wound that healing attempts fail.                             |
| 19  | **Backdoor Code.** Someone else can override your implant remotely… and sometimes does.                |
| 20  | **Reject Host.** Implant rejects your body. Take d3 damage after each mission until replaced/upgraded. |

### Experimental Graft Table (d12)

Roll when a marine receives an unstable, prototype graft instead of a standard replacement. Each graft gives a **perk AND a flaw**.

| d12 | Graft                                                                                                                                                                                     |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Infrared Eye.** See in darkness and through smoke. Flaw: bright lights blind you (-2 dice for 1 round).                                                                                 |
| 2   | **Servo Arm.** +1 Might and can crush steel. Flaw: unpredictable twitch — roll d6 each mission; on 1, it attacks nearest object/ally once.                                                |
| 3   | **Toxin Filter Lung.** Immune to gas/poison. Flaw: requires daily nanite infusion or lose 1 Grit.                                                                                         |
| 4   | **Adrenal Node.** Once per mission, add +2 dice to any roll. Flaw: after use, lose d3 HP from burnout.                                                                                    |
| 5   | **Dermal Plating.** Gain +1 DRR. Flaw: skin stiff and pale. Stealth rolls at -1 die.                                                                                                      |
| 6   | **Ossified Fist.** Can punch for Dmg 2, Armor-Piercing. Flaw: hand too stiff for fine tasks. Cannot use gear requiring SR > 1.                                                            |
| 7   | **Neural Overclocker.** +1 Tech. Flaw: on natural 1, take d3 damage from seizures.                                                                                                        |
| 8   | **Spider Limbs.** Extra mechanical arms. Can wield 3rd weapon/tool. Flaw: +1 slot permanently used by the limbs.                                                                          |
| 9   | **Tail-Spike.** Natural melee weapon (Dmg 2, Brutal). Flaw: +1 slot; enemies always notice you first.                                                                                     |
| 10  | **Vascular Nanite Mesh.** Once per mission, ignore a Wound result. Flaw: permanent corruption risk — roll d20 each mission; on 1, nanites revolt (take d6 damage).                        |
| 11  | **Overclocked Heart.** Initiative always succeeds in your favor. Flaw: after combat, roll d6; on 1, suffer heart failure (Broken).                                                        |
| 12  | **Hive Interface.** Can control up to 2 drones as if they were your own limbs. Flaw: alien whispers creep in — once per mission, GM may force you to act against squad goals for 1 round. |

### Cybernetic & Vat Replacement Gear

| Item                         | Slots | SR  | MR  | Cost | Special                                                                                                             |
| ---------------------------- | ----- | --- | --- | ---- | ------------------------------------------------------------------------------------------------------------------- |
| **Basic Cybernetic Limb**    | 1     | 2   | 3   | 3 RP | Restores lost arm/leg. Roll on **Cybernetic Flaw Table**.                                                           |
| **Advanced Cybernetic Limb** | 1     | 3   | 2   | 5 RP | Restores function, +1 die on relevant checks (Might for arms, Reflex for legs). Immune to flaws.                    |
| **Vat-Grown Limb**           | 1     | 2   | 4   | 4 RP | Perfect organic replacement. No flaws, but fragile (-1 DRR if targeted).                                            |
| **Basic Sensory Implant**    | 0.5   | 2   | 3   | 2 RP | Replaces eye or ear. Grants function back. Roll on **Cybernetic Flaw Table**.                                       |
| **Advanced Sensory Implant** | 0.5   | 3   | 2   | 4 RP | Replaces eye/ear with enhancements (infrared, zoom, sonic filters). No flaws.                                       |
| **Vat-Grown Organ**          | 1     | 2   | 4   | 4 RP | Replaces kidney, lung, liver, etc. No flaws, but costly.                                                            |
| **Synthetic Organ**          | 1     | 2   | 3   | 3 RP | Cybernetic replacement organ. Restores function but roll on **Cybernetic Flaw Table**.                              |
| **Experimental Graft**       | 1-2   | 3   | 2   | 6 RP | Roll on **Experimental Graft Table** for perk + flaw.                                                               |
| **Nanite Core**              | 1     | 2   | 2   | 5 RP | Colony of stabilizing nanites permanently grafted in. Once per mission, auto-stabilize a Wound. Risk of corruption. |
| **Cerebral Backup Implant**  | 1     | 2   | 2   | 8 RP | Stores a snapshot of your brain. On death, transfer to clone/cyber body (GM discretion).                            |

## Blips (Placeholder)

**Blips** = the alien horrors and threats of the Graveyard.

- Initially appear as **scanner contacts**.
- Could be:
  - Swarms of xenos.
  - Rogue AI drones.
  - Psychic predators.
  - Rival scavengers or marines.

Blips will have:

- **HP, Armor, Attack Dice, Panic/Morale ratings.**
- Malfunction-like “instinct” tables.

---

## Introductory Scenario (Placeholder)

**Mission 1: The Lost Beacon**

- The squad is dispatched to investigate a distress signal from a derelict frigate.
- Objectives:
  - Secure the bridge.
  - Recover the black box.
  - Survive extraction.
- Hazards:
  - Jammed doors, flickering power, false scanner blips.
  - First contact with alien Blips.
  - Environmental collapse.

Scenario will introduce:

- Basic tests (gear use, DRs).
- Combat (projectiles, melee, malfunctions).
- Panic & Rally system.
- First taste of wounds, replacement, and paranoia.# HULLBREACH
