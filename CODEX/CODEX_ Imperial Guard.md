# CODEX: IMPERIAL GUARD

# **ORDERS**

## **General Rules**

An **Order** is a directive issued by an **Officer** model to one or more eligible units. When an Order takes effect, it modifies the behavior of the target unit(s) or detachment as described in the Order's rules text. Orders are not psychic powers, shooting attacks, or morale tests — they are a unique game mechanic specific to Codex: Imperial Guard.

### **Who May Issue Orders**

Only models with one of the following Special Rules may issue Orders:

* ***Junior Officer***  
* ***Senior Officer***  
* ***Commanding Officer***  
* ***Tank Commander***  
* ***Artillery Officer***

A model's Officer designation is listed on its datasheet.

### **Restrictions on the Issuing Officer**

An Officer may not attempt to issue an Order if any of the following conditions apply:

* The Officer is locked in combat.  
* The Officer is embarked in a vehicle or building.  
* The Officer’s unit is **BROKEN** or falling back.  
* The Officer’s unit is **PINNED**.

### **Restrictions on the Target Unit**

An Order may target a unit if any of the following conditions apply, unless the Order’s rules text explicitly states otherwise:

* The target unit is embarked in a vehicle or building.  
* The target unit is locked in combat.  
* The target unit is **BROKEN** or falling back.  
* The target unit is **PINNED**.  
* The target unit has already received an Order during this phase whether or not that Order was successful.

### **Orders and Other Actions**

Issuing an Order does not prevent the Officer’s unit from acting normally later in the same phase (moving, shooting, charging, advancing, reactions, etc.).  The Officer is not required to perform any specific action after issuing an Order unless compelled by the Order itself.

## **Infantry Command Hierarchy**

The Imperial Guard infantry command structure operates on three tiers. Each tier may only issue Orders to the tier directly below it. Orders do not skip tiers.

| Tier | Designation | Order Type | Target | Range |
| :---: | ----- | ----- | ----- | :---: |
| 1 | ***Junior Officer*** | Tactical Orders | A single unit in his Platoon | 12” |
| 2 | ***Senior Officer*** | Operation Orders | A single Platoon | 24” |
| 3 | ***Commanding Officer*** | Strategic Orders | A single Detachment | 48” |

### ***Junior Officer***

A ***Junior Officer*** may issue **one Tactical Order** per Battle Round.  The target must be a single friendly non-vehicle unit from Codex: Imperial Guard that meets all of the following conditions:

* The target unit is part of the Officer’s own Platoon  
* The target unit is in **PLATOON COHERENCY**.  
* At least one model in the target unit is within 12” of the ***Junior Officer***.

### ***Senior Officer***

A ***Senior Officer*** may issue **one Operational Order** per Battle Round.  The target must be a friendly ***Junior Officer*** model from Codex: Imperial Guard from the same Detachment within 24” of the ***Senior Officer***.  The Order is transmitted using the **RELAY MECHANIC** *(see PROCEDURE FOR ISSUING INFANTRY ORDERS BELOW)*.

**ALTERNATIVE USE: Direct Tactical Order:** Instead of issuing an Operational Order, a ***Senior Officer*** may issue a single **Tactical Order** directly to one **Orphaned** unit (see **LOSS OF COMMAND**) within 12”.  He may issue no further orders this turn, and may not do so if he has already issued an **Operational Order** this turn.

A ***Senior Officer*** may also issue **Tactical Orders** to units in his own Platoon (if applicable), following the ***Junior Officer*** rules.  This expends his **Operational Order** usage for the turn.

### ***Commanding Officer***

A ***Commanding Officer*** may issue **one Strategic Order** per Battle Round.  The target must be a friendly ***Senior Officer*** model from Codex: Imperial Guard within 48” of the ***Commanding Officer***.  The Order is transmitted using the **RELAY MECHANIC**.

