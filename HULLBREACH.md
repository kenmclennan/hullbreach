---
title: HULLBREACH

---

# HULLBREACH

## Design Prompt

HULLBREACH is a rules-light roleplaying game inspired by **MÖRK BORG** and **Cepheus Engine**, but reskinned for a sci-fi setting:  
Players take the role of **heavily armoured, bioengineered space marines** exploring derelict ships in a **spaceship graveyard**, battling alien horrors.

Core themes:

- **Tense exploration** of claustrophobic starship corridors.
- **Resource management** (ammo, gear, supplies, power cells).
- **Risk/reward** (push deeper for better salvage, at higher danger).
- **Over-the-top violence** with heavy weapons, flamers, grenades, chainblades.
- **Malfunctions** that are as funny as they are dangerous.
- **Marines and their power armour** can survive terrible wounds through nanites, cybernetics, and onboard AIs.
- **Gear-driven progression**: equipment defines actions; carrying capacity & Rank limit choices.

The game must remain **rules-light**: few mechanics, lots of dice rolled, quick but brutal combat and comedy.

---

## Ideas to Implement

- **Malfunction tables by gear type** (projectile, melee, special weapons, utility gear, armor systems).  
- **Medical treatments**: replacement limbs, organs, and even heads (cybernetic or vat-grown).  
- **Advantages and flaws** tied to replacement parts, with better options at higher Rank.  
- **Onboard AI control** when a marine is unconscious (reduced capability but not out of play).  
- **Task HP system** for hacking, cutting, and repairs under fire.  
- **Tiers of Gear** tied to Rank progression.  
- **Promotion system** for advancing Rank.  
- **Combat Zones & Movement mechanics** — revisit to refine tactical depth.  

---

## Character Creation

### Generate Attributes & Starting Rank

Each character has four attributes (range –3 to +3). Roll **1d6** to see how many points you can spend **and to determine your starting Rank**.

| d6  | Points   | Starting Rank        |
|-----|----------|----------------------|
| 1–2 | 4 points | Specialist (Rank 2)  |
| 3–5 | 5 points | Trooper (Rank 1)     |
| 6   | 6 points | Trooper (Rank 1)     |

The attributes are as follows:

| Attribute  | Description                                |
| ---------- | ------------------------------------------ |
| **Reflex** | Dodging, aiming, piloting                  |
| **Tech**   | Hacking, sensors, demolitions, interfacing |
| **Might**  | Melee, breaching, raw strength             |
| **Grit**   | Endurance, survival, pain threshold        |

The cost for assigning points is as follows:
 
| Modifier | Cost        |
|----------|-------------|
| –3       | –3 (refund) |
| –2       | –2 (refund) |
| –1       | –1 (refund) |
| 0        | Free        |
| +1       | 1           |
| +2       | 3           |
| +3       | 5           |

No stat may start higher than +3 or lower than –3.

### Roll Hit Points

Base HP now comes from your **armour model** (see Armour section), plus your **Grit** score.  

### Choose Armour

Select one of the available **Armour Models**. This defines your starting **Base HP, Carry Capacity, Movement, Damage Reduction, Wound Threshold, and Attribute bonuses**.  

### Choose Gear

   - Take basic survival kit (rations, oxygen, comms).
   - Roll or pick starting weapons, armor, and tools (see Gear section).
   - You may only carry items up to your **Armour’s Carry Capacity** without penalty.

### Define Your Marine

   - Give a name, callsign, or designation.
   - Your starting **Rank** is determined above. Higher Ranks will be earned through promotion.
   - Optionally, roll on background/flaw tables (to be added).

Then you’re ready for your first mission.

---

## Armour

At character creation, choose one of the following **Armour Models**.  
Your armour defines your **Base HP, Carry Capacity, Movement difficulty, Damage Reduction, Wound Threshold, and Attribute bonuses**.  

| Armour Model              | Base HP | Carry Capacity | Move DR | DRR | WT | Bonus | Notes |
|----------------------------|---------|----------------|---------|-----|----|-------|-------|
| **Revenant Lightframe**    | 10      | Might + 6      | DR 6    | 1   | 4  | +1 Reflex | Recon suit: agile and quiet, ideal for scouts. |
| **Bastion Carapace**       | 11      | Might + 10     | DR 8    | 2   | 5  | +1 Might  | Standard-issue heavy infantry shell. Balanced. |
| **Vindicator Assault Harness** | 12  | Might + 12     | DR 10   | 2   | 6  | +2 Might  | Power-assisted brute force armour for breachers. |
| **Wraith Pattern Exo**     | 10      | Might + 8      | DR 6    | 1   | 4  | +1 Reflex, +1 Tech | Stealth and recon rig with sensor uplinks. |
| **Juggernaut Siege Frame** | 13      | Might + 14     | DR 12   | 3   | 7  | +2 Grit   | Walking bunker, built to soak up incoming fire. |
| **Aegis Guardian Plate**   | 11      | Might + 10     | DR 8    | 2   | 5  | +1 Reflex, +1 Grit | Defensive armour with stabilizers and AI-assisted reflexes. |

### Movement Check

- To move **1 zone**, make a **Reflex test vs your armour’s Move DR**.  
- Each **success = 1 zone moved** (max 2 zones per action).  
- **Failure = no movement** — you stumble, snag, or your armour slows you.  
- **Critical (3+ successes):** move 3 zones in a burst of speed.  
- **Complication (all 1s):** your armour makes a loud clang, vents sparks, or trips — roll on the Noise/Attention Table (to be written).  

---

## 💥 Damage & Wounds

- **Damage** reduces your armour’s **HP** after applying Damage Reduction (DRR).  
- At **0 HP**, your **suit is destroyed** — it no longer provides DRR or movement bonuses, but you may fight on if you survive wounds.  
- **Wound Threshold (WT):** Any single attack that deals ≥ WT damage causes a **Wound** to the marine inside the armour.  
- Wounds bypass armour and affect the **body** (limbs, organs, senses).  

---

## ⚡ Wounds Table (d20)

Whenever a Wound is inflicted, roll d20. Effects stack.  

