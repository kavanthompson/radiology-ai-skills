---
name: core-radiology-physics
description: High-yield Imaging Physics frameworks, formulas, and concepts extracted from Core Radiology 2nd Edition (Sun, Shi, Mandell) and aligned to ABR Core blueprint. Use for ABR Core exam prep, radiation dose calculations, CT/MRI/US/fluoroscopy physics, artifacts, and safety. Covers CTDI/DLP, radiation biology, MRI safety and sequences, ultrasound physics, and common artifacts.
---

# Core Radiology – Imaging Physics

**Source**: *Core Radiology: A Visual Approach to Diagnostic Imaging*, 2nd Edition (Sun, Shi, Mandell), Chapter 15 – Imaging Physics + ABR Core high-yield topics.

**Purpose**: Actionable physics toolkit for residents. Formulas, decision rules, and classic traps for the Core Exam and daily practice.

---

## 1. Radiation Dose Frameworks

### CT Dosimetry
- **CTDI** (Computed Tomography Dose Index) = average phantom dose from a single rotation
- **CTDIw** (weighted) = (2/3 × peripheral) + (1/3 × central)
- **CTDIvol** = CTDIw / pitch  
  - Independent of scan length
  - Reference levels exist by body region
- **DLP** (Dose Length Product) = CTDIvol × scan length (mGy·cm)  
  - Best single metric for estimating patient risk from a CT exam
- Effective dose ≈ DLP × conversion factor (k-factor, body-region specific)

**Typical effective doses (approximate)**
| Exam              | Effective Dose |
|-------------------|----------------|
| Chest radiograph  | 0.1 mSv        |
| Mammography       | 0.4 mSv        |
| Head CT           | 2 mSv          |
| Chest CT          | 7 mSv          |
| Abdomen CT        | 8 mSv          |
| Upper GI series   | 6 mSv          |

### Radiation Biology Essentials
- Stochastic effects (cancer, genetic) have no threshold; probability increases with dose
- Deterministic effects (skin injury, cataracts, sterility) have thresholds
- ALARA: As Low As Reasonably Achievable
- Fetal risk highest in organogenesis (weeks 3–8); higher doses later can cause growth restriction or CNS effects

---

## 2. CT Physics High-Yield

- Higher kVp → more penetration, lower contrast, lower dose for same noise (within limits)
- Higher mAs → lower noise, higher dose (linear)
- Pitch >1 → faster coverage, lower dose, potential for gaps
- Iterative reconstruction reduces noise and allows dose reduction
- Beam hardening, partial volume, motion, metal, and ring artifacts are classic

**Hounsfield Units**  
Water = 0, Air = –1000, Fat ≈ –50 to –100, Soft tissue ≈ 20–40, Bone high positive

---

## 3. MRI Physics & Safety

### Key Sequences & Weighting
- T1: fat bright, fluid dark (anatomy)
- T2: fluid bright (pathology)
- FLAIR: fluid suppressed (lesions near CSF)
- DWI/ADC: restricted diffusion (acute infarct, abscess, cellular tumors)
- GRE/SWI: susceptibility (blood products, calcium, iron)

### Safety Zones
- Zone I: public
- Zone II: supervised interface
- Zone III: restricted, screened
- Zone IV: magnet room itself

**Absolute contraindications** (most scanners): ferromagnetic implants, certain pacemakers (unless conditional), metallic foreign bodies in critical locations (eye, etc.)

**SAR** (Specific Absorption Rate) limits heating; higher at 3T than 1.5T

**Quench**: helium venting; evacuate, do not enter if oxygen displaced

---

## 4. Ultrasound Physics

- Frequency ↑ → resolution ↑, penetration ↓
- Attenuation ∝ frequency
- Acoustic impedance determines reflection
- Doppler: frequency shift proportional to velocity and cosine of angle (best at 0°, none at 90°)
- Aliasing when Nyquist limit exceeded (PRF/2)
- Common artifacts: reverberation, shadowing, enhancement, mirror image, speed displacement

---

## 5. Fluoroscopy & Radiography

- Dose spreading (moving the beam) reduces peak skin dose
- Grid improves contrast but increases dose
- Magnification increases dose and spatial resolution
- Last-image hold and pulsed fluoro reduce dose
- Collimation is the most effective real-time dose-reduction tool

---

## 6. Classic Formulas & Numbers to Memorize

| Concept                    | Formula / Value                          |
|----------------------------|------------------------------------------|
| CTDIvol                    | CTDIw / pitch                            |
| DLP                        | CTDIvol × length                         |
| Effective dose             | DLP × k-factor                           |
| Nyquist limit              | PRF / 2                                  |
| Doppler shift              | ∝ velocity × cos θ                       |
| SNR                        | ↑ with √(NEX), voxel size, field strength|
| Contrast-to-noise (CNR)    | (Signal A – Signal B) / noise            |

---

## 7. Anti-Patterns & Core Exam Traps

- CTDIvol alone does not represent total patient dose — DLP does.
- Pitch >1 reduces dose but can introduce artifacts if too high.
- Higher kVp lowers contrast; do not use it indiscriminately for “dose reduction.”
- MRI safety is about ferromagnetic risk and SAR, not just “metal.”
- Doppler angle near 90° gives near-zero shift — do not interpret as no flow.
- Stochastic risk has no threshold; even low doses carry some probability.
- “Low dose” protocols still require justification and optimization (ALARA).

---

## 8. How to Use This Skill

**ABR Core prep**  
“Quiz me on CTDI vs DLP”  
“MRI safety zones”  
“Effect of pitch on dose and noise”  
“Ultrasound artifacts”

**Clinical / protocol questions**  
Provide scenario → skill returns the relevant physics principle, formula, or safety rule.

**Teaching (ResidentShield)**  
“Teaching point on why DLP is better than CTDIvol for risk” or “Explain ALARA simply.”

**Protocol optimization**  
Use the frameworks to reason about dose, noise, and image quality trade-offs.

---

*Module 9 of Core Radiology skill series. Previous: Thoracic, GI, GU, Neuro, MSK, Breast, Cardiac, IR. This completes the major Core Radiology domains.*
