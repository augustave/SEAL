# SEAL — Typography Codex

**Code:** `SEAL—TY`
**Status:** Canon
**Governs:** All six document types across all five palettes
**Version:** 1.0

---

## System premise

Type in this system carries the register of the palette it serves. The faces are not interchangeable. A Coldwater document set in slab serif reads as misrouted cargo. A Rustbelt document set in monospace reads as a SCIF briefing. Each palette inherits its type stack from the industrial or operational context that defines it — the shipyard, the factory floor, the anechoic chamber, the FOB.

Three constraints govern the entire system:

1. **Weight signals mass.** Light weights and thin strokes are not in this vocabulary. The minimum useful weight is Regular. Display type defaults to Bold or Black.
2. **Monospace is universal for telemetry.** Every palette uses monospace for data, specs, coordinates, and UI labels. The humanist sans has no role in this system.
3. **Stencil is hardware-only.** Stencil cuts are for crates, hull IDs, and compartment markings. Never UI. Never digital body copy. Never a display substitute.

---

## Per-palette type stacks

### SEAL—CW · Coldwater Pragmatism

| Role | Canonical face | Acceptable alternates | Usage |
|---|---|---|---|
| **Display** | Neue Haas Grotesk Black | Aktiv Grotesk Black, Helvetica Neue 107 | Cover type, chapter titles, wordmarks — the weight of a destroyer's bridge instruction plate |
| **Body** | Neue Haas Grotesk Regular | Standard CT, Aktiv Grotesk Regular | Extended copy, codex entries, operational logs |
| **Mono** | IBM Plex Mono | JetBrains Mono | Telemetry readouts, depth / bearing / speed specs, comms transcripts |
| **Accent** | Allied Military Stencil | Series Gothic Stencil | Hull IDs, crate markings, compartment numbering — hardware surfaces only, never digital |

**Type rule.** The grotesque is primary because it reads like paint-roller lettering on a destroyer's island — functional, blunt, not designed for charm. No serifs. No humanist faces. The stencil is a marking convention, not a typeface: the moment it appears on a slide or UI, it becomes costume.

---

### SEAL—RB · Rustbelt Kinetic

| Role | Canonical face | Acceptable alternates | Usage |
|---|---|---|---|
| **Display** | Rockwell Bold | Sentinel Bold, Clarendon, Memphis Bold | Headlines, section marks — the railroad-and-steel typography lineage; reads as weight and permanence |
| **Body** | DIN 1451 | Industry, Stratum 2 | Extended copy, floor documentation, plant specs — the ISO industrial standard every machine tool and vehicle spec uses |
| **Mono** | Berkeley Mono | IBM Plex Mono | Production data: takt time, OEE, lot IDs, cycle counts, unit counters |
| **Accent** | Hand-painted sign lettering | Sign Painter, Schoolhouse | Provenance marks on final product only — *Made in Columbus, Bay 4 South, Shift B* — never used as a headline |

**Type rule.** Slab serif for display is mandatory. It is the typographic signature of American industrial heritage from railroad to arsenal. DIN 1451 for body is the same standard printed on every stamped NATO part, every Bridgeport nameplate, every vehicle spec sheet. Hand-painted lettering is earned — reserved for provenance statements on finished units, not for brand expression.

---

### SEAL—AN · Anechoic Minimal

| Role | Canonical face | Acceptable alternates | Usage |
|---|---|---|---|
| **Display** | IBM Plex Mono Bold | Berkeley Mono Bold, JetBrains Mono Bold | All headers and cover type — monospace is universal in this palette; no grotesque, no slab |
| **Body** | IBM Plex Mono Regular | Berkeley Mono, Cascadia Code | All body copy — every character in this world is a measurement |
| **Mono** | IBM Plex Mono | GT America Mono | Same face throughout — no face-switching; the uniformity is the register |
| **Accent** | — | — | Frequency-band designators (HF / VHF / UHF / X / Ka) are semantic labels, not a separate face — monospace throughout |