A ***Commanding Officer*** may issue **Operational Orders** and **Tactical Orders** to valid targets (ignoring detachment restrictions) using the ***Junior Officer*** and ***Senior Officer*** rules.  This expends his **Strategic Order** usage for the turn.

## **Procedure for Issuing Infantry Orders**

### **Tactical Orders: Procedure**

Use the following procedure when a ***Junior Officer*** issues a **Tactical Order**:

1. **DECLARE:** The ***Junior Officer*** declares which **Tactical Order** he is issuing and nominates one eligible target unit.  
2. **TEST:** The target unit takes a **Leadership Test**, using the highest Leadership value available to it (including Shared Leadership from **PLATOON COHERENCY**, if applicable).  
3. **RESOLVE:**   
   1. **If the test is passed:** The Order takes effect immediately.  Apply the Order’s rules as described in its entry.  
   2. **If the test is failed:** The Order has no effect. The Officer has expended his Order for the turn.  
4. **Check for Incompetent Command or Inspired Tactics.**

### **Operational Orders: Procedure**

Use the following procedure when a ***Senior Officer*** issues an **Operational Order**:

1. **DECLARE:** The ***Senior Officer*** declares which **Operational Order** he is issuing and nominates one eligible ***Junior Officer*** as the relay target.  
2. **ISSUING OFFICER’S TEST:** The ***Senior Officer’s*** unit takes a **Leadership Test**, using the ***Senior Officer’s*** Leadership value.  
   1. **If the test is passed:** Proceed to Step 3\.  Check for **Inspired Tactics** at the ***Senior Officer*** tier (tier 2).  
   2. **If the test is failed:** The Order is not transmitted. The ***Senior Officer*** has expended his Order for the turn.  Check for **Incompetent Command** at the ***Senior Officer*** tier (tier 2).  
3. **RELAY OFFICER’S TEST:** The target ***Junior Officer’s*** unit takes a **Leadership Test**, using the ***Junior Officer’s*** Leadership value.  
   1. **If the test is passed:** The Order takes effect on all units in the ***Junior Officer’s*** Platoon that are currently in **PLATOON COHERENCY**.  Check for **Inspired Tactics** at the ***Junior Officer*** tier (tier 1).  
   2. **If the test is failed:** The Order is lost.  The ***Junior Officer*** has **not** expended one of his own Orders.  Check for **Incompetent Command** at the ***Junior Officer*** tier (tier 1).

### **Strategic Orders: Procedure**

Use the following procedure when a ***Commanding Officer*** issues a **Strategic Order**:

1. **DECLARE:** The ***Commander Officer*** declares which **Operational Order** he is issuing and nominates one eligible ***Senior Officer*** as the relay target.  
2. **ISSUING OFFICER’S TEST:** The ***Commanding Officer’s*** unit takes a **Leadership Test**, using the ***Commanding Officer’s*** Leadership value.  
   1. **If the test is passed:** Proceed to Step 3\.  Check for **Inspired Tactics** at the ***Commanding Officer*** tier (tier 3).  
   2. **If the test is failed:** The Order is not transmitted. The ***Commanding Officer*** has expended his Order for the turn.  Check for **Incompetent Command** at the ***Commanding Officer*** tier (tier 3).  
3. **RELAY OFFICER’S TEST:** The target ***Senior Officer’s*** unit takes a **Leadership Test**, using the ***Senior Officer’s*** Leadership value.  
   1. **If the test is passed:** The Order takes effect on all units in the ***Senior Officer’s*** Detachment that are currently in **PLATOON COHERENCY**.  Check for **Inspired Tactics** at the ***Senior Officer*** tier (tier 2).  
   2. **If the test is failed:** The Order is lost.  The ***Senior Officer***  has **not** expended one of his own Orders.  Check for **Incompetent Command** at the ***Senior Officer*** tier (tier 2).

## **Incompetent Command & Inspired Tactics**

After any Leadership test made as part of issuing or relaying an Order, check the dice result:

* **Incompetent Command (Double 6s):** The Order does not take effect regardless of if the Leadership test would otherwise have passed.  Additionally, no further Orders may be issued by an Officer at the **same command tier as the Officer whose unit rolled the double 6s** for the remainder of the turn.  
* **Inspired Tactics (Double 1s):** The Order takes effect (the test is automatically passed).  Additionally, all further Orders issued by Officers at the **same command tier as the officer who rolled the double 1s** are automatically successful for the remainder of the turn; no Leadership tests are required.

**Incompetent Command** and **Inspired Tactics** triggered during a relay test (the receiving Officer’s roll) have a narrower scope than those triggered during the issuing test:

* They affect subsequent **relay tests made by that specific officer** for the remainder of the turn.  
* They do **not** cascade upward to the issuing Officer’s tier.  
* They do **not** cascade downward to affect **Tactical Orders** issued by that officer independently.

## **Vox Casters & Orders**

If **both** the issuing Officer’s unit and the target unit contain a model equipped with a Vox-caster, a failed Leadership test made as part of issuing or relaying an Order may be re-rolled.  The rerolled result must be kept even if it is worse.

* Vox-caster rerolls occur before checking for **Incompetent Command** or **Inspired Tactics**.  If the reroll produces double 6s or double 1s, those results apply.

## **Tactical Orders**

**Tactical Orders** are issued by a ***Junior Officer*** to a single unit in his Platoon that is in **PLATOON COHERENCY** and within 12”.  **Tactical Orders** compel the ordered unit to act; the unit must perform the action described.

### **Movement Phase**

Movement Phase orders may only be issued at the beginning of your own Movement Phase before any units before any units have moved.

| Order | Effect |
| :---: | ----- |
| **“Move\! Move\! Move\!”** | The ordered unit may not make a normal move or advance move this turn.  Instead, the ordered unit immediately moves up to 3D6”.  Normal movement rules apply (difficult terrain, dangerous terrain, etc.).  The unit counts as having moved and advanced and may not shoot or declare a charge this turn. |
| **“Into Position\!”** | The ordered unit makes a normal move.  After completing this move, the unit counts as having remained stationary for the purpose of shooting. |
| **“Get Your Heads Down\!”** | The ordered unit immediately becomes **PINNED**.  While **PINNED** as a result of this Order, the unit gains \+2 to its cover save (instead of the normal \+1 usually granted by being **PINNED**).  If the unit is in the open, it gains a \+5 cover save instead of the usual \+6. |

### **Shooting Phase**

Shooting Phase orders may only be issued at the beginning of your own Shooting Phase before any units have fired.

| Order | Effect |
| ----- | ----- |
| **“First Rank, Fire\! Second Rank, Fire\!”** | The ordered unit must make a shooting attack this turn.  All models in the unit firing **Lasguns** or **Hot-Shot Lasguns** fire one additional shot (e.g. a Lasgun at half range fires 3 shots instead of 2; at full range, 2 shots instead of 1). |
| **“Take Aim\!”** | The ordered unit must make a shooting attack this turn.  All models in the unit gain \+1 BS for this attack, to a maximum of BS5. |
| **“Suppressive Fire\!”** | The ordered unit must make a shooting attack this turn.  All non-Melee weapons in the unit gain the ***Pinning*** special rule for this attack. |
| **“Pick Your Targets\!”** | The ordered unit must make a shooting attack this turn.  The unit automatically passes its **Split Fire** test this turn and may split fire between up to three targets instead of the normal two. |
| **“Fix Bayonets\!”** | The ordered unit **may not** make a shooting test this turn.  Each model in the unit gains \+1 Initiative, and ***Counter-Attack*** until the beginning of your next Player Turn. |

### **Assault Phase**

Assault Phase Orders may only be issued at any time during the Assault Phase of either player’s turn, and may be issued to units locked in combat.