| d20 | Wound |
|-----|-------|
| 1   | **Bruised Ribs.** Wind knocked out. –1 Reflex until end of mission. |
| 2   | **Fractured Hand.** Drop whatever you’re holding. Using 2H weapons adds +1 DR to all rolls. |
| 3   | **Shattered Foot.** Movement hobbled. Move DR +2. |
| 4   | **Eye Trauma.** Vision blurred or one eye lost. –1 die on ranged attacks. |
| 5   | **Ear Rupture.** Deaf on one side. Surprise attacks from that flank gain +1 die. |
| 6   | **Broken Arm.** Can’t use that arm. Drop items, 2H weapons impossible. |
| 7   | **Shoulder Dislocation.** –1 Might until repaired. |
| 8   | **Gut Puncture.** Bleeding internally. Take d3 Grit damage immediately. |
| 9   | **Collapsed Lung.** Breathing assisted by suit. –1 Grit until cybernetic/vat replacement. |
| 10  | **Cracked Spine.** Neural feedback. –1 Tech and Reflex. |
| 11  | **Severed Hand.** Lose hand; can’t use 2H gear. Must be replaced. |
| 12  | **Crushed Leg.** Can’t sprint. Move limited to 1 zone max. |
| 13  | **Severed Arm.** –2 Might. All gear in that hand lost. |
| 14  | **Severed Leg.** Move DR increases by +4, sprinting impossible. |
| 15  | **Severe Internal Trauma.** Suit’s nanites keep you alive, but you take d6 Grit damage. |
| 16  | **Organ Loss.** Kidney, spleen, liver, or equivalent. Immediate med treatment required or die at mission end. |
| 17  | **Massive Head Trauma.** Suit AI takes partial control. –2 Reflex and Tech until replaced (cybernetic or vat head). |
| 18  | **Catastrophic Bleed.** Artery ruptured. Lose d3 HP at end of each round until treated. |
| 19  | **Decapitation (Partial).** Head severed or crushed — but suit AI puppets the body for d3 rounds. Afterwards: dead without replacement. |
| 20  | **Fatal Core Damage.** Heart or brain destroyed. Nanites keep you alive for 1 round. If not treated immediately (Med Task HP 3), you die. |

---

## Core Rules

### Resolution Mechanic

All tests are made using **gear**, not abstract skills. Every weapon, tool, or system has a **Skill Rating** and a **Malfunction Rating**.

1. **Build the Dice Pool**  
   - Roll a number of **d6 = Attribute + Gear Skill Rating**.  
   - Minimum: 1 die is always rolled.  

2. **Count Successes**  
   - Each roll of **5 or 6 = 1 success**.  
   - **1 success** = task completed (or 1 point of damage).  
   - More successes = stronger outcome, faster completion, or additional damage.  

3. **Weapons & Damage**  
   - Each success = 1 damage (unless weapon says otherwise).  
   - Targets reduce incoming damage by armor.  

4. **Task HP**  
   - Some challenges have HP that must be reduced to 0 (e.g. hacking a computer, cutting through a bulkhead, repairing a reactor).  
   - Each success rolled reduces the Task HP by 1.  
   - Each roll represents about one round of time under pressure.  

5. **Malfunctions**  
   - Each item has a **Malfunction Rating (MR)**.  
   - If you roll that many **1s** in a single test, a malfunction occurs.  
   - If you roll fewer dice than the MR, a malfunction only occurs if **all dice are 1s**.  
   - Malfunctions occur even if the test succeeds.  
   - Roll on the relevant **Malfunction Table**.  

---

## Carrying Capacity

Carry up to **Might + 8 items**.
- Exceeding this adds +2 dice difficulty (reduce successes by 1 for each test).
- Cannot exceed double capacity.

---

## Hit Points (HP)

- Start with **Grit + d8** HP (minimum 1).
- At **0 HP**: you are **Broken**.
- At negative HP: dead — unless your armour, nanites, or AI keep you going.

**Broken (d4):**

1. Unconscious for d4 rounds, AI takes partial control.  
2. Crippled (lose arm/eye/leg), AI keeps you functional.  
3. Bleeding out: death in d2 hours unless treated; nanites slow the process.  
4. Decapitated — but your suit keeps fighting until help arrives.  

---

## Rank

Ranks measure your experience and seniority within **HULLBREACH**.  
They unlock access to better equipment and privileges on the battlefield.

- **Trooper (Rank 1)** — Standard recruits. Access to Tier-1 gear.  
- **Specialist (Rank 2)** — Trusted operators. Access to Tier-1 and Tier-2 gear.  
- **Sergeant (Rank 3)** — Veteran leaders. Access to Tier-1 through Tier-3 gear.  
- **Lieutenant (Rank 4)** — Elite marines. Access to all four gear tiers.  

### Gear Tiers (Placeholder)

Gear is divided into four tiers. Each Rank unlocks higher tiers, with the most advanced weapons and equipment restricted to veterans. (Gear lists to come.)

### Promotion (Placeholder)

After completing missions, marines may be promoted to higher ranks. The process for promotion will be detailed later.

---

## Fire Modes

- **Full Auto** — Add +2 SR to the attack. Must reload immediately after firing.  
- **Burst** — May split damage across multiple targets in a 120° arc in the same zone.  
- **Suppression** — Targeted enemies’ movement is halved.  
- **Full Suppression** — Targets are pinned; cannot move this round. Requires reload afterwards.  

---

## Weapon Traits

- **Unreliable** — In Burst or Suppression, MR worsens by –1.  
- **Armor-Piercing** — Ignores 1 tier of armor (or all armor for advanced/prototype weapons).  
- **Shredding** — Targets struck without armor must make a morale check.  
- **Tracer** — Allies firing at the same target this round gain +1 die.  
- **Brutal** — On a crit (multiple 6s), deal +1 damage beyond normal.  
- **Stable Mount** — If braced (mounted, prone, bipod), gain +1 SR.  
- **Silent** — Does not trigger automatic Reaction checks.  
- **Overheat** — Cannot fire in Full Auto two turns in a row without a malfunction check.  

---

## Reloading

Reloading is a tense, risky process:

- **Takes an action.**  
- Make a **Reflex test using the weapon’s Skill Rating**.  
- You must roll a number of successes equal to the weapon’s **Reload Rating**.  
- If you succeed, the weapon is reloaded.  
- If you fail, the reload is incomplete, but progress is kept (Reload HP).  
- Some gear makes this process easier (see Reload Gear).  

---
## Projectile Weapons

| Tier | Weapon Name          | Hands | Slots | Range   | SR | MR | Dmg | Reload | Cost | Special |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 1    | **Slugspitter 9mm**  | 1H    | 1     | Short   | 2  | 3  | 1   | 1      | 1 RP | Reliable, cheap sidearm |
| 1    | **Viper PDW**        | 2H    | 1     | Short   | 2  | 3  | 1   | 1      | 2 RP | Burst capable |
| 1    | **Ironclad Mk.12**   | 2H    | 2     | Medium  | 3  | 4  | 1   | 2      | 2 RP | Rugged; +1 MR (hard to break) |
| 1    | **Banshee .45**      | 1H    | 1     | Short   | 2  | 2  | 1   | 1      | 1 RP | Deafening; +1 to Reaction rolls nearby |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 2    | **Direwolf Carbine** | 2H    | 1     | Medium  | 3  | 3  | 1   | 1      | 3 RP | Suppression capable |
| 2    | **Havoc-10 Auto**    | 2H    | 1     | Short   | 3  | 2  | 1   | 1      | 3 RP | Auto fire; reroll 1 die/attack; Unreliable |
| 2    | **Gorgon Handcannon**| 1H    | 2     | Short   | 2  | 2  | 2   | 1      | 4 RP | Devastating; MR 2 |
| 2    | **Hammerjack**       | 2H    | 2     | Short   | 3  | 3  | 2   | 1      | 3 RP | +1 die within Short range |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 3    | **Hellkite DMR**     | 2H    | 2     | Long    | 4  | 3  | 2   | 2      | 5 RP | Precision: convert 1 success to crit |
| 3    | **Maelstrom MG**     | 2H    | 2     | Medium  | 4  | 2  | 1   | 2      | 6 RP | Suppression & Full Suppression capable; Overheat |
| 3    | **Cerberus Tri-Pistol** | 1H | 1     | Short   | 3  | 2  | 1   | 1      | 5 RP | Triple Burst; MR check each use |
| 3    | **Tombstone Riotgun** | 2H   | 2     | Short   | 4  | 3  | 2   | 2      | 5 RP | Shredding shells: armor counts as –1 tier; Burst capable |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 4    | **Oblivion Rail-Pistol** | 1H | 1    | Medium  | 4  | 2  | 2   | 2      | 8 RP | Armor-Piercing |
| 4    | **Hydra Rotary Cannon** | 2H | 3    | Medium  | 5  | 2  | 1   | 3      | 10 RP| Auto fire (+2 SR); Full Suppression capable; Overheat |
| 4    | **Eidolon Silent Rifle** | 2H | 1    | Long   | 4  | 3  | 2   | 2      | 7 RP | Silent; malfunctions only on 2 ones |
| 4    | **Colossus Breaker** | 2H    | 3     | Long    | 5  | 1  | 3   | 3      | 10 RP| Each success = 3 dmg; recoil: –1 Reflex next round |

