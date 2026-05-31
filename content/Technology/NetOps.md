---
tags:
  - technology
  - netops
  - hacking
  - electronic-warfare
---
# NetOps

*Network Operations — the practice of infiltrating, subverting, and denying electronic systems across the full spectrum of modern warfare. From a locked door to a hardened military drone, if it runs on signal, it can be broken.*

---

## Overview

Every system in the Antevic Sector runs on signal. Building management, weapon IFF, drone uplinks, vehicle navigation, security architecture, communications networks — all of it is connected, all of it is addressable, and all of it has a failure mode. NetOps is the professional discipline of finding those failure modes and exploiting them before the other side does.

The defining piece of hardware is the **Cortical Interface (CI)** — a sub-cranial implant that translates neural intent into machine-language commands at speeds no external interface can match. Without a CI, network operations are reduced to physical terminal access and manual input. With one, a trained operator can reach across a room, a building, or a battlefield and reshape the electronic environment in real time.

NetOps divides into two distinct disciplines with different tools, different risks, and different skill ceilings:

**Infrastructure Operations** — targeted intrusion into static systems. Buildings, networks, databases, terminals. They do not fight back. What they have is architecture, and architecture has weaknesses.

**Electronic Warfare** — broad-spectrum signal manipulation. Area-effect disruption, suppression, and deception that degrades an enemy's ability to coordinate, communicate, and fight as a unit. Where infrastructure ops is surgical, EW is industrial.

Both disciplines run on COMTECH. Both require a CI. Beyond that, the toolkits do not overlap — EW cannot substitute for a targeted hack, and a targeted hack cannot substitute for area signal suppression.

---

## Net Operatives

### The Slicer

The **MOS 12 Network Operations Specialist** — field handle: **Slicer** — is the professional class of NetOps operator. Any operator with a CI and COMTECH skill can attempt basic infrastructure hacking. What separates a Slicer from everyone else is sustained superiority: the talent architecture to operate under fire, hold a flagged system through escalating countermeasures, and execute precision electronic warfare while the rest of the squad is in contact.

Slicers are mission-critical assets. Losing the CI to Burnout mid-operation is not a setback — it is a tactical emergency. They know this. Good ones plan accordingly.

### Biological Advantage

Scientists have established that female operators adapt cortical interface integration more effectively across multiple performance metrics — faster neural handshake, lower signal attenuation, more reliable sustained-access maintenance under stress conditions. The field reflects this. Female Slicers are disproportionately represented in military NetOps programs and paramilitary contractor roles at every tier, where females further augment themselves physically to keep up with male counterparts . This does not mean male Slicers are rare — it means the best ones tend to be women, and the programs that produce elite operators have quietly built their selection criteria around that reality.

---

## Cortical Interface Tiers

The Cortical Interface is the hardware prerequisite for all NetOps and EW operations. Three tiers exist in general circulation. All are surgical implants occupying 1 Biochemistry slot.

---

### Civic-Grade Cortical Interface
**Cost:** $1,800 | **AV:** R

Entry-level cortical interface — a sub-cranial co-processor bonded to the neural signal layer at the prefrontal cortex. Enables infrastructure hacking and basic COMTECH-dependent operations via CI push. No NetOps modifier — civic-grade hardware lacks the hardened signal architecture required for active target hacking or electronic warfare; those operations require Military-grade Cortical Interface (CI) minimum. Available through licensed augmentation clinics and a well-supplied grey market.

*If degraded (Blowback result 5): all NetOps rolls at −2 dice until end of combat.*

---

### Military-Grade Cortical Interface (CI)
**Cost:** $4,500 | **AV:** MRR | **NetOps modifier:** +1 all NetOps rolls

Military-specification cortical interface with hardened signal architecture and active threat-isolation firmware. Grants +1 on all NetOps COMTECH rolls — infrastructure hacking, active target hacking, and all EW actions. This is the minimum hardware tier for active target hacking and electronic warfare; civic-grade CI cannot substitute. Standard issue for MOS 12 Network Operations Specialists and any operator whose mission profile includes electronic warfare. Acquired through military procurement, specialist augmentation programs, or restricted black-market channels.

*If degraded (Blowback result 5): all NetOps rolls at −2 dice until end of combat.*

---

### Military-Hardened Cortical Interface
**Cost:** $9,000 | **AV:** MRRII | **NetOps modifier:** +2 all NetOps rolls

Top-tier cortical interface with full-spectrum signal hardening, counter-intrusion shielding, and extended broadcast range. Grants +2 on all NetOps COMTECH rolls — replaces the +1 bonus of the Military-grade CI. Additionally extends the effective range of the following EW actions: Signal Jam (Short → Medium), Broadband Suppression (Short → Long), Uplink Sever (Medium → Long), Sensor Blind (Medium → Long). Requires Military-grade Cortical Interface (CI) already installed, or replaces it — counts as one implant either way. Found in elite special operations programs, high-end black-market augmentation, and faction-sponsored operative builds where signal superiority is the primary mission.

*If degraded (Blowback result 5): all NetOps rolls at −2 dice until end of combat.*

---

### CI Burnout — Repair Rules

CI Burnout is triggered by Active Hacking Blowback result 6 or by a successful Burn outcome against a target's CI. A burned CI is non-functional — all NetOps and EW actions are impossible until repaired.

**Field Repair**
Requires: TAC-D Field Diagnostic Deck | Time: 1 Stretch | Roll: COMTECH −2

On 1+ ✦: CI is partially restored for the remainder of the scene — all NetOps rolls at −2 dice. Each additional ✦ beyond the first reduces this penalty by 1 (minimum −1 die). Full function cannot be restored in the field regardless of successes. Usable once per CI Burnout event — if the field repair roll fails, the CI remains burned; full repair is the only remaining option.

**Full Repair**
Requires: MedLab or equipped workshop | Time: 1 Shift | Roll: COMTECH −1

On 1+ ✦: CI fully restored — all functions and modifiers return to normal. On failure: CI remains non-functional; retry after the next Shift. Field repair is not a prerequisite — full repair may be attempted directly from Burnout if conditions are met.

> **Civic-grade CI note:** Civic-grade CI carries no NetOps modifier and cannot be used for active target hacking or EW. CI Damage (Blowback result 5) and CI Burnout apply to all tiers — even a burned civic-grade CI disables infrastructure hacking until repaired.

---

### Gear Reference

| Gear | NetOps Modifier | Notes |
|---|---|---|
| No CI / CI Burnout | Impossible | CI required — no exceptions |
| Civic-grade CI | 0 | Infrastructure hacking only — not active targets or EW |
| Military-grade Cortical Interface (CI) | +1 | All NetOps rolls |
| Military-hardened CI | +2 | All NetOps rolls; extended EW ranges |
| TAC-D Field Diagnostic Deck | +2 | General COMTECH only — does not apply to NetOps hacks; required for field CI repair |

---

## Security Systems

*"When safety is first, you last."*
— Orochi-Susanoo advertisement, Antevic Sector

Every lock is a question. The Slicer's job is knowing the answer before the system does.

Infrastructure security across the Antevic Sector runs the full spectrum — from a six-digit keypad on a storage closet to layered VI-monitored biometric architecture guarding a tier-one megacorp data vault. What they share is this: every system has a failure mode. The question is how much it costs to find it.

Systems are organized below by difficulty tier — from the hardest to beat to the most exploitable. Each entry carries its formal name, field handle, and a description of how it works and why it resists compromise.

### Difficulty Tiers

| Tier | COMTECH Modifier | Typical Affiliation |
|---|---|---|
| Unsecured / Civilian | 0 | Residential, commercial, low-security public infrastructure |
| Corporate Standard | −1 | Mid-tier corporate facilities, warehouses, branch offices |
| Military Standard | −2 | Active military installations, government secure facilities |
| Military Hardened / Corporate Elite | −3 | High-value military assets, megacorp tier-one facilities |
| VI-Monitored | −4 | Any affiliation — live VI oversight elevates any system to this tier |

> **Corporate Elite note:** A megacorp operating at full resource depth does not use military-standard security — it exceeds it. Tier-one data architecture, biosynthetics labs, arms R&D floors — these facilities carry Corporate Elite (−3) ratings and in some cases exceed Military Hardened through sheer redundancy. Do not assume military = maximum difficulty. It rarely is.

> **VI-Monitored note:** VI-Monitored is not a system type — it is an overlay. Any system at any tier becomes VI-Monitored if a sentient VI is actively watching it. A civilian terminal with live VI oversight is harder to crack than an unmonitored military system. The −4 modifier applies regardless of underlying hardware.

### Advanced Systems

**Multi-Modal Authentication** | Handle: **Multi-Latch** | Tier: VI-Monitored / Military Hardened

The hardest door in the room. Multi-Latch combines multiple authentication methods into a single synchronized check — typically EM-Print scanning, BloodGate vascular mapping, and Cortical Interface recognition, cross-referencing all three simultaneously. The layered approach ensures that compromising one layer doesn't open the door. Each layer checks the others for inconsistencies. Spoofing one while the others hold will flag the entire attempt. Bypassing Multi-Latch without inside access requires coordinated compromise of every layer in parallel — a feat that demands either exceptional preparation, a complicit authorized user, or direct destruction of the hardware.

*Found at: megacorp tier-one vaults, black-site installations, command-level military facilities, head-of-state security infrastructure.*

**Bio-Electromagnetic Field Scanning** | Handle: **EM-Print** | Tier: Military Hardened / Corporate Elite

Every living being generates a unique bio-electromagnetic field — a signature produced by the specific architecture of their nervous system, impossible to replicate without an exact biological copy. EM-Print scanners read this field in real time, including its fluctuations and harmonic patterns, and reject anything that doesn't match an authorized profile precisely. Replicating a person's EM-Print without cloning their neural structure is not currently possible with available technology.

*Found at: high-security corporate research facilities, military command nodes, installations where identity verification cannot be left to chance.*

**Pulse Resonance Identification** | Handle: **DeepScan** | Tier: Military Hardened / Corporate Elite

DeepScan sends a harmless resonance pulse through the body and maps the resulting vibration pattern against internal anatomy — bones, organs, tissue density, structural geometry. Internal anatomy is substantially harder to forge than surface biometrics. A severed limb fails immediately; without live circulatory response, the resonance pattern degrades in seconds.

*Found at: high-security government and military installations, facilities where physical impersonation is a credible threat.*

**Cortical Recognition** | Handle: **Cort Key** | Tier: Military Standard / Military Hardened

Cortical Interface scanners read specific brainwave patterns associated with pre-registered thoughts or memories. The system requires the authorized person's actual mind — a severed head or a cloned brain will not reproduce the precise neural firing pattern of a living, conscious individual recalling a specific memory. Cort Key systems detect coercion through elevated stress hormones and anomalous neural activity.

*Found at: secure military access points, corporate executive infrastructure, high-value data repositories.*

**Vascular Pattern Recognition** | Handle: **BloodGate** | Tier: Military Standard / Corporate Standard

BloodGate reads the unique flow of blood through an individual's veins — pressure variance, flow rate, vessel geometry — using infrared imaging and thermal overlay. The live circulatory requirement is absolute: a severed hand fails, a synthetic limb fails, a corpse fails. Thermal imaging and pheromone detection confirm the presence of a living, non-coerced authorized individual.

*Found at: mid-to-high tier military and corporate facilities, anywhere that physical impersonation or coercion is a credible threat model.*

**Sentient VI Recognition** | Handle: **VI-Gate** | Tier: VI-Monitored (any hardware level)

VI-Gate is not a sensor system — it is a live evaluator. A sentient VI monitors access points in real time, analyzing microexpressions, vocal patterns, gait, behavioral cues, and contextual inconsistencies. It does not check credentials. It watches people. Fooling VI-Gate requires either a highly trained infiltrator capable of sustained behavioral performance or direct compromise of the VI itself.

*Found at: any installation that can afford and maintain a sentient VI. Common in megacorp executive zones, black-site operations, and military command facilities.*

**DNA Spectroscopy** | Handle: **Spectro** | Tier: Military Standard / Corporate Standard

Laser spectrometers analyze DNA fragments shed in real time from skin cells or saliva, verifying genetic identity against a pre-registered profile. Spectro is rarely deployed alone — it typically operates in tandem with EM-Print or BloodGate as a secondary layer. Spliced or artificially edited DNA is detected.

*Found at: research facilities, biotech installations, locations where genetic verification adds meaningful security value.*

**Behavioral Biometrics** | Handle: **PatternID** | Tier: Corporate Standard / Military Standard

PatternID monitors not who you are but how you behave — gait, typing rhythm, gesture patterns, interaction cadence. Dynamic authentication of this kind is difficult to forge with precision because behavior is continuous, not discrete. PatternID is most effective as a long-duration monitoring system rather than a point-of-entry gate — it catches impostors who pass initial authentication but cannot sustain the performance across an extended period.

*Found at: corporate facilities where personnel work in-place over extended periods; monitoring infrastructure rather than entry points.*

### Basic Systems

**Access Code Terminal** | Handle: **Keystring** | Tier: Unsecured / Corporate Standard

Numeric or alphanumeric passcode entered via physical keypad, holographic interface, or Cortical Interface push. Basic encryption secures the code in transit; systems lock after repeated failures and may trigger silent alerts. Countermeasures: social engineering, direct surveillance, brute-force software targeting outdated encryption. Keystring is the lock on most doors in the Sector — which means most Slicers cracked their first system through one.

**Synced Credentials** | Handle: **Mag-Key** | Tier: Unsecured / Corporate Standard

Physical card swipe, CI digital swipe, or single-use temporary code. Possession of the card or an authenticated CI link is the only requirement. Countermeasures: cloning, theft, interception of weak encryption handshakes. Mag-Key compromised is Mag-Key open — there is no secondary challenge layer.

**Proximity Authentication Tag** | Handle: **ProxTag** | Tier: Unsecured / Corporate Standard

Embedded RFID chips in wearables, prosthetics, or implanted tissue communicating with nearby readers. CI-enabled tags authenticate dynamic biometric responses for additional security, but base-level ProxTag is vulnerable to signal-mimicking devices and relay attacks.

**Biometric Touch Scanner** | Handle: **BioTouch** | Tier: Unsecured / Corporate Standard

Fingerprint or handprint scan compared against a pre-registered database. BioTouch sensors identify cold or lifeless tissue and may incorporate moisture and temperature verification, but the countermeasure list is long and well-documented. BioTouch is a deterrent against opportunistic entry, not a barrier against a prepared Slicer.

**Voice Recognition** | Handle: **VoxLock** | Tier: Unsecured / Corporate Standard

Vocal pitch, tone, and cadence analyzed against a registered identity. Vulnerable to high-quality recordings, synthesized voice software, and coercion. Popular because it requires no physical hardware beyond a microphone and integrates trivially into existing CI infrastructure.

**Mechanical Lock** | Handle: **Analog Latch** | Tier: Unsecured

Physical key, physical tumbler. No power draw, no network connection, no digital attack surface. The Analog Latch survives power outages, network failures, and every form of remote intrusion because there is nothing to connect to. Its countermeasures are as old as the lock itself: picks, bump keys, brute force, duplication.

---

## Infrastructure Operations

Infrastructure targets are static systems — buildings, networks, terminals, databases, automated facilities. They do not fight back. They do not have will. What they have is architecture, and architecture has weaknesses.

Infrastructure hacking follows the standard COMTECH framework. A single roll is sufficient for a straightforward target at close range. Extended Operations handle large, complex, or hardened facilities across multiple Stretches. The difference between a clean run and a compromised position is usually one failed roll at the wrong moment.

