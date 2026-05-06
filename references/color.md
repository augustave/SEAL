# SEAL — Color Codex

**Code:** `SEAL—CL`
**Status:** Canon
**Governs:** All six document types across all four palettes
**Version:** 1.2 (verified — WCAG-checked, hardware specs audited)

---

## System premise

Each palette declares five system colors, an extended palette, and hardware-grade specifications. The five system roles are the minimum needed to build any document. The extended colors are descriptive variants from the codex entries. The hardware specs (RAL, Pantone, FED-STD 595, Cerakote) exist because this brand lands on physical objects, and the painter does not work in hex.

The five system roles, in order:

1. **Ground.** The darkest backdrop. Carries the palette's thermal signature — cold for Coldwater, warm-carbon for Rustbelt, absent for Anechoic, warm-red for Desert.
2. **Surface.** The container layer — panels, cards, dividers — slightly lifted from Ground. Adds depth without breaking the field.
3. **Signature.** The mid-tone that identifies the theater across the room. Haze grey is Coldwater. Bridgeport green is Rustbelt. Mu-metal silver is Anechoic. FDE is Desert. This color carries the most narrative weight after the accent.
4. **Text.** The primary readable type color — calibrated off-white per palette, never pure white.
5. **Accent.** The single protected semantic color. Alert, signal, ID, completion. Never decoration.

Three constraints govern the entire system:

1. **One protected accent per palette.** Semantic only. Never used at more than ~3% of any composition. No headlines. No backgrounds.
2. **Anti-glint is doctrine.** Flat application. No gradients. No bevels. No gloss. The only permitted sheen is environmental — light on water, glass, raw metal.
3. **Hardware specs are first-class.** Hex is for screen. RAL / Cerakote / FED-STD specs are for hardware. A brand that cannot be painted on the chassis is not a defense brand.

---

## Composition ratios

Used as a default for any single-palette composition. STACK documents that combine palettes obey separate rules (see Cross-palette rules below).

| Role | Coverage | Rationale |
|---|---|---|
| Ground | 40–55% | The base. Largest single area in any composition. |
| Signature | 25–35% | The theater identifier. Dominant after Ground. |
| Surface | 10–20% | Panels and containers. Lifts depth. |
| Text | 5–15% | Variable by content density. |
| Accent | < 3% | One element per layout. Semantic, not aesthetic. |

---

## Per-palette color systems

### SEAL—CW · Coldwater Pragmatism

**System palette**

| Role | Name | Hex | Hardware spec | Reference |
|---|---|---|---|---|
| **Ground** | Anechoic Hull | `#0E1014` | RAL 9005 / FED-STD 37038 | Flat light-absorbing SSN hull and UUV skin coating |
| **Surface** | Trench Navy | `#1A2733` | FED-STD 35042 (Sea Blue) | Deep cold-water blue-black; secondary panel layer |
| **Signature** | Haze Grey 5-H | `#7A828A` | FED-STD 26270 / Pantone Cool Gray 9 C | USN 5-H topside signature; the mid-tone that says *destroyer* |
| **Text** | Overcast White | `#D6DCE0` | Pantone Cool Gray 1 C | High-latitude daylight; cool, never pure |
| **Accent** | Safety Orange | `#FF4F00` | FED-STD 12473 / Pantone 165 C / RAL 2009 | USCG / survival gear / flotation; emergency state only |

**Extended palette**

| Name | Hex | Hardware spec | Usage |
|---|---|---|---|
| North Atlantic Grey | `#9EA8AE` | FED-STD 36320 | Secondary text, dividers, muted UI chrome |
| Zinc-Primer Seafoam | `#7A8E82` | RAL 6021 (approx) | Background variant — the green-grey under chipped paint |

**Coldwater rule.** The palette is cold. No warmth enters except the accent — and the accent's permitted context is emergency. If a Coldwater composition reads warm, FDE or cosmoline has contaminated it; correct it.

---

### SEAL—RB · Rustbelt Kinetic

**System palette**

| Role | Name | Hex | Hardware spec | Reference |
|---|---|---|---|---|
| **Ground** | Forged Iron | `#1F1B17` | RAL 9011 (Graphite Black) | Warm gunmetal with carbon — not true black, not cool |
| **Surface** | Oxide Primer | `#5C3A28` | RAL 3009 / FED-STD 30117 | Zinc-chromate primer red-brown; the surface before the topcoat |
| **Signature** | Bridgeport Green | `#4D5A45` | RAL 6011 (Reseda Green, approx) | 1950s Bridgeport / South Bend / Monarch lathe color — institutional cast-iron green |
| **Text** | Cosmoline Cream | `#DACDA8` | Pantone 7527 C | Preserved-steel off-white, warm |
| **Accent** | MIG Arc-Blue | `#7AB5FF` | Pantone 2915 C (approx) | 6500K spark-spatter with violet undertone; reserved for unit-complete states, manufacture flash |