---

## Projectile Weapon Reload Gear

| Tier | Gear Name            | Slots | Reloads / Effect                          | Cost | Special |
|------|----------------------|-------|-------------------------------------------|------|---------|
| 1    | **Ammo Pouch**       | 1     | 3 reloads (Reload 1 weapons only)         | 1 RP | Standard issue. Simple reload action. |
| 1    | **Spare Magazine**   | 0.5   | 1 reload (handgun/SMG only)               | 0.5 RP | Can be stashed in pockets. |
| 2    | **Bandolier Rig**    | 1     | 4 reloads (any weapon)                    | 2 RP | May reload as free action once per mission. |
| 2    | **Drum Magazine**    | 1     | 2 reloads (LMG/SMG/Shotgun only)          | 2 RP | Reload Rating reduced by 1. |
| 2    | **Ammo Satchel**     | 2     | 6 reloads (mixed weapon types)            | 3 RP | Bulky. Takes 2 hands to access in combat. |
| 3    | **Belt Feed Unit**   | 2     | Continuous feed: 5 reloads (LMG/MG only)  | 4 RP | Ignore Reload Rating 2 once per combat. |
| 3    | **Quick-Loader Frame** | 1   | 3 reloads (any)                           | 4 RP | Reduce Reload Rating by 1 (min 1). |
| 4    | **Ammo Backpack**    | 3     | Continuous feed: 8 reloads (any 2H weapon)| 6 RP | Can sustain Auto/Suppression for 3 turns before Ammo Die is rolled. |
| 4    | **Auto-Loader Module** | 2   | 4 reloads (any)                           | 7 RP | Reloads occur automatically when weapon empties; no action needed. |

---

## Projectile Weapon Malfunctions

When a projectile weapon malfunctions, roll on the following table:

| d6 | Malfunction |
|----|-------------|
| 1   | **Accidental Ammo Ejection.** Mag or shells spill out. Weapon is empty and must be reloaded. |
| 2   | **Jam (2).** Weapon locks. Requires a **Tech test using the weapon’s SR**, needing **2 successes** to clear. Until cleared, weapon cannot fire. |
| 3   | **Stuck on Full Auto.** Weapon goes wild, spraying uncontrollably. Requires a **Tech test (3 successes)** to repair. If failed, weapon becomes **Jam (3)** until cleared. |
| 4   | **Accidental Discharge.** Weapon fires into a random friendly in the same zone (ally must roll Reflex to avoid). |
| 5   | **Burst Pipe.** The shot ruptures old ship infrastructure. Roll on the Environmental Hazards Sub-Table. |
| 6   | **Barrel Rupture.** Weapon explodes. It is destroyed. Holder takes **d3 damage**. |

### Clearing Jams
- Clearing a jam always requires a **Tech test with the weapon’s SR**.  
- The number in parentheses = **successes needed**.  
- While jammed, the weapon cannot fire.  

---

### Environmental Hazards Sub-Table (d6)

| d6 | Hazard |
|----|--------|
| 1–2 | **Steam Vent.** Scalding steam fills the zone. Everyone takes **1 damage** unless in sealed armor. Visibility reduced until end of round. |
| 3–4 | **Toxic Gas.** Corrosive fumes spread. Anyone without respirators or sealed armor must succeed a **Grit test (2 successes)** or take **d2 damage**. |
| 5   | **Acid Spray.** Pipes burst, spraying acid. Everyone in zone takes **d3 damage** and armor degrades 1 tier. |
| 6   | **Vacuum Breach.** Hull tears open slightly. Everyone must pass a **Reflex test (2 successes)** or be pulled into cover/ground; unanchored gear may be lost. |

---

## Melee Weapons

| Tier | Weapon Name         | Hands | Slots | Range | SR | MR | Dmg | Reload | Cost | Special |
|------|---------------------|-------|-------|-------|----|----|-----|--------|------|---------|
| 1    | **Combat Knife**    | 1H    | 1     | Short | 2  | 4  | 1   | —      | 1 RP | Always ready; can be thrown (Short, Dmg 1) |
| 1    | **Shock Baton**     | 1H    | 1     | Short | 2  | 3  | 1   | —      | 2 RP | Stun: on 2+ successes, target loses 1 action |
| 2    | **Chainsword**      | 1H    | 2     | Short | 3  | 3  | 2   | —      | 3 RP | Brutal; Unreliable |
| 2    | **Power Axe**       | 2H    | 2     | Short | 3  | 2  | 3   | —      | 4 RP | Armor-Piercing; Kickback |
| 3    | **Monomolecular Blade** | 1H | 1   | Short | 4  | 3  | 2   | —      | 5 RP | Ignores armor on a crit |
| 3    | **Chainfist**       | 2H    | 3     | Short | 4  | 2  | 3   | —      | 6 RP | Counts as breaching tool (Task HP –1 per roll) |
| 4    | **Power Hammer**    | 2H    | 3     | Short | 5  | 2  | 4   | —      | 8 RP | Stuns all enemies in same zone on crit |
| 4    | **Void Scythe**     | 2H    | 2     | Short | 5  | 1  | 3   | —      | 9 RP | Shredding; may sweep across 2 targets |

---

## Melee Weapon Malfunctions

When a melee weapon (chainsword, power axe, etc.) malfunctions, roll on this table:

| d6 | Malfunction |
|----|-------------|
| 1   | **Slipped Grip.** You fumble the weapon. Costs 1 action to recover. |
| 2   | **Stuck Fast.** Weapon bites deep into wall, floor, or enemy. Requires a **Might test (2 successes)** to pull free. Until then, it’s stuck. |
| 3   | **Overload.** Power field or chain drive overheats. Take **d2 damage** from feedback; weapon is unusable until repaired (Tech 2). |
| 4   | **Kickback.** Weapon recoils violently. You fall prone unless you pass a **Reflex test (2 successes)**. |
| 5   | **Friendly Nick.** In the chaos, your swing clips an ally in the same zone for **d2 damage**. |
| 6   | **Catastrophic Break.** Blade shatters / chain seizes. Weapon is destroyed in a spray of shards or sparks; you take **d3 damage**. |