### The Hack Roll

Make a COMTECH roll. Apply the target's security tier modifier and any gear modifiers. On 1+ ✦, the hack succeeds — spend ✦ on outcomes below.

**Entry states:**
- **Hack fails** — An alert flag is raised and the system locks: −2 COMTECH on all subsequent attempts against this target until physically bypassed or reset.
- **Hack succeeds, no Silent Entry spent** — Access is gained, but the entry is logged by the system. No immediate alarm is triggered. At the end of the current Stretch, the GM makes a passive OBSERVATION roll on behalf of active security (see Logged Entry table below). 1+ ✦ means the log entry has been noticed and is being investigated — what follows is tier-appropriate and arrives on the GM's timeline.
- **Hack succeeds, Silent Entry spent (+1 ✦)** — No log entry. No trace. No alert on entry. Clean.

**Logged Entry — passive OBSERVATION roll by tier:**

| Security Tier | OBSERVATION Dice | Detection Chance |
|---|---|---|
| Unsecured / Civilian | 2 | 30.6% |
| Corporate Standard | 3 | 42.1% |
| Military Standard | 5 | 59.8% |
| Military Hardened / Corporate Elite | 8 | 76.7% |
| VI-Monitored | Automatic | 100% |

> A live VI does not wait for the end of the Stretch. It detects the log entry at the moment of entry and responds immediately — on its timeline, not yours.

### Success Outcomes — Infrastructure

**Silent Entry** — Cost: +1 ✦

No log entry is created. The system does not register the connection was made. From this position you can read passively — monitor data flows, observe active users, map system architecture — without any record of your presence. Silent Entry covers entry only. Further actions carry normal alert risk — Ghost Mode, by contrast, removes that risk entirely for the Stretch.

*The Slicer who goes in quiet stays in longest. The ones who go in loud rarely get a second chance.*

**Extended Access** — Cost: +1 ✦

The connection remains active for 2 Stretches even if the Slicer is interrupted and must leave the terminal. Combat, movement, an emergency — none of it closes the session. Return to the terminal within those 2 Stretches and the connection is still live. Extended Access does not make the Slicer invisible and does not prevent alert flags from other actions — it only keeps the door open while they're away from it.

**Data Pull** — Cost: +1 ✦

Each spend extracts one specific piece of data — precise and deliberate, not a sweep. The target could be credentials, personnel files, facility schematics, tactical data, or a map of connected systems. A Data Pull from a connected administrative terminal before the main breach is the standard preparation — architecture maps, access lists, and security schedules are all recoverable this way.

**Lateral Access** — Cost: +2 ✦

One connected system adjacent to the target becomes accessible without a new roll. Networks are not islands — a terminal connects to a server, a server connects to a building management system, a building management system connects to security feeds, emergency lockdowns, and environmental controls. The connected system inherits the current alert state.

**System Subversion** — Cost: +2 ✦

You alter one stored parameter within the target system. An access list is updated — a name added, a name removed. A lockdown state is toggled. An alert threshold is raised or lowered. Targeting data is corrupted. A scheduled action is cancelled or triggered early. System Subversion is precise and permanent within the current operational context — the change holds until someone with physical access corrects it or a system audit catches the anomaly.

**Ghost Mode** — Cost: +3 ✦

Full access for the current Stretch. No alert possible. No log trace. Even failed attempts within the Stretch do not trigger alerts — you are architecturally invisible for the duration. Ghost Mode is the ceiling of infrastructure penetration — total access, zero footprint. A Slicer who consistently reaches Ghost Mode on military-hardened targets is either exceptionally skilled, exceptionally well-equipped, or has intelligence that makes the job look easier than it is. Usually all three.

### Extended Operations

Large or hardened infrastructure targets cannot be fully compromised in a single roll. Extended Operations represent a sustained intrusion across multiple Stretches — methodical, cumulative, and punishing if interrupted at the wrong moment.

**How it works:** Before the operation begins, the GM sets 2 thresholds for the target — a **Success Threshold** (total ✦ required to fully compromise) and an **Alert Threshold** (number of failed rolls the system tolerates before locking out and responding). Each Stretch, the Slicer makes 1 COMTECH roll. ✦ accumulate toward the success threshold. Failures accumulate toward the alert threshold. Reaching the success threshold completes the operation. Reaching the alert threshold resets all accumulated ✦, locks the system for 1 Shift, and triggers Hard Blowback.

**Interruption:** If the Slicer is interrupted before hitting either threshold, progress pauses — it does not reset. When they return to the system within the same Shift, they resume from where they stopped. A new Shift resets progress.

**Threshold guidance by tier:**

| Security Tier | Typical Success Threshold | Typical Alert Threshold |
|---|---|---|
| Unsecured / Civilian | 2–3 ✦ | 3 failures |
| Corporate Standard | 3–4 ✦ | 2 failures |
| Military Standard | 4–5 ✦ | 2 failures |
| Military Hardened / Corporate Elite | 5–7 ✦ | 2 failures |
| VI-Monitored | 6–8 ✦ | 1 failure — VI may respond before threshold is reached |

**Alert Response by tier:**

