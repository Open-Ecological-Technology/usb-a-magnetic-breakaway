# V 04 Bill of Materials

**Project:** BusKill USB-A Magnetic Breakaway Connector (open-source laptop kill cord)
**BOM Version:** 4
**Status:** In progress
**Last updated:** 2025-05

---

## Components & Cost

*(Unit costs are single-unit retail prices, without bulk discounts)*

| # | Component | Manufacturer | MPN | Description | QTY | Unit Cost | Subtotal | Supplier | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | USB male | *(unknown)* | *(unknown)* | Full-size USB-A male connector — spec TBD | 1 | $0.14 | $0.14 | [Amazon](https://amzn.to/43tGNuv) | Part number needed |
| 2 | USB female (10 mm) | *(unknown)* | *(unknown)* | Full-size USB-A female connector, 10 mm — spec TBD | 1 | $0.14 | $0.14 | [Amazon](https://amzn.to/43tGNuv) | Part number needed |
| 3 | Pogo receptors | Mill-Max | 3024-0-01-15-00-00-03-0 | Spring-loaded target contact, flat face, PCB mount | 4 | $0.32 | $1.28 | [Mouser](https://www.mouser.com/ProductDetail/Mill-Max/3024-0-01-15-00-00-03-0?qs=oyhNEzdnFLo7R2sYdNBgsw%3D%3D) | MOQ: 1. Price decreases with quantity; shipping required. |
| 4 | Pogo pins | Mill-Max | 7973-0-15-20-77-14-11-0 | 2.66mm spring-loaded pin, solder cup, through-hole | 4 | $1.13 / $1.27 | $4.52 / $5.08 | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/7973-0-15-20-77-14-11-0/10197225) / [Mouser](https://www.mouser.com/ProductDetail/Mill-Max/7973-0-15-20-77-14-11-0?qs=%252B6g0mu59x7KQy9JOdoVaiw%3D%3D) | MOQ: 1. Price decreases with quantity; shipping required. |
| 5 | 3D printed release | *(in-house)* | — | PLA, printed from STL | 1 | — | — | `Goldfishlaser Version/CAD Files/intermediary design files/usbamagb_v04.0.stl` | Material: PLA. Print settings (infill %, layer height) TBD. Combined plastic cost for items 5–6: $8.76 (13.76g / 4.61m filament) |
| 6 | 3D printed breakaway | *(in-house)* | — | PLA, printed from STL | 1 | — | — | `Goldfishlaser Version/CAD Files/intermediary design files/usbamagb_v04.0.stl` | See item 5 for combined cost. |
| 7 | 1/8" cube magnets | K&J Magnetics | B222 | N52 neodymium, 1/8" cube | 8 | $0.18 | $1.44 | [KJ Magnetics](https://www.kjmagnetics.com/proddetail.asp?prod=B222) | MOQ: 1. N52 gold plated variant may perform better. Pull force and operating temp spec TBD. |
| 8 | USB extension cord | *(unknown)* | *(unknown)* | Spec TBD | 1 | $8.00 | $8.00 | *(unknown)* | Supplier and part number needed |
| 9 | Carabiner | *(unknown)* | *(unknown)* | Small keychain-style, anodized aluminum | 1 | $0.80 | $0.80 | *(unknown)* | Retail estimate; bulk pricing ~$0.46/unit (Alibaba). Supplier TBD. |

### Estimated Total Per Unit

| Path | Total |
| --- | --- |
| Digikey (pogo pins) | **$24.32** |
| Mouser (pogo pins) | **$24.88** |

*(Excludes 3D printing cost, which is rolled into plastic line above. Does not include shipping.)*

---

## Alternative & Legacy Vendors

### Pogo Pins

| Prototype Version | Type | MPN | Price/pin | MOQ | Link |
| --- | --- | --- | --- | --- | --- |
| >= v.2.3.9 (current) | 2.66mm spring-loaded, solder cup | Mill-Max 7973-0-15-20-77-14-11-0 | $1.13 (Digikey) / $1.27 (Mouser) | 1 | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/7973-0-15-20-77-14-11-0/10197225) / [Mouser](https://www.mouser.com/ProductDetail/Mill-Max/7973-0-15-20-77-14-11-0?qs=%252B6g0mu59x7KQy9JOdoVaiw%3D%3D) |
| =< v.2.3.8 (legacy) | 7.58mm spring-loaded, solder cup | Mill-Max 0947-0-15-20-77-14-11-0 | $0.97 | 1 | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/0947-0-15-20-77-14-11-0/7402798) |
| =< v3.9 (legacy) | 3.00mm radius contact pad, 2.00mm height | *(unknown)* | $0.07 | 500 | [Alibaba](https://www.alibaba.com/product-detail/Circular-SMD-Contact-Pad-3-0_62437659039.html) |

### Magnets

**Cube magnets (1/8") — current form factor**

| Prototype Version | Vendor | MPN | Price/magnet | MOQ | Notes | Link |
| --- | --- | --- | --- | --- | --- | --- |
| >= v.3 (current) | K&J Magnetics | B222 | $0.18 | 1 | N52; gold plated variant may be better | [B222](https://www.kjmagnetics.com/proddetail.asp?prod=B222) |
| v.1 (legacy) | Dongguan Hj Tech Co., Ltd. | *(unknown)* | $0.03 | 1000* | Custom shapes. *Vendor accommodated sub-MOQ orders. | [Alibaba](https://www.alibaba.com/product-detail/Hot-Sale-Strong-Electric-Custom-Shape_62489784248.html) |

**Hex magnets — alternative form factor, not used in v4**

| Vendor | Price/magnet | MOQ | Link |
| --- | --- | --- | --- |
| Skyup Magnetics (Ningbo) Co., Ltd. | $0.02–$0.60 | 1 | [Alibaba](https://www.alibaba.com/product-detail/12-Years-Experience-factory-producing-rare_62153270553.html) |
| Xiamen Balin Magnetic Materials Co., Ltd. | $0.05–$0.50 | 1 | [Alibaba](https://www.alibaba.com/product-detail/Powerful-rare-earth-hexagon-neodymium-magnet_62113152666.html) |
| Hangzhou Shengshideng Magnetics Co., Ltd. | $1.00–$10.00 | 1 | [Alibaba](https://www.alibaba.com/product-detail/14-Years-Experience-factory-producing-neodymium_60745639237.html) |

**Disc magnets — ⚠️ DO NOT USE (too weak)**

| Prototype Version | Vendor | Size | Grade | Price/magnet | MOQ | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| =< v.2.3.8 | MANHXSCY | 4×3mm | N35 | $0.08 | 100 | URL no longer active. |
| Not used | MANHXSCY | 5×4mm | N35 | $0.175 | 50 | URL no longer active. |
| — | K&J Magnetics | 1/16" dia. × 1/32" thick | N52 | $0.14 | 100 | [D101-N52](https://www.kjmagnetics.com/proddetail.asp?prod=D101-N52) |