---

## Special Weapons

| Tier | Weapon Name          | Hands | Slots | Range   | SR | MR | Dmg | Reload | Cost | Special |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 1    | **Incendiary Thrower** | 2H  | 2     | Short   | 2  | 3  | 2   | 1      | 3 RP | Area attack (all in zone); Unreliable |
| 2    | **Flame Projector**  | 2H    | 2     | Short   | 3  | 2  | 2   | 2      | 4 RP | Suppression capable; Shredding |
| 2    | **Plasma Torch**     | 1H    | 1     | Short   | 2  | 3  | 2   | 1      | 3 RP | Dual-use: melee cutter or ranged blast (Short) |
| 3    | **Heavy Flamer**     | 2H    | 3     | Medium  | 4  | 2  | 3   | 2      | 6 RP | Area attack (zone + adjacent); Overheat |
| 3    | **Plasma Ejector**   | 2H    | 2     | Medium  | 4  | 2  | 3   | 2      | 6 RP | Armor-Piercing; Friendly Splash |
| 4    | **Inferno Cannon**   | 2H    | 3     | Long    | 5  | 2  | 4   | 3      | 9 RP | Full Suppression capable; area burns for d3 rounds |
| 4    | **Plasma Incinerator** | 2H | 3     | Medium  | 5  | 1  | 4   | 3      | 10 RP| Catastrophic on crit fail (auto Malfunction) |

---

## Special Weapon Malfunctions

Flamers, plasma throwers, and other volatile heavy weapons are powerful but risky. When they malfunction, roll on this table:

| d6 | Malfunction |
|----|-------------|
| 1   | **Pilot Light Out.** Flamer fails to ignite. Spend 1 action to reignite. |
| 2   | **Fuel Leak.** Tank or hose leaks. You are drenched in flammable liquid. Next fire source that hits you deals **+d6 damage**. |
| 3   | **Backwash.** Fuel vents backwards. Take **d3 damage** and armor degrades 1 tier. |
| 4   | **Blowback.** Plasma vent or fuel line bursts. Everyone in same zone makes a **Reflex test (2 successes)** or takes **d2 damage**. |
| 5   | **Friendly Splash.** Flame jet arcs wide, catching an ally in the same zone for **d3 damage**. |
| 6   | **Catastrophic Explosion.** Tank or plasma coil detonates. You take **d6 damage**; all others in Short range take **d3 damage**. Weapon destroyed. |

---

## Utility Gear

| Item | Slots | SR | MR | Cost | Special |
|------|-------|----|----|------|---------|
| **Plasma Welder** | 2 | 2 | 3 | 3 RP | Cuts through bulkheads/doors (Task HP –1); can seal doors. |
| **Monotool** | 1 | 1 | 4 | 1 RP | Universal wrench/driver/saw; grants +1 die to basic repairs. |
| **Industrial Cutter** | 2 | 2 | 3 | 3 RP | Destroys crates, plating, alien bone; doubles as crude melee (Dmg 2, Unreliable). |
| **Repair Kit** | 1 | 2 | 4 | 2 RP | Restores 1 DRR to armor/gear with Tech test. Consumable (3 uses). |
| **Armour Patch Foam** | 1 | 1 | 4 | 2 RP | Seals breaches, restores 1 DRR for remainder of mission. Consumable (1 use). |
| **Stasis Spray** | 1 | 1 | 4 | 2 RP | Freezes corrosion/acid/bleeding. Restores 1d4 HP if applied immediately after injury. |
| **Motion Tracker** | 1 | 2 | 3 | 2 RP | Detects movement in adjacent zones. May reveal false positives on malfunction. |
| **Bioscanner** | 1 | 2 | 3 | 3 RP | Picks up heat/life signs; range = 2 zones. |
| **Spectral Analyzer** | 1 | 2 | 2 | 3 RP | Detects cloaked/stealthed targets. On malfunction: ghost echoes. |
| **Seismic Probe** | 2 | 3 | 3 | 4 RP | Maps weak points; reduces Task HP by 2 when breaching/cutting. |
| **Survey Drone** | 2 | 2 | 2 | 4 RP | Remote recon drone (range 3 zones). On malfunction: attracts attention. |
| **Medi-Pack** | 1 | 2 | 4 | 2 RP | Restores d6 HP with Tech test. Consumable (3 uses). |
| **Field Surgery Kit** | 2 | 2 | 3 | 3 RP | Stabilizes crippled limbs; restores Broken results 2 or 3. |
| **Nanite Injector** | 1 | 2 | 2 | 3 RP | Restores 2d4 HP but adds “Corruption” (flaw roll at mission end). |
| **Cybernetic Spares** | 2 | 2 | 3 | 4 RP | Emergency replacement limb/eye; restores function but may glitch (new flaw). |
| **Standard Cyberdeck** | 2 | 2 | 3 | 3 RP | Hack doors, turrets, terminals (Task HP –1). |
| **Black Ice Deck** | 3 | 3 | 2 | 5 RP | Advanced hacking; can attack systems. On malfunction: feedback damage (d2). |
| **Signal Scrambler** | 1 | 1 | 3 | 2 RP | Jams comms in 1 zone; hostile AI lose 1 die to tests. |
| **Data Spike** | 1 | 1 | 2 | 2 RP | Brute-force breach tool. +2 SR vs electronic locks. |
| **Override Chip** | 0.5 | 0 | – | 1 RP | Single-use passkey. Auto-unlocks a standard door/terminal. |
| **Grapple Gun** | 2 | 2 | 3 | 3 RP | Fires line 2 zones. Move Reflex test auto-succeeds if grapple attached. |
| **Mag Boots** | 1 | 1 | 4 | 2 RP | Walk in zero-G. On malfunction: stuck or release fails. |
| **Climbing Rig** | 1 | 1 | 4 | 1 RP | Ropes & ascenders. Grants +2 SR on climb tests. |
| **Thruster Pack** | 2 | 2 | 2 | 4 RP | Short burst (move 2 zones, vertical or zero-G). On malfunction: spin out. |
| **Portable Breach Charge** | 2 | 2 | 2 | 3 RP | Blows open bulkhead/door (Task HP instantly 0). 1 use only. |

---

## Utility Gear Malfunctions (d6)

| d6 | Malfunction |
|----|-------------|
| 1 | **Power Drain.** Gear flickers out, requires 1 action to reboot. |
| 2 | **Overheat.** Tool sears user — take **1 damage**. |
| 3 | **Misread.** Scanner gives false info (phantom blips, wrong life signs). |
| 4 | **Lockout.** Gear locks; requires **Tech test (2 successes)** to restore. |
| 5 | **Feedback.** Sparks/shock: user takes **d2 damage**, nearby electronics glitch. |
| 6 | **Catastrophic Short.** Tool fries itself. Destroyed in sparks and smoke. |# HULLBREACH

