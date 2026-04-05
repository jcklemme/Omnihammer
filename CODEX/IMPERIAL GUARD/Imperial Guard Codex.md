# **CODEX: IMPERIAL GUARD**

*Compiled Session Document — All rules, datasheets, and design notes from the Imperial Guard development pass.*

---

# PART 1: FACTION RULES

---

## **IMPERIAL GUARD SPECIAL RULES**

### **Voice of Command (Revised)**

The **Voice of Command** special rule has been replaced by the tiered command system described in the **COMMAND HIERARCHY** section below. All officers in Codex: Imperial Guard have one of the following command designations: **Junior Officer**, **Senior Officer**, or **Commanding Officer**.

An **Officer** can attempt to issue an order provided he is not locked in combat, embarked in a vehicle or building, falling back, or has gone to ground. Issuing an **Order** does not prevent the **Officer's** unit from acting (shooting, advancing, etc.) later in that phase.

**Orders** cannot be issued to embarked units, or units that previously received an **Order** that phase (whether or not the **Order** was successful). Unless otherwise stated, **Orders** cannot be issued to units that are locked in combat, are falling back, or have gone to ground.

**Incompetent Command:** If double 6s are rolled for an ordered unit's Leadership test, the order does not take effect, and no further **Orders** can be issued by any **Officer** at that tier for the remainder of this turn.

**Inspired Tactics:** If double 1s are rolled for an ordered unit's Leadership test, once the **Order** has been resolved, all further **Orders** issued by officers at that tier are automatically successful for the remainder of this turn.

---

### **Heavy Weapons Team**

For all game purposes, each Heavy Weapons Team or Veteran Weapons Team is treated as a single model with the ***Bulky*** special rule — it may only fire one weapon in the Shooting phase, only gains one additional attack for charging, and only counts as one model for Morale checks, in addition to any other rules/situations governing number of models.

---

### **Tank Orders**

A **Tank Commander** can roll 2D6 at the beginning of its controlling player's turn. If the result is 9 or less, it may issue one of the following **Orders** during the indicated phase. Tank Orders do not use Leadership tests and are not affected by ***Inspired Tactics***, ***Incompetent Command***, or **Vox-casters**.

**"Full Throttle!":** (Movement) The Tank Commander's unit immediately moves Flat Out, up to 6+D6", regardless of being **Heavy**.

**"Gunners, Kill on Sight!":** (Shooting) The Tank Commander's unit immediately makes a shooting attack. The Tank Commander must shoot at a different target than the rest of his unit. The Tank Commander must resolve his shooting attack first. Once this shooting attack has been resolved, resolve the shooting attacks made by the rest of the unit. These must be at a different target than the Tank Commander's shooting attack, and cannot be at a unit that was forced to disembark as a result of the Tank Commander's initial shooting attack.

**"Strike and Shroud!":** (Shooting) The Tank Commander's unit must make a shooting attack. After this shooting attack has been resolved, all vehicles in the unit who have not already done so must use their smoke launchers.

---

# PART 2: COMMAND HIERARCHY

---

## **COMMAND TIERS**

The Imperial Guard operates under a rigid three-tier command hierarchy. Each tier of command can only issue orders to the tier directly below it. Orders do not skip tiers.

| Tier | Title | Targets | Order Scope |
| :---: | :---- | :---- | :---- |
| **Tier 1** | **Platoon Commander** (Junior Officer) | Individual squads within his Platoon that are in **PLATOON COHERENCY** | **Tactical Orders** — squad-level actions |
| **Tier 2** | **Company Commander** (Senior Officer) | **Platoon Commanders** within range | **Operational Orders** — Platoon-wide directives relayed through the Platoon Commander |
| **Tier 3** | **Regimental Commander** (Commanding Officer) | **Company Commanders** within range | **Strategic Orders** — Company-wide or detachment-wide directives |

**Orders do not skip tiers.** A Company Commander may not directly order an Infantry Squad — he orders its Platoon Commander, who relays the order to his squads. A Regimental Commander may not directly order a Platoon Commander — he orders the Company Commander, who relays it downward.

---

## **PLATOON COHERENCY**

A **Platoon** is a formation consisting of one **Platoon Command Squad** and one or more **Infantry Squads** (and potentially attached support units). Each squad in a Platoon is its own **UNIT** for all game purposes — movement, shooting, coherency, and targeting. However, squads in a Platoon share a morale infrastructure through **PLATOON COHERENCY**.

### Establishing Platoon Coherency

A squad is in **PLATOON COHERENCY** if it can trace an unbroken chain of friendly units from the same Platoon back to the **Platoon Command Squad**, where each link in the chain has at least one model within 3" of a model from the next unit in the chain.

- The **Platoon Command Squad** is always the anchor of the chain. A chain that does not include the Platoon Command Squad does not grant Platoon Coherency.
- A squad does not need to be directly within 3" of the Platoon Command Squad — it only needs to be within 3" of another squad that is itself in Platoon Coherency (i.e., the chain can pass through intermediate squads).
- Platoon Coherency is checked whenever a rule requires it. A squad that was in Platoon Coherency at the start of a phase is considered to have been in Platoon Coherency for the duration of that phase, even if casualties during the phase break the chain. The updated coherency status takes effect at the start of the next phase.

### Effects of Platoon Coherency

**1. Pooled Casualty Threshold.** When determining whether the 25% casualty threshold has been reached for **CASUALTY TESTS**, count the total starting strength of all squads in the Platoon that are currently in Platoon Coherency as the "starting strength," and the total remaining models in those squads as the "current strength."

**2. Shared Leadership.** Squads in Platoon Coherency may use the **Platoon Commander's** Leadership value for all **MORALE TESTS** (Casualty Tests, Pinning Tests, Break Tests, and Regroup Tests).

**3. Order Eligibility.** Only squads in Platoon Coherency may receive **Tactical Orders** from their Platoon Commander.

### Breaking Platoon Coherency

A squad loses Platoon Coherency if the chain of units connecting it back to the Platoon Command Squad is broken, the Platoon Command Squad is destroyed, or the squad voluntarily moves out of chain range.

**Immediate effect:** A squad that loses Platoon Coherency is **fully independent** from the start of the next phase. It reverts to its own starting strength for the 25% casualty threshold, its own Leadership value for morale tests, and ineligibility to receive Tactical Orders.

A squad that re-establishes the 3" chain back to the Platoon Command Squad regains Platoon Coherency and all its benefits.

---

## **LOSS OF COMMAND**

### Platoon Commander Killed

When a **Platoon Commander** model is removed as a casualty:

1. **All squads in the Platoon** must take an immediate **BREAK TEST**, using their own Leadership value.
2. **Platoon Coherency is permanently lost** for this Platoon for the remainder of the game.
3. **Surviving members of the Platoon Command Squad** remain on the table but may not issue Orders and do not serve as a coherency anchor.

**Orphaned Squads:** Squads from a Platoon that has lost its commander use their own Leadership for all tests, their own starting strength for casualty thresholds, and cannot receive Tactical Orders from any Platoon Commander. They **can** still be targeted by a **Company Commander's** Tactical Orders directly, but this burns his order for the turn.

### Company Commander Killed

When a **Company Commander** model is removed as a casualty:

1. **All Platoon Commanders** in the Company must take an immediate **BREAK TEST** using their own Leadership value.
   - If a Platoon Commander fails, his entire Platoon follows the **PLATOON COMMANDER KILLED** sequence above.
2. **No further Operational Orders** may be issued to Platoons in this Company for the remainder of the game, unless a Regimental Commander issues a Strategic Order to restore command.

### Regimental Commander Killed

When a **Regimental Commander** model is removed as a casualty:

1. **All Company Commanders** must take an immediate **BREAK TEST** using their own Leadership value. Failures cascade downward.
2. **No further Strategic Orders** may be issued for the remainder of the game.

---

## **THE RELAY MECHANIC**

When a higher-tier officer issues an order to a lower-tier officer, the order must be **relayed**.

1. The issuing officer declares the order and nominates a target officer within range.
2. The **issuing officer's** unit takes a **Leadership test** (subject to all normal modifiers).
   - If failed, the order is not transmitted. The issuing officer has expended the order.
   - **Incompetent Command** (double 6s) shuts down that command tier for the turn.
   - **Inspired Tactics** (double 1s) makes all further orders at that tier auto-succeed for the turn.
3. If the issuing officer's test succeeds, the **target officer** must take his own **Leadership test** to relay the order.
   - If failed, the order is lost. The target officer has not expended one of his own orders.
   - If passed, the order takes effect on all eligible units.

### Relay and Vox-Casters

If the **issuing officer's** unit has a Vox-caster AND the **target officer's** unit has a Vox-caster, a failed Leadership test by either officer may be re-rolled (once per test). Both units must have Vox-casters.

### Relay and Inspired Tactics / Incompetent Command

**Inspired Tactics** and **Incompetent Command** triggered by the issuing officer affect all subsequent orders at that tier. They do **not** cascade to the relay test. **Inspired Tactics** and **Incompetent Command** triggered by the relay test affect all subsequent relay tests by that specific officer for the turn. They do not cascade upward.

---

## **OFFICER DESIGNATIONS**

### Junior Officer

May issue one **Tactical Order** per turn to a single friendly non-vehicle unit from Codex: Imperial Guard that is part of the officer's own Platoon, in **PLATOON COHERENCY**, and within 12".

### Senior Officer

May issue one **Operational Order** per turn to a single friendly **Platoon Commander** within 12". The order is relayed using the **RELAY MECHANIC**.

Alternatively, may issue a **Tactical Order** directly to a single orphaned squad within 12", expending his order for the turn.

May also issue **Tactical Orders** to units in his own unit's Platoon (if applicable) following Junior Officer rules.

### Commanding Officer

May issue one **Strategic Order** per turn to a single friendly **Company Commander** within 24". The order is relayed downward through the command chain.

May also issue **Operational Orders** following Senior Officer rules, and **Tactical Orders** to his own attached unit.

---

# PART 3: ORDERS

---

## **TACTICAL ORDERS**

*Issued by a Junior Officer to a single squad in his Platoon that is in Platoon Coherency and within 12". Tactical Orders compel the ordered unit to act.*

### Movement Phase

**"Move! Move! Move!"**
(Movement) Instead of making a normal or advance move, the ordered unit immediately moves up to 3D6" (roll three dice and use the highest result). Normal movement rules apply. The unit counts as having advanced and may not shoot or charge this turn.

**"Into Position!"**
(Movement) The ordered unit makes a normal move. After completing this move, the unit counts as having remained stationary for the purposes of shooting (allowing Heavy Weapons to fire normally).

**"Get Your Heads Down!"**
(Movement) The ordered unit immediately goes to ground. The unit gains +2 to its cover save (instead of the normal +1).

### Shooting Phase

**"First Rank, Fire! Second Rank, Fire!"**
(Shooting) The ordered unit must make a shooting attack. All models firing Lasguns or Hot-Shot Lasguns fire one additional shot.

**"Take Aim!"**
(Shooting) The ordered unit must make a shooting attack. All models gain +1 BS (to a maximum of BS5).

**"Suppressive Fire!"**
(Shooting) The ordered unit must make a shooting attack. All weapons gain ***Pinning***. For each unsaved wound, the target gains one additional suppression token.

**"Concentrated Fire!"**
(Shooting) The ordered unit must make a shooting attack. The unit automatically passes its ***Split Fire*** test and may split fire between up to three targets.

**"Fix Bayonets!"**
(Shooting) The ordered unit may not shoot this turn. The unit gains +1 Attack and ***Counter-Attack*** until the end of the next Assault Phase. If the unit declares a charge this turn, it also gains ***Furious Charge***.

### Assault Phase

**"Hold the Line!"**
(Assault) The ordered unit gains ***Stubborn*** until the end of the current Assault Phase. If unengaged, it instead gains ***Counter-Attack*** and ***Stubborn*** until the end of the next Assault Phase.

