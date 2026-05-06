# SEAL

**Brand doctrine system for defense-tech and American Dynamism, organized along the SEA / AIR / LAND operational-domain taxonomy.**

Five canonical palettes. Six document types. Eight iron rules.

> *Sea, air, land — every domain has a doctrine. Every doctrine has a look.*

---

## What this is

SEAL is a Claude skill in the AKTE mold — installable, opinionated, fixed typology, non-negotiable iron rules. It generates brand doctrine for the new defense-industrial stack: Anduril, Saronic, Shield AI, Epirus, Hadrian, Hermeus, Apex, Hidden Level, et al.

The name encodes the system's elasticity. SEAL is the canonical military framing of operational domains — sea, air, land — extended in this system by spectrum (Anechoic) and substrate (Rustbelt).

## The five palettes

| Code | Name | Domain | Cover line |
|---|---|---|---|
| `SEAL—CW` | **Coldwater Pragmatism** | USV / UUV / naval autonomy — sea | *The ocean doesn't care about your DoD rating. Build like it.* |
| `SEAL—RB` | **Rustbelt Kinetic** | Manufacturing / Arsenal / production base — industrial substrate | *The prototype is the brochure. The line is the product.* |
| `SEAL—AN` | **Anechoic Minimal** | EW / directed energy / RF / SIGINT — spectrum | *Spectrum is terrain. We hold the high ground.* |
| `SEAL—DP` | **Desert Pragmatism** | CENTCOM / Group-1/2 UAS / austere ground — land | *Build for the FOB. Everything else follows.* |
| `SEAL—AH` | **Apex Heraldic** | Air superiority / strategic strike / hypersonics — air | *Range is power. Altitude is authority.* |

## The eight iron rules

1. Mass over swagger
2. Anti-glint is doctrine
3. One protected accent per palette
4. Real units only
5. Cultural lineage required
6. Stack-aware
7. Reject the tourist palette
8. One-line thesis on the cover

Full rules in [`SKILL.md`](./SKILL.md).

## Repository layout

```
SEAL/
├── SKILL.md                          ← skill frontmatter, workflow, iron rules
├── SEAL.skill                        ← packaged skill (downloadable)
├── index.html                        ← live demo (rendered self-referential CODEX)
├── references/
│   ├── coldwater.md                  ← SEAL—CW full codex
│   ├── rustbelt.md                   ← SEAL—RB full codex
│   ├── anechoic.md                   ← SEAL—AN full codex
│   ├── desert.md                     ← SEAL—DP full codex
│   ├── apex_heraldic.md              ← SEAL—AH full codex
│   ├── typography.md                 ← per-palette type stacks
│   ├── color.md                      ← 5-value system palette per palette, hex + RAL/Pantone/FED-STD/Cerakote
│   ├── imagery.md                    ← per-palette light, atmosphere, framing
│   ├── coexistence.md                ← STACK rules (carrier-wins principle)
│   └── violations.md                 ← wrong/right specimens for each iron rule
└── examples/
    └── seal_demo.html                ← self-referential CODEX demo
```

## Install as a Claude skill

Download [`SEAL.skill`](./SEAL.skill) and install via Claude's skill registry.

## Lineage

`AKTE → DEADLIGHT → THEATER → SEAL`

Origin: the AD codex of Coldwater Pragmatism, Rustbelt Kinetic, Anechoic Minimal, and Desert Pragmatism — written in late 2025 as a doctrinal vocabulary for the new defense-industrial stack. Renamed THEATER → SEAL in May 2026 to encode the SEA/AIR/LAND operational-domain taxonomy and admit Apex Heraldic as the canonical air palette.

## Author

ANP Studio · Ebenz Augustave · NYC

## License

MIT