## Design Prompt

HULLBREACH is a rules-light roleplaying game inspired by **MÖRK BORG** and **Cepheus Engine**, but reskinned for a sci-fi setting:  
Players take the role of **heavily armoured, bioengineered space marines** exploring derelict ships in a **spaceship graveyard**, battling alien horrors.

Core themes:

- **Tense exploration** of claustrophobic starship corridors.
- **Resource management** (ammo, gear, supplies, power cells).
- **Risk/reward** (push deeper for better salvage, at higher danger).
- **Over-the-top violence** with heavy weapons, flamers, grenades, chainblades.
- **Malfunctions** that are as funny as they are dangerous.
- **Marines and their power armour** can survive terrible wounds through nanites, cybernetics, and onboard AIs.
- **Gear-driven progression**: equipment defines actions; carrying capacity & Rank limit choices.

The game must remain **rules-light**: few mechanics, lots of dice rolled, quick but brutal combat and comedy.

---

## Ideas to Implement

- **Malfunction tables by gear type** (projectile, melee, special weapons, utility gear, armor systems).  
- **Medical treatments**: replacement limbs, organs, and even heads (cybernetic or vat-grown).  
- **Advantages and flaws** tied to replacement parts, with better options at higher Rank.  
- **Onboard AI control** when a marine is unconscious (reduced capability but not out of play).  
- **Task HP system** for hacking, cutting, and repairs under fire.  
- **Tiers of Gear** tied to Rank progression.  
- **Promotion system** for advancing Rank.  
- **Combat Zones & Movement mechanics** — revisit to refine tactical depth.  

---

## Character Creation

### Generate Attributes & Starting Rank

Each character has four attributes (range –3 to +3). Roll **1d6** to see how many points you can spend **and to determine your starting Rank**.

| d6  | Points   | Starting Rank        |
|-----|----------|----------------------|
| 1–2 | 4 points | Specialist (Rank 2)  |
| 3–5 | 5 points | Trooper (Rank 1)     |
| 6   | 6 points | Trooper (Rank 1)     |

The attributes are as follows:

| Attribute  | Description                                |
| ---------- | ------------------------------------------ |
| **Reflex** | Dodging, aiming, piloting                  |
| **Tech**   | Hacking, sensors, demolitions, interfacing |
| **Might**  | Melee, breaching, raw strength             |
| **Grit**   | Endurance, survival, pain threshold        |

The cost for assigning points is as follows:
 
| Modifier | Cost        |
|----------|-------------|
| –3       | –3 (refund) |
| –2       | –2 (refund) |
| –1       | –1 (refund) |
| 0        | Free        |
| +1       | 1           |
| +2       | 3           |
| +3       | 5           |

No stat may start higher than +3 or lower than –3.

### Roll Hit Points

Base HP now comes from your **armour model** (see Armour section), plus your **Grit** score.  

### Choose Armour

Select one of the available **Armour Models**. This defines your starting **Base HP, Carry Capacity, Movement, Damage Reduction, Wound Threshold, and Attribute bonuses**.  

### Choose Gear

   - Take basic survival kit (rations, oxygen, comms).
   - Roll or pick starting weapons, armor, and tools (see Gear section).
   - You may only carry items up to your **Armour’s Carry Capacity** without penalty.

### Define Your Marine

   - Give a name, callsign, or designation.
   - Your starting **Rank** is determined above. Higher Ranks will be earned through promotion.
   - Optionally, roll on background/flaw tables (to be added).

Then you’re ready for your first mission.

---

## Armour

At character creation, choose one of the following **Armour Models**.  
Your armour defines your **Base HP, Carry Capacity, Movement difficulty, Damage Reduction, Wound Threshold, and Attribute bonuses**.  

| Armour Model              | Base HP | Carry Capacity | Move DR | DRR | WT | Bonus | Notes |
|----------------------------|---------|----------------|---------|-----|----|-------|-------|
| **Revenant Lightframe**    | 10      | Might + 6      | DR 6    | 1   | 4  | +1 Reflex | Recon suit: agile and quiet, ideal for scouts. |
| **Bastion Carapace**       | 11      | Might + 10     | DR 8    | 2   | 5  | +1 Might  | Standard-issue heavy infantry shell. Balanced. |
| **Vindicator Assault Harness** | 12  | Might + 12     | DR 10   | 2   | 6  | +2 Might  | Power-assisted brute force armour for breachers. |
| **Wraith Pattern Exo**     | 10      | Might + 8      | DR 6    | 1   | 4  | +1 Reflex, +1 Tech | Stealth and recon rig with sensor uplinks. |
| **Juggernaut Siege Frame** | 13      | Might + 14     | DR 12   | 3   | 7  | +2 Grit   | Walking bunker, built to soak up incoming fire. |
| **Aegis Guardian Plate**   | 11      | Might + 10     | DR 8    | 2   | 5  | +1 Reflex, +1 Grit | Defensive armour with stabilizers and AI-assisted reflexes. |

### Movement Check

- To move **1 zone**, make a **Reflex test vs your armour’s Move DR**.  
- Each **success = 1 zone moved** (max 2 zones per action).  
- **Failure = no movement** — you stumble, snag, or your armour slows you.  
- **Critical (3+ successes):** move 3 zones in a burst of speed.  
- **Complication (all 1s):** your armour makes a loud clang, vents sparks, or trips — roll on the Noise/Attention Table (to be written).  

---

## 💥 Damage & Wounds

- **Damage** reduces your armour’s **HP** after applying Damage Reduction (DRR).  
- At **0 HP**, your **suit is destroyed** — it no longer provides DRR or movement bonuses, but you may fight on if you survive wounds.  
- **Wound Threshold (WT):** Any single attack that deals ≥ WT damage causes a **Wound** to the marine inside the armour.  
- Wounds bypass armour and affect the **body** (limbs, organs, senses).  

---

## ⚡ Wounds Table (d20)

Whenever a Wound is inflicted, roll d20. Effects stack.  

| d20 | Wound |
|-----|-------|
| 1   | **Bruised Ribs.** Wind knocked out. –1 Reflex until end of mission. |
| 2   | **Fractured Hand.** Drop whatever you’re holding. Using 2H weapons adds +1 DR to all rolls. |
| 3   | **Shattered Foot.** Movement hobbled. Move DR +2. |
| 4   | **Eye Trauma.** Vision blurred or one eye lost. –1 die on ranged attacks. |
| 5   | **Ear Rupture.** Deaf on one side. Surprise attacks from that flank gain +1 die. |
| 6   | **Broken Arm.** Can’t use that arm. Drop items, 2H weapons impossible. |
| 7   | **Shoulder Dislocation.** –1 Might until repaired. |
| 8   | **Gut Puncture.** Bleeding internally. Take d3 Grit damage immediately. |
| 9   | **Collapsed Lung.** Breathing assisted by suit. –1 Grit until cybernetic/vat replacement. |
| 10  | **Cracked Spine.** Neural feedback. –1 Tech and Reflex. |
| 11  | **Severed Hand.** Lose hand; can’t use 2H gear. Must be replaced. |
| 12  | **Crushed Leg.** Can’t sprint. Move limited to 1 zone max. |
| 13  | **Severed Arm.** –2 Might. All gear in that hand lost. |
| 14  | **Severed Leg.** Move DR increases by +4, sprinting impossible. |
| 15  | **Severe Internal Trauma.** Suit’s nanites keep you alive, but you take d6 Grit damage. |
| 16  | **Organ Loss.** Kidney, spleen, liver, or equivalent. Immediate med treatment required or die at mission end. |
| 17  | **Massive Head Trauma.** Suit AI takes partial control. –2 Reflex and Tech until replaced (cybernetic or vat head). |
| 18  | **Catastrophic Bleed.** Artery ruptured. Lose d3 HP at end of each round until treated. |
| 19  | **Decapitation (Partial).** Head severed or crushed — but suit AI puppets the body for d3 rounds. Afterwards: dead without replacement. |
| 20  | **Fatal Core Damage.** Heart or brain destroyed. Nanites keep you alive for 1 round. If not treated immediately (Med Task HP 3), you die. |

