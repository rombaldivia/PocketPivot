# PocketPivot

<p align="center">
  <strong>Compact Mechanical Positioning System for MagSafe-Compatible Smartphones</strong>
</p>

<p align="center">
  A low-cost, portable, and fabrication-oriented stand designed for stable recording, viewing, and everyday device positioning.
</p>

---

## Design Overview

**PocketPivot** is a compact mechanical support developed for MagSafe-compatible smartphones. The concept combines magnetic attachment, articulated positioning, and a foldable structural arrangement to provide repeatable device orientation without the size or cost of larger commercial stands.

The project focuses on practical mechanical design rather than electronic complexity. Its engineering value lies in the integration of a compact support geometry, adjustable joints, manufacturable parts, and an accessible CAD package suitable for continued prototyping and refinement.

PocketPivot is intended for:

- Video recording and short-form content creation.
- Product photography and tabletop shots.
- Video calls and remote meetings.
- Tutorials, demonstrations, and hands-free reference.
- Everyday multimedia viewing.

---

## Engineering Intent

The design is guided by four primary objectives:

| Objective | Design Intent |
| --- | --- |
| Portability | Maintain a compact footprint suitable for transport and daily use. |
| Adjustability | Provide practical angular positioning through articulated mechanical joints. |
| Stability | Support a smartphone without excessive movement during normal interaction. |
| Accessibility | Use geometry and manufacturing methods compatible with low-cost prototyping. |

---

## Complete Assembly

![PocketPivot complete assembly](assets/figures/pocketpivot_full_assembly.jpg)

The complete assembly integrates the circular magnetic interface, upper pivot, central structure, lower positioning mechanism, and support base into a single compact device.

---

## PocketPivot in Motion

<p align="center">
  <a href="assets/videos/PocketPivot.mp4">
    <img src="assets/figures/pocketpivot_front_perspective.jpg" width="680" alt="Watch the PocketPivot mechanical positioning demo">
  </a>
</p>

<p align="center">
  <strong>▶ Watch the mechanical positioning demonstration</strong><br>
  <sub>Click the preview to open the complete PocketPivot MP4 demonstration.</sub>
</p>

---

## Mechanical Design Views

| Front Perspective | Front View | Rear Mechanism |
|:---:|:---:|:---:|
| <img src="assets/figures/pocketpivot_front_perspective.jpg" width="250" alt="PocketPivot front perspective"> | <img src="assets/figures/pocketpivot_front_view_fixed.jpg" width="250" alt="PocketPivot front view"> | <img src="assets/figures/pocketpivot_rear_mechanism_fixed.jpg" width="250" alt="PocketPivot rear mechanism"> |
| Magnetic interface, upper joint, compact body, and support base. | Alignment of the mounting plate, central structure, and lower positioning mechanism. | Articulated rear mechanism used to control smartphone orientation. |

---

## Mechanical Architecture

PocketPivot is organized around a small number of functional elements:

### Magnetic Mounting Interface

The circular front interface is intended to align with MagSafe-compatible smartphones and cases. Its geometry provides a clear mounting reference while keeping the phone centered relative to the support structure.

### Articulated Positioning

The upper and rear joints control device orientation. Their design must provide sufficient friction to hold the selected position while remaining adjustable during normal use.

### Compact Structural Body

The central body transfers load between the magnetic mount and the support base. Openings and reduced material regions help preserve a lightweight structure while maintaining the required mechanical continuity.

### Support Base

The lower structure stabilizes the assembly and defines the usable positioning range. Its geometry is intended to balance compactness, contact area, and clearance between moving parts.

---

## Main Features

- MagSafe-compatible circular mounting interface.
- Adjustable mechanical positioning for recording and viewing.
- Compact and foldable architecture.
- Stable support across multiple practical angles.
- Low-cost fabrication using accessible manufacturing methods.
- Editable native SolidWorks parts, assemblies, and drawings.
- STEP exports for neutral CAD exchange and manufacturing review.
- STL files for rapid prototyping and 3D printing.
- Dedicated visual and motion documentation.

---

## CAD Package

| Directory | Engineering Purpose |
| --- | --- |
| [`SolidWorks/`](SolidWorks/) | Editable native parts, assemblies, and technical drawings. |
| [`STEP/`](STEP/) | Neutral geometry for cross-platform CAD exchange and manufacturing review. |
| [`STL/`](STL/) | Mesh exports for rapid prototyping and additive manufacturing. |
| [`assets/figures/`](assets/figures/) | Assembly views and mechanical documentation. |
| [`assets/videos/`](assets/videos/) | Motion and positioning demonstrations. |

---

## Repository Structure

```text
PocketPivot/
├── README.md
├── SolidWorks/
│   ├── *.SLDPRT
│   ├── *.SLDASM
│   └── *.SLDDRW
├── STEP/
│   └── *.STEP
├── STL/
│   └── *.STL
└── assets/
    ├── figures/
    │   ├── pocketpivot_full_assembly.jpg
    │   ├── pocketpivot_front_perspective.jpg
    │   ├── pocketpivot_front_view_fixed.jpg
    │   └── pocketpivot_rear_mechanism_fixed.jpg
    └── videos/
        └── PocketPivot.mp4
```

---

## Manufacturing Considerations

Before fabrication, verify:

- Final smartphone and case clearance.
- Magnet diameter, thickness, polarity, and retention method.
- Joint tolerances and the friction required to maintain orientation.
- Clearance between moving and mating components.
- Print orientation, support requirements, and anisotropic strength.
- Base contact area and resistance to overturning.
- Fastener dimensions and accessibility during assembly.

These parameters should be validated through physical prototyping because printed material, manufacturing process, and magnet selection directly influence the final mechanical behavior.

---

## Development Status

The current CAD revision defines the resolved mechanical arrangement shown in the assembly and design views. The project remains open to dimensional refinement, tolerance optimization, magnetic-interface validation, and physical testing.

Future iterations may focus on reducing part count, improving folding behavior, strengthening high-load joints, and refining the relationship between portability and stability.

---

<p align="center">
  <strong>Compact geometry. Practical articulation. Accessible fabrication.</strong>
</p>
