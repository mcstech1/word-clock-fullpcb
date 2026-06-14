# Bill of materials & build cost

Two "BOMs" live in this project

1. **`pcb/assembly/BOM_jlcpcb.xlsx` + `CPL_jlcpcb.xlsx`** — the files you
   upload to **JLCPCB** for PCB assembly. Leave them as-is.
2. **This page** — the cost of the *complete* clock for someone rebuilding it.

Prices are real sourced parts (~mid-2026, incl. VAT — they fluctuate). PCB/assembly prices are
from the last JLCPCB order.

## Full build cost

Most parts are bought in **packs** (a 10-pack of LDRs, a box of screws, a 1 kg spool…) but one
clock only uses a fraction. The **share** column = the share of the pack one clock consumes, and
**€/clock = share × pack price**.

| # | Item | Buy as (pack) | Pack price | Used /clock | **share** | **€/clock** |
|---|------|---------------|-----------:|------------:|----------:|------------:|
| 1 | **PCB + SMT assembly** (JLCPCB merchandise) | 5 boards | €298.13 | 1 board | 1/5 = 20 % | **€59.63** |
| 2 | **Shipping**| per order (5 boards) | €60.12 | — | 1/5 = 20 % | **€12.02** |
| 3 | **5 V / 6 A power adapter, EU** — [AliExpress](https://de.aliexpress.com/item/4000443793258.html) | 1 pc | €5.39 | 1 | 100 % | **€5.39** |
| 4 | **DC barrel jack / pigtail** 5.5×2.5 mm 90°, 30 cm — [AliExpress](https://de.aliexpress.com/item/1005009842534963.html) | 5-pc pack | €5.29 | 1 | 1/5 = 20 % | **€1.06** |
| 5 | **Neodymium magnets** N35 10×5 mm — [AliExpress](https://de.aliexpress.com/item/1005010158024883.html) | 60-pc pack | €9.59 | 10 | 10/60 = 17 % | **€1.60** |
| 6 | **Diffuser film** — [AliExpress](https://de.aliexpress.com/item/1005007519292019.html) | roll 40 × 300 cm | €5.59 | ~40 × 45 cm | ~15 % | **~€0.84** |
| 7 | **LDR** GL5528 (5 mm) — [eBay](https://www.ebay.de/itm/122233227066) | 10-pack | €3.49 | 1 | 1/10 = 10 % | **€0.35** |
| 8 | **Screws** M2.5 × 10 mm | box ~200 | ~€10.00 | 12 | 12/200 = 6 % | **~€0.60** |
| 9 | **ABS filament** — main body | 1 kg spool | ~€20.00 | 317 m ≈ 0.80 kg | 80 % | **~€16.00** |
| 10 | **PLA filament** — back plate | 1 kg spool | ~€20.00 | 140 m ≈ 0.42 kg | 42 % | **~€8.40** |
| — | _CNC alternative to #9 + #10_ | block PE | €__ | 1 | — | €__ |
| | | | | | **Total:** | **≈ €106** |

(Per-clock subtotal of the small parts #3–8: PSU €5.39 + jack €1.06 + magnets €1.44 + film €0.84 + LDR €0.35 + screws €0.60 ≈ **€9.7**. The wall mount is printed as part of the housing.)