---

## Core Rules

### Resolution Mechanic

All tests are made using **gear**, not abstract skills. Every weapon, tool, or system has a **Skill Rating** and a **Malfunction Rating**.

1. **Build the Dice Pool**  
   - Roll a number of **d6 = Attribute + Gear Skill Rating**.  
   - Minimum: 1 die is always rolled.  

2. **Count Successes**  
   - Each roll of **5 or 6 = 1 success**.  
   - **1 success** = task completed (or 1 point of damage).  
   - More successes = stronger outcome, faster completion, or additional damage.  

3. **Weapons & Damage**  
   - Each success = 1 damage (unless weapon says otherwise).  
   - Targets reduce incoming damage by armor.  

4. **Task HP**  
   - Some challenges have HP that must be reduced to 0 (e.g. hacking a computer, cutting through a bulkhead, repairing a reactor).  
   - Each success rolled reduces the Task HP by 1.  
   - Each roll represents about one round of time under pressure.  

5. **Malfunctions**  
   - Each item has a **Malfunction Rating (MR)**.  
   - If you roll that many **1s** in a single test, a malfunction occurs.  
   - If you roll fewer dice than the MR, a malfunction only occurs if **all dice are 1s**.  
   - Malfunctions occur even if the test succeeds.  
   - Roll on the relevant **Malfunction Table**.  

---

## Carrying Capacity

Carry up to **Might + 8 items**.
- Exceeding this adds +2 dice difficulty (reduce successes by 1 for each test).
- Cannot exceed double capacity.

---

## Hit Points (HP)

- Start with **Grit + d8** HP (minimum 1).
- At **0 HP**: you are **Broken**.
- At negative HP: dead — unless your armour, nanites, or AI keep you going.

**Broken (d4):**

1. Unconscious for d4 rounds, AI takes partial control.  
2. Crippled (lose arm/eye/leg), AI keeps you functional.  
3. Bleeding out: death in d2 hours unless treated; nanites slow the process.  
4. Decapitated — but your suit keeps fighting until help arrives.  

---

## Rank

Ranks measure your experience and seniority within **HULLBREACH**.  
They unlock access to better equipment and privileges on the battlefield.

- **Trooper (Rank 1)** — Standard recruits. Access to Tier-1 gear.  
- **Specialist (Rank 2)** — Trusted operators. Access to Tier-1 and Tier-2 gear.  
- **Sergeant (Rank 3)** — Veteran leaders. Access to Tier-1 through Tier-3 gear.  
- **Lieutenant (Rank 4)** — Elite marines. Access to all four gear tiers.  

### Gear Tiers (Placeholder)

Gear is divided into four tiers. Each Rank unlocks higher tiers, with the most advanced weapons and equipment restricted to veterans. (Gear lists to come.)

### Promotion (Placeholder)

After completing missions, marines may be promoted to higher ranks. The process for promotion will be detailed later.

---

## Fire Modes

- **Full Auto** — Add +2 SR to the attack. Must reload immediately after firing.  
- **Burst** — May split damage across multiple targets in a 120° arc in the same zone.  
- **Suppression** — Targeted enemies’ movement is halved.  
- **Full Suppression** — Targets are pinned; cannot move this round. Requires reload afterwards.  

---

## Weapon Traits

- **Unreliable** — In Burst or Suppression, MR worsens by –1.  
- **Armor-Piercing** — Ignores 1 tier of armor (or all armor for advanced/prototype weapons).  
- **Shredding** — Targets struck without armor must make a morale check.  
- **Tracer** — Allies firing at the same target this round gain +1 die.  
- **Brutal** — On a crit (multiple 6s), deal +1 damage beyond normal.  
- **Stable Mount** — If braced (mounted, prone, bipod), gain +1 SR.  
- **Silent** — Does not trigger automatic Reaction checks.  
- **Overheat** — Cannot fire in Full Auto two turns in a row without a malfunction check.  

---

## Reloading

Reloading is a tense, risky process:

- **Takes an action.**  
- Make a **Reflex test using the weapon’s Skill Rating**.  
- You must roll a number of successes equal to the weapon’s **Reload Rating**.  
- If you succeed, the weapon is reloaded.  
- If you fail, the reload is incomplete, but progress is kept (Reload HP).  
- Some gear makes this process easier (see Reload Gear).  

---
## Projectile Weapons

| Tier | Weapon Name          | Hands | Slots | Range   | SR | MR | Dmg | Reload | Cost | Special |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 1    | **Slugspitter 9mm**  | 1H    | 1     | Short   | 2  | 3  | 1   | 1      | 1 RP | Reliable, cheap sidearm |
| 1    | **Viper PDW**        | 2H    | 1     | Short   | 2  | 3  | 1   | 1      | 2 RP | Burst capable |
| 1    | **Ironclad Mk.12**   | 2H    | 2     | Medium  | 3  | 4  | 1   | 2      | 2 RP | Rugged; +1 MR (hard to break) |
| 1    | **Banshee .45**      | 1H    | 1     | Short   | 2  | 2  | 1   | 1      | 1 RP | Deafening; +1 to Reaction rolls nearby |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 2    | **Direwolf Carbine** | 2H    | 1     | Medium  | 3  | 3  | 1   | 1      | 3 RP | Suppression capable |
| 2    | **Havoc-10 Auto**    | 2H    | 1     | Short   | 3  | 2  | 1   | 1      | 3 RP | Auto fire; reroll 1 die/attack; Unreliable |
| 2    | **Gorgon Handcannon**| 1H    | 2     | Short   | 2  | 2  | 2   | 1      | 4 RP | Devastating; MR 2 |
| 2    | **Hammerjack**       | 2H    | 2     | Short   | 3  | 3  | 2   | 1      | 3 RP | +1 die within Short range |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 3    | **Hellkite DMR**     | 2H    | 2     | Long    | 4  | 3  | 2   | 2      | 5 RP | Precision: convert 1 success to crit |
| 3    | **Maelstrom MG**     | 2H    | 2     | Medium  | 4  | 2  | 1   | 2      | 6 RP | Suppression & Full Suppression capable; Overheat |
| 3    | **Cerberus Tri-Pistol** | 1H | 1     | Short   | 3  | 2  | 1   | 1      | 5 RP | Triple Burst; MR check each use |
| 3    | **Tombstone Riotgun** | 2H   | 2     | Short   | 4  | 3  | 2   | 2      | 5 RP | Shredding shells: armor counts as –1 tier; Burst capable |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 4    | **Oblivion Rail-Pistol** | 1H | 1    | Medium  | 4  | 2  | 2   | 2      | 8 RP | Armor-Piercing |
| 4    | **Hydra Rotary Cannon** | 2H | 3    | Medium  | 5  | 2  | 1   | 3      | 10 RP| Auto fire (+2 SR); Full Suppression capable; Overheat |
| 4    | **Eidolon Silent Rifle** | 2H | 1    | Long   | 4  | 3  | 2   | 2      | 7 RP | Silent; malfunctions only on 2 ones |
| 4    | **Colossus Breaker** | 2H    | 3     | Long    | 5  | 1  | 3   | 3      | 10 RP| Each success = 3 dmg; recoil: –1 Reflex next round |