| Order | Effect |
| ----- | ----- |
| **“Hold the Line\!”** | The ordered unit gains ***Stubborn*** until the end of the current Assault Phase |
| **“Forward\! For the Emperor\!”** | The ordered unit must declare a charge this turn if a valid target exists within range.  The unit gains \+1” to its charge distance and ***Furious Charge*** until the end of the current Assault Phase.  If no valid charge target exists, the Order has no effect but is still wasted. |

### **Any Phase**

Any Phase Orders may be issued at any time noted in the Order’s effect, in any phase, on either player’s turn and may be issued to units locked in combat.

| Order | Effect |
| ----- | ----- |
| **“Get Back in the Fight\!”** | This Order may only be issued to a unit that is **BROKEN** or **PINNED**.  This is an exception to the normal restriction preventing Orders from targeting **BROKEN** or **PINNED** units. If the target unit is **BROKEN**, it immediately regroups.  The unit counts as having moved this turn. If the target unit is **PINNED**, it immediately becomes unpinned.  The unit counts as having moved this turn. |
| **“Stand Fast\!”** | This Order may only be issued immediately before the target unit is required to take a **MORALE TEST** (Break Test, Casualty Test, or Pinning Test).  The unit may reroll the failed test.  The result of the reroll stands even if it is worse than the original roll. |

## **Operational Orders**

**Operational Orders** are issued by a ***Senior Officer*** within 24” and relayed via the **RELAY MECHANIC**.  When an **Operational Order** takes effect, it applies to all units in the target ***Junior Officer’s*** Platoon that are currently in **PLATOON COHERENCY**.  **Operational Orders** provide buffs, they do not compel the affected units to perform specific actions.

### **Movement Phase**

Movement Phase orders may only be issued at the beginning of your own Movement Phase before any units before any units have moved.

| Order | Effect |
| ----- | ----- |
| **“Dig In”** | All affected units that remain stationary this turn gain \+1 to their cover saves until the start of the controlling player’s next turn.  Units in the open gain a 6+ cover save instead.  This bonus does not stack with the cover save bonus granted by being **PINNED**. |
| **“Advance by Bounds”** | All affected units may advance using 2D6” (use the highest die) instead of D6”.  Units that advance under this Order may fire Assault weapons at normal BS (instead of Snap Fire) and may fire Rapid Fire weapons with snap fire (instead of not being permitted to fire at all).  All other consequences of advancing still apply. |

### **Shooting Phase**

Shooting Phase orders may only be issued at the beginning of your own Shooting Phase before any units have fired.

| Order | Effect |
| ----- | ----- |
| **“All Units, Engage at Will”** | When issuing this order, the ***Senior Officer*** nominates one enemy unit he has line of sight to.  All affected units gain ***Preferred Enemy*** against the nominated enemy unit until the end of the turn. |
| **“Concentrated Barrage”** | All affected units that shoot at the **same target unit** gain \+1 BS for that attack.  Models that shoot at a different target do not receive the bonus.  The ***Senior Officer*** does not nominate the target; the bonus applies based on the affected units target declarations. |

### **Any Phase**

Any Phase Orders may be issued at any time noted in the Order’s effect, in any phase, on either player’s turn and may be issued to units locked in combat.

| Order | Effect |
| ----- | ----- |
| **“Hold at All Costs\!”** | All affected units with at least 1 model within 3” of an objective marker gain ***Fearless***. |
| **“Regroup and Reform\!”** | This Order may only target a Platoon that contains one or more **BROKEN** units.  This is an exception to the normal restriction preventing Orders from being relayed to **BROKEN** targets. All **BROKEN** units in the Platoon that are still in **PLATOON COHERENCY** may immediately attempt to regroup.  Each unit takes a Regroup test.  Units that pass regroup as normal.  Units that fail remain **BROKEN**. |
| **“Reassign Squad”** | This Order may only target a single **orphaned** unit in the ***Senior Officer’s*** own Detachment.  The ***Senior Officer*** nominates one Platoon Commander in his Detachment.  The **orphaned** unit is permanently reassigned to the nominated Platoon Commander’s Platoon for the remainder of the game.  The reassigned squad is subject to all **PLATOON COHERENCY** rules; it may establish the 3” chain to the new Platoon Command Squad, benefit from Shared Leadership and Pooled Casualty Threshold, and receive Tactical Orders from its new Platoon Commander.  This Order does not require a **RELAY MECHANIC**, no Leadership test is made by the receiving ***Junior Officer***. |

