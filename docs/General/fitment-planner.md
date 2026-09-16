---
layout: guide
title: Build fitment planner
---

# Build fitment planner

Fitment is a system: **iPod model + rear case + storage adapter + storage media + battery + added electronics**. Check the whole system before placing an order or closing the case.

## Planning worksheet

Copy this into an issue, note, or test log before buying.

| Field | Record |
| --- | --- |
| iPod identity | Apple name, original capacity, firmware, and rear-case depth |
| Current configuration | Original/replacement drive, battery condition, existing modifications |
| Storage | Adapter brand/revision, media brand/model/capacity, number of cards |
| Battery | Seller, advertised capacity, **measured dimensions**, connector orientation, date code if present |
| Rear case | Existing or replacement; thin/thick; hold-switch/headphone assembly compatibility |
| Other hardware | Bluetooth, USB-C, AirTag, Taptic Engine, screen, custom frame, or none |
| Evidence | Direct vendor compatibility page, build photos, bench test, and date |
| Open-case result | Restore, charging, audio, controls, case closes without force |

## Initial reference matrix: extended batteries in Classic/Video builds

This table transcribes the **iFlash third-party extended-battery guide’s sample fitment reference**. It is not a buying recommendation or a universal guarantee: iFlash warns that aftermarket packs sold under the same mAh label vary in quality, actual capacity, and physical dimensions. Check the live source, measure the received pack, and test open-case before reassembly.

| Battery label in iFlash sample guide | iFlash-Quad | iFlash-Dual | iFlash-Solo | iFlash-SATA | iFlash-CF |
| --- | --- | --- | --- | --- | --- |
| 1,800 mAh | Thick back | Thick back | Thick back | Thick back | Thick back |
| 2,000 mAh | Thin back | Thick back | Thick back* | Thick back | Thick back |
| 1,900 mAh | Thin back† | Thick back | Thick back* | Thick back | Thick back |
| 3,000 mAh | Thick back | Thick back | Thick back | Thick back | Thick back |

\* The source says some samples were a very tight fit in a thin 5th-generation back with an iFlash-Solo; that is not a recommendation to force a case closed.

† The source says this sample required removing a frame protrusion for a thin-back fit. This guide does not recommend that irreversible alteration until it has its own documented, tested procedure.

Source: [iFlash third-party extended battery guide](https://www.iflash.xyz/3rd-party-extended-battery-guide/), accessed 2026-09-16. Its table is useful as a starting point, but its warning is part of the evidence: published labels and dimensions can differ from the item delivered.

## Hard stop rules

Stop, reassess, and do not close the case if:

- the battery is swollen, creased, punctured, hot, or physically larger than its verified fit;
- a ribbon has a sharp crease, bears the weight of a component, or touches a closing clip;
- the rear case needs sustained force, rocks, bulges, or leaves a gap;
- a connector only reaches by stretching its flex cable;
- any board-level mod has not been tested independently before adding other new variables.

## Test one variable at a time

For a first build, install storage and retain the original battery/case. Restore and test. Then add a battery in a separate session. Add Bluetooth, USB-C, or other board-level work only after that basic configuration is stable. This makes faults diagnosable and avoids reopening a difficult metal case repeatedly.

## How this page becomes a trustworthy database

Each confirmed configuration should add a row to a future test log with exact part numbers, photographs, measured battery dimensions, firmware, operating system used for restore, test duration, and outcome. Do not aggregate several community reports into a “works” label without preserving those variables.