---

## Projectile Weapon Reload Gear

| Tier | Gear Name            | Slots | Reloads / Effect                          | Cost | Special |
|------|----------------------|-------|-------------------------------------------|------|---------|
| 1    | **Ammo Pouch**       | 1     | 3 reloads (Reload 1 weapons only)         | 1 RP | Standard issue. Simple reload action. |
| 1    | **Spare Magazine**   | 0.5   | 1 reload (handgun/SMG only)               | 0.5 RP | Can be stashed in pockets. |
| 2    | **Bandolier Rig**    | 1     | 4 reloads (any weapon)                    | 2 RP | May reload as free action once per mission. |
| 2    | **Drum Magazine**    | 1     | 2 reloads (LMG/SMG/Shotgun only)          | 2 RP | Reload Rating reduced by 1. |
| 2    | **Ammo Satchel**     | 2     | 6 reloads (mixed weapon types)            | 3 RP | Bulky. Takes 2 hands to access in combat. |
| 3    | **Belt Feed Unit**   | 2     | Continuous feed: 5 reloads (LMG/MG only)  | 4 RP | Ignore Reload Rating 2 once per combat. |
| 3    | **Quick-Loader Frame** | 1   | 3 reloads (any)                           | 4 RP | Reduce Reload Rating by 1 (min 1). |
| 4    | **Ammo Backpack**    | 3     | Continuous feed: 8 reloads (any 2H weapon)| 6 RP | Can sustain Auto/Suppression for 3 turns before Ammo Die is rolled. |
| 4    | **Auto-Loader Module** | 2   | 4 reloads (any)                           | 7 RP | Reloads occur automatically when weapon empties; no action needed. |

---

## Projectile Weapon Malfunctions

When a projectile weapon malfunctions, roll on the following table:

| d6 | Malfunction |
|----|-------------|
| 1   | **Accidental Ammo Ejection.** Mag or shells spill out. Weapon is empty and must be reloaded. |
| 2   | **Jam (2).** Weapon locks. Requires a **Tech test using the weapon’s SR**, needing **2 successes** to clear. Until cleared, weapon cannot fire. |
| 3   | **Stuck on Full Auto.** Weapon goes wild, spraying uncontrollably. Requires a **Tech test (3 successes)** to repair. If failed, weapon becomes **Jam (3)** until cleared. |
| 4   | **Accidental Discharge.** Weapon fires into a random friendly in the same zone (ally must roll Reflex to avoid). |
| 5   | **Burst Pipe.** The shot ruptures old ship infrastructure. Roll on the Environmental Hazards Sub-Table. |
| 6   | **Barrel Rupture.** Weapon explodes. It is destroyed. Holder takes **d3 damage**. |

### Clearing Jams
- Clearing a jam always requires a **Tech test with the weapon’s SR**.  
- The number in parentheses = **successes needed**.  
- While jammed, the weapon cannot fire.  

---

### Environmental Hazards Sub-Table (d6)

| d6 | Hazard |
|----|--------|
| 1–2 | **Steam Vent.** Scalding steam fills the zone. Everyone takes **1 damage** unless in sealed armor. Visibility reduced until end of round. |
| 3–4 | **Toxic Gas.** Corrosive fumes spread. Anyone without respirators or sealed armor must succeed a **Grit test (2 successes)** or take **d2 damage**. |
| 5   | **Acid Spray.** Pipes burst, spraying acid. Everyone in zone takes **d3 damage** and armor degrades 1 tier. |
| 6   | **Vacuum Breach.** Hull tears open slightly. Everyone must pass a **Reflex test (2 successes)** or be pulled into cover/ground; unanchored gear may be lost. |

---

## Melee Weapons

| Tier | Weapon Name         | Hands | Slots | Range | SR | MR | Dmg | Reload | Cost | Special |
|------|---------------------|-------|-------|-------|----|----|-----|--------|------|---------|
| 1    | **Combat Knife**    | 1H    | 1     | Short | 2  | 4  | 1   | —      | 1 RP | Always ready; can be thrown (Short, Dmg 1) |
| 1    | **Shock Baton**     | 1H    | 1     | Short | 2  | 3  | 1   | —      | 2 RP | Stun: on 2+ successes, target loses 1 action |
| 2    | **Chainsword**      | 1H    | 2     | Short | 3  | 3  | 2   | —      | 3 RP | Brutal; Unreliable |
| 2    | **Power Axe**       | 2H    | 2     | Short | 3  | 2  | 3   | —      | 4 RP | Armor-Piercing; Kickback |
| 3    | **Monomolecular Blade** | 1H | 1   | Short | 4  | 3  | 2   | —      | 5 RP | Ignores armor on a crit |
| 3    | **Chainfist**       | 2H    | 3     | Short | 4  | 2  | 3   | —      | 6 RP | Counts as breaching tool (Task HP –1 per roll) |
| 4    | **Power Hammer**    | 2H    | 3     | Short | 5  | 2  | 4   | —      | 8 RP | Stuns all enemies in same zone on crit |
| 4    | **Void Scythe**     | 2H    | 2     | Short | 5  | 1  | 3   | —      | 9 RP | Shredding; may sweep across 2 targets |

---

## Melee Weapon Malfunctions

When a melee weapon (chainsword, power axe, etc.) malfunctions, roll on this table:

| d6 | Malfunction |
|----|-------------|
| 1   | **Slipped Grip.** You fumble the weapon. Costs 1 action to recover. |
| 2   | **Stuck Fast.** Weapon bites deep into wall, floor, or enemy. Requires a **Might test (2 successes)** to pull free. Until then, it’s stuck. |
| 3   | **Overload.** Power field or chain drive overheats. Take **d2 damage** from feedback; weapon is unusable until repaired (Tech 2). |
| 4   | **Kickback.** Weapon recoils violently. You fall prone unless you pass a **Reflex test (2 successes)**. |
| 5   | **Friendly Nick.** In the chaos, your swing clips an ally in the same zone for **d2 damage**. |
| 6   | **Catastrophic Break.** Blade shatters / chain seizes. Weapon is destroyed in a spray of shards or sparks; you take **d3 damage**. |

