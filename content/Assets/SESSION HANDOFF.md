---
tags: [meta, session-handoff]
---
# SESSION HANDOFF

*Last updated: March 2026 — Population audit + Codex audit + Timeline fix + Campaign Handout added.*

---

## Campaign Identity

**Game:** Ironsworn: Starforged mechanics in the MAD GALAXY universe  
**Players:** 2–3  
**GM:** Gray  
**Tone:** R-rated military sci-fi — unflinching violence, body horror, moral ambiguity, Cold War political tension, corporate malfeasance. No plot armor. Consequence-driven fiction.  
**Vows are called:** Missions  
**Full campaign philosophy:** see `private/GM Notes/Campaign Handout.md`

---

## Infrastructure

- **Vault:** `E:\MAD GALAXY` (external SSD — if MCP drops mid-session, likely Windows USB power management suspending the drive; fix via Control Panel → Power Options → Advanced → USB Selective Suspend = Disabled, Hard Disk → Never)
- **Quartz:** `C:\mad-galaxy-quartz` — content xcopy'd from vault
- **Sync command:** `cd C:\mad-galaxy-quartz && npx quartz sync --no-pull`
- **Batch file:** `sync-wiki.bat` on Desktop — run after any vault changes
- **Live site:** https://mad-galaxy-wiki.vercel.app
- **GitHub:** https://github.com/Gray-Geist/MAD-GALAXY-WIKI (branch: v4)
- **Vercel build:** `npx quartz build`, output dir `public`
- **vercel.json:** `{ "cleanUrls": true, "trailingSlash": false }`
- **quartz.config.ts fonts:** Rajdhani (header), Share Tech (body), Space Mono (code)
- **private/** folder is in Quartz `ignorePatterns` — never rendered on the wiki
- `index.md` at vault root must be kept identical to `HOME.md`

---

## Critical MCP Behavior Notes

- `patch_vault_file` with `targetType: heading` causes **content duplication** on large files — always use `create_vault_file` with full content for rewrites
- `patch_vault_file` with `targetType: frontmatter` works correctly even when no frontmatter exists
- File naming: **replacement files must be named identically** to the files they replace; new pages must be clearly differently named
- MCP tools are only available in Claude Desktop sessions, not the web interface
- Obsidian must be running when Claude Desktop launches for MCP to connect
- If tools drop mid-session: relaunch Obsidian, restart Claude Desktop, start new conversation
- **Start fresh conversations** to prevent MCP disconnects — long sessions cause drops and compaction

---

## ✅ YAML Frontmatter Pass — COMPLETE

All vault pages tagged. Final 8 files: Primus System, Ryūgū System, Cannard Noz System, Aaru System, Ahura System, Ikhemu-sek System, Kissinger System, Asphodel System.

---

## ✅ Full Codex Audit — COMPLETE

Read entire Codex (.txt, 517KB) against all vault files. All pages confirmed faithful. Five thin megacorps (Cadre Galactic, Gogol Combine, Fabrique Orbital, IDC, Merrick-Gran) are stubs in the Codex itself — not compaction.

---

## ✅ Pages Created / Updated (Last Session)

- **`Universe/The Savage Wars.md`** — NEW standalone page
- **`Universe/History of Humanity.md`** — updated with full timeline table; war duration corrected to ~90 years (1320–1410 AE)
- **`Systems & Planets/Coalition/Baadensenar System.md`** — Autarch speeches added
- **`Culture/Jargon & Slang.md`** — ~30 missing Codex entries added
- **`private/GM Notes/Campaign Handout.md`** — NEW: full campaign philosophy, tone, and table rules
- **All 8 population files** — corrected per population canon below

---

## Population Canon — LOCKED

**Total Sector: 200 billion across ~2,000 physically discovered systems**

| Nation | Population | Notes |
|---|---|---|
| Republic of Man | ~80B | Oldest, most established |
| Novoset Continuum | ~40B | Authoritarian, dense |
| UCF | ~20B | Youngest superpower, quality over quantity |
| Coalition | ~15–18B | Post-Savage Wars decline |
| Ul'Rekar | ~10–12B | Wealthy, insular |
| All others | ~remainder | Minor powers, independents |

**Named world populations (all confirmed correct in vault):**

| World | Population | World | Population |
|---|---|---|---|
| Alexandria (station) | 10 million | Sot Prime | 0 (formerly 10B) |
| Aquila | 10 billion | Silo Station | 0 (formerly 100,000) |
| Aetna | 50 million | Solus | 50,000 |
| Sabine | 5 million | Denfert | 200,000 |
| Aurelia | REDACTED | Lux Aureum | 1.5 billion |
| Alpha Terra | 200 million | Umbreich | 20 million |
| Rho station | 200,000 | Gaesmere | 30 million |
| Pacem | 200,000 permanent | Petran | 50 million |
| Veles | 1 million | Helgoth | 3 billion |
| Archipelago (station) | 250,000 | Noirhaven | 6 million |
| Mycenae | 300 million | Vinnusemi | 760,000 |
| Ogun Beltline | REDACTED | Montalba | 150,000 |
| Solarus Station | 100,000 | Járnbraut | 75,000 |
| Orisha Oko | 1 million | Niagara | 60,000 |
| Erinle | 50 million | Winthrop | 150,000 |
| Nagas | ~1,000 | Taranis | 200,000 |
| Suijin | 30,000 | Cissonius | 200 million |
| Mazandaran | 400 million | Cissonia | 1 million |
| Manichae | 3 billion | Ankou | 500,000 |
| Hara | 11 million | Karnax | ~10,000–100,000 |
| Angra | 23 million | Denderon | 100 million |
| | | KCom Station | 100,000 |

---

## MAD GALAXY Timeline

**BP** = Before Pilgrimage · **AE** = After Earth

| Date | Event |
|---|---|
| **-99 BP** | The Cataclysms — elites pillage resources to build Lighthuggers |
| **0 AE** | The elites depart — *the Pilgrimage* |
| **98 AE** | Chained Eidolon Reaction Drive invented; Earth abandoned; humanity arrives — *the Exploration* |
| **239 AE** | Humanity spreads too fast and slows — *the Decline* |
| **740 AE** | Technology halted; colonies dead; Old Earth coordinates lost |
| **748 AE** | Womb Genesis nanotech perfected — massive population boom |
| **937 AE** | Overpopulation; masses cling to megacities — *the Squeeze* |
| **1000 AE** | Super-megacity construction — *the Roaring Construction* |
| **1215 AE** | Populations venture out — *the Colonization* |
| **1317 AE** | First Contact — entire planets go silent |
| **1320 AE** | Combined Forces created — **Savage Wars begin** |
| **1324 AE** | Fall of Sot Prime; Astral Alliance formed |
| **1410 AE** | Battle of the Grave — **Savage Wars end** |
| **1411 AE** | Unity Day; Republic rises; Cold War begins |
| **1440–1453 AE** | Wars of Independence; Coalition loses superpower status; UCF born |
| **1488–1509 AE** | Secession Wars; UCF solidifies |
| **1517 AE** | **Current era** — Cold War intensifies |

---

## Key Lore Canon

- **Autarch's real name:** High Regent Arden Laurent
- **Maximillien Pieters** assassinated 1517 AE (GM only)
- **Mr. Kagawa** is a secret Autarch ally (GM only)
- **Netjer** is a real AI entity — Ul'Rekar secretly hold it prisoner on Ul'Haupt (GM only — see `private/GM Notes/The Ul'Rekar Secret.md`)
- **History of Humanity** is a living document — update as the universe evolves through play
- **The Savage Wars** lasted ~90 years (1320–1410 AE); Silo Station destroyed in The Hounding (100,000 dead); Sot Prime formerly 10B

---

## GM Reference Documents (private/GM Notes/)

- **Campaign Handout.md** — Table tone, R-rated expectations, Hardcore Energy doctrine, The Concise Way backstory philosophy, Starforged mechanics note (Vows = Missions), inspirations list
- **The Ul'Rekar Secret.md** — Full GM-only Netjer/Ul'Haupt lore
- **Culminating Galactic Event.md** — Autarch's real name, Pieters assassination, Mr. Kagawa
- **Squad Log.md** — Full 43-session archive

---

## ⏳ Remaining Tasks

1. **Novoset Continuum systems & planets** — entire superpower, no pages yet (~40B population)
2. **UCF systems & planets** — entire superpower, no pages yet (~20B population)
3. **NPC Characters folder** — ~15 pages to create
4. **Education Primer section** — home for `education_primer_index.jpg` and `education_primer_index2.jpg`
5. **Sector Events section** — home for `sector_events_index.jpg`
6. **Spacecraft & Naval Doctrine** — place `spacecraft_weapons_pulse_howitzer.jpg`
7. **Missing art** — NKG and Pep-O megacorp pages need images
8. **Star Nations page** — add reference to `republic_gov_structure.png`

---

## Remaining Source Docs to Process

- CODE SCARLET.docx
- MAD GALAXY Setting Summary.docx
- Campaign Handout - The 21 Questions.docx *(not yet in vault)*
*(Squad Log and Culminating Galactic Event already processed into private/GM Notes/)*