## **Strategic Orders**

**Strategic Orders** are issued by a ***Commanding Officer*** to a ***Senior Officer*** within 48” and relayed via the **RELAY MECHANIC**.  **Strategic Orders** provide broad, lasting effects across the target Company’s detachment.

### **Start of Turn**

Start of Turn orders must be issued during the Start of Turn Phase, before the Movement Phase has begun.

| Order | Effect |
| ----- | ----- |
| **Directive: Reserves Forward** | Reserve rolls for units in the target ***Senior Officer’s*** detachment succeed on a 3+ (instead of the normal value).  Units arriving from reserve may reroll scatter dice when Deep Striking. |
| **Directive: Reassign Platoon** | This Order may only target an **orphaned** Platoon (a Platoon whose detachment no longer contains a ***Senior Officer***).  The ***Commanding Officer*** nominates one surviving ***Senior Officer*** in the army.  The orphaned Platoon is permanently reassigned to the nominated ***Senior Officer’s*** detachment for the remainder of the game.  The ***Senior Officer*** may interact with the reassigned Platoon’s ***Junior Officer*** and units following all normal ***Senior Officer*** rules, including issuing direct **Tactical Orders** to orphaned units within the Platoon.  This Order is relayed via the **RELAY MECHANIC**.  The nominated ***Senior Officer*** must pass a Leadership test to accept the reassignment.  If the test fails, the Platoon is not reassigned. |
| **Directive: Tighten the Net** | Until the end of the controlling player’s turn, all Leadership tests made for the purpose of issuing or relaying Orders with the target ***Senior Officer’s*** Detachment are made with a \+1 modifier.  Additionally, Officers in the target Detachment may relay Orders as though their units were equipped with Vox-casters, regardless of whether they actually are.  Existing Vox-casters still function normally; this Order does not grant rerolls to units that do not have them, but removes the requirement that both ends of the relay possess one. |

### **Movement Phase**

Movement Phase orders may only be issued at the beginning of your own Movement Phase before any units before any units have moved.

| Order | Effect |
| ----- | ----- |
| **Directive: Forward Deployment** |  |
|  |  |

### **End of Turn**

Start of Turn orders must be issued during theEnd of Turn Phase, after all other phases have concluded

# **IMPERIAL GUARD WARGEAR**

## **Wargear Costs**

## **Wargear Profiles**

### **Ranged Weapons**

