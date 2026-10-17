# Generator Specification Report

**Equipment:** Honda EV6010 Generator
**Status:** Permanently mounted in MK ARC equipment trailer
**Prepared by:** Tom Sayles, KE4HET
**Date:** 2026-10-16

---

## Identification

| Field          | Value                   |
|----------------|-------------------------|
| Make / Model   | Honda EV6010            |
| Serial Number  | ECB-1021107             |
| Installation   | Permanently mounted in  |
|                | trailer (forward end)   |

---

## Electrical Output

| Field               | Value                   |
|---------------------|-------------------------|
| Rated Output        | 6,010 W (6.0 kVA)       |
| Maximum Output      | 6,500 W                 |
| AC Voltage          | 120 V / 240 V           |
| AC Frequency        | 60 Hz                   |
| AC Outlets          | 120V duplex (×2),       |
|                     | 120/240V twist-lock (×1)|

---

## Engine

| Field               | Value                   |
|---------------------|-------------------------|
| Engine Model        | Honda GX340             |
| Displacement        | 337 cc                  |
| Fuel Type           | Gasoline (unleaded)     |
| Oil Type            | SAE 10W-30              |
| Oil Capacity        | 1.1 qt (1.0 L)          |
| Spark Plug          | BPR4HS (NGK 7823)       |
| Cooling             | Air-cooled, OHV         |
| Fuel Tank Capacity  | 3.5 gal (13.0 L)        |
| Run Time @ 1/2 load | ~14 hrs                 |

---

## Physical

| Field          | Value                   |
|----------------|-------------------------|
| Dry Weight     | ~195 lbs (88.5 kg)      |
| Dimensions     | 27.5"L × 19.5"W ×      |
|                | 22.6"H (approx.)        |

> ⚠️ The generator's installed weight (~550 lbs with enclosure/box)
> counts against the trailer's GVWR. Maximum allowable cargo with the
> generator mounted is approximately **1,250 lbs**.
> See [trailer-incident-fd2026.md](../fd2026-aar/trailer-incident-fd2026.md)
> for full weight analysis.

---

## RV Installation Manual

The RV-specific variant is the **Honda EVD6010** (EVD = dealer /
RV-installed). The installation guide covering both the EV6010 and
EVD6010 is:

**EV4010/6010 · EVD4010/6010 Generator Installation Manual**
P/N: 31ZB56AH2 (©1997 American Honda Motor Co., Inc.)
[PDF — bdub.net mirror](http://www.bdub.net/manuals/Honda_EVD6010_Installation.pdf)

> Installation and pre-delivery service must be performed by an
> authorized Honda servicing dealer.

---

## Clearance Requirements

### RV Compartment — Minimum Installation Clearances

The following values are taken directly from the **CAUTION label**
affixed to the generator (EV4010/EV6010 Owner's Manual, Honda
Motor Co., Ltd., 2007):

| Direction          | Minimum Clearance       |
|--------------------|-------------------------|
| Front              | 33 mm (1.3 in)          |
| Rear               | 30 mm (1.2 in)          |
| Top                | 26 mm (1.02 in)         |
| Engine side        | 30 mm (1.2 in)          |
| Generator side     | 34 mm (1.34 in)         |

**Compartment door ventilation opening:** minimum **545 cm²
(84.5 in²)**

**Compartment sealing:** The compartment must be **completely
sealed** to prevent exhaust vapors from entering the living/working
space.

### Carbon Monoxide / Exhaust Safety

- Generator must **never** be operated in a closed or partially
  closed space where people may be present.
- Exhaust outlet must be directed away from doors, windows, and
  any occupied area.
- Placing awnings or other objects near the exhaust outlet will
  restrict ventilation and may cause CO to accumulate.

### Breaker Box Clearance

The generator box cover must maintain sufficient clearance from
the adjacent breaker box to prevent contact, heat transfer, or
interference with circuit breaker operation.

> ⚠️ **Known issue:** The generator box cover is currently warped
> and has **insufficient clearance to the breaker box**.
> The cover must be straightened or replaced before the next
> deployment. See
> [Issue #4](https://github.com/tsayles/mk-equip-trailer/issues/4).

---

## Hour Meter

| Field          | Value                              |
|----------------|------------------------------------|
| Model          | ENM 36"                            |
| Part Number    | Honda 08181-ENM-036AH              |
| Installed      | 2026-09-02 (Bryant's T&M, Renton)  |

*Note: Remote control and meter assembly (Honda 39700-ZB5-014) was
discontinued — the hour meter was installed as an alternative.*

---

## Service History

### 2026-09-02 — Full Service

**Shop:** Bryant's Tractor & Mower Inc.
501 SW 12th St, Renton WA 98057 · (425) 228-6454
**Invoice:** #346261

**Work Performed:**
- Changed engine oil and filter
- Replaced air filter element
- Replaced fuel filter (fuel line)
- Installed new spark plug (BPR4HS / NGK 7823)
- Cleaned fuel system
- Cleaned engine cooling fins
- Checked / cleaned battery & safety systems
- Installed hour meter (ENM 36")

**Cost:**

| Item             | Amount   |
|------------------|----------|
| Parts            | $151.83  |
| Labor (1.8 hrs)  | $176.40  |
| Extras           | $5.00    |
| Tax              | $34.99   |
| **Total**        | **$368.22** |

*Paid in full.*
Source document: `KE4HET/MnK-ARC/2026-09-02-MK-Generator-Invoice.PDF`

---

## Open Issues

| Issue | Description |
|-------|-------------|
| [#4](https://github.com/tsayles/mk-equip-trailer/issues/4) | Repaint/rebuild generator box — cover is warped and has insufficient clearance to the breaker box |
| [#8](https://github.com/tsayles/mk-equip-trailer/issues/8) | Generator full service record (2026-09-02) |

---

## References

- [FD 2026 AAR — Trailer Incident](../fd2026-aar/trailer-incident-fd2026.md)
- Honda EV6010 Owner's Manual