---

## Special Weapons

| Tier | Weapon Name          | Hands | Slots | Range   | SR | MR | Dmg | Reload | Cost | Special |
|------|----------------------|-------|-------|---------|----|----|-----|--------|------|---------|
| 1    | **Incendiary Thrower** | 2H  | 2     | Short   | 2  | 3  | 2   | 1      | 3 RP | Area attack (all in zone); Unreliable |
| 2    | **Flame Projector**  | 2H    | 2     | Short   | 3  | 2  | 2   | 2      | 4 RP | Suppression capable; Shredding |
| 2    | **Plasma Torch**     | 1H    | 1     | Short   | 2  | 3  | 2   | 1      | 3 RP | Dual-use: melee cutter or ranged blast (Short) |
| 3    | **Heavy Flamer**     | 2H    | 3     | Medium  | 4  | 2  | 3   | 2      | 6 RP | Area attack (zone + adjacent); Overheat |
| 3    | **Plasma Ejector**   | 2H    | 2     | Medium  | 4  | 2  | 3   | 2      | 6 RP | Armor-Piercing; Friendly Splash |
| 4    | **Inferno Cannon**   | 2H    | 3     | Long    | 5  | 2  | 4   | 3      | 9 RP | Full Suppression capable; area burns for d3 rounds |
| 4    | **Plasma Incinerator** | 2H | 3     | Medium  | 5  | 1  | 4   | 3      | 10 RP| Catastrophic on crit fail (auto Malfunction) |

---

## Special Weapon Malfunctions

Flamers, plasma throwers, and other volatile heavy weapons are powerful but risky. When they malfunction, roll on this table:

| d6 | Malfunction |
|----|-------------|
| 1   | **Pilot Light Out.** Flamer fails to ignite. Spend 1 action to reignite. |
| 2   | **Fuel Leak.** Tank or hose leaks. You are drenched in flammable liquid. Next fire source that hits you deals **+d6 damage**. |
| 3   | **Backwash.** Fuel vents backwards. Take **d3 damage** and armor degrades 1 tier. |
| 4   | **Blowback.** Plasma vent or fuel line bursts. Everyone in same zone makes a **Reflex test (2 successes)** or takes **d2 damage**. |
| 5   | **Friendly Splash.** Flame jet arcs wide, catching an ally in the same zone for **d3 damage**. |
| 6   | **Catastrophic Explosion.** Tank or plasma coil detonates. You take **d6 damage**; all others in Short range take **d3 damage**. Weapon destroyed. |

---

## Utility Gear

| Item | Slots | SR | MR | Cost | Special |
|------|-------|----|----|------|---------|
| **Plasma Welder** | 2 | 2 | 3 | 3 RP | Cuts through bulkheads/doors (Task HP –1); can seal doors. |
| **Monotool** | 1 | 1 | 4 | 1 RP | Universal wrench/driver/saw; grants +1 die to basic repairs. |
| **Industrial Cutter** | 2 | 2 | 3 | 3 RP | Destroys crates, plating, alien bone; doubles as crude melee (Dmg 2, Unreliable). |
| **Repair Kit** | 1 | 2 | 4 | 2 RP | Restores 1 DRR to armor/gear with Tech test. Consumable (3 uses). |
| **Armour Patch Foam** | 1 | 1 | 4 | 2 RP | Seals breaches, restores 1 DRR for remainder of mission. Consumable (1 use). |
| **Stasis Spray** | 1 | 1 | 4 | 2 RP | Freezes corrosion/acid/bleeding. Restores 1d4 HP if applied immediately after injury. |
| **Motion Tracker** | 1 | 2 | 3 | 2 RP | Detects movement in adjacent zones. May reveal false positives on malfunction. |
| **Bioscanner** | 1 | 2 | 3 | 3 RP | Picks up heat/life signs; range = 2 zones. |
| **Spectral Analyzer** | 1 | 2 | 2 | 3 RP | Detects cloaked/stealthed targets. On malfunction: ghost echoes. |
| **Seismic Probe** | 2 | 3 | 3 | 4 RP | Maps weak points; reduces Task HP by 2 when breaching/cutting. |
| **Survey Drone** | 2 | 2 | 2 | 4 RP | Remote recon drone (range 3 zones). On malfunction: attracts attention. |
| **Medi-Pack** | 1 | 2 | 4 | 2 RP | Restores d6 HP with Tech test. Consumable (3 uses). |
| **Field Surgery Kit** | 2 | 2 | 3 | 3 RP | Stabilizes crippled limbs; restores Broken results 2 or 3. |
| **Nanite Injector** | 1 | 2 | 2 | 3 RP | Restores 2d4 HP but adds “Corruption” (flaw roll at mission end). |
| **Cybernetic Spares** | 2 | 2 | 3 | 4 RP | Emergency replacement limb/eye; restores function but may glitch (new flaw). |
| **Standard Cyberdeck** | 2 | 2 | 3 | 3 RP | Hack doors, turrets, terminals (Task HP –1). |
| **Black Ice Deck** | 3 | 3 | 2 | 5 RP | Advanced hacking; can attack systems. On malfunction: feedback damage (d2). |
| **Signal Scrambler** | 1 | 1 | 3 | 2 RP | Jams comms in 1 zone; hostile AI lose 1 die to tests. |
| **Data Spike** | 1 | 1 | 2 | 2 RP | Brute-force breach tool. +2 SR vs electronic locks. |
| **Override Chip** | 0.5 | 0 | – | 1 RP | Single-use passkey. Auto-unlocks a standard door/terminal. |
| **Grapple Gun** | 2 | 2 | 3 | 3 RP | Fires line 2 zones. Move Reflex test auto-succeeds if grapple attached. |
| **Mag Boots** | 1 | 1 | 4 | 2 RP | Walk in zero-G. On malfunction: stuck or release fails. |
| **Climbing Rig** | 1 | 1 | 4 | 1 RP | Ropes & ascenders. Grants +2 SR on climb tests. |
| **Thruster Pack** | 2 | 2 | 2 | 4 RP | Short burst (move 2 zones, vertical or zero-G). On malfunction: spin out. |
| **Portable Breach Charge** | 2 | 2 | 2 | 3 RP | Blows open bulkhead/door (Task HP instantly 0). 1 use only. |

---

## Utility Gear Malfunctions (d6)

| d6 | Malfunction |
|----|-------------|
| 1 | **Power Drain.** Gear flickers out, requires 1 action to reboot. |
| 2 | **Overheat.** Tool sears user — take **1 damage**. |
| 3 | **Misread.** Scanner gives false info (phantom blips, wrong life signs). |
| 4 | **Lockout.** Gear locks; requires **Tech test (2 successes)** to restore. |
| 5 | **Feedback.** Sparks/shock: user takes **d2 damage**, nearby electronics glitch. |
| 6 | **Catastrophic Short.** Tool fries itself. Destroyed in sparks and smoke. |