**"Forward, for the Emperor!"**
(Assault) The ordered unit must declare a charge if a valid target exists. The unit gains +1 to its charge distance roll and ***Furious Charge***. If no valid target exists, the order has no effect but is expended.

### Any Phase

**"Get Back in the Fight!"**
(Any) May only target a unit that is falling back or has gone to ground. The unit immediately regroups (if falling back) or cancels going to ground. The unit counts as having moved.

**"Stand Fast!"**
(Any) May only be issued immediately before the ordered unit takes a **MORALE TEST**. The unit may re-roll the failed morale test. The result of the re-roll stands.

---

## **OPERATIONAL ORDERS**

*Issued by a Senior Officer to a Platoon Commander within 12". Relayed via the Relay Mechanic. Affects all squads in the target Platoon that are in Platoon Coherency. Operational Orders do not compel actions — they provide buffs.*

**"All Units, Engage at Will"**
(Shooting) All coherent squads gain ***Preferred Enemy*** against a single enemy unit nominated by the Company Commander. Lasts until end of turn.

**"Concentrated Barrage"**
(Shooting) All coherent squads that shoot at the **same target** gain +1 BS. Squads shooting at different targets do not receive the bonus.

**"Dig In!"**
(Movement) All coherent squads that remain stationary gain +1 to cover saves until the start of the next turn. Units in the open gain a 6+ cover save instead. Does not stack with going to ground.

**"Advance by Bounds"**
(Movement) All coherent squads may advance with 2D6 (use highest) instead of 1D6. Squads that advance may fire Assault weapons at normal BS (instead of snap fire) and Rapid Fire weapons with snap fire (instead of not firing at all).

**"Hold at All Costs!"**
(Any) All coherent squads gain ***Stubborn*** until the start of the next turn. Squads within 3" of an objective marker gain ***Fearless*** instead.

**"Regroup and Reform!"**
(Any) May only target a Platoon with broken/falling back squads. All broken squads still in Platoon Coherency may immediately attempt to regroup with +1 to Leadership.

---

## **STRATEGIC ORDERS**

*Issued by a Commanding Officer to a Company Commander within 24". Relayed downward through the command chain. Strategic Orders provide broad, lasting effects.*

**Directive: Creeping Barrage**
(Shooting) All ***Barrage*** weapons in the target Company's detachment gain +1 Strength and ***Ignores Cover*** until end of turn. Units hit must take Pinning tests at -1 Leadership.

**Directive: Forward Deployment**
(Movement) Nominate one Platoon. That Platoon's squads may make an additional D6" move after normal movement. Units count as having advanced for shooting.

**Directive: Reserves Forward**
(Any — start of turn) Reserve rolls for units in the target detachment succeed on a 3+. Units arriving from reserve may re-roll scatter dice when deep striking.

**Directive: Strategic Withdrawal**
(Movement) All falling back units in the target detachment may immediately halt and regroup regardless of enemy proximity. Regrouped units may not shoot this turn. All units in the detachment gain +2 Ld for Casualty Tests and Break Tests this turn.

**Directive: Tactical Reassignment**
(Any — start of turn) Nominate one **Orphaned** Platoon. For the remainder of the game, that Platoon is reassigned to a surviving Company Commander, who may issue Operational Orders to the orphaned squads as a group. The squads do not regain Platoon Coherency.

**Directive: General Advance / General Retreat**
(Movement) **All units** in the target detachment must advance (General Advance: +1" to normal movement) or fall back toward deployment zone (General Retreat: 3D6 pick highest for fall back, may shoot with snap fire after falling back).

---

# PART 4: FORCE ORGANIZATION

---

## **COMPANY DETACHMENT** *(Standard)*

| CATEGORY | MIN | MAX | NOTES |
| :---- | :---: | :---: | :---- |
| **HQ** | **1** | **2** | Must include at least one Company Commander (Senior Officer). |
| **TROOPS** | **2** | **6** | Each Troops selection is a **Platoon** (see below). |
| **ELITE** | **0** | **3** | |
| **FAST ATTACK** | **0** | **3** | |
| **HEAVY SUPPORT** | **0** | **3** | |
| **LORD OF WAR** | **0** | **1** | |
| **FORTIFICATIONS** | **0** | **2** | |

**Platoon Composition:**

| Component | Min | Max |
| :---- | :---: | :---: |
| Platoon Command Squad | 1 | 1 |
| Infantry Squad | 2 | 5 |
| Heavy Weapons Squad | 0 | 2 |
| Special Weapons Squad | 0 | 1 |
| Conscript Squad | 0 | 1 |

**No Dedicated Transports** for Infantry Squads or Platoon Command Squads in a standard Company Detachment.

---

## **REGIMENTAL COMMAND DETACHMENT** *(Optional)*

May only be taken in addition to at least one other detachment. Maximum one per army.

| CATEGORY | MIN | MAX | NOTES |
| :---- | :---: | :---: | :---- |
| **HQ** | **1** | **1** | Must be a Regimental Commander (Commanding Officer). |
| **ELITE** | **0** | **2** | Regimental advisors, bodyguards, sanctioned psykers. |
| **TROOPS** | **0** | **1** | Regimental command security Platoon (optional). |
| **HEAVY SUPPORT** | **0** | **1** | Regimental-level fire support. |

---

## **SPECIAL DETACHMENTS — OVERVIEW**

Three additional detachment types exist for specialized formations. These are defined in separate documents:

- **Armored Company Detachment** — Tank Commander (HQ), Leman Russ Squadrons (Troops). Tank Orders, direct command, no relay. *(Architecture defined, full build TBD.)*
- **Mechanized Company Detachment** — Company Commander (HQ), Mechanized Platoons (Troops, must take Chimera/Taurox). Infantry hierarchy with mounted bonuses. *(Architecture defined, full build TBD.)*
- **Artillery Battery Detachment** — Battery Commander (HQ), Gun Batteries (Troops, crew-served only). Fire Missions, Forward Observers. *(Full build complete — see below.)*

All special detachments plug into the Regimental Commander tier via Strategic Orders.

---

## **ARTILLERY BATTERY DETACHMENT**

| CATEGORY | MIN | MAX | NOTES |
| :---- | :---: | :---: | :---- |
| **HQ** | **1** | **1** | Battery Commander (Artillery Officer). |
| **TROOPS** | **2** | **4** | Gun Batteries (crew-served only). |
| **ELITE** | **0** | **2** | Forward Observer Teams, Enginseer Teams. |
| **FAST ATTACK** | **0** | **1** | Sentinel Squadrons (perimeter security). |
| **HEAVY SUPPORT** | **0** | **1** | Superheavy crew-served artillery, Hydra Batteries. |
| **FORTIFICATIONS** | **0** | **2** | Gun emplacements, bunkers. |

### Fire Missions

Fire Missions are issued by the Battery Commander at the start of the Shooting Phase to a gun battery in his detachment. He must pass a **Leadership test**. Fire Missions may target any gun battery regardless of range (via vox), or within 36" without a Vox-caster. **Incompetent Command** and **Inspired Tactics** apply.

**"Concentrated Bombardment"** — All guns fire at a single point. Each subsequent gun reduces scatter by 2" (minimum 0").

