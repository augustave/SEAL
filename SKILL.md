---
name: seal
description: "Generate brand doctrine, palette codices, and visual operating language for defense-tech and American Dynamism companies across the SEA / AIR / LAND operational-domain taxonomy. Use when the user asks for a defense aesthetic, brand doctrine, palette, visual operating language, or VOL, or names any canonical SEAL palette — Coldwater Pragmatism (USV/UUV/naval — sea), Rustbelt Kinetic (manufacturing/Arsenal-1 — industrial substrate), Anechoic Minimal (EW/directed energy/RF/SIGINT — spectrum across all domains), or Desert Pragmatism (CENTCOM/Anduril/Group-2 UAS — land). Also use when building brand identity for any defense-tech company (Anduril, Saronic, Shield AI, Epirus, Hadrian, Apex, Firestorm, Hidden Level, etc.) or articulating a visual language for an operational domain. Trigger even when the user does not say SEAL by name — any defense-tech aesthetic request is in scope. Output is one of six document types: CODEX, CARD, STACK, BRIEF, COVER, or INDEX. Do NOT use for civilian brand identity, product design, or lifestyle moodboards. Use AKTE for archival/bureaucratic documents; use KAMI for editorial/literary documents."
license: MIT
---

# SEAL

Brand doctrine system for defense-tech and American Dynamism, organized along the SEA / AIR / LAND operational-domain taxonomy. Four canonical palettes mapped across operational domains, six document types, eight iron rules. Tagline: *Sea, air, land — every domain has a doctrine. Every doctrine has a look.*

The name encodes the system's elasticity. SEAL is the canonical military framing of operational domains — sea, air, land — extended in this system by spectrum (Anechoic) and substrate (Rustbelt). The four current palettes occupy three of the four operational corners; **Air is the canonical missing palette** and the next most important draft.

Origin: the AD codex of Coldwater Pragmatism, Rustbelt Kinetic, Anechoic Minimal, and Desert Pragmatism — written in late 2025 as a doctrinal vocabulary for the new defense-industrial stack (Anduril, Saronic, Shield AI, Epirus, Hadrian, et al.). SEAL packages that codex as a reusable skill.

SEAL is the operational mirror of AKTE. Where AKTE catalogs an object as an archival accession, SEAL positions a company within an operational domain. Both share a skeleton: opinionated constraints, distributable as a Claude skill, fixed typology, non-negotiable iron rules.

## Domain mapping

| Domain | Palette | Status |
|---|---|---|
| **Sea** | Coldwater Pragmatism (`SEAL—CW`) | Canonical |
| **Air** | Apex Heraldic (`SEAL—AH`) | Canonical |
| **Land** | Desert Pragmatism (`SEAL—DP`) | Canonical |
| **Spectrum** (across all) | Anechoic Minimal (`SEAL—AN`) | Canonical |
| **Industrial substrate** (under all) | Rustbelt Kinetic (`SEAL—RB`) | Canonical |

Sea, Air, and Land are operational layers. Spectrum sits over all of them. Industrial sits beneath all of them. The stack relationship is the brand.

## The five palettes (canonical)

| Code | Name | Domain | Reference file |
|---|---|---|---|
| `SEAL—CW` | Coldwater Pragmatism | USV / UUV / naval autonomy / sub-surface | `references/coldwater.md` |
| `SEAL—RB` | Rustbelt Kinetic | Manufacturing / Arsenal / production base | `references/rustbelt.md` |
| `SEAL—AN` | Anechoic Minimal | EW / directed energy / RF / SIGINT / spectrum | `references/anechoic.md` |
| `SEAL—DP` | Desert Pragmatism | CENTCOM / Group-1/2 UAS / austere ground ops | `references/desert.md` |
| `SEAL—AH` | Apex Heraldic | Air superiority / strategic strike / standoff weapons / strategic ISR / hypersonics | `references/apex_heraldic.md` |

When the user asks for work in a specific palette, read **only** the relevant reference file. Do not preload all five — progressive disclosure is the rule.

When the user asks for work that doesn't match any of the five cleanly, do not invent a sixth palette without explicit user confirmation. Push back: tell them what's missing and ask whether to (a) extend an existing palette, (b) write a new one, or (c) refuse the brief if it doesn't belong in the defense-tech surface area. Orbital, Polar, and Cyber/Software are the most likely legitimate sixth candidates.

## The six document types