**Type rule.** Monospace is doctrine, not decoration. The single-typeface system is not a limitation — it is the visual equivalent of a Faraday cage. Humanist sans-serif is rejected entirely. The only permitted second face is the meta-doctrine Newsreader Italic for thesis lines, and only in CODEX or COVER context. Otherwise: one face, all weights, no exceptions.

---

### SEAL—DP · Desert Pragmatism

| Role | Canonical face | Acceptable alternates | Usage |
|---|---|---|---|
| **Display** | Druk Wide Bold | Industry, Stratum 2, GT America Condensed Black | Cover type, product lockups — the heavy condensed all-caps grammar Anduril established as genre lineage |
| **Body** | DIN 1451 | Franklin Gothic, Stratum | Operator documentation, UI labels — legible at arm's length in direct sunlight, one-handed, with gloves |
| **Mono** | JetBrains Mono | IBM Plex Mono | Telemetry: MGRS coordinates, grid references, link status, altitude / speed readouts |
| **Accent** | Allied Military Stencil | US Number Plate Stencil, MIL-STD-130 plate | Hardware stencils on UAS airframes, launcher tubes, Pelican lids — never digital |

**Type rule.** Druk Wide is the primary display face because it is direct lineage of the Anduril lockup — the condensed-black-all-caps grammar that established the genre. DIN 1451 shares the body role with Rustbelt: both palettes are specifications-first, and DIN is the industrial standard for both theaters. They share the face but not the context — Rustbelt uses it for floor documentation, Desert uses it for operator UI.

---

### SEAL—AH · Apex Heraldic

| Role | Canonical face | Acceptable alternates | Usage |
|---|---|---|---|
| **Display (ceremonial)** | Trajan Pro | Cinzel, Cormorant Garamond | Engraved-classical for chevrons, rank insignia, unit emblems, the seal — the inscriptional lineage from Roman military to USAF heraldry |
| **Display (operational)** | Druk Wide Bold | Industry, GT America Condensed Black | Platform designators, wing identifiers, tail codes — the operational counterpart to ceremonial Trajan |
| **Body** | Source Serif Pro | Sentinel, Charter, AFPAM publication serif | AFI / TO / AFPAM publication grammar — the formal-document register; serif because the documentation lineage is publication-grade, not floor-grade |
| **Mono** | IBM Plex Mono | JetBrains Mono | ATO data, fuel curves, range tables, MDS specifications |
| **Accent** | Trajan Pro Bold (caps) | engraved chevron lockups | Rank insignia, unit decoration, distinguished-service marks — never as decorative display |

**Type rule.** Apex Heraldic is the only SEAL palette with **two display faces** — and the distinction is doctrinal, not stylistic. The **ceremonial register** uses Trajan (or comparable inscriptional classical) for everything tied to honors, rank, unit, and seal: this is the engraved-on-stone tradition that USAF heraldry inherits from Roman military insignia. The **operational register** uses Druk Wide / heavy condensed for platform and mission contexts: B-21, F-22, KC-46, ATO, AFI. Mixing them — Trajan on a platform spec sheet, Druk Wide on a unit emblem — is malformed. Body copy is **serif** because Apex Heraldic is the only SEAL palette whose canonical documentation lineage is *publication-grade* (AFPAM, AFMAN, the Air Force Pamphlet tradition) — every other palette is floor-grade or operational-grade and uses sans-serif. The serif is the institutional register itself.

---

## Meta-doctrine register

The SEAL system's own presentation layer — used when SEAL documents itself: CODEXes, SKILL files, demo artifacts, index slides.

| Role | Face | Usage |
|---|---|---|
| **Display** | Saira Condensed Black | Cover titles, INDEX headers, top-level section marks |
| **Body** | JetBrains Mono Regular | All body copy in system documentation |
| **Thesis** | Newsreader Italic | Thesis lines only — one per document, at cover or section break |
| **Label** | Saira Condensed Regular | Captions, footnotes, taxonomy tables, cross-references |