**Auto-Weapons and Cannons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Autopistol | 12” | 3 | \- | Pistol |
| Autogun | 24” | 3 | \- | Rapid Fire |
| Battle Cannon | 72” | 8 | 3 | Ordinance 1, Large Blast |
| Taurox Battle Cannon | 48” | 7 | 4 | Heavy 1, Blast |
| Vanquisher Battle Cannon | 72” | 8 | 3 | Heavy 1, Armourbane |
| Earthshaker Cannon | 36”-240” | 9 | 3 | Ordinance 1, Barrage, Large Blast |
| Baneblade Cannon | 72” | 9 | 2 | Primary Weapon 1, Apocalyptic Blast |
| Hellhammer Cannon | 36” | 10 | 1 | Primary Weapon 1, Ignores Cover, Massive Blast |
| Magma Cannon | 60” | 10 | 1 | Primary Weapon 1, Large Blast |
| Quake Cannon | 24”-180” | 9 | 3 | Primary Weapon 1, Apocalyptic Blast |
| Eradicator Nova Cannon | 26” | 6 | 4 | Heavy 1, Large Blast, Ignores Cover |
| Stormsword Siege Cannon | 36” | 10 | 1 | Primary Weapon 1, Apocalyptic Blast, Ignores Cover |
| Tremor Cannon | 60” | 8 | 3 | Primary Weapon 1, Massive Blast, **Earthshock** |
| Taurox Gatling Cannon | 24” | 4 | \- | Heavy 10 |
| Punisher Gatling Cannon | 24” | 5 | \- | Heavy 20 |
| Assault Cannon | 24” | 6 | 4 | Heavy 4, Rending |
| Autocannon | 48” | 7 | 4 | Heavy 2 |
| Hydra Autocannon | 72” | 7 | 4 | Heavy 2, Skyfire |
| Exterminator Autocannon | 48” | 7 | 4 | Heavy 4, Twin-linked |
| Demolisher (Siege) Cannon | 24” | 10 | 2 | Ordinance 1, Large Blast |
| Quad-gun | 48” | 7 | 4 | Heavy 4, Interceptor, Skyfire, Twin-linked |
| Stormshard Mortar | 48” | 4 | 6 | Heavy 2, Barrage, Blast, Ignores Cover, Shred |

**Earthshock:** All models under this weapon’s blast marker that were not removed from play as a result of that shooting attack must make a Dangerous Terrain test once the hit has been resolved.

**Boltguns:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Bolt Pistol | 12” | 4 | 5 | Pistol |
| Boltgun | 24” | 4 | 5 | Rapid Fire |
| Storm Bolter | 24” | 4 | 5 | Assault 2 |
| Heavy Bolter | 36” | 5 | 4 | Heavy 3 |
| Vulcan Mega-Bolter | 60” | 6 | 3 | Heavy 15 |

**Las Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Laspistol | 12” | 3 | \- | Pistol |
| Hot-Shot Laspistol | 6” | 3 | 3 | Pistol |
| Lasgun | 24” | 3 | \- | Rapid Fire |
| Hot-Shot Lasgun | 18” | 3 | 3 | Rapid Fire |
| Hot-Shot Volley Gun | 24” | 4 | s | Salvo 2/4 |
| Multi-laser | 36” | 6 | 6 | Heavy 3 |
| Lascannon | 48” | 9 | 2 | Heavy 1 |

**Melta Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Inferno Pistol | 6” | 8 | 1 | Pistol, Melta |
| Meltagun | 12” | 8 | 1 | Assault, Melta |
| Multi-Melta | 24” | 8 | 1 | Heavy 1, Melta |
| Melta Cannon | 24” | 8 | 1 | Heavy 1, Blast, Melta |
| Volcano Cannon | 120” | 10 | 2 | Primary Weapon 1, Terrible Weapon Large Blast |

**Plasma Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Plasma Pistol | 12” | 7 | 2 | Pistol, Gets Hot |
| Plasma Gun | 24” | 7 | 2 | Rapid Fire, Gets Hot |
| Plasma Cannon | 36” | 7 | 2 | Heavy 1, Blast, Gets Hot |
| Executioner Plasma Cannon | 36” | 7 | 2 | Heavy 3, Blast, Gets Hot |

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
| Frag Missile | 48” | 4 | 6 | Heavy 1, Blast |
| Flakk Missile | 48” | 7 | 4 | Heavy 1, Skyfire |
| Krak Missile | 48” | 8 | 3 | Heavy 1 |

**Stub Guns and Shotguns:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Shotgun | 12” | 3 | \- | Assault 2 |
| Heavy Stubber | 36” | 4 | 6 | Heavy 3 |
| Ripper Gun | 12” | 5 | \- | Assault 3 |

**Sniper Rifle**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Sniper Rifle | 36” | X | 6 | Heavy 1, Sniper |

**Chem Cannon:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Chem Cannon | Template | 1 | 3 | Heavy 1, Poisoned (2+) |