**Extended palette**

| Name | Hex | Hardware spec | Usage |
|---|---|---|---|
| Safety Yellow | `#F5C518` | FED-STD 13538 / Pantone 109 C / RAL 1023 | OSHA forklift / hazard stripe / bollard — secondary alert, not the protected accent |
| Concrete Grey | `#7A7269` | RAL 7037 | Floor-tone background variant |
| Cosmoline Dark | `#8A7E60` | Pantone 7503 C | Muted text variant for secondary copy |

**Rustbelt rule.** Bridgeport Green is earned. It must read as a working machine tool, not a brand wash. Forged Iron and Cosmoline Cream carry the warmth — there is carbon in this palette and the carbon is non-negotiable. Safety Yellow is a secondary alert; in any hierarchy conflict, MIG Arc-Blue wins.

---

### SEAL—AN · Anechoic Minimal

**System palette**

| Role | Name | Hex | Hardware spec | Reference |
|---|---|---|---|---|
| **Ground** | Anechoic Void | `#0A0A0A` | RAL 9005 / Cerakote H-146 (Graphite Black) | True absence; the chamber, not "dark mode" |
| **Surface** | Rack Black | `#16191D` | Pantone Black 6 C | Equipment chassis black; cool, slightly lifted from Ground |
| **Signature** | Mu-Metal | `#525861` | Pantone Cool Gray 10 C | Magnetic shielding silver-grey; blue-grey, never warm |
| **Text** | Trace Idle | `#C0CACC` | Pantone Cool Gray 3 C | CRT at rest; cool, faint green undertone |
| **Accent** | P31 Phosphor | `#3CFF7A` | Pantone 802 C (approx) | CRT oscilloscope trace, ~525 nm green; reserved for active signal, live data, confirmed lock |

**Restricted secondaries** — semantic-only, never decorative:

| Name | Hex | Hardware spec | Permitted context |
|---|---|---|---|
| TEMPEST Red | `#9D0000` | Pantone 7621 C | Unencrypted / classified-side data paths under red/black separation doctrine |
| Keysight Cobalt | `#1A4F8C` | Pantone 7693 C | Instrumentation chrome — VNA / spectrum analyzer panel references |

**Anechoic rule.** The Ground is not dark mode. Dark mode warms its blacks and softens its surfaces; the Void rejects both. P31 Phosphor appears on one element per frame — the live trace, the active state. The two restricted secondaries appear only in documents addressing TEMPEST or instrumentation contexts; they have no role in general brand application.

---

### SEAL—DP · Desert Pragmatism

**System palette**

| Role | Name | Hex | Hardware spec | Reference |
|---|---|---|---|---|
| **Ground** | IR Blackout | `#1B1714` | Cerakote H-146 (NIR-suppressed) | Warm near-black; carbon with red undertone |
| **Surface** | Coyote Dark | `#3D3327` | Cerakote H-235 (Coyote Tan, deepened) | Panel and container layer; deeper than FDE |
| **Signature** | Flat Dark Earth | `#9F8A6E` | Cerakote H-265 / Magpul FDE / Anduril Sentry tone | The CENTCOM signature; lighter than commonly rendered |
| **Text** | Bone | `#E5D9B4` | Pantone 7527 C | Sun-bleached off-white; readable on FDE and Coyote at arm's length in direct sun |
| **Accent** | VS-17 Cerise | `#E5004C` | Pantone 199 C / closest RAL 3027 | Ground-to-air recognition panel cerise side; also Anduril sabre red lineage |

**Extended palette**

| Name | Hex | Hardware spec | Usage |
|---|---|---|---|
| Coyote Brown 498 | `#81715D` | Pantone 7503 C / Cerakote H-235 | Mid-tone variant; transition between FDE and Surface |
| Ranger Green | `#4A5440` | Pantone 5605 C / Cerakote H-238 (Sniper Green) | Subdued vegetation tone; INDOPACOM / AFRICOM contexts |
| Khaki | `#A89060` | Pantone 7503 C | Daylight-washed field variant |