| Security Tier | Alert Response |
|---|---|
| Unsecured / Civilian | Automated alert; response in D6 Stretches |
| Corporate Standard | Silent alarm; armed response in D3 Stretches |
| Military Standard | Zone lockdown; armed response in D6 Rounds |
| Military Hardened / Corporate Elite | Site-wide lockdown; counter-Slicer response possible; armed response in D3 Rounds |
| VI-Monitored | VI responds at moment of detection — on its timeline, not yours |

---

## Active Operations

Active targets have agency. They fight back. The risk profile is categorically different from infrastructure — and the minimum hardware requirement reflects that. Civic-grade CI cannot be used for active target hacking. Military-grade Cortical Interface (CI) is the floor.

*Out here, the difference between a Slicer and a soldier is that the soldier shoots back with a rifle — the Slicer shoots back through your skull.*

### Target Types

**Flat Resistance Targets** — passive systems with no active operator. Resistance is fixed by target tier. Roll COMTECH against the modifier; no opposed roll.

| Target | Tier Equivalent | COMTECH Modifier |
|---|---|---|
| Civilian cyberware (commercial implants, prosthetics) | Unsecured / Civilian | 0 |
| Military cyberware (SmartLync Military, standard CI) | Corporate Standard | −1 |
| Combat drone — operator uplink severed | Corporate Standard | −1 |
| Military-hardened cyberware (SmartLync Elite, military-hardened CI) | Military Standard | −2 |
| Combat drone — operator uplink live | Military Standard | −2 |
| Weapon system (turret, IFF-gated weapon) | Military Standard | −2 |
| Military vehicle (APC, ground transport) | Military Standard | −2 |
| Military vehicle — hardened (dropship, command vehicle, tank, mech) | Military Hardened / Corporate Elite | −3 |

**Opposed Roll Targets** — systems with active human operators or autonomous VI-class intelligence. Full opposed COMTECH roll: both sides roll, attacker needs more ✦ than defender to succeed.

| Target | Roll Type |
|---|---|
| Enemy NetOps Specialist | Full opposed COMTECH |
| VI-monitored system | Full opposed COMTECH (VI uses its COMTECH rating) |

### Success Outcomes — Active Targets

Infrastructure outcomes (Silent Entry, Extended Access, Ghost Mode) do not apply to active targets. Spend ✦ beyond the first on the following outcomes. Multiple outcomes may be purchased on a single roll.

| Cost | Outcome | Effect |
|---|---|---|
| +1 ✦ | Disrupt | Target suffers −1 die on all rolls using the affected system for 1 Round. Cumulative — a second Disrupt on the same target adds another −1 die. |
| +1 ✦ | Expose | Strip IFF data, reveal position, or break encryption on the hacked target. For 1 Stretch: the Slicer's team gains +1 die on OBSERVATION and RANGED COMBAT rolls against the hacked target. The hacked target loses any TacLink coordination benefits for the same duration. |
| +2 ✦ | Sever | Cut the uplink between a drone and its operator, or between SmartLync and a weapon system. Drone uplink severed — drone is autonomous, and is often confused or inactive, until operator restores uplink (Full Action COMTECH). SmartLync weapon fires as standard CHEM until uplink is restored. |
| +2 ✦ | Override | Seize partial control of any discrete controllable system on the target — redirecting a turret's targeting, locking a vehicle's steering, forcing a drone to halt, opening or sealing a vehicle hatch, cutting power to a specific system. Duration: 1 Round base, +1 Round per additional ✦ spent on Override. |
| +3 ✦ | Burn | Destroy hardware. Against soldier cybernetics: target's CI is non-functional until repaired (see CI Burnout Repair Rules) — all cyberware dependent on it ceases to function; target also suffers 1 damage (ignores AR). Against drones: targeting system destroyed. Against vehicles: one system disabled (roll D6: 1–2 = sensors, 3–4 = weapons, 5–6 = drive). |

> **Override — extending duration:** Maintaining Override past its base duration requires a new COMTECH roll (Full Action) at the same modifier. On failure, control is lost.

### Counter-Hacking — Enemy NetOps Specialists

An enemy NetOps Specialist who detects intrusion acts on their own initiative card. Counter-hacking is a Full Action COMTECH roll. They do not need to wait to be targeted first.

**Detection:** A NetOps Specialist automatically detects intrusion against any system they are actively monitoring (declared at start of their turn). Against unmonitored systems in their network, they make a passive OBSERVATION roll at the end of each Round — success means they detect the intrusion and may respond with a counter-hack on their next turn.

**Counter-hack resolution:**
- If the enemy NetOps Specialist initiates a counter-hack against the attacking Slicer: full opposed COMTECH roll. The Slicer is now the defender.
- If the Slicer wins: counter-hack fails.
- If the enemy Slicer wins: Blowback on the attacking Slicer (see Blowback table below).

**Thread Lock interaction:** If the attacking Slicer has Thread Lock active against this target, the enemy NetOps Specialist's counter-hack roll is at −1 die and any failure by the enemy Slicer triggers Hard Blowback automatically. Thread Lock does not prevent the enemy from acting on their own initiative — it degrades their effectiveness when they do.

### Blowback

Every failed active hack roll triggers the Blowback table. For lower-tier targets, rolls of 5–6 are treated as 4 unless Hard Blowback applies. Hard Blowback (Thread Lock trigger or GM call): result is automatically 5 or 6 (GM chooses based on situation and target tier).