**Deathstrike Missile:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Deathstrike Missile | 12”-∞ | 10 | 1 | Ordinance 1, Apocalyptic Blast, Barrage, Ignores Cover, One Use Only |

**Demolition Charge:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Demolition Charge | 6” | 8 | 2 | Assault 1, Large Blast, One Use Only |

**Grenade Launcher:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Frag Grenade | 24” | 3 | 6 | Assault 1, Blast |
| Krak Grenade | 24” | 6 | 4 | Assault 1 |

**Grenadier Gauntlet**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Grenadier Gauntlet | 12” | 4 | 6 | Assault 1, Blast |

**Hell Missiles:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Hellfury Missiles | 72” | 4 | 5 | Heavy 1, Large Blast, Ignores Cover, One Use Only |
| Hellstrike Missiles | 72” | 8 | 3 | Ordinance 1, One Use Only |

**Mortar:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Mortar | 48” | 4 | 6 | Heavy 1, Barrage, Blast |

**Multiple Rocket Pod:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Multiple Rocket Pod | 48” | 4 | 6 | Heavy 1, Large Blast |

**Storm Eagle Rockets:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Storm Eagle Rockets | 24”-120” | 10 | 4 | Ordinance D3, Barrage, Large Blast |

**Taurox Missile Launcher:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Frag Missile | 48” | 4 | 6 | Heavy 2, Blast |
| Krak Missile | 48” | 8 | 3 | Heavy 2 |

### **Melee Weapons**

**Force Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Force Stave | Melee | \+2 | 4 | Force, Concussive |
| Force Sword | Melee | User | 3 | Force |
| Force Axe | Melee | \+1 | 2 | Force, Unwieldy |

 

**Power Weapons:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Power Sword | Melee | User | 3 | \- |
| Power Axe | Melee | \+1 | 2 | Unwieldy |
| Power Maul | Melee | \+2 | 4 | Concussive |
| Power Lance | Melee | \+1/User\* | 3/4\* | \- |
| Power Klaw | Melee | x2 | 2 | Specialist Weapon, Unwieldy |
| Power Fist | Melee | 2x | 2 | Specialist Weapon, Unwieldy |

\* The first values are used only when charging

**Hunting Lances:** Counts as a Close Combat Weapon, except during the first time an equipped model charges into close combat, for the duration of that phase, that model adds \+2 to it’s Initiative, and the Hunting Lance uses the following profile:

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Hunting Lance | Melee | \+2 | 3 | Specialist Weapon, One Use Only |

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
**Medi-Pack:** A unit that contains at least one model with a medi-pack has the Feel No Pain special rule.  
**Platoon Standard:** A unit that contains a model with a platoon standard counts as scoring an additional wound for the purposes of calculating assault results.  
**Refractor Field:** 5+ Invul save.  
**Regimental Standard:** Counts as a platoon standard. Additionally, any friendly units from Codex: Imperial Guard within 12” of a model with a regimental standard reroll failed morale, fear and pinning tests.  
**Rosarius:** 4+ Invul save.  
**Slabshield:** If a model with a slabshield is in base contact with one or more models with a slabshield from the same unit, it adds \+1 to its armor save. Furthermore, if a target (friend or foe) is partially obscured from the firer’s view by at least one model with a slabshield, that target receives \+1 to its cover save.  
**Snare Mines:** Enemy units that charge a unit with snare mines count as having made a disordered charge.  
**Vox-caster:** Failed Leadership tests for orders issued to a unit with a vox-caster can be re-rolled, provided the officer’s unit also has a vox-caster. An officer may not use a vox-casters ability on his own unit.

### **Heirlooms of Conquest**

**Bale Eye:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Bale Eye | 6” | 3 | 3 | Pistol |

**Kurov’s Aquila:** The officer, and all friendly units from Codex: Imperial Guard within 6”, have the Preferred Enemy special rule. In addition, the bearer may reroll a single failed Leadership test per turn.