**"Danger Close"** — Battery may ignore minimum range. Scatter increases to 3D6". D6 per friendly unit within 6" of target; on a 1, D3 S5 AP- hits.

**"Smoke Screen"** — No damage. Place smoke markers (one per gun, 5" wide) that block LOS until end of next player turn.

**"Sustained Bombardment"** — Fire normally, leave markers. Next turn the battery fires again at the same point without a new Fire Mission, scatter reduced by D6".

**"Counter-Battery Fire"** — Direct Fire at enemy artillery or Barrage vehicles. +1 BS and ***Tank Hunters***.

---

# PART 5: UNIT DATASHEETS

---

## **Company Command Squad** *(HQ)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Company Commander | 4 | 4 | 3 | 3 | 2 | 3 | 3 | 9 | 5+ | 5+ | Infantry (Character) |
| Veteran | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 5+ | - | Infantry |

**Unit Composition:** 1 Company Commander and 4 Veterans — X pts

**Special Rules:**
- ***Senior Officer***
- ***Command Authority:*** Friendly units from Codex: Imperial Guard within 6" may use his Leadership for **MORALE TESTS**.

**Wargear:** Flak Armor, Laspistol, Close Combat Weapon, Frag Grenades, Refractor Field (Commander). Flak Armor, Lasgun, Frag Grenades (Veterans).

**Options:**
- Commander may replace Laspistol/CCW with: Bolt Pistol, Plasma Pistol, Boltgun, Power Sword, Power Axe, Power Maul, Power Fist — X pts each
- Commander may upgrade to Carapace Armor — X pts
- Commander may upgrade Refractor Field to Power Field — X pts
- Commander may take Melta Bombs — X pts
- Commander may take one Heirloom of Conquest — X pts
- Squad may include up to 2 additional Veterans — X pts per model
- Up to 2 Veterans may take special weapons (Flamer, Grenade Launcher, Meltagun, Plasma Gun, Hot-Shot Lasgun) — X pts each
- Up to 2 Veterans may take heavy weapons (Heavy Bolter, Autocannon, Lascannon, Missile Launcher) — X pts each
- One Veteran may take a Vox-caster — X pts
- One Veteran may take a Regimental Standard — X pts
- One Veteran may take a Medi-Pack — X pts

---

## **Platoon Command Squad** *(Troops — part of a Platoon)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Platoon Commander | 3 | 3 | 3 | 3 | 1 | 3 | 2 | 8 | 5+ | - | Infantry (Character) |
| Guardsman Veteran | 3 | 4 | 3 | 3 | 1 | 3 | 1 | 7 | 5+ | - | Infantry |

**Unit Composition:** 1 Platoon Commander and 4 Guardsman Veterans — X pts

**Special Rules:**
- ***Junior Officer***
- ***Platoon Anchor:*** Anchors Platoon Coherency. If destroyed, all squads in the Platoon lose coherency permanently and take immediate Break Tests.

**Wargear:** Flak Armor, Laspistol, Close Combat Weapon, Frag Grenades (Commander). Flak Armor, Lasgun, Frag Grenades (Veterans).

**Options:**
- Commander may replace Laspistol/CCW with: Bolt Pistol, Plasma Pistol, Boltgun, Power Sword, Power Fist — X pts each
- Commander may take Melta Bombs — X pts
- Commander may take a Refractor Field — X pts
- One Veteran may take a special weapon (Flamer, Grenade Launcher, Meltagun, Plasma Gun, Hot-Shot Lasgun) — X pts
- One Veteran may take a Vox-caster — X pts
- One Veteran may take a Platoon Standard — X pts
- One Veteran may take a Medi-Pack — X pts

---

## **Infantry Squad** *(Troops — part of a Platoon)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Sergeant | 3 | 3 | 3 | 3 | 1 | 3 | 2 | 8 | 5+ | - | Infantry (Character) |
| Guardsman | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 5+ | - | Infantry |

**Unit Composition:** 1 Sergeant and 9 Guardsmen — X pts. Fixed at 10 models.

**Special Rules:**
- ***Platoon Infantry:*** Subject to **PLATOON COHERENCY** rules. Uses Platoon Commander's Leadership and pooled casualty threshold while in coherency.

**Wargear:** Flak Armor, Laspistol, Close Combat Weapon, Frag Grenades (Sergeant). Flak Armor, Lasgun, Frag Grenades (Guardsmen).

**Options:**
- Sergeant may replace Laspistol/CCW with: Bolt Pistol, Plasma Pistol, Boltgun, Power Sword, Power Fist — X pts each
- Sergeant may take Melta Bombs — X pts
- One Guardsman may take a special weapon (Flamer, Grenade Launcher, Meltagun, Plasma Gun, Hot-Shot Lasgun) — X pts
- One Guardsman may take a Vox-caster — X pts
- The entire squad may take Krak Grenades — X pts
- Two Guardsmen may be replaced by a Heavy Weapons Team (single Bulky model) with one of: Heavy Bolter, Missile Launcher, Autocannon, Lascannon, Mortar — X pts

---

## **Battery Commander** *(HQ — Artillery Battery Detachment)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Battery Commander | 4 | 4 | 3 | 3 | 2 | 3 | 3 | 9 | 5+ | 5+ | Infantry (Character) |
| Gunnery Veteran | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 5+ | - | Infantry |

**Unit Composition:** 1 Battery Commander and 3 Gunnery Veterans — X pts

**Special Rules:**
- ***Artillery Officer:*** May issue one **Fire Mission** per turn via Leadership test. Unlimited range via vox, 36" without.
- ***Fire Coordination:*** Gun batteries in this detachment subtract 1" from scatter distance (minimum 0").
- ***Command Authority:*** Friendly Artillery Battery units within 6" may use his Leadership for morale tests.