| Target Tier | On Failed Roll |
|---|---|
| Soldier cybernetics / civilian drones | Roll D6 — results 5–6 treated as 4 unless Hard Blowback |
| Military vehicle / Military Hardened system | Roll D6 — full table |
| Combat drone with live operator uplink | Roll D6 — full table |
| Enemy NetOps Specialist | Roll D6 — full table |
| VI-monitored system | Roll D6 — full table |

**Active Hacking Blowback Table:**

| D6 | Result |
|---|---|
| 1 | **Signal Spike.** CI broadcasts a detectable signal — all enemies in Short range of the Slicer are alerted to their position. Stress +1. |
| 2 | **Feedback Loop.** COMTECH −1 die on all NetOps rolls until end of Stretch. Stress +1. |
| 3 | **Hard Disconnect.** Forcibly ejected from the target system. All active NetOps connections to this target severed. Cannot re-attempt this target until the start of your next turn. |
| 4 | **Counter-Intrusion.** If an enemy NetOps Specialist is present: they immediately gain +2 dice on their next counter-hack roll against this Slicer this Round. If no enemy Slicer is present: the system locks down — the target's COMTECH modifier increases by −1 for the remainder of the Stretch. |
| 5 | **CI Damage.** Cortical Interface (CI) is degraded — all NetOps rolls at −2 dice until end of combat. Does not constitute full Burnout; CI is still functional. |
| 6 | **CI Burnout.** Cortical Interface (CI) is non-functional. All NetOps actions impossible until repaired — see CI Burnout Repair Rules. Field repair: TAC-D + 1 Stretch, COMTECH −2, partial restore. Full repair: MedLab/workshop + 1 Shift, COMTECH −1. Stress +2. |

### Vehicle Hacking — Tier Reference

| Vehicle Class | Tier Equivalent | COMTECH Modifier |
|---|---|---|
| Civilian transport, cargo hauler | Unsecured / Civilian | 0 |
| Corporate security vehicle, light patrol | Corporate Standard | −1 |
| Military APC, standard dropship | Military Standard | −2 |
| Command vehicle, hardened dropship, drone carrier, tank, mech | Military Hardened / Corporate Elite | −3 |
| VI-piloted autonomous combat vehicle | VI-Monitored | Opposed roll |

---

## Electronic Warfare

Electronic Warfare is the battlefield application of signal disruption, suppression, and deception. Where NetOps is surgical — targeted, precise, requiring direct CI interface with a specific system — EW is broad-spectrum: area-effect, signal-based, and available to any operator with military-grade hardware.

### EW vs. NetOps — Scope Distinction

| | NetOps | Electronic Warfare |
|---|---|---|
| **Nature** | Targeted intrusion into a specific system | Broad-spectrum signal disruption |
| **Requires CI?** | Yes — Military-grade CI minimum | Yes — Military-grade CI minimum for all EW actions |
| **Range** | Terminal / direct connection | Short to Long range |
| **Effect** | Precise outcomes (access, override, burn) | Area degradation, disruption, denial |
| **Primary user** | NetOps Specialists (Slicers) | Any operator with military-grade CI; Uplink Sever is Slicer-only |

A Slicer can use both toolkits. A soldier with a military-grade CI can use most EW actions but cannot perform NetOps. The toolkits do not overlap — EW cannot substitute for a targeted hack, and a targeted hack cannot substitute for area signal suppression.

### SMAFF and CI Operations

SMAFF (Signal Masking and Frequency Filtering) generates a temporary disruption cloud — it is not a persistent equipped state. All CI-dependent operations within an active SMAFF cloud suffer −2 dice regardless of faction. An operator who deploys SMAFF and then attempts EW or NetOps actions from inside the cloud works against themselves. Tactically correct behavior: deploy SMAFF, move outside the cloud, then operate. TacLink bonuses are fully suppressed within the cloud for its duration — this is a hard effect, not a modifier.

### EW Actions

---

#### Signal Jam
**Action:** Quick Action | **Requires:** Military-grade CI | **Roll:** COMTECH | **Range:** Short (Medium with military-hardened CI)

Suppress one signal within range — one communications channel, drone uplink, or CI-linked signal you are aware of. The targeted signal is suppressed for the current Stretch. Affected targets cannot send or receive communications via the jammed channel. Drones on a suppressed uplink lose new command input — they hold position or execute their last instruction.

Jamming hardened military comms uses a standard hack roll at −2 (military-standard modifier). Failure triggers Blowback per the EW Blowback table. Only one signal may be jammed at a time. Signal Jam ends when the Slicer terminates it, when the Slicer is Broken or their CI burns out, or at the start of the next Stretch.

**Who can use it:** Any operator with military-grade CI or better. Slicers apply full dice pool; non-Slicer operators roll base COMTECH only.

*You cannot jam what you don't know is there. If a signal is hidden or disguised, detecting it first requires a successful OBSERVATION roll or prior intelligence.*

---

#### Broadband Suppression
**Action:** Full Action | **Requires:** Military-grade CI | **Roll:** COMTECH | **Range:** All targets in Short range zone (Long range with military-hardened CI)

