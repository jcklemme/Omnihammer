# DAEMONIC INCURSION — FACTION RULES & WARLORD TRAITS PROPOSAL (v0.1)

*Design proposal for Codex: Chaos — Daemonic Incursion detachment.*

---

## DESIGN BRIEF

**Problem:** A Daemonic Incursion army has low unit count (3 units at 850 points), almost no shooting, and spends Turns 1-2 walking forward with nothing meaningful to do. The detachment currently grants a single benefit ("may deploy normally instead of using Daemonic Summoning") with no mechanical identity beyond the individual unit rules.

**Goal:** Give the Daemonic Incursion detachment a faction mechanic that:
1. Creates decision density every turn (the daemon player always has something to think about)
2. Provides resilience against being shot off the table before engaging
3. Escalates over time (the opponent is on a clock)
4. Rewards positioning, not just "move forward and charge"
5. Feels lore-accurate — daemons warp reality, persist through death, and grow stronger as the veil thins

**Comparison to other factions:**
- Orks: WAAAGH! Energy (earn-and-spend economy) + Warboss Ambitions (secret objective) + Klan Kultur (static faction bonus)
- Guard: Command Hierarchy (officer chain with cascading consequences) + Orders (activation-based buffs)
- Marines: Chapter Tactics (static faction bonus) + Combat Squads (deployment flexibility)

**What this proposal contains:** Three interlocking sub-mechanics that form a single system called **The Warp Bleeds Through**, plus Warlord Traits for Khorne and Chaos Undivided.

---

# THE WARP BLEEDS THROUGH

*The presence of daemons in realspace is an open wound in the fabric of reality. The longer they persist — and the more violence erupts around them — the thinner the veil becomes. Reality buckles. The air screams. And from the widening rift, more horrors pour through.*

**Restriction:** The following rules apply only to units in a **Daemonic Incursion** detachment. Daemons taken as allies in a Chaos Space Marines or other detachment do not benefit from these rules (they are bound by Daemonic Summoning instead, representing a more controlled and limited manifestation).

---

## 1. THE WARP TIDE

The daemon player tracks their current **Warp Tide** level on a counter or die visible to both players. The Warp Tide represents how thoroughly the barrier between realspace and the Immaterium has been compromised.

**Starting Level:** 0

**Generation:**

| Trigger | Warp Tide Gained |
| :---- | :---: |
| Start of each daemon player turn | +1 |
| A friendly daemon unit completely destroys an enemy unit in the Assault Phase | +1 |
| A friendly daemon unit is completely destroyed (reduced to 0 models) | +1 |
| The daemon Warlord slays an enemy **CHARACTER** in close combat | +2 |

**Rules:**
- Warp Tide may not exceed 12.
- Warp Tide never decreases.
- Warp Tide is generated immediately when the triggering event occurs.

### Designer Notes — Warp Tide

**Why it never decreases:** Unlike WAAAGH! Energy, which is earned and spent (creating an economy), the Warp Tide is a one-way escalation. Once reality starts cracking, it doesn't heal. This is the fundamental design distinction between the two systems: Orks manage a resource; daemons ride an inevitable wave. The opponent is on a clock, not competing in a resource game.

**Why destroyed daemon units generate Warp Tide:** This is the single most important design decision in the system. Daemons are creatures of emotion and psychic energy — their violent destruction sends shockwaves through the warp, thinning the veil further and drawing more daemonic attention. Mechanically, this means the opponent cannot simply shoot the daemon army off the table without consequences. Every unit they destroy makes the survivors stronger. This creates a genuine dilemma: focus fire to remove threats quickly (but accelerate the Tide), or spread damage to slow the Tide (but leave dangerous units operational).

**Projected Warp Tide curve at 850 points (Bloodthirster + 2×8 Bloodletters vs. a standard army):**

