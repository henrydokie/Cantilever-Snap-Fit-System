# Cantilever Snap Fit System

This repository contains the design files and visual documentation for a basic cantilever snap fit system intended for 3D printing and iterative prototyping.

## Overview

Cantilever snap fits are commonly used in plastic part design to enable reversible assembly without fasteners. This system demonstrates a simple male-female locking interface, designed with additive manufacturing tolerances in mind.

The current version is `v3`.

---

## 📁 Files Included

| File Name                                | Description                                      |
|-----------------------------------------|--------------------------------------------------|
| `Cantilever Snap Fit 1 v3.f3d`          | Fusion 360 source model (full assembly)          |
| `Cantilever Snap Fit 1 v3 Assembly.png` | Rendered assembly view                           |
| `Cantilever Snap Fit 1 v3 Female.png`   | Rendered view of the female half                 |
| `Cantilever Snap Fit 1 v3 Male.png`     | Rendered view of the male half                   |
| `Femalev3.3mf`                          | Exported mesh of the female half (3D printable)  |
| `Malev3.3mf`                            | Exported mesh of the male half (3D printable)    |

---

## 💡 Design Considerations

- Material: PLA for FDM 3D printing
- Clearance: Designed with a 0.15 mm press-fit offset for standard printer tolerances
- Snap fit type: **Cantilever beam** with a locking ledge
- Modeled for iterative design: geometry can be adjusted for stiffness or fit