**Wargear:** Flak Armor, Laspistol, Close Combat Weapon, Frag Grenades, Refractor Field (Commander). Flak Armor, Lasgun, Frag Grenades (Veterans).

**Options:**
- Commander may replace weapons with items from Ranged/Melee Weapons lists — X pts
- Commander may upgrade to Carapace Armor — X pts
- Commander may take a Heirloom of Conquest — X pts
- One Veteran may take a Vox-caster — X pts
- One Veteran may take a special weapon — X pts
- Unit may take a Chimera as Dedicated Transport — X pts (Fire Missions issued while embarked suffer -1 Ld)

---

## **Gun Battery** *(Troops — Artillery Battery Detachment)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Gun Crewman | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 5+ | - | Infantry |
| Gun Crew Sergeant | 3 | 3 | 3 | 3 | 1 | 3 | 2 | 8 | 5+ | - | Infantry (Character) |

**Artillery Piece:** T6, W2, 3+ Sv (default).

**Unit Composition:** 1 Gun Crew Sergeant, 1 Artillery Piece, and 4 Gun Crewmen — X pts

**Special Rules:**
- ***Artillery*** (Core Rules)
- ***Dug In:*** Stationary gun crew gains 5+ cover (4+ after two consecutive stationary turns).
- ***Fixed Position:*** Artillery piece that never moved all game gains +1T and +1W.

**Gun Options:**

| Gun | Range | S | AP | Type |
| :---- | :---: | :---: | :---: | :---- |
| Earthshaker Cannon | 36"-240" | 9 | 3 | Ordnance 1, Barrage, Large Blast |
| Medusa Siege Gun | 36"-120" | 10 | 2 | Ordnance 1, Barrage, Large Blast |
| Heavy Mortar | 24"-120" | 6 | 4 | Heavy 1, Barrage, Large Blast |
| Quad Launcher (Thudd Gun) | 12"-60" | 5 | 5 | Heavy 4, Barrage, Blast |
| Heavy Quad Launcher | 24"-120" | 7 | 3 | Heavy 4, Barrage, Blast |

**Options:**
- Up to 2 additional guns with 4 crew each — X pts per gun
- One Crewman per gun may take a Vox-caster — X pts
- Each gun may take Camo Netting — X pts
- Each gun may take Entrenching Tools (for crew) — X pts

---

## **Forward Observer Team** *(Elites — Artillery Battery Detachment)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Forward Observer | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 5+ | - | Infantry |
| Observer Sergeant | 3 | 3 | 3 | 3 | 1 | 3 | 2 | 8 | 5+ | - | Infantry (Character) |

**Unit Composition:** 1 Observer Sergeant and 2 Forward Observers — X pts

**Special Rules:**
- ***Designate Target:*** Instead of shooting, designate an enemy unit in LOS. Until end of turn, gun batteries firing at the designated unit reduce scatter by an additional D6" and reduce the target's cover save by 1.
- ***Stealth***, ***Scouts***
- ***Small Team:*** May not be joined by Independent Characters.

**Wargear:** Flak Armor, Laspistol, CCW, Frag Grenades, Auspex (Sergeant). Flak Armor, Lasgun, Frag Grenades, Vox-caster (one Observer).

**Options:**
- Up to 2 additional Forward Observers — X pts per model
- Team may take Camo Gear — X pts per model

---

## **Named Characters** *(Placeholders)*

Colonel 'Iron Hand' Straken and Color Sergeant Kell exist as placeholder imports from 7th edition. These profiles are not authoritative and require a full rewrite in a future pass. Straken's "Gung-ho" challenge reference is flagged as an error — challenges are not a core OmniHammer mechanic.

---

# PART 6: WARGEAR

---

## **Wargear Costs**

*Placeholder — to be completed during points costing pass.*

## **Wargear Profiles**

### **Ranged Weapons**

**Auto-Weapons and Cannons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Autopistol | 12" | 3 | - | Pistol |
| Autogun | 24" | 3 | - | Rapid Fire |
| Battle Cannon | 72" | 8 | 3 | Ordinance 1, Large Blast |
| Taurox Battle Cannon | 48" | 7 | 4 | Heavy 1, Blast |
| Vanquisher Battle Cannon | 72" | 8 | 3 | Heavy 1, Armourbane |
| Earthshaker Cannon | 36"-240" | 9 | 3 | Ordinance 1, Barrage, Large Blast |
| Baneblade Cannon | 72" | 9 | 2 | Primary Weapon 1, Apocalyptic Blast |
| Hellhammer Cannon | 36" | 10 | 1 | Primary Weapon 1, Ignores Cover, Massive Blast |
| Magma Cannon | 60" | 10 | 1 | Primary Weapon 1, Large Blast |
| Quake Cannon | 24"-180" | 9 | 3 | Primary Weapon 1, Apocalyptic Blast |
| Eradicator Nova Cannon | 26" | 6 | 4 | Heavy 1, Large Blast, Ignores Cover |
| Stormsword Siege Cannon | 36" | 10 | 1 | Primary Weapon 1, Apocalyptic Blast, Ignores Cover |
| Tremor Cannon | 60" | 8 | 3 | Primary Weapon 1, Massive Blast, **Earthshock** |
| Taurox Gatling Cannon | 24" | 4 | - | Heavy 10 |
| Punisher Gatling Cannon | 24" | 5 | - | Heavy 20 |
| Assault Cannon | 24" | 6 | 4 | Heavy 4, Rending |
| Autocannon | 48" | 7 | 4 | Heavy 2, Rending |
| Hydra Autocannon | 72" | 7 | 4 | Heavy 2, Skyfire, Rending |
| Exterminator Autocannon | 48" | 7 | 4 | Heavy 4, Twin-linked, Rending |
| Demolisher (Siege) Cannon | 24" | 10 | 2 | Ordinance 1, Large Blast |
| Quad-gun | 48" | 7 | 4 | Heavy 4, Interceptor, Skyfire, Twin-linked, Rending |
| Stormshard Mortar | 48" | 4 | 6 | Heavy 2, Barrage, Blast, Ignores Cover, Shred |