| Code | Type | What it is | When to use |
|---|---|---|---|
| `SEAL—01` | `CODEX` | Full ~10-section expanded doctrine entry (Vibe / Color / Materials / Visuals / Typography / Voice / Interface / Sound & Motion / Rejections / Lineage / Stack / Thesis) | Default. The headline artifact. Use when the user asks to "expand," "write," or "draft" a palette. |
| `SEAL—02` | `CARD` | Single-page summary: name, vibe (1 paragraph), palette (5–7 colors), three signature visual references, thesis line. ~250 words total. | Quick reference, slide insert, brand brief appendix. |
| `SEAL—03` | `STACK` | Cross-palette relationship map showing how the doctrines interlock — which carries which payload, which feeds which supply chain, which depends on which for survival. | When the user is building VOL infrastructure or needs to communicate the full ecosystem at once. |
| `SEAL—04` | `BRIEF` | Application document: take one palette and project it onto a specific company, product, or campaign. Identifies what the company already does well, what it gets wrong, and the palette-specific corrections. | Brand audits, pitch prep, creative direction for a specific named target (e.g. "apply Coldwater to Saronic"). |
| `SEAL—05` | `COVER` | Thesis-line + signature image direction. The cover page artifact. ~50 words plus visual brief. | Title slides, deck covers, single-image brand statements. |
| `SEAL—06` | `INDEX` | Full taxonomy view: all palettes with one-line summaries, the stack relationship in one sentence, and pointers to the codex entries. | Onboarding a new collaborator, master-document context, inside-front-cover of a multi-palette deliverable. |

When ambiguous, default to `CODEX`. It's the headline artifact and works for most requests.

## Iron rules (eight, non-negotiable)

These are the rules that make a palette doctrinally SEAL vs. moodboard. Every output must obey all eight. If a brief asks for something that violates a rule, push back rather than comply.

1. **Mass over swagger.** Defense aesthetics carry tonnage. Reject Silicon Valley register — agility, lightness, optimism, friendliness, "delight." The work has weight because the hardware does. The voice is closer to a merchant marine log than a product launch.

2. **Anti-glint is doctrine.** Matte finishes only. No gradients in UI. No beveled chrome. No showroom polish on hardware. The only permitted shine is environmental — water, glass, metal under direct light — never finish itself. Gloss is the visual signature of marketing; the brand is hardware.

3. **One protected accent per palette.** Each palette reserves exactly one high-saturation color as a semantic class — alert, signal, ID, completion. Never decoration. Coldwater = safety orange. Rustbelt = MIG arc-blue. Anechoic = P31 phosphor green (with TEMPEST red and Keysight cobalt as restricted secondaries). Desert = VS-17 cerise / Anduril sabre red. Apex Heraldic = heraldic gold (with Old Glory red as restricted secondary for combat decoration). Multiple accent colors collapse the doctrine into product packaging.

4. **Real units only.** Bearings, knots, decibels, PSI, hours-on-station, units-per-month, nautical miles, megawatts, NF, OEE, takt time. Never "blazing fast," "next-generation," "AI-powered," "revolutionary," "world-class." If a number can be measured by an instrument, use the instrument's unit. Marketing units (better, faster, smarter) are forbidden.

5. **Cultural lineage required.** Every palette must trace a 30+ year industrial heritage that predates the current company. Coldwater inherits Bath Iron Works, Electric Boat, Royal Navy Type 26, Cold War SOSUS. Rustbelt inherits Willow Run, River Rouge, Kaiser Shipyards, the Arsenal of Democracy. Anechoic inherits Bell Labs, HP/Agilent/Keysight, Tektronix, Cold War SIGINT. Desert inherits the entire CENTCOM-era visual record from 2003 forward. Apex Heraldic inherits SAC, the SR-71 / B-2 / B-21 lineage at Plant 42, the USAF ribbon and chevron heraldic system, AFRL, and the LeMay-era documentary record. A palette without lineage is a moodboard.

6. **Stack-aware.** Every palette declares its position in the doctrine stack — which other palettes carry its payload, which feed its supply chain, which it depends on for survival. No palette stands alone. Coldwater's USV carries an Anechoic-doctrine EW payload, built on a Rustbelt-doctrine production line, deployed alongside Desert-doctrine ground forces. The stack is the brand.

7. **Reject the tourist palette.** Do not borrow another palette's signifiers casually. Coldwater does not wear FDE. Anechoic does not wear safety orange. Rustbelt does not wear haze grey. If a payload moves between domains, the carrier's palette wins — never the payload's. Cross-pollination breaks the doctrine.

8. **One-line thesis, on the cover.** Every palette ships with one quotable sentence — the line that goes on the cover page when the palette is presented. *"The ocean doesn't care about your DoD rating."* / *"Spectrum is terrain."* / *"The prototype is the brochure. The line is the product."* / *"Build for the FOB. Everything else follows."* / *"Range is power. Altitude is authority."* No palette is finished until the line is written.

