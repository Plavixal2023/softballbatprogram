# Floral-Scented Youth Softball Bat Grip  
**File:** `manufacturing/floral-grip-manufacturing-process.md`  
**Revision:** 1.0  **Date:** 2025-07-04  

---

## 1 Materials List & Preferred Suppliers  

| # | Material | Grade / Spec | Typical Qty per Grip | Preferred Supplier* | Alt. Supplier |
|---|----------|--------------|----------------------|---------------------|---------------|
| 1 | Thermoplastic Elastomer (TPE) base resin | Shore A 60, medical-grade, food-contact compliant | 42 g | BASF “Elastollan 1185A” | RTP Company TPE 2560-A |
| 2 | Floral Micro-capsules (lavender) | 5–8 µm urea-formaldehyde shell, 45 % wt lavender oil | 0.60 g | MicroFragrance Inc. “Lavacap-45” | Encapsys LLC |
| 3 | Floral Micro-capsules (rose) | 5–8 µm urea-formaldehyde shell, 45 % wt rose oil | 0.60 g | MicroFragrance Inc. “Rosacap-45” | Encapsys LLC |
| 4 | Gradient Color Masterbatch (pink) | Pantone 707 C compatible, heat-stable | 0.80 g | Clariant ColorWorks | Ampacet |
| 5 | Gradient Color Masterbatch (purple) | Pantone 2582 C compatible, heat-stable | 0.80 g | Clariant ColorWorks | Ampacet |
| 6 | Odour Fixative | Cyclodextrin USP-grade | 0.20 g | Wacker Chemie | SPI Pharma |
| 7 | Solvent Blend (in-mold painting) | Ethyl acetate / IPA 70 : 30 | 2 mL / grip | Sigma-Aldrich | VWR |

\*All suppliers comply with REACH, CPSIA, and IFRA standards.

---

## 2 Scent Micro-Encapsulation Process  

1. **Oil Phase Prep**  
   • Mix essential oil (lavender / rose) with 3 % antioxidant BHT.  
2. **Emulsion Polymerisation**  
   • Aqueous phase: 30 % urea, 2 % resorcinol, pH 8.5.  
   • Shear: 12 000 rpm, 20 min → droplet size ~6 µm.  
3. **Shell Formation**  
   • Add 37 % formaldehyde, maintain 55 °C for 3 h while stirring at 300 rpm.  
4. **Cure & Wash**  
   • Raise to 75 °C for 1 h to harden shells.  
   • Filter 1 µm, rinse to conductivity ≤50 µS/cm.  
5. **Drying**  
   • Fluid-bed 45 °C until moisture <2 %.  
6. **Quality Metrics**  
   • Encapsulation efficiency ≥92 %.  
   • Mean diameter 5-8 µm (laser diffraction).  

---

## 3 Injection-Molding Parameters (Over-Mold on Carbon Handle)  

| Zone | Temp (°C) | Notes |
|------|-----------|-------|
| Feed | 40 | Avoid premature melt |
| Barrel 1 | 160 | Initial melt |
| Barrel 2 | 175 | Pigment dispersion |
| Barrel 3 | 185 | Capsule dispersion (hold <190 °C) |
| Nozzle | 180 | Prevent drool |
| Mold | 35 ±2 | Promote surface finish |

Process set-up:  
* Screw speed 60 rpm • Back pressure 4 bar  
* Injection speed 70 mm/s (stage 1), 30 mm/s (stage 2)  
* Peak injection pressure 950 bar; hold 550 bar 6 s  
* Cooling 14 s; total cycle 28 s  

Capsules dosed via side-feeder at 2.8 wt % during last 30 % of screw travel to minimise shear rupture (loss ≤ 3 %).

---

## 4 Texture Pattern Tooling Specifications  

| Feature | Spec |
|---------|------|
| Pattern Motif | 5-petal flower, 8 mm repeat, angular offset 15°/row |
| Ridge Height | 3.0 ± 0.1 mm |
| Valley Width | 2.2 ± 0.1 mm |
| Surface Finish | Ra ≤ 0.4 µm on ridge tops; Ra 1.2 µm in valleys |
| Tooling Method | EDM + laser etch for fine petal veins |
| Steel | H-13, 48 HRC, chrome-nitride coated |

Draft angle 1.5° to ensure release of deep petals without drag marks.

---

## 5 Quality Control – Scent Longevity  

| Test | Method | Acceptance |
|------|--------|------------|
| Capsule Integrity | SEM imaging, 50× sample | ≥95 % intact |
| Fragrance Retention | GC-MS after 5 k tumble swings @ 40 °C | ≥90 % initial peak area |
| Odour Panel | 20-person blind sniff, ASTM E544 | Median score ≥3/5 after 3 months |
| Abrasion | Taber CS-17, 500 cycles | Weight loss <0.4 g |

Failures are quarantined; root-cause logged in CAPA system.

---

## 6 Color Gradient Application  

1. **Dual-Masterbatch Co-Feed**  
   • Zone mixing screw with 60 % pink, 40 % purple base.  
   • Color shift controlled by time-based feeder program (change rate 0.8 %/s).  
2. **In-Mold Painting (Optional Enhancement)**  
   • Robot sprays 15 µm translucent pearl layer using solvent blend (#7).  
   • Flash-off 8 s; UV cure 30 s @ 365 nm to lock gradient.  
   • Final gloss ≥70 GU; ΔE color tolerance ≤1.5.

---

## 7 Assembly Instructions  

1. **Prep Handle** – Wipe carbon handle with IPA; roughen 400 grit 50 mm from knob.  
2. **Primer Tape** – Apply 0.2 mm double-sided PE tape spiral, 5 mm pitch.  
3. **Grip Over-Mold** – Position handle core in mold, ensuring 3 mm gap at knob.  
4. **Molding Cycle** – Run parameters (Section 3). Vent at petal valleys.  
5. **Trimming** – De-flash gate at mid-seam; inspect 360°.  
6. **Post-Cure** – 50 °C oven 1 h to stabilise scent distribution.  
7. **Serial Laser Mark** – Etch batch/date underside of grip (0.1 mm depth).  
8. **Final Fit** – Check axial play <0.25 mm; torque test 7 N·m twist 5 s.

---

## 8 Safety & Regulatory Compliance  

| Standard | Requirement | Evidence |
|----------|-------------|----------|
| **CPSIA** | Total Pb <100 ppm; Phthalates <0.1 % | SGS report #CPS-1542 |
| **REACH** | No SVHC >0.1 % | Intertek REACH screening |
| **IFRA-49** | Lavender & rose usage within Category 4 limits | Calculation sheet, signed perfumer |
| **EN 71-3** | Heavy metals migration pass | TÜV test 21-07-17644 |
| **Prop 65** | No listed reproductive toxins | Certificate of Conformity |

Safety Data Sheets stored in PLM; lot-level traceability maintained 10 yrs.

---

**End of Document**