**Earthshock:** All models under this weapon's blast marker that were not removed from play must make a Dangerous Terrain test.

**Boltguns:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Bolt Pistol | 12" | 4 | 5 | Pistol |
| Boltgun | 24" | 4 | 5 | Rapid Fire |
| Storm Bolter | 24" | 4 | 5 | Assault 2 |
| Heavy Bolter | 36" | 5 | 4 | Heavy 3 |
| Vulcan Mega-Bolter | 60" | 6 | 3 | Heavy 15 |

**Las Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Laspistol | 12" | 3 | - | Pistol |
| Hot-Shot Laspistol | 6" | 3 | 3 | Pistol |
| Lasgun | 24" | 3 | - | Rapid Fire |
| Hot-Shot Lasgun | 18" | 3 | 3 | Rapid Fire |
| Hot-Shot Volley Gun | 24" | 4 | 3 | Salvo 2/4 |
| Multi-laser | 36" | 6 | 6 | Heavy 3 |
| Lascannon | 48" | 9 | 2 | Heavy 1 |

**Melta Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Inferno Pistol | 6" | 8 | 1 | Pistol, Melta |
| Meltagun | 12" | 8 | 1 | Assault 1, Melta |
| Multi-Melta | 24" | 8 | 1 | Heavy 1, Melta |
| Melta Cannon | 24" | 8 | 1 | Heavy 1, Blast, Melta |
| Volcano Cannon | 120" | 10 | 2 | Primary Weapon 1, Terrible Weapon, Large Blast |

**Plasma Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Plasma Pistol | 12" | 7 | 2 | Pistol, Gets Hot |
| Plasma Gun | 24" | 7 | 2 | Rapid Fire, Gets Hot |
| Plasma Cannon | 36" | 7 | 2 | Heavy 1, Blast, Gets Hot |
| Executioner Plasma Cannon | 36" | 7 | 2 | Heavy 3, Blast, Gets Hot |

**Flamer Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Hand Flamer | Template | 3 | 6 | Pistol |
| Flamer | Template | 4 | 5 | Assault 1 |
| Heavy Flamer | Template | 5 | 4 | Assault 1 |
| Inferno Cannon | Template | 6 | 4 | Heavy 1, Torrent |

**Missile Launcher:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Frag Missile | 48" | 4 | 6 | Heavy 1, Blast |
| Flakk Missile | 48" | 7 | 4 | Heavy 1, Skyfire |
| Krak Missile | 48" | 8 | 3 | Heavy 1 |

**Stub Guns and Shotguns:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Shotgun | 12" | 3 | - | Assault 2 |
| Heavy Stubber | 36" | 4 | 6 | Heavy 3 |
| Ripper Gun | 12" | 5 | - | Assault 3 |

**Sniper Rifle:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Sniper Rifle | 36" | X | 6 | Heavy 1, Sniper |

**Chem Cannon:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Chem Cannon | Template | 1 | 3 | Heavy 1, Poisoned (2+) |

**Deathstrike Missile:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Deathstrike Missile | 12"-∞ | 10 | 1 | Ordinance 1, Apocalyptic Blast, Barrage, Ignores Cover, One Use Only |

**Demolition Charge:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Demolition Charge | 6" | 8 | 2 | Assault 1, Large Blast, One Use Only |

**Grenade Launcher:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Frag Grenade | 24" | 3 | 6 | Assault 1, Blast |
| Krak Grenade | 24" | 6 | 4 | Assault 1 |

**Grenadier Gauntlet:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Grenadier Gauntlet | 12" | 4 | 6 | Assault 1, Blast |

**Hell Missiles:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Hellfury Missiles | 72" | 4 | 5 | Heavy 1, Large Blast, Ignores Cover, One Use Only |
| Hellstrike Missiles | 72" | 8 | 3 | Ordinance 1, One Use Only |

**Mortar:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Mortar | 48" | 4 | 6 | Heavy 1, Barrage, Blast |

**Multiple Rocket Pod:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Multiple Rocket Pod | 48" | 4 | 6 | Heavy 1, Large Blast |

**Storm Eagle Rockets:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Storm Eagle Rockets | 24"-120" | 10 | 4 | Ordinance D3, Barrage, Large Blast |

**Taurox Missile Launcher:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Frag Missile | 48" | 4 | 6 | Heavy 2, Blast |
| Krak Missile | 48" | 8 | 3 | Heavy 2 |

### **Melee Weapons**

**Force Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Force Stave | Melee | +2 | 2 | Force, Concussive |
| Force Sword | Melee | User | 2 | Force |
| Force Axe | Melee | +1 | 2 | Force, Unwieldy |

**Power Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Power Sword | Melee | User | 2 | Power Weapon |
| Power Axe | Melee | +1 | 2 | Power Weapon, Unwieldy |
| Power Maul | Melee | +2 | 2 | Power Weapon, Concussive |
| Power Lance | Melee | +1/User* | 2 | Power Weapon |
| Power Klaw | Melee | x2 | 2 | Power Weapon, Specialist Weapon, Unwieldy |
| Power Fist | Melee | x2 | 2 | Power Weapon, Specialist Weapon, Unwieldy |

\* The first value is used only when charging.

**Hunting Lances:** Counts as a Close Combat Weapon, except during the first time an equipped model charges into close combat, for the duration of that phase, that model adds +2 to its Initiative, and the Hunting Lance uses the following profile:

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Hunting Lance | Melee | +2 | 3 | Specialist Weapon, One Use Only |