Degrade all communications signals in the affected zone simultaneously. Less precise than Signal Jam but covers the entire area rather than a single channel. On success, all targets in range suffer −1 die on COMTECH and COMMAND rolls that depend on electronic communication (including giving orders via TacLink) for 1 Round per ✦ rolled.

**Who can use it:** Any operator with military-grade CI or better. Non-Slicer operators roll base COMTECH only.

**Extra ✦:** Spend on either extended duration (+1 Round per ✦) or additional zones (+1 adjacent zone per ✦) — not both on the same roll.

**SMAFF interaction:** −2 dice if the operator is inside an active SMAFF cloud.

---

#### Uplink Sever
**Action:** Full Action | **Requires:** Military-grade CI | **Roll:** COMTECH vs. flat resistance (drone tier) | **Range:** Medium (Long with military-hardened CI)

Targets the control uplink between drone and operator across a range band simultaneously — rather than hacking a single drone directly. On success, all drones of the same operator network within range lose their uplinks simultaneously — each is autonomous, and often confused or inactive, until the operator restores each uplink (Full Action COMTECH per drone). A single roll can neutralize an entire drone element at once.

**Who can use it:** Slicer only. Uplink Sever requires the precision signal threading of MOS training — non-Slicer operators cannot distinguish individual uplink frequencies at range without dedicated equipment.

**Extra ✦:** Each ✦ beyond the first extends the effect to one additional drone in range, or extends autonomous duration by 1 Round.

---

#### Sensor Blind
**Action:** Full Action | **Requires:** Military-grade CI | **Roll:** COMTECH vs. flat resistance (sensor system tier) | **Range:** Medium

Suppress motion trackers, targeting sensors, and observation drones in the target zone. On success, all sensor-based OBSERVATION rolls in the affected zone are at −2 dice for 1 Stretch (stealth) or 3 Rounds (combat). Automated systems that rely on sensors — sentry guns, autonomous targeting — lose their detection capability for the same duration.

**Who can use it:** Any operator with military-grade CI or better. Non-Slicer operators roll base COMTECH only.

**Extra ✦:** Each ✦ beyond the first extends duration by 1 Round in combat, or by 1 Stretch in stealth mode.

**SMAFF interaction:** SMAFF already suppresses sensors within its cloud. Sensor Blind applied to a zone already under SMAFF is redundant for that zone's duration but extends the suppression window beyond the cloud's dissipation.

---

#### Counter-EW
**Action:** Quick Action (declare before any EW roll is made against your team this Round) | **Requires:** Military-grade CI | **Roll:** Opposed COMTECH vs. the incoming EW action

Harden your own signals against enemy jamming. Declare Counter-EW at the start of your turn or as an interrupt when an enemy EW action targets your team. Roll COMTECH — each ✦ cancels one ✦ from the enemy's EW roll. If all enemy ✦ are cancelled, the EW action fails. If some ✦ remain, the EW action succeeds at reduced effect (GM determines — typically reduced duration or reduced range).

**Who can use it:** Any operator with military-grade CI or better. Non-Slicer operators roll base COMTECH only.

**TacLink:** A successful Counter-EW roll also protects TacLink integrity for this Round — the team retains Formation bonuses and coordinated fire even if SMAFF is active, provided the Counter-EW roll succeeds before the cloud takes effect.

---

#### IFF Spoof
**Action:** Full Action (or Quick Action — see variant below) | **Requires:** Military-grade CI | **Roll:** COMTECH | **Range:** Self and allies within Short range (Self-Spoof); opposed roll against target (Target Spoof)

Falsify friend-or-foe transponder data. Two applications:

**Self-Spoof:** The operator broadcasts a falsified IFF signal covering themselves and all allies within Short range at the moment of activation. Opposed COMTECH roll against the system or operator reading the feed (flat resistance for automated systems; full opposed for enemy NetOps Specialists). On success: the covered team reads as friendly to affected weapon systems and TacLink threat displays. Duration: 1 Stretch, +1 Stretch per additional ✦. Automated systems — turrets, IFF-gated weapons, drone targeting — will not engage covered targets for this duration. Human operators reading the feed roll OBSERVATION at −1 die for each ✦ spent on the spoof roll beyond the first to identify the falsified signal.

**Quick Action variant:** Declare before rolling. Reduce duration to 3 Rounds. The spoof covers the activating operator only. Usable when speed matters more than coverage.

**Target Spoof:** Inject false hostile IFF into a specific target's transponder. Opposed COMTECH roll against flat resistance (vehicles, automated systems) or full opposed roll (enemy NetOps Specialist). On success: target reads as hostile to their own automated systems and any operators relying on TacLink threat data. Automated systems will engage the spoofed target. Human operators can override visually — they are not forced to engage — but forced to verbally confirm targeting rather than trust their feed, degrading coordination (−1 die COMMAND for affected operators this Round). Duration: 1 Round base, +1 Round per additional ✦.

**Who can use it:** Any operator with military-grade CI or better. Non-Slicer operators roll base COMTECH only.

**SMAFF interaction:** If the target of a spoof is inside an active SMAFF cloud, the spoof roll is at −2 dice. If the activating operator is inside their own SMAFF cloud, their spoof roll is at −2 dice.

