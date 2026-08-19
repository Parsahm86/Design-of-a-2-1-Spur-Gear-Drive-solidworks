# Design of a 2:1 Spur Gear Drive – SolidWorks Project

A complete 3D CAD design of a **standard Spur Gear Drive (Pinion 20T & Gear 40T)** created in SOLIDWORKS.  
This project includes individual part models, the complete assembly, engineering drawings with **GD&T (Geometric Dimensioning and Tolerancing)**, and a motion animation.

---

## Assembly Render

![Spur Gear Render](RENDERS/ass-superGear-40-20-VidRender.gif)

---

## Project Overview

This project is a fully functional, manufacturable spur gear set designed according to **ISO standards**. It includes:

- **2 Unique Parts:** A 20-tooth driving gear (Pinion) and a 40-tooth driven gear.
- **Manufacturing Compliance:** All parts are designed with **GD&T**, **Datum schemes (A, B, C)**, and **DFM (Design for Manufacturing)** principles.
- **Standards:** Applied ISO standards for modules, pressure angles, and fits (H7, h12).
- **Gear Ratio:** Designed for a 2:1 speed reduction application.

---

## Gear Parameters

The assembly consists of the following gear specifications:

| Parameter | Pinion (20T) | Gear (40T) |
|-----------|--------------|------------|
| Module | 2 | 2 |
| Pitch Diameter | 40 mm | 80 mm |
| Outside Diameter | 44 mm | 84 mm |
| Root Diameter | 35 mm | 75 mm |
| Face Width | 15 mm | 15 mm |
| Bore Diameter | 12 mm | 20 mm |
| Pressure Angle | 20° | 20° |
| Number of Teeth | 20 | 40 |

---

## Selected Materials

| Component | Material | Standard |
|-----------|----------|----------|
| Pinion Gear (20T) | **Plain Carbon Steel (AISI 1045)** | AISI 1045 |
| Gear (40T) | **Plain Carbon Steel (AISI 1045)** | AISI 1045 |

---

## Technical Features

- **Standardization:** Fully compliant with **ISO** gear standards.
- **Geometric Tolerancing (GD&T):** Applied **Position (⌖)** with MMC, **Flatness (⏥)** for mounting faces, and **Perpendicularity** to ensure correct assembly.
- **Fits & Tolerances:** 
  - Bore 1 (20T): `Ø12 H7` for a precise shaft fit.
  - Bore 2 (40T): `Ø20 H7` for a precise shaft fit.
  - Outside Diameters: `h11` to prevent binding during meshing.
- **Assembly Data:** Center distance calculated at **60 mm** for perfect tooth engagement.
- **Surface Finish:** Recommended **Ra 1.6** for gear teeth to reduce wear and noise.

---

## Motion Animation

![Motion Animation](RENDERS/ass-superGear-40-20-VidRender.mp4)

[▶ Watch Motion Animation (MP4)](RENDERS/ass-superGear-40-20-VidRender.mp4)

---

## Project Files

- [SolidWorks Assembly](CAD/ASSEMBLY/ass-superGear-40-20.SLDASM)
- [SolidWorks Part Files (20T & 40T)](CAD/PARTS/)
- [Engineering Drawings](CAD/DRAWING/)
- [Motion Animation](RENDERS/)
- [STEP File](STEP%20FILE/ISO%20standard%20Spur%20Gear%20Drive%20(2-1%20ratio).STEP)

---

## File Formats

| File Type | Format |
|-----------|--------|
| SolidWorks Parts | `.SLDPRT` |
| SolidWorks Assembly | `.SLDASM` |
| SolidWorks Drawing | `.SLDDRW` |
| PDF Drawing | `.PDF` |
| STEP Assembly | `.STEP` |
| Animation | `.GIF` / `.MP4` |

---

## Folder Structure

```text
Design-of-a-2-1-Spur-Gear-Drive-solidworks/
├── CAD/
│   ├── ASSEMBLY/
│   │   └── ass-superGear-40-20.SLDASM
│   ├── DRAWING/
│   │   ├── Design of a 2-1 Spur Gear Drive-DrawingFile.pdf
│   │   ├── spur gear_iso-DrawingFile.SLDDRW
│   ├── PARTS/
│   │   ├── spur gear_iso-20T.SLDPRT
│   │   └── spur gear_iso-40T.SLDPRT
│   └── RENDERS/
│       ├── ass-superGear-40-20-VidRender.gif
│       └── ass-superGear-40-20-VidRender.mp4
├── STEP FILE/
│   └── ISO standard Spur Gear Drive (2-1 ratio).STEP
└── README.md
```