**Desert rule.** Saturation is forbidden except at the accent. Every non-accent color from Ground to Text falls within the desaturated brown band. VS-17 Cerise is not interchangeable with Coldwater's Safety Orange — the protocol is ground-to-air recognition, not maritime survival; the hue is red-pink, not red-orange; using one in the other's theater violates the tourist palette rule.

---

### SEAL—AH · Apex Heraldic

**System palette**

| Role | Name | Hex | Hardware spec | Reference |
|---|---|---|---|---|
| **Ground** | Old Glory Blue | `#0A2240` | Pantone 282 C / FED-STD 35044 | The deepest USAF ceremonial blue; flag heraldry, formal seal, parade grammar |
| **Surface** | Strategic Steel | `#243348` | Pantone 539 C (approx) | Between Old Glory and Air Force Blue; uniform-blue chrome, panel layer |
| **Signature** | Air Force Blue | `#5C7A99` | Pantone 5395 C | The canonical institutional USAF blue; the chevron color, the wing-emblem color |
| **Text** | Service White | `#EDE9DC` | Pantone 7527 C (warm) | Starched dress-shirt off-white; slight cream, formal register |
| **Accent** | Heraldic Gold | `#E0AA0F` | Pantone 7406 C / FED-STD 13591 | Air Force gold; rank insignia, unit decoration, distinguished service, the chevron — never a logo color |

**Restricted secondary** — semantic-only, never decorative:

| Name | Hex | Hardware spec | Permitted context |
|---|---|---|---|
| Old Glory Red | `#BF0A30` | Pantone 193 C | Combat decoration, valor citation, campaign-ribbon red bars only — never as a wash, never as a brand color |

**Extended palette**

| Name | Hex | Hardware spec | Usage |
|---|---|---|---|
| Stratospheric Cyan | `#4F8FCC` | Pantone 285 C | Bright-sky blue from the ribbon rack; high-altitude UI accents, range-ring renders |
| Carbon Black | `#0E0E10` | Cerakote H-146 / RAM coating | Strike-platform finish — B-2, B-21, F-22 RAM; restricted to operational contexts, never ceremonial |
| Service Cream | `#F5EFDD` | Pantone 7527 C (lighter) | Document-paper variant; formal-publication ground for AFI / TO layouts |

**Apex Heraldic rule.** Two registers must coexist without blurring: the **dress register** (polished, ceremonial, Heraldic Gold present, Old Glory Blue ground, Service White type) and the **operational register** (matte, anti-glint, Carbon Black accents, no gold, range-ring graphics). A B-21 in chrome render is malformed. A class-A wool jacket in matte finish is malformed. The brand carries both. Heraldic Gold is the protected accent for **identity and decoration only** — rank, unit, campaign citation, distinguished service. It never appears on a button, a CTA, or a logo treatment. Old Glory Red is restricted to combat-decoration contexts (the red stripe in a campaign ribbon, the Distinguished Flying Cross ribbon, valor citations) — a brand piece using Old Glory Red as a wash is malformed.

---

## Accent index — the five protected accents

| Palette | Accent | Hex | Hardware spec | Protocol | Never |
|---|---|---|---|---|---|
| SEAL—CW | Safety Orange | `#FF4F00` | FED-STD 12473 / Pantone 165 C / RAL 2009 | Maritime survival, flotation, emergency state | Decoration, headline, background fill |
| SEAL—RB | MIG Arc-Blue | `#7AB5FF` | Pantone 2915 C (approx) | Unit-complete state, manufacture flash, line running | Background wash, secondary text, idle state |
| SEAL—AN | P31 Phosphor | `#3CFF7A` | Pantone 802 C (approx) | Active signal, live trace, confirmed lock | Any context where signal is not present |
| SEAL—DP | VS-17 Cerise | `#E5004C` | Pantone 199 C / closest RAL 3027 | Friendly ID, ground-to-air marker, IFF state | Decoration, section heading, background |
| SEAL—AH | Heraldic Gold | `#E0AA0F` | Pantone 7406 C / FED-STD 13591 | Rank, unit decoration, distinguished service, chevron | Logo color, button, CTA, decorative wash |