**IFF Spoof Blowback:** On a failed spoof roll against a hardened system (Military Hardened / Corporate Elite tier or above, or enemy NetOps Specialist): the operator's CI signal signature is flagged — enemy NetOps Specialist or counter-EW system gains +2 dice on their next counter-hack or EW roll against this operator. Additionally, the operator's position is broadcast to the enemy team — all enemies gain +2 dice on OBSERVATION and RANGED COMBAT rolls against the operator for the remainder of the current Round.

---

### TacLink Disruption — Mechanical Effects

TacLink disruption — from SMAFF, TS-34 Bot Popper, or successful EW action — removes the following benefits for affected soldiers for the duration of the disrupting effect:

- **Shared OBSERVATION:** Successful OBSERVATION by one linked member is no longer shared to all. Each member detects threats independently.
- **Surprise defense:** The group no longer benefits from the rule that any linked member's successful OBSERVATION prevents surprise for the whole group.
- **Formation bonuses:** Any formation-based bonus dice are lost.
- **Coordinated fire:** Characters cannot benefit from the Giving Orders Full Action bonus on another character's roll if the link between them is disrupted.

Individual soldiers are not broken — they continue to fight, but as independent actors rather than a coordinated unit. A Slicer who understands this doesn't need to kill the enemy. They just need to make the enemy stop trusting each other.

### EW Blowback Table

Roll when: a COMTECH EW roll fails (except IFF Spoof, which has its own Blowback text above), or when a Push on an EW roll produces ☠ on a stress die.

| D6 | Result |
|---|---|
| 1 | **Backscatter.** The EW attempt is detectable — enemy signals officer or NetOps Specialist pinpoints the source. They know the operator's zone. Stress +1. |
| 2 | **Frequency Bleed.** The failed attempt partially disrupts your own team's comms. All allies in Short range suffer −1 die on COMMAND rolls this Round. |
| 3 | **Signal Collapse.** The EW system overloads — the operator cannot use any EW actions until the start of their next turn. |
| 4 | **Counter-Lock.** Enemy signals are hardened against this specific EW action for the remainder of the Stretch — any retry of the same action against the same target is at −2 dice. |
| 5 | **TacLink Bleed.** The operator's own TacLink feed is disrupted — they lose all TacLink benefits (shared OBSERVATION, surprise defense, formation bonuses) until end of Stretch. Other team members are unaffected. |
| 6 | **Source Trace.** The failed signal is traced back to the operator's CI. All enemies gain +2 dice on OBSERVATION and RANGED COMBAT rolls against the operator for 1 Round. |

---

## Terminology

| Term | Definition |
|---|---|
| **NetOps** | Network Operations — the full discipline of CI-enabled hacking, active target manipulation, and electronic warfare |
| **Slicer** | Field handle for an MOS 12 Network Operations Specialist |
| **CI** | Cortical Interface — the sub-cranial implant required for all NetOps and EW operations |
| **CI Burnout** | Complete CI failure — all NetOps and EW impossible until repaired (see CI Burnout Repair Rules) |
| **CI Damage** | Degraded CI state from Blowback result 5 — functional but at −2 dice on all NetOps rolls until end of combat |
| **TAC-D** | TAC-D Field Diagnostic Deck — specialist gear; required for field CI repair; grants +2 on general COMTECH rolls (not NetOps hacks) |
| **Infrastructure Ops** | Hacking of static systems — buildings, networks, terminals, databases |
| **Active Ops** | Hacking of targets with agency — soldier cybernetics, vehicles, drones, enemy Slicers |
| **EW** | Electronic Warfare — area-effect signal disruption, suppression, and deception |
| **TacLink** | Encrypted tactical network — shared OBSERVATION, surprise defense, formation bonuses; disrupted by SMAFF, TS-34, and successful EW |
| **SMAFF** | Signal Masking and Frequency Filtering — disruption cloud from the M-3B smoke grenade; suppresses all CI operations within the cloud at −2 dice regardless of faction |
| **Flat Resistance** | Fixed COMTECH modifier applied to passive active targets (drones, vehicles, soldier cybernetics) with no active operator |
| **Opposed Roll** | Full opposed COMTECH — used against enemy NetOps Specialists and VI-monitored systems |
| **Hard Blowback** | Elevated blowback — result automatically 5 or 6 on the Blowback table; triggered by Thread Lock or GM call |
| **Thread Lock** | Slicer talent — flags one target; their NetOps rolls at −1 die, failed counter-hacks trigger Hard Blowback automatically |
| **Cold Process** | Slicer talent — roll base dice only on NetOps rolls until first failure per Stretch |
| **Signal Jam** | EW action and Slicer talent — suppress one signal within range as a Quick Action |
| **Ghost Mode** | Infrastructure outcome — full access, no trace, no alert possible for the current Stretch; costs +3 ✦ |
| **Silent Entry** | Infrastructure outcome — clean entry with no log; costs +1 ✦ |
| **Logged Entry** | Infrastructure hack outcome where access is gained but the connection is recorded; passive detection roll at Stretch end |
| **VI-Gate** | Sentient VI security system — live evaluator watching behavior rather than checking credentials |
| **Extended Operations** | Multi-Stretch intrusion against large or hardened targets; governed by Success Threshold and Alert Threshold |

---

*See also: [[Technology/Cyberware & Implants|Cyberware & Implants]], [[Technology/Synthetic Intelligence|Synthetic Intelligence]], [[HOME|← Back to Home]]*