**Payback:** 

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Payback | 36” | 5 | 4 | Heavy 3, Rending |

**Power Field:** 4+ Invul save.

**The Blade of Conquest:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| The Blade of Conquest | Melee | \+1 | 3 | Master-crafted |

**The Deathmask of Ollanius:** 4+ Invul save, bearer gains It Will Not Die and Fear special rules.

**The Emperor’s Benediction:** 

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| The Emperor’s Benediction | 12” | 5 | 4 | Pistol, Precision Shot, Master-crafted |

**The Laurels of Command:** Whenever a friendly unit from Codex: Imperial Guard within 6” of the bearer is required to make a Morale check, the bearer of the Laurels may choose whether they pass or fail. However, if the model with the Laurels is removed as a casualty, all friendly units from Codex: Imperial Guard within 6” must make an immediate pinning test.

**The Tactical Auto-Reliquary of Tyberius:**  When rolling Leadership tests for orders issued by an officer with the Tactical Auto-Reliquary, any successful Leadership test that results in a double will count as Inspired Tactics. However, if you roll a double 1 while using the Tactical Auto-Reliquary, you still benefit from Inspired Tactics, though the officer has “accidentally” shut the device out of the vox network – it may no longer be used in this game.

**Envenomed Blade:** 

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Envenomed Blade | Melee | User | \- | Poisoned(2+) |

**Ripper Pistol:**

| Name | Range | Strength | AP | Type |
| :---: | :---: | :---: | :---: | :---: |
| Ripper Pistol | 12” | X | 3 | Pistol, Sniper |

 

### **Vehicle Equipment**

**Augur Array:** If you attempt to bring a unit on the reserve using Deep Strike, and the location chosen for its deployment is within 6” of a vehicle with an augur array, that unit does not scatter. The augur array must have been on the battlefield at the start of the turn for it to be used.

**Camo Netting:** A vehicle with camo netting counts its cover save as being 1 point better than normal. This means that it always has a cover save of 6+, even if it is in the open.

**Enclosed Crew Compartment:** Vehicles with the enclosed crew compartment upgrade no longer have the “Open-topped” portion of their unit type.

**Fire Barrels:** The first time an enemy unit attempts to charge a vehicle with fire barrels, that unit suffers D6 S4 AP5 hits. These hits are randomly allocated.

**Recovery Gear:** If a vehicle with recovery gear is immobilized, then in subsequent turns it may attempt to repair itself. To make the attempt, roll a D6 at the end of the Movement phase; on a roll of 6, the vehicle is no longer immobilized. Note that this does not restore a structure point.

**Relic Plating:** The equipped vehicle gains the Adamantium Will special rule.

# **UNIT PROFILES**

#### Color Sergeant Kell

|  | WS | BS | S | T | W | I | A | Ld | Save | Inv | Type |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Color Sergeant Kell | 4 | 4 | 3 | 3 | 2 | 4 | 2 | 8 | 4+ | \- | Infantry (Character) |

If a **Company Command Squad** includes **Lord Castellan Creed,** then it may replace one **Veteran** with **Color Sergeant Kell**  
---

Color Sergeant Kell has the following rules:  
***Listen Up, Maggots\!:*** If Kell is in the same unit as Creed, Leadership tests for orders issued by Creed can be taken on Kell’s leadership, not that of the ordered unit.  
***Look Out – Arghh\!:***  
***Sworn Protector***

---

Color Sergeant Kell is equipped with the following Wargear:

Carapace Armor  
Laspistol  
Power Fist  
Power Sword  
Frag Grenades  
Regimental Standard\*  
\*(No Veteran may carry a Regimental Standard in a Company Command Squad that includes Kell)

Options:

* Placeholder

# **FORCE ORGANIZATION**

### **Placeholder**

Placeholder

# **Profile SUMMARY**

## **Unit Statlines**