**Servo Arm:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Servo Arm | Melee | x2 | 1 | Specialist Weapon, Unwieldy |

### **Armor**

**Carapace Armor:** 4+ Armor Save
**Flak Armor:** 5+ Armor Save
**Power Armor:** 3+ Armor Save

### **Special Issue Wargear**

**Brute Shield:** 5+ Invul save, can reroll To Wound rolls when resolving Hammer of Wrath hits.
**Camo Gear:** Cover save is 1 better than normal, has a 6+ minimum cover save, even in the open.
**Medi-Pack:** A unit that contains at least one model with a medi-pack has the ***Feel No Pain*** special rule.
**Platoon Standard:** A unit that contains a model with a platoon standard counts as scoring an additional wound for the purposes of calculating assault results.
**Refractor Field:** 5+ Invul save.
**Regimental Standard:** Counts as a platoon standard. Additionally, any friendly units from Codex: Imperial Guard within 12" of a model with a regimental standard reroll failed morale, fear and pinning tests.
**Rosarius:** 4+ Invul save.
**Slabshield:** If a model with a slabshield is in base contact with one or more models with a slabshield from the same unit, it adds +1 to its armor save. Furthermore, if a target (friend or foe) is partially obscured from the firer's view by at least one model with a slabshield, that target receives +1 to its cover save.
**Snare Mines:** Enemy units that charge a unit with snare mines count as having made a disordered charge.
**Vox-caster:** Failed Leadership tests for orders issued to a unit with a vox-caster can be re-rolled, provided the officer's unit also has a vox-caster. An officer may not use a vox-caster's ability on his own unit.

### **Heirlooms of Conquest**

**Bale Eye:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Bale Eye | 6" | 3 | 3 | Pistol |

**Kurov's Aquila:** The officer, and all friendly units from Codex: Imperial Guard within 6", have the ***Preferred Enemy*** special rule. In addition, the bearer may reroll a single failed Leadership test per turn.

**Payback:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Payback | 36" | 5 | 4 | Heavy 3, Rending |

**Power Field:** 4+ Invul save.

**The Blade of Conquest:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| The Blade of Conquest | Melee | +1 | 2 | Power Weapon, Master-crafted |

**The Deathmask of Ollanius:** 4+ Invul save, bearer gains ***It Will Not Die*** and ***Fear***.

**The Emperor's Benediction:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| The Emperor's Benediction | 12" | 5 | 4 | Pistol, Precision Shot, Master-crafted |

**The Laurels of Command:** Whenever a friendly unit from Codex: Imperial Guard within 6" of the bearer is required to make a Morale check, the bearer may choose whether they pass or fail. If the bearer is removed as a casualty, all friendly units within 6" must make an immediate pinning test.

**The Tactical Auto-Reliquary of Tyberius:** Any successful Leadership test for orders that results in a double counts as Inspired Tactics. If double 1 is rolled, Inspired Tactics activates but the device is shut out of the vox network for the remainder of the game.

**Envenomed Blade:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Envenomed Blade | Melee | User | - | Poisoned (2+) |

**Ripper Pistol:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Ripper Pistol | 12" | X | 3 | Pistol, Sniper |

### **Vehicle Equipment**

**Augur Array:** Deep Striking units within 6" of a vehicle with an augur array do not scatter. Must have been on the table at the start of the turn.

**Camo Netting:** Cover save is 1 point better than normal. Always has a 6+ cover save, even in the open.

**Enclosed Crew Compartment:** Vehicle no longer has "Open-topped."

**Fire Barrels:** First time an enemy charges this vehicle, the charging unit suffers D6 S4 AP5 hits.

**Recovery Gear:** If immobilized, roll D6 at end of Movement phase; on a 6, no longer immobilized. Does not restore a structure point.

**Relic Plating:** Vehicle gains ***Adamantium Will***.

---

# PART 7: REGIMENTAL DOCTRINE — DEATH KORPS OF KRIEG

---

## **Doctrine Rules**

### **Siege Discipline**

While a Death Korps **INFANTRY** unit is in cover, reduce the AP of all incoming ranged attacks against that unit by 1 (e.g., AP3 becomes AP4, AP2 becomes AP3). Attacks with AP— are not affected. Does not grant cover where none exists.

### **Iron Discipline**

Death Korps **INFANTRY** and **CAVALRY** units that are in **PLATOON COHERENCY** gain ***Stubborn***.

## **Drawbacks**

### **Penitent Discipline**

Death Korps officers may never benefit from **Inspired Tactics**. Double 1s are simply a passed test. In a mixed army, a Krieg officer's double 1s do not activate Inspired Tactics for any officer in the army.

### **The Cost of Conviction**

Whenever a Death Korps **INFANTRY** or **CAVALRY** unit is completely destroyed, all friendly non-Death Korps units from Codex: Imperial Guard suffer -1 to Leadership for Morale Tests (not Order tests) until the start of the controlling player's next turn. Does not stack.

## **Force Organization Modifications**

- Platoons may include up to **3** Heavy Weapons Squads (instead of 2).
- Death Rider Squadrons available as Fast Attack.
- Combat Engineer Squads available as Elites.
- Fortifications slots increased to **3**.

## **Unique Units**

### Death Rider Squadron *(Fast Attack)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Death Rider | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 4+ | Cavalry |
| Ridemaster | 3 | 3 | 3 | 3 | 1 | 3 | 2 | 8 | 4+ | Cavalry (Character) |
| Death Rider Mount | - | - | 4 | - | - | 4 | 1 | - | - | - |

**Unit Composition:** 5 Death Riders — X pts