## Workflow

When a request comes in, work in this order:

1. **Identify the document type.** Read the user's brief and pick one of the six types above. If they say "expand X," it's `CODEX`. If they say "summarize," it's `CARD`. If they say "apply to Saronic," it's `BRIEF`. If they say "what are the palettes," it's `INDEX`. If unclear, default to `CODEX` and confirm.

2. **Identify the palette.** Match the brief to one of the four canonical palettes. If it doesn't match, ask before inventing a fifth. Air is the canonical next palette and the most likely legitimate fifth.

3. **Read only the relevant reference file.** Do not preload all four. If `BRIEF` or `STACK` requires multiple, read them in sequence, not in parallel.

4. **Apply the iron rules.** Before writing, mentally check each output against all eight rules. If the brief asks for something that breaks a rule (e.g., "make Coldwater feel more optimistic and friendly"), push back — the rule wins, not the brief.

5. **Write in the doctrinal register.** Match the voice of the existing codex entries: terse, declarative, technically grounded, no marketing copy, no exclamation, no second-person sales voice. Specs in real units. Lineage cited. Thesis line landed.

6. **Always end with the thesis line.** Every output, regardless of type, includes the palette's one-line thesis. For new palettes, write the line first and let the rest of the codex defend it.

## Voice and register

The voice across all SEAL outputs is constant:

- **Declarative.** No hedging, no "perhaps," no "could be argued."
- **Technically grounded.** Reference real hardware, real plants, real frequencies, real ships, real wars.
- **Terse.** Sentences earn their length. A four-word sentence is permitted; a four-clause sentence has to justify itself.
- **No exclamation.** Ever. The work is not exciting, it is heavy.
- **No marketing verbs.** No "unlock," "empower," "revolutionize," "disrupt," "delight." Use measurement verbs: detect, jam, deny, deceive, illuminate, characterize, stamp, weld, ship, sail, loiter, emit.
- **Cite by name.** "Anduril" not "a defense-tech company." "Bath Iron Works" not "a shipyard." "P31 phosphor" not "green." Names are doctrine.
- **First person plural is permitted, sparingly.** "We see you. You don't see us." This is the cypherpunk-restraint mode of Anechoic. Do not overuse.

## What this skill rejects

- **Genericized "tech-defense" aesthetic.** Not every dark-mode dashboard with a topo map is SEAL. The palette must be specifically chosen for the operational domain.
- **Civilian-bleed.** No outdoor lifestyle photography, no "rugged" hipster cosplay, no Brooklyn-warehouse industrial chic. The work is the work.
- **Aestheticized violence.** Explosions, kill counts, gun-porn close-ups. The doctrine respects the seriousness of the subject; sensationalism is amateur.
- **Pacifist hand-wringing in the copy.** The skill assumes the user has already accepted the work. Hand-wringing belongs elsewhere.
- **Inventing palettes on demand.** The four canonical palettes cover most of the contemporary defense-tech surface. Air is the legitimate next; Orbital, Polar, Cyber/Software, Logistics require explicit doctrinal expansion — not improvisation.

## Reference files

- `references/coldwater.md` — Coldwater Pragmatism full codex (`SEAL—CW`, sea)
- `references/rustbelt.md` — Rustbelt Kinetic full codex (`SEAL—RB`, industrial substrate)
- `references/anechoic.md` — Anechoic Minimal full codex (`SEAL—AN`, spectrum)
- `references/desert.md` — Desert Pragmatism full codex (`SEAL—DP`, land)
- `references/apex_heraldic.md` — Apex Heraldic full codex (`SEAL—AH`, air)
- `references/typography.md` — Typography codex: canonical type stacks for all four palettes, meta-doctrine register, six shared rules, full face index
- `references/color.md` — Color codex: five-value system palette per palette with hex, extended field colors, protected accent index, usage ratios, cross-palette rules
- `references/imagery.md` — Imagery codex: per-palette light, atmosphere, subject framing, geography of record, permitted render contexts, cross-palette image rules
- `references/coexistence.md` — Coexistence codex: the carrier-wins principle for STACK documents, six operational rules, common pairings, what STACK rejects
- `references/violations.md` — Violations codex: wrong/right specimens for each of the eight iron rules, common compound violations, final-review checklist

## Examples

- `examples/seal_demo.html` — A self-referential CODEX entry: SEAL documenting itself in its own format. Use as a structural reference for what a finished CODEX looks like rendered.

---

*Sea, air, land — every domain has a doctrine. Every doctrine has a look.*