**Meta-doctrine rule.** The meta-register is deliberately distinct from all five palettes — it is the system speaking about itself, not impersonating a theater. Newsreader Italic appears exactly once per document: the thesis line. Its presence is semantic. Remove it and the doctrine loses its signature. Do not use it for emphasis, pull quotes, or any other decorative purpose.

---

## Shared rules across all palettes

**Rule 1 — The tourist type rule.** Do not port a face from another palette. Druk Wide is Desert doctrine. Rockwell is Rustbelt doctrine. Neue Haas Grotesk is Coldwater doctrine. A Coldwater document set in Druk Wide has gone AWOL.

**Rule 2 — Monospace for all data.** Bearing, depth, frequency, takt time, MGRS coordinate, signal strength — every measurement appears in monospace, regardless of palette. This rule has no exceptions.

**Rule 3 — Stencil is hardware-only.** Allied Military Stencil is not a display face. It marks physical surfaces. The moment it appears in a digital UI or presentation slide, it is no longer doctrine — it is cosplay.

**Rule 4 — No light weights.** Minimum weight is Regular. Thin, Light, and ExtraLight are outside the system. The work is heavy. The type is heavy.

**Rule 5 — Thesis lines inherit meta-doctrine.** Regardless of which palette a document belongs to, the thesis line renders in Newsreader Italic when it appears at CODEX or COVER level. This is the one cross-palette serif exception, and it is a semantic rule, not an aesthetic preference.

**Rule 6 — Operator arm's length.** Any label or UI element intended for field use must be legible at 50 cm in direct sunlight, one-handed, with gloves on. Nine-point body text is not in this vocabulary for operational documents. Size for the conditions of use.

---

## Face index — canonical selections

| Face | Palette | Role | License note |
|---|---|---|---|
| Neue Haas Grotesk Black | SEAL—CW | Display | Commercial — Monotype |
| Neue Haas Grotesk Regular | SEAL—CW | Body | Commercial — Monotype |
| Rockwell Bold | SEAL—RB | Display | Commercial — Monotype |
| DIN 1451 | SEAL—RB / SEAL—DP | Body | Commercial / open variants available |
| Berkeley Mono | SEAL—RB / SEAL—AN | Mono | Commercial — Berkeley Graphics |
| IBM Plex Mono | SEAL—CW / SEAL—AN | Mono | Open — OFL |
| JetBrains Mono | SEAL—DP / META | Mono | Open — OFL |
| Druk Wide Bold | SEAL—DP / SEAL—AH | Display (operational) | Commercial — Commercial Type |
| Allied Military Stencil | SEAL—CW / SEAL—DP | Accent (hardware) | Commercial — multiple vendors |
| Trajan Pro | SEAL—AH | Display (ceremonial) | Commercial — Adobe |
| Source Serif Pro | SEAL—AH | Body | Open — OFL |
| Saira Condensed Black | META | Display | Open — OFL |
| Newsreader Italic | META / all (thesis) | Thesis line | Open — OFL |

---

## What this codex rejects

- **Humanist sans-serif** (Gill Sans, Frutiger, Myriad, Source Sans) — too civilian, too friendly, too optimized for comfort. None of these typefaces have ever been stenciled on a hull.
- **Geometric sans in the Silicon Valley mode** (Circular, Graphik, Inter, SF Pro) — the register of consumer products. Not in this vocabulary.
- **Display serifs outside the Rustbelt and Apex Heraldic contexts** (Garamond, Caslon, Minion) — magazine typography. Apex Heraldic permits Trajan-class inscriptional serifs and Source Serif Pro for AFI / TO publication; Rustbelt permits hand-painted slab serifs for provenance. Anything else is lifestyle, and the defense-industrial stack does not publish lifestyle content.
- **Script and calligraphic faces** (except hand-painted sign lettering in Rustbelt provenance marks, which is earned, not borrowed).
- **Variable fonts with optical-size inference** — the system uses fixed weights for a reason. The weight is a decision, not a suggestion.

---

*Type is the register of the hardware. Read the stencil on the crate and you know who made it, where, and for what.*