| Turn | Passive | Estimated Kill/Death Triggers | Cumulative Warp Tide |
| :---: | :---: | :---: | :---: |
| 1 | +1 | 0 (advancing, no contact) | 1 |
| 2 | +1 | 0-1 (Bloodthirster may charge) | 2-3 |
| 3 | +1 | 1-2 (main engagement begins) | 4-6 |
| 4 | +1 | 1-2 (sustained combat) | 6-9 |
| 5 | +1 | 0-1 (mopping up) | 7-11 |

The army typically hits Warp Tide 3 (Rift Zones activate Dangerous Terrain) by Turn 3, Warp Tide 6 (Resurgence improves, Rift Zones suppress reactions) by Turn 4, and may reach 9+ (maximum Rift Zone intensity) in a long, bloody game. This pacing means the mechanic is quiet in Turns 1-2 (the daemon player is advancing), becomes noticeable in Turn 3, and dominant in Turns 4-5. The opponent has roughly 2-3 turns to deal serious damage before the Tide overwhelms them.

---

## 2. WARP RIFT ZONES

*Reality buckles and distorts in the presence of daemonic entities. Mortals who stray too close feel their courage waver, the ground crack beneath their feet, and the air itself reject their presence.*

Each unit composed entirely of models with the ***Daemon*** USR in a **Daemonic Incursion** detachment generates a **Warp Rift Zone** — an aura extending outward from the unit. The size and intensity of this zone scales with the current Warp Tide level:

| Warp Tide | Zone Radius | Effects on Enemy Units Within the Zone |
| :---: | :---: | :---- |
| 0–2 | 3" | **Whispers of the Warp:** Enemy units suffer **-1 Leadership**. |
| 3–5 | 6" | **The Veil Thins:** -1 Leadership. The zone counts as **Dangerous Terrain** for enemy models. |
| 6–8 | 6" | **Reality Fractures:** -2 Leadership. Dangerous Terrain. Enemy units must pass a **Leadership test** to use ***Stand & Shoot!*** or ***Return Fire!*** reactions. If failed, the reaction is lost (the unit does not fire). |
| 9+ | 9" | **The Warp Made Manifest:** -2 Leadership. Dangerous Terrain. Leadership test for reactions. Enemy units that **start their turn** wholly within the zone suffer D6 S4 AP- hits. |

**Rules:**
- Leadership penalties from multiple overlapping Warp Rift Zones **do not stack**. Use the single worst modifier.
- Dangerous Terrain from Warp Rift Zones is tested when enemy models move through or end their movement within the zone.
- Models with the ***Daemon*** USR are never affected by Warp Rift Zones.
- The Leadership test for reactions uses the unit's modified Leadership (after the zone's Ld penalty). The test is taken before any firing is resolved. If passed, the reaction proceeds normally. If failed, the reaction is lost and the unit does not fire.
- The D6 S4 AP- hits at Warp Tide 9+ are resolved at the start of the enemy player's turn, before any movement.

### Designer Notes — Warp Rift Zones

**Why Leadership is the primary lever:** Every daemon in the game already causes ***Fear***, which requires an Ld test. The Rift Zone Ld penalty makes Fear tests meaningfully harder. An Ld 8 Space Marine at -1 tests Fear at Ld 7 (passes ~58%). At -2, they test at Ld 6 (passes ~42%). An Ld 7 unit at -2 tests at Ld 5 (passes ~28%). This turns ***Fear*** from a forgettable rule into a genuine threat in the mid-to-late game, without adding any new mechanics — it just makes an existing daemon rule actually matter.

**The Ld penalty also interacts with:**
- **Break Tests** (enemy units failing morale near daemons)
- **Pinning Tests** (if any daemon weapons cause Pinning)
- **Fear tests** (as above)
- **The reaction Ld test** at Warp Tide 6+ (see below)
- **Tank Shock morale tests** (if daemon engines are in the army)

This single modifier ripples through multiple existing systems, creating emergent interactions without new rules overhead.

**Why reactions require a Leadership test instead of being flat suppressed:** The reaction system (Return Fire!, Stand & Shoot!, Overwatch) is a **locked design pillar** of OmniHammer. Flat suppression would undermine a core design principle. The Leadership test instead creates a probability gate that interacts with the Ld penalty already imposed by the zone. At Warp Tide 6-8 with -2 Ld:

| Unit Base Ld | Modified Ld | Chance to React |
| :---: | :---: | :---: |
| 10 (Daemons, Marines) | 8 | 72% |
| 8 (Standard Marines) | 6 | 42% |
| 7 (Guard Veterans) | 5 | 28% |
| 6 (Basic Guard) | 4 | 17% |

Elite armies still mostly react. Horde armies are badly disrupted. This is the correct scaling — daemons should terrify mortal soldiers more than transhuman supersoldiers. The precedent for reaction suppression already exists in the Chaos codex (Mark of Slaanesh on vehicles grants flat suppression within 12"), so this is actually more conservative than existing Chaos rules.

**Why Dangerous Terrain instead of Difficult Terrain:** Difficult Terrain slows movement but is survivable. Dangerous Terrain forces a save-or-die roll (typically a 1 on a D6 causes a wound). For daemons, who need the enemy to come to THEM for melee, Dangerous Terrain creates a meaningful deterrent without making it impossible to approach. It also punishes enemy charges through the zone — a unit charging through Dangerous Terrain takes the test, potentially losing models before the fight starts.

**Why the zone radius starts small (3") and grows:** At Warp Tide 0-2 (Turns 1-2), the zone is essentially just base contact range. The daemon player has to be very close to an enemy for the Ld penalty to matter. By Warp Tide 3-5, the 6" radius means the zone extends to a meaningful distance — roughly the width of a charge range. At Warp Tide 9+, the 9" zone is enormous, covering a significant area of the battlefield. This progression mirrors the lore: a small rift grows into a gaping wound.

**Positioning game:** The daemon player now cares about WHERE their units are, not just whether they're moving forward. Placing Bloodletters to create overlapping Rift Zones that cover a chokepoint, or positioning the Bloodthirster to project a Rift Zone over an objective, creates real tactical decisions beyond "charge the nearest enemy."

**Open Question — D6 S4 AP- at Warp Tide 9+:** Is this too punishing? At S4, it wounds T4 on 4+ and T3 on 3+. Against a 10-model Guard squad wholly within the zone, that's ~1.7 casualties per turn from the environment alone. Against Marines in power armor (3+ save), it's ~0.56 casualties. It's meant to represent reality itself rejecting mortal presence — the air is toxic, the ground is corrosive, physics stops working. If it feels too strong in testing, it could be dropped to S3 or made D3 hits instead of D6.

---

## 3. DAEMONIC RESURGENCE

*Daemons are not truly slain — they are merely banished back to the Immaterium, where they coalesce, reform, and claw their way back through the wound in reality. The wider the rift, the faster they return.*

### Resurgence (Ongoing Units)

At the start of each daemon player's **Movement Phase**, before any units move, perform a **Resurgence Check** for each friendly daemon unit on the battlefield that has lost models but is not destroyed:

Roll a D6 for each slain model from that unit. If the roll meets the threshold below, that model is returned to the unit:

| Warp Tide | Model Returns On |
| :---: | :---: |
| 0–2 | No Resurgence |
| 3–5 | 6+ |
| 6–8 | 5+ |
| 9+ | 4+ |

**Rules:**
- Returned models are placed in unit coherency with surviving models, as close to the unit as possible.
- Returned models count as having moved this turn (they may not shoot heavy weapons at full BS, etc.).
- Returned models may act normally in subsequent phases (they may charge, fight in melee, etc.).
- A model may only be returned via Resurgence once per turn (no stacking with other return effects in the same phase).
- Resurgence is rolled before any other start-of-turn effects.

### Daemonic Reformation (Destroyed Units)

**Warp Tide 7+ required. Once per game.**

If a friendly daemon unit has been completely destroyed, the daemon player may declare a **Daemonic Reformation** at the start of their Movement Phase. The destroyed unit is placed in **Ongoing Reserves** at its **minimum starting unit size** (e.g., 8 Bloodletters with no upgrades). It arrives next turn via **Deep Strike**, using the standard ***Daemonic Summoning*** placement rules (within 6" of a friendly model with a Personal Icon, no scatter). If no friendly model with a Personal Icon is on the battlefield when it arrives, the unit is destroyed per the normal Daemonic Summoning consequence.

**Rules:**
- Daemonic Reformation may only be used once per game, regardless of how many units have been destroyed.
- The reformed unit returns at minimum unit size with default wargear only (no upgrades, no Bloodreaper, no Instrument/Icon).
- The reformed unit counts toward the army's unit count for victory conditions.
- The reformed unit benefits from all Daemonic Incursion rules (Warp Rift Zones, Resurgence) upon arrival.

### Designer Notes — Daemonic Resurgence

**Why Resurgence starts at Warp Tide 3 (not immediately):** If models returned from Turn 1, the daemon army would be too resilient too early. Delaying to Warp Tide 3 (typically Turn 3) means the daemon army takes real casualties in the early game — they're not invincible, and shooting them matters. Resurgence kicks in when the army is already damaged and engaged, representing the widening rift allowing faster reformation.

**Expected Resurgence output (unit of 8 Bloodletters, 4 models lost):**

| Warp Tide | Roll Needed | Expected Models Returned | Chance of ≥1 Return |
| :---: | :---: | :---: | :---: |
| 3–5 | 6+ | 0.67 | 52% |
| 6–8 | 5+ | 1.33 | 80% |
| 9+ | 4+ | 2.0 | 94% |

At Warp Tide 3-5, Resurgence is unreliable — you might get one model back, you might not. This is the "trickle" phase. At 6-8, you're reliably recovering 1-2 models per turn. At 9+, the unit is actively regenerating — the daemon unit becomes very hard to permanently degrade without wiping it in a single phase.

**Interaction with Daemonic Instability:** A daemon unit that loses combat takes Instability wounds (losing models). On the daemon player's next turn, Resurgence may return some of those models. This creates a compelling dynamic: the unit is constantly hemorrhaging models from Instability but regenerating from Resurgence. The net effect depends on how badly they're losing combat. If the daemon unit is losing by 1-2 (mild Instability), Resurgence can keep pace. If they're losing badly (Instability at -4 or worse), Resurgence can't keep up and the unit will eventually be banished. This feels right — daemons cling to reality tenaciously but can still be overwhelmed.

**Interaction with Daemonic Icon:** The Daemonic Icon returns D3 models on a natural 2 during Instability Tests. This is a separate mechanic from Resurgence (Icon triggers during the Assault Phase, Resurgence triggers at the start of the Movement Phase). They don't directly stack, but a unit with both an Icon and Resurgence is significantly more resilient. This is intentional — the Icon costs points, and investing in it should pay off.

**Why Reformation is once per game:** Unlimited Reformation would make daemon units effectively immortal — the opponent wipes a unit, it comes back, they wipe it again, it comes back. Once per game means the daemon player must choose WHICH destroyed unit to bring back, creating a meaningful strategic decision. The returned unit is at minimum size with no upgrades, so it's a shadow of its former self — enough to contest an objective or provide a Personal Icon beacon, not enough to win a major engagement.

**Why Reformation uses Daemonic Summoning rules:** This maintains consistency with the existing daemon deployment framework. It also means the reformed unit needs a Personal Icon beacon — which means another daemon unit must be alive on the battlefield. If the daemon player's last unit is destroyed, they can't reform anything. This prevents Reformation from saving a completely tabled army.

---

## SYSTEM INTERACTION SUMMARY

The three sub-mechanics form a feedback loop:

1. **Warp Tide** rises passively and from violence (killing or being killed).
2. **Warp Rift Zones** scale with Warp Tide, making the battlefield increasingly hostile to the enemy.
3. **Daemonic Resurgence** scales with Warp Tide, making the daemon army increasingly persistent.

The opponent's dilemma:
- **Kill daemons quickly?** Accelerates the Warp Tide (destroyed units generate +1), making Rift Zones and Resurgence stronger sooner.
- **Avoid killing daemons?** The daemons close to melee range, where they're devastating, and the Tide rises passively anyway.
- **Focus fire one unit to prevent Resurgence?** Overkilling a unit triggers the Destruction bonus (+1 Tide) and leaves the other daemon units untouched.
- **Spread damage to slow the Tide?** Damaged (but not destroyed) daemon units benefit from Resurgence, recovering models each turn.

There is no "correct" answer for the opponent — every strategy feeds the daemon army in some way. The question is which tradeoff hurts least. This is the intended play experience: fighting daemons should feel like fighting an inexorable force of nature.

---

## OPEN DESIGN QUESTIONS

1. **Cap at 12 vs. uncapped:** Is 12 the right cap for Warp Tide? In large games (2000+ points) with more units and more violence, the cap might be reached too early, causing the mechanic to plateau. A higher cap (15? 20?) with additional threshold tiers might be needed for larger games. For 850 points, 12 is more than sufficient.

2. **Should Warp Tide have a risk/downside at extreme levels?** In lore, the warp is dangerous even for daemons — an uncontrolled rift can swallow everything. A possible rule: at Warp Tide 10+, each daemon unit must pass an Ld test at the start of the daemon player's turn or suffer D3 wounds from warp instability. At Ld 10, this would fail ~8% of the time — a small but real risk that creates tension. This could be a good "pressure release valve" if the mechanic proves too strong in testing.

3. **Reaction suppression too aggressive?** Even as an Ld test (not flat suppression), blocking reactions is a strong effect. If testing reveals it's too much, the fallback is to drop the reaction test entirely and keep the Ld penalty as the sole effect at Warp Tide 6-8. The Ld penalty still has value via Fear, Break Tests, and Pinning.

4. **Resurgence on multi-wound models:** The Bloodthirster has W8. If it loses 3 wounds, does Resurgence apply? As written, Resurgence rolls "for each slain model" — a model that has lost wounds but is alive is not slain. Resurgence only returns slain (removed) models, not lost wounds. This is correct for infantry (Bloodletters die in one wound), but means the Bloodthirster gets zero benefit from Resurgence. Is that intentional? The Bloodthirster probably doesn't need Resurgence (it has 8 wounds and Resistant to Small Arms), but it's worth flagging. If multi-wound model healing is desired, that could be a separate "Warp Regeneration" effect (e.g., at Warp Tide 6+, daemon models with multiple wounds regain 1 lost wound at the start of each daemon turn — effectively It Will Not Die without a roll).

5. **Interaction with Daemonic Summoning in mixed detachments:** If a Chaos Space Marines detachment summons daemon allies via Daemonic Summoning, do those summoned daemons generate Warp Rift Zones? As written, no — the rules are restricted to the Daemonic Incursion detachment. This is intentional (summoned daemons are a more controlled manifestation), but should be explicitly stated.

---

# WARLORD TRAITS

*At the start of the game, the player designates one HQ character as the army's Warlord and assigns a Warlord Trait. The Warlord may select a trait from the Core Rules table or from the table matching their god allegiance below. A Warlord with the* ***Daemon of Khorne*** *rule (or Mark of Khorne) selects from the Khorne table. A Warlord with no specific god allegiance (or Mark of Chaos Undivided) selects from the Undivided table.*

---

## KHORNE WARLORD TRAITS

| # | Name | Effect |
| :---: | :---- | :---- |
| 1 | **Slaughterborn** | Each time a unit containing the Warlord completely destroys an enemy unit in the **ASSAULT PHASE**, the Warlord gains **+1 Attack** for the remainder of the game (cumulative, maximum +3). |
| 2 | **Blood God's Champion** | Friendly units with the ***Daemon of Khorne*** special rule within 12" of the Warlord gain **+1 Strength** on the turn they successfully complete a **CHARGE** move. This bonus applies for the duration of that Assault Phase only and stacks with ***Furious Charge***. |
| 3 | **Skull Taker** | The Warlord and all friendly units gain ***Preferred Enemy (Characters)*** (re-roll failed To Hit rolls against enemy **CHARACTER** models in close combat). Additionally, if the Warlord slays an enemy **CHARACTER** in a **Heroic Duel**, generate **+1 Warp Tide** immediately (in addition to any normal generation triggers). |

### Designer Notes — Khorne Warlord Traits

**Slaughterborn** is the snowball pick. It rewards getting the Warlord into combat early and often, ideally against smaller or weaker units that can be wiped quickly to stack the Attack bonus. On a Bloodthirster (5 base A + D6 Daemon Weapon + 2 Rage on charge), +3A is enormous — it takes an already devastating melee profile and makes it absurd. The "unit containing the Warlord" language means the Warlord doesn't have to personally deal every wound; it just needs to be part of the unit that gets the kill. Since the Bloodthirster is a solo model, this means the Bloodthirster's unit (itself) must wipe the enemy. For an IC Chaos Lord joined to a squad, the whole squad's kills count.

**Blood God's Champion** is the army support pick. It makes the Warlord a force multiplier rather than a solo blender. Bloodletters on the charge go from S4 (base) + 1 (Furious Charge) + 1 (Blood God's Champion) = **S6**, wounding T4 Marines on 2+ instead of 3+. That's a 50% increase in wound output on the charge. The Bloodthirster itself goes from S8 + 1 (FC) + 1 (BGC) = **S10** on the charge, wounding T6 on 2+. The 12" aura range means the Warlord needs to stay reasonably close to the Bloodletters — creating a positioning incentive that interacts with Warp Rift Zone placement.

**Skull Taker** is the character hunter pick. Preferred Enemy (Characters) army-wide means every unit in the army — Bloodletters, the Bloodthirster, everything — re-rolls failed To Hit rolls against enemy Characters in close combat. For Bloodletters at WS5 hitting a WS5 Captain (normally 4+, 50% hit rate), re-rolling failures raises them to 75%. For the Bloodthirster at WS10 hitting WS6 (normally 3+, 67%), re-rolling raises to 89%. The army-wide scope is broad but the trigger is narrow — it only matters against Characters, which is a subset of most enemy armies. The Warp Tide bonus for Heroic Duel kills (+1, stacking with the base table's +2 for slaying a Character in close combat) means a successful duel generates +3 Warp Tide total — an enormous spike that rewards the Warlord for seeking out and destroying enemy champions through the duel mechanic specifically.

**Note on Preferred Enemy scope:** The standard ***Preferred Enemy*** USR re-rolls failed hits against the specified target. "Characters" here means any model with the (Character) type designation — this includes Sergeants, Champions, Independent Characters, and Monstrous Creature Characters. It does NOT require a Heroic Duel to activate — the army always re-rolls against Characters in melee, whether in a duel or normal combat. The Heroic Duel bonus is the Warp Tide spike only.

**Which to take?**
- Against horde armies (Guard, Orks): **Blood God's Champion** — the S bonus helps Bloodletters cut through volume.
- Against character-heavy elite armies (Marines, Custodes): **Skull Taker** — re-roll hits against their characters army-wide, spike the Tide with duel kills.
- Against monster-heavy armies (Tyranids, Daemons mirror): **Slaughterborn** — stack attacks to overwhelm multi-wound targets.

---

## CHAOS UNDIVIDED WARLORD TRAITS

| # | Name | Effect |
| :---: | :---- | :---- |
| 1 | **Indomitable Presence** | The Warlord and all friendly units within 12" gain the ***Stubborn*** special rule (ignore negative Leadership modifiers on Morale and Pinning tests). For units composed entirely of models with the ***Daemon*** USR, this instead applies to **Daemonic Instability Tests** — the unit ignores the standard -1 penalty per three wounds lost when taking Instability Tests while within 12" of the Warlord. |
| 2 | **Lord of the Black Crusade** | While the Warlord is alive, the controlling player may re-roll any failed **Reserve Rolls**. Additionally, once per game, at the start of any of the controlling player's turns, the player may declare that one unit in **Ongoing Reserves** arrives automatically this turn (no Reserve Roll required). |
| 3 | **Favour of the Pantheon** | At the start of the game, after selecting deployment zones but before deploying, choose one of the following boons. The Warlord gains the chosen boon for the duration of the game: |

**Favour of the Pantheon — Boon Options:**
- **Khorne's Rage:** The Warlord gains +1 Attack.
- **Nurgle's Resilience:** The Warlord gains +1 Toughness.
- **Tzeentch's Cunning:** The Warlord's **INVULNERABLE SAVE** is improved by +1 (to a maximum of 3+). If the Warlord does not have an Invulnerable Save, it gains a 5+ Invulnerable Save instead.
- **Slaanesh's Grace:** The Warlord gains +1 Initiative and +2" to charge distances.

### Designer Notes — Undivided Warlord Traits

**Indomitable Presence** is the anchor pick. For mortal Chaos units (CSM, Cultists), Stubborn prevents cascading morale failures. For daemon units, the Instability modifier removal is extremely powerful — a daemon unit that lost combat by 6 wounds would normally test at Ld 10 - 2 = Ld 8 (the penalty is -1 per 3 wounds lost by, so -2 for losing by 6). With this trait, they test at a flat Ld 10. The daemon player parks the Warlord centrally and creates a stabilization aura.

This interacts with the Warp Rift Zone Ld penalty — the enemy near the Warlord is at -1 or -2 Ld, while the daemon units near the Warlord ignore their own Instability penalties. The contrast is thematic: the Warlord's presence stabilizes the rift for its allies while destabilizing it for enemies.

**Lord of the Black Crusade** is the reserve manipulation pick. Re-rolling Reserve Rolls is broadly useful for any Chaos army that uses reserves (Deep Striking daemons, Outflanking units, Daemonic Reformation units). The once-per-game auto-arrival is the headline: it guarantees a critical unit arrives exactly when needed. For a Daemonic Incursion army, this pairs naturally with Daemonic Reformation — the reformed unit doesn't just go to Ongoing Reserves, it arrives automatically next turn with no reserve roll.

**Favour of the Pantheon** is the flexibility pick and the thematic heart of Undivided — drawing from all four gods without being beholden to any one. The choice is made after seeing the opponent's deployment zone (but before deploying), so the daemon player can react to the matchup:
- **Khorne's Rage (+1A):** Extra attack, always useful. Simple and reliable.
- **Nurgle's Resilience (+1T):** Pushes a Chaos Lord from T4 to T5 (wounded on 5+ by S4 weapons instead of 4+). Significant durability bump against standard weapons.
- **Tzeentch's Cunning (+1 Invuln):** A 4++ becoming 3++ is enormous. A 5++ becoming 4++ is also very strong. Best pick against AP2 weapons and power weapons.
- **Slaanesh's Grace (+1I, +2" charge):** Striking before the enemy in melee and reaching them more reliably. Best against assault-oriented opponents where striking first matters.

---

# COMPLETE WARLORD TRAITS — FUTURE TABLES (SCOPE NOTE)

The following tables are **not included in this proposal** but are planned:
- **Nurgle Warlord Traits** (3 traits)
- **Slaanesh Warlord Traits** (3 traits)
- **Tzeentch Warlord Traits** (3 traits)

These will be drafted when those god-specific units are being developed. The framework (3 traits per god, player selects freely, restricted by Warlord's mark/god allegiance) is established here and will carry forward.

---

# REVISION HISTORY

| Version | Date | Changes |
| :---- | :---- | :---- |
| v0.1 | 2026-04-05 | Initial proposal. Warp Tide + Warp Rift Zones + Daemonic Resurgence + Khorne/Undivided Warlord Traits. |
| v0.2 | 2026-04-05 | Fixed CLAUDE.md violations: removed "Challenge" references (replaced with Heroic Duel / close combat), removed "Instant Death" (does not exist in OmniHammer). Reworked Skull Taker trait to Preferred Enemy (Characters) army-wide. Updated Warp Tide CHARACTER trigger to reference close combat instead of Challenge. |