**Special Rules:** ***Hunting Lance***, ***Cavalry Charge*** (Furious Charge + Hammer of Wrath + extra +1S on lance when charging), ***Expendable Vanguard*** (destruction does not trigger Cost of Conviction), ***Iron Discipline*** (Stubborn within 3" of any DKoK unit).

**Wargear:** Flak Armor (4+ with mount barding), Laspistol, Hunting Lance, Frag Grenades, Death Rider Mount.

**Options:** Up to 5 additional Riders (X pts/model). One may upgrade to Ridemaster (X pts). Ridemaster may swap laspistol or lance for pistol/melee upgrades.

### Combat Engineer Squad *(Elites)*

|  | WS | BS | S | T | W | I | A | Ld | Save | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Combat Engineer | 3 | 3 | 3 | 3 | 1 | 3 | 1 | 7 | 4+ | Infantry |
| Engineer Watch Master | 3 | 3 | 3 | 3 | 1 | 3 | 2 | 8 | 4+ | Infantry (Character) |

**Unit Composition:** 1 Watch Master and 4 Combat Engineers — X pts

**Special Rules:** ***Siege Engineers*** (Move Through Cover, Stealth, no I penalty charging through difficult terrain), ***Gas Warfare*** (Gas Bombs don't scatter), ***Breach and Clear*** (+1 to wound in melee vs. units in cover/buildings).

**Wargear:** Carapace Armor (4+), Shotgun, CCW, Frag Grenades, Krak Grenades.

**Gas Bombs:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Gas Bomb | Template | 1 | - | Assault 1, Poisoned (2+), One Use Only |

**Options:** Up to 5 additional Engineers (X pts/model). Up to 2 may swap Shotgun for Flamer/Meltagun/Heavy Flamer. One may take Demolition Charge. Entire unit may take Gas Bombs (X pts/model).

## **Unique Wargear**

**Death Korps Greatcoat:** 5+ Armor Save (functionally identical to Flak Armor).

**Entrenching Tools:** Close Combat Weapon. Unit that remained stationary gains 6+ cover in the open; improves to 5+ if stationary for two consecutive turns.

---

# PART 8: CORE RULES UPDATES

---

## **Artillery — Updated Rules** *(Core Rules — Special Model Types)*

*The following replaces the existing Artillery section in the Core Rules.*

Units with artillery or mobile weapon platforms typically have a gun mounted on its own base, and is controlled and fired by a separate model.

The specific unit entry will list the profile and characteristics of the specific artillery piece. If no profile is specified, assume the artillery piece has 6 Toughness, 1 Wound, and a 3+ armor save.

- If the artillery piece was using Armor Values (as if it were a vehicle), instead give it a Toughness of 6 plus 1 toughness for each point of Armor Value above 10.

**MOVING ARTILLERY:** Each artillery model needs at least one crew member in order to move. The artillery piece moves at the speed of the slowest crew member within 2" of it. Crew members must remain within 2" of the artillery piece at the end of their movement.

**SHOOTING ARTILLERY:** In order for an artillery model to shoot, one of its designated crew members within 2" of the artillery model may elect to shoot using the artillery piece instead of their own weapon. Use the artillery AND firing model for determining line of sight. Ranges are measured from the barrel of the artillery model.

- Unless otherwise noted, a model may not shoot artillery after moving.
- Artillery without at least one designated crew member within 2" may not shoot.

**SHOOTING AT ARTILLERY:** Artillery models may be allocated wounds from ranged attacks as if they were a regular model in the unit.

- Artillery models do NOT benefit from the **TAKE COVER!** reaction, even if the rest of the unit has.

**MELEE ATTACKS:** A unit attacking a unit with artillery models may choose to allocate any of their attacks specifically on the artillery models, hitting on a 3+. Artillery models cannot fight back.

**MORALE & UNIT SIZE:** Artillery models are never counted as a model in the unit for purposes of determining starting strength, morale checks, and similar rules.

**TRANSPORTS:** Unless otherwise noted by the specific unit entry, artillery models cannot be placed on transports.

---

### **ABANDONED ARTILLERY** *(New Sub-Section)*

When all designated crew members for an artillery piece are removed as casualties, the artillery piece becomes **ABANDONED**.

**Status of an Abandoned Gun:**
- May not move or shoot.
- No longer part of any unit. Treated as a neutral battlefield object.
- Retains its Toughness, Wounds, and Armor Save characteristics.

**Targeting an Abandoned Gun:**
- Any player may target an abandoned gun with ranged or melee attacks.
- When shooting, treat as a single model unit with no cover save (unless terrain provides it).
- In melee, hit on a 3+. The gun cannot fight back.
- Reduced to zero wounds = destroyed and removed.

**Crewing an Abandoned Gun:**

Any **INFANTRY** model from either player may attempt to crew an abandoned gun by moving into base contact.

1. Model must be in base contact at the start of the Shooting Phase.
2. The model's unit must pass a **Leadership test**. If failed, the gun is not crewed this turn.
3. If passed, the model becomes the gun's crew. The gun may be fired this turn.

**Firing a Crewed Gun:**
- **Same datasheet** as original crew: fires at the crewing model's normal BS.
- **Any other unit profile:** fires using **SNAP FIRE** (6+ to hit).
- Crewing model may not fire personal weapons in the same phase.
- Crewing model may voluntarily abandon the gun at the start of any Movement Phase.
- If the crewing model is removed as a casualty, the gun returns to Abandoned status.
- Crewing model retains its own unit membership for coherency, morale, and all other purposes.

**Self-propelled artillery (Basilisk, Medusa, etc.) is NOT affected by these rules.** Self-propelled guns are vehicles and follow vehicle destruction rules.

---

## **WARGEAR FIXES APPLIED** *(Cross-Codex)*

The following corrections were applied to the Imperial Guard Wargear during this session. These fixes align the IG wargear with the OmniHammer Weapon Family Style Guide:

1. **Power Weapons** — All corrected to AP2 with ***Power Weapon*** USR.
2. **Power Lance** — Normalized to match Power Spear (AP2 throughout).
3. **Force Weapons** — All corrected to AP2.
4. **Autocannons** — All profiles gain ***Rending*** per style guide.
5. **Hot-Shot Volley Gun** — AP typo fixed ("s" → 3).
6. **Meltagun** — Type corrected to "Assault 1, Melta".
7. **Volcano Cannon** — Formatting fixed.
8. **The Blade of Conquest** — Corrected to AP2 with ***Power Weapon*** USR.