**Cross-accent rule.** The five accents are semantically incompatible. Safety Orange means *something has gone wrong or someone needs to live*. Arc-Blue means *a unit just got made*. P31 Phosphor means *a signal is active*. VS-17 Cerise means *a friendly is marked*. Heraldic Gold means *this unit / individual / campaign earned it*. Swapping accents does not break aesthetics — it breaks the doctrine. A Desert document with Arc-Blue on a unit counter is not a style error. It is a category error. An Apex Heraldic deck with Heraldic Gold on a CTA button is not a style error — it is the doctrinal equivalent of pinning a Distinguished Flying Cross to a t-shirt.

---

## Contrast and legibility rules

These rules close the contrast gaps verified in v1.2 against WCAG 2.1 AA.

1. **Text appears on Ground or Surface only.** Text on Signature fails contrast in four of five palettes (CW 2.82:1, AN 4.29:1, DP 2.35:1, AH 3.68:1). Body copy never sits on Haze Grey, Mu-Metal, FDE, or Air Force Blue — those surfaces are for hardware, illustration, or color blocks, not type.

2. **Accent at minimum 18 pt for type.** VS-17 Cerise on IR Blackout reads 3.76:1 — sufficient for large type, insufficient for body. P31 Phosphor on Signature reads 5.39:1 — body-safe. Coldwater Safety Orange on Ground reads 5.78:1 — body-safe. Heraldic Gold on Old Glory Blue reads 7.54:1 — body-safe. Default rule: accent-as-type at headline weight only unless Ground-pair contrast clears 4.5:1.

3. **Accent never on Surface in DP.** VS-17 Cerise on Coyote Dark reads 2.61:1 — fails at all sizes. Place VS-17 marks on Ground or directly on Bone, not on the Surface layer.

4. **Heraldic Gold never on Signature in AH.** Heraldic Gold on Air Force Blue reads 2.11:1 — fails at all sizes. Gold accent appears on Old Glory Blue (Ground, 7.54:1) or Strategic Steel (Surface, 6.04:1), never on the Signature surface.

5. **Verified contrast pairs (palette → safe combinations):**
    - **CW** — Text on Ground (13.76:1), Text on Surface (10.98:1), Accent on Ground (5.78:1), Accent on Surface (4.61:1).
    - **RB** — All combinations AA or better. Text on Signature passes (4.64:1).
    - **AN** — Text on Ground (11.84:1), Text on Surface (10.55:1), Accent on Ground (14.87:1).
    - **DP** — Text on Ground (12.65:1), Text on Surface (8.77:1), Accent on Ground at 18 pt+ (3.76:1).
    - **AH** — Text on Ground (13.14:1), Text on Surface (10.53:1), Accent on Ground (7.54:1), Accent on Surface (6.04:1).

---

## Cross-palette rules

1. **No palette borrows another's signature color.** FDE does not appear in a Coldwater document. Mu-Metal does not appear in a Desert document. Bridgeport Green does not appear in an Anechoic document. These are theater boundaries, not aesthetic preferences.

2. **STACK documents declare their stacking.** A document that combines two or more palettes must be explicitly typed as STACK and must show the stack relationship — which palette carries which payload. Two accents in one composition without a STACK declaration is malformed.

3. **Light-mode is not in this system.** All five palettes ground in dark colors because the operational context is dark — submarine interiors, factory third shifts, SCIFs, FOBs at 0300, AOCs at night. A "light-mode Coldwater" is a print-on-paper exception, not a system variant. The single permitted exception is Apex Heraldic's **dress register** — formal AFI / TO publications and ceremonial documents may use Service Cream as ground, with Old Glory Blue type, Heraldic Gold for decoration. The dress register is the only light-mode pattern that is doctrinally legitimate.

4. **The accent is never the headline.** No protected accent ever appears as the primary color of headline type. Headlines render in Text or Signature. The accent's job is to mark, not to lead.

---

## What this system rejects

- **Gradients, beveling, gloss.** Flat color only. Anti-glint is doctrine.
- **Pastels and desaturated accents.** The accent must carry signal strength. A muted VS-17 Cerise is no longer VS-17 Cerise — it is pink. Pink is not in this vocabulary.
- **Pure white text.** Every palette specifies a calibrated off-white. `#FFFFFF` reads as a screen artifact, not a deliberate choice.
- **Saturation creep.** Coldwater stays cold. Desert stays desaturated brown. Anechoic stays absent. Rustbelt stays warm-iron. Drift toward saturation in any non-accent role is contamination.
- **Hex-only specification.** Any deliverable that will reach hardware must include the RAL or Cerakote spec. A coater cannot work from `#9F8A6E`. They can work from H-265.

---

*Color is the first signal. Read it wrong and you're in the wrong theater.*
