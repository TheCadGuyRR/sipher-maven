# revenant-sipher
Top-Down Reverse-Horror Tactical Extractor

# SIPHER: REVENANT MAVEN (Working Title)

> **Top-down reverse-horror stealth & destructible-terrain action.**  
> *Dune* tension meets *Vodobanka* tactical cues, *Liero* wall destruction, and *Carrion* predator horror.

---

## Core Premise

You play as an evolving, nautiloid-inspired biomass horror hunting human and faction forces inside procedurally generated buildings with destructible walls, room lightbulbs, and connected vent networks. Stalk in the shadows, shatter overhead lights, slip into vents, hijack corpses, and pick off squads in the dark.

### Signature Ambush Loop (Vent → Possession → Lights Out)
1. Slip into a room through the vents and eliminate an isolated soldier.
2. **Possess (`X`)** the corpse and step out into the room while squadmates hesitate.
3. Shoot out the room's **lightbulb** to plunge the space into darkness.
4. Once squadmates open fire and shred the possessed body, pop back into your main nautiloid form and hunt them **in the dark**—where you hold the visibility and ambush advantage.

---

## Game Modes

* **Extraction:** Procedurally generated building with destructible walls and room lightbulbs. Eliminate every soldier one by one using stealth and tactical ambushes.
  * **Alarm & Reinforcements:** If spotted, a soldier triggers a **5-second alarm timer**—kill them before it finishes. If the alarm sounds, **reinforcements** enter through the building's main entrance after **30 seconds**, arriving more alert and trigger-happy.
* **Survival:** Same building and destructible-wall setup as Extraction, but enemies already know you are there from the start, deploying **poison gas**, **flamethrower squads**, and heavy pressure while you begin at **Stage 0**.
* **Sandbox:** Start at **Stage 5** inside a **Lab** full of defenseless **Doctors and Lab Technicians** to test abilities, movement, lighting, and mutations.

---

## Creature Customization & Evolution (Stages 0–5)

Base silhouette: **Nautiloid** with a **White shell** and **Orange tentacles**. Customize both **tentacle shape** and **shell shape**, and export/import your creature build as a **Markdown (`.md`) save file**.

* **Stage 0:** Small frame; low HP; relies heavily on stealth, vents, and ambush tactics.
* **Stage 1:** **Grey shell** with **Orange tentacles**.
* **Stage 2:** Mid-tier growth progression (bridge toward heavy shell tiers).
* **Stage 3:** **Black shell** with **Orange tentacles**.
* **Stage 4:** Consuming a soldier lets you absorb a **faction trait**.
* **Stage 5:** Consuming a **Flamethrower trooper** unlocks **fire projection** plus a **random trait**.

### Faction Traits (Stage 4+ Absorption)
* **Ghoulkins:** Short-circuit lights across the building for **30 seconds**.
* **Gastro Cult:** Attacks apply **poison that mutates into a contagion/virus**—surviving soldiers can accidentally infect their own squadmates.
* **Imp Union:** Transform into a **crab-like form for 15 seconds** that takes **zero bullet damage**.

---

## Top-Down Visuals & Soldiers

### Minimalist Top-Down Rig
* **Soldier Body:** Black circle with a small **colored square** indicating faction/race (**Ghoulkins**, **Gastro Cult**, **Imp Union**), plus **two circles in front** representing arms holding their weapon.
* **Destructible Environment:** Walls can be blasted/pierced open; **every room has a lightbulb** that can be shot out to darken the room and aid stealth.

### Enemy Archetypes
* **Tier 1 (Pistol):** **5-shot magazine** with a visible reload icon; carries a **flashlight cone**; can deploy **motion detectors** (**10-second install** with an installation progress icon).
* **Tier 2 (Shotgun):** **8-shell capacity** with a **longer reload** than pistols and a visible reload icon; carries a **flashlight cone** and **grenades**.
* **Tier 3 (Flamethrower):** Fires continuously for **10 seconds** before stopping for a **longer reload**.
* **Doctor / Lab Tech (Sandbox):** Defenseless non-combatants that flee when threatened.

---

## Controls

| Input | Action |
| :--- | :--- |
| `WASD` | Move around |
| `Left Click` (Click & Drag) | **Thrust single tentacle** — fast mobility or piercing bleed attack; drag to increase range |
| `Right Click` (Click & Drag) | **Pierce (4 tentacles)** — heavy forward strike to destroy walls or kill soldiers; drag to increase range |
| `R` | **Pulse** — reveals every soldier inside the building for **5 seconds**, then fades |
| `E` | Enter / exit **vents** |
| `X` | **Possess** — project a tentacle into a dead soldier's body and control it; if the body is shot apart, return to your main body |

---

## Save System (Markdown `.md`)

* **Export:** Download a `.md` file containing your saved creature configuration (shell shape, tentacle shape, and customization choices).
* **Import:** Upload a saved `.md` file to restore your creature setup cleanly.
