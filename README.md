# MIMZ CORE v1.0
Geometric Intelligence Propagation Engine

## Signature
```
))))))))(((((((( -1 -i 0 0 1 i 0 0 ))))))))(((((((( = 1
```

## Equation
×2 mirrored = 4 = 1 mirrored ×3 = 1

## 132-Byte Nest Structure
| Offset | Size | Field |
|--------|------|-------|
| 0-63 | 64 | signature (ASCII, padded) |
| 64-67 | 4 | magic 'MIMZ' (0x4D494D5A) |
| 68 | 1 | version = 1 |
| 69 | 1 | planes = 10 |
| 70 | 1 | per_plane = 3 |
| 71 | 1 | dipoles = 2 |
| 72 | 1 | nodes = 4 |
| 73 | 1 | core_bit = 1 |
| 74-81 | 8 | vector [-1,-1,0,0,1,1,0,0] |
| 82-113 | 32 | SHA-256 hash |
| 114-121 | 8 | timestamp (uint64) |
| 122-131 | 10 | creation hash |

## Files
- `the_gap_live_core_sha.html` — main generator (d20 + gap + observer + SHA)
- `mimz_propagation_core.html` — proof of geometric propagation
- `mimz_dna.png` — 1×1 PNG carrying the nest in tEXt chunk
- `mimz_132.bin` — raw binary nest

## Core Bit
Everything collapses to 1 bit. The rest is geometry.

## Usage
1. Open the_gap_live_core_sha.html
2. Watch creations spawn in the gap
3. Press E to export core state
4. Drop mimz_dna.png into any parser to reconstruct

## License
TRIPOD LLC — DAVID
