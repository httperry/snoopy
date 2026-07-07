[← Back to Root](https://github.com/httperry/snoopy)

# Bill of Materials

**Snoopy** — 3-Port Ethernet Switch with CM4 Monitoring
Last Updated: 2026-07-06 · REV 1.0

> This BOM reflects the current schematic revision. Quantities are per board unless otherwise noted. All passives are sourced from LCSC

---

## Core Compute

| Component | Source | Qty | Product Link |
|---|---|---|---|
| Raspberry Pi CM4 | Raspberry Pi | 1 | [raspberrypi.com](https://www.raspberrypi.com/products/compute-module-4/) |
| DF40C-100DS-0.4V(51) CM4 Board-to-Board Connector | LCSC | 2 | [lcsc.com](https://www.lcsc.com/product-detail/Board-to-Board-Connectors_HRS_C597931.html) |

---

## Networking

*Source: [Schematics/Ethernet Connections](./Schematics/Ethernet%20Connections/README.md)*

| Component | Source | Qty | Product Link |
|---|---|---|---|
| RTL8367S-CG 3-Port GbE Switch IC | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Ethernet-ICs_REALTEK-RTL8367S-CG_C2760849.html) |
| JT7-1119NL Integrated MagJack (GbE RJ45) | LCSC | 2 | [lcsc.com](https://www.lcsc.com/product-detail/Ethernet-Connectors_PULSE-JT7-1119NL_C3178801.html) |
| SMTWEM2515STR Ethernet Pulse Transformer | LCSC | 4 | [lcsc.com](https://www.lcsc.com/product-detail/LAN-Transformers_YIYUAN-SMTWEM2515STR_C5301785.html) |
| TAXM25M4RLBCCT2T 25MHz Crystal | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Crystals_YJX-TAXM25M4RLBCCT2T_C164045.html) |

---

## Power Management

*Source: [Schematics/PWR Management](./Schematics/PWR%20Management/README.md)*

| Component | Source | Qty | Product Link |
|---|---|---|---|
| TPS54360DDAR 60V 3.5A Buck Converter | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/DC-DC-Converters_TI_C44377.html) |
| SY8089A1AAC 3A Synchronous Buck Regulator | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/DC-DC-Converters_Silergy_C479074.html) |
| TPS2378DDAR PoE PD Controller | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Power-Management-ICs_TI_C337500.html) |
| LM66100DCKR Ideal Diode Controller | LCSC | 2 | [lcsc.com](https://www.lcsc.com/product-detail/PMIC-Gate-Drivers_TI_C2869734.html) |
| USBLC6-2SC6 USB ESD Protection | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/ESD-and-Surge-Protection_TECH-PUBLIC_C2827654.html) |
| MB10S Bridge Rectifier | LCSC | 2 | [lcsc.com](https://www.lcsc.com/product-detail/Rectifier-Diodes_Huixin_C49435626.html) |
| SS510 Schottky Diode | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Schottky-Diodes_Slkor_C513471.html) |
| MK-12C03-G015 Power Switch | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Slide-Switches_G-Switch_C2890358.html) |
| TYPE-C-31-M-12 USB-C Connector | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/USB-Connectors_C165948.html) |
| ZEMS16086S-2R2M 2.2µH Inductor | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Inductors_ZE_C48945029.html) |
| YSPI0630A-220M 22µH Inductor | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Inductors_YJYCOIN_C497873.html) |
| FTC201610S2R2MBCA 2.2µH Inductor | LCSC | 1 | [lcsc.com](https://www.lcsc.com/product-detail/Inductors_cjiang_C58323440.html) |

---

## Passives — Capacitors

| Value | Footprint | Qty | Manufacturer P/N | Source | LCSC # |
|---|---|---|---|---|---|
| 100nF | C0402 | 29 | AC0402KRX7R9BB104 | YAGEO | C288326 |
| 10µF | C0603 | 4 | HGC0603R5106M250NTHJ | Chinocera | C747296 |
| 18pF | C0402 | 2 | GRM1555C1H180JA01D | muRata | C33149 |
| 100nF | C0402 | 1 | CC0402KRX5R8BB104 | YAGEO | C106256 |
| 1nF | C0402 | 2 | CC0402KRX7R8BB102 | YAGEO | C541372 |
| 100nF | C0603 | 2 | GCJ188R72A104KA01D | muRata | C161117 |
| 4.7µF | C1206 | 1 | GRM31CC72A475KE11L | muRata | C237304 |
| 3.3nF | C0402 | 1 | CC0402KRX7R9BB332 | YAGEO | C107028 |
| 22µF | C0603 | 2 | CL10A226MP8NUNE | SAMSUNG | C86295 |
| 22µF | C0402 | 1 | HGC0402R52226M100NTEJ | Chinocera | C22367823 |

---

## Passives — Resistors

| Value | Footprint | Qty | Manufacturer P/N | Source | LCSC # |
|---|---|---|---|---|---|
| 2.49kΩ | R0402 | 1 | FRC0402F2491TS | FOJAN | C2933083 |
| 4.7kΩ | R0402 | 9 | CRCW04024K70FKED | VISHAY | C482193 |
| 470Ω | R0402 | 4 | FRC0402F4700TS | FOJAN | C2909361 |
| 5.1kΩ | R0603 | 2 | RMC06035.1K5%N | Tyohm | C269696 |
| 63.4Ω | R0603 | 1 | PTFR0603B63R4P9 | RESI | C47115900 |
| 200kΩ | R0402 | 1 | ARG02BTC2003 | Viking | C298414 |
| 1MΩ | R0805 | 1 | AR05BTC1004 | Viking | C374666 |
| 24.9kΩ | R0603 | 1 | PTFR0603B24K9N9 | RESI | C2692729 |
| 100kΩ | R0402 | 2 | RT0402BRD07100KL | YAGEO | C852472 |
| 19.1kΩ | R0402 | 1 | FRC0402F1912TS | FOJAN | C2998158 |
| 18kΩ | R0402 | 1 | AECR0402F18K0K9 | RESI | C352468 |
| 22.1kΩ | R0402 | 1 | CRCW040222K1FKED | VISHAY | C844504 |
