# ASME SDC 2025–26: Dual Trapdoor Sorting Mechanism

SolidWorks mechanism design for the American Society of Mechanical Engineers' Student Design Competition 2025–26 — a dual trapdoor sequential-release mechanism built for an autonomous waste-sorting robot at the University of Central Florida.

## Problem

The robot's basket needed to release two color-categorized waste types at two separate drop-off locations, using a single fast-release mechanism rather than two independent ones. I designed a dual trapdoor mechanism that opens the two trapdoors sequentially, based on how far the trigger mechanism has been pushed, using differential trigger-length actuation.

## Viewing the files

- **Quick view, no SolidWorks license needed:** open the `.EASM` files in the `eDrawings/` folder with the free [eDrawings Viewer](https://www.edrawingsviewer.com/). This folder has a curated subset of the full version history below.
- **Full native files:** every version folder (`PSB-v1` through `PSB-v5`, `PSB-Alex-8x8`, `Basket-prototype-1-materials`) contains the original `.SLDASM`/`.SLDPRT` files for anyone with SolidWorks who wants to inspect the feature tree and mate scheme directly.

## Version history

| Version | Changes/representation |
|---|---|
| PSB v1 | Intial design was modified to better fit the basket chassis, molding around the chassis for maximum volume for article storage |
| PSB v2 | v1 was modified with better tolerancing and dimensions, as well as including ramped surfaces at the back walls, pushing the articles further into the basket for maximum possible storage|
| PSB v3 | v2 was modified to included a dual rail design for the triggers, allowing for more stable trigger pressing. The design also changed to fit around the new chassis model, again maximizing internal storage volume. |
| PSB v4 | Enlarged triggers for easier claw entry |
| **PSB v5** | **Final design** — the version referenced in my resume and portfolio |
| PSB Alex 8x8 | Refitted for an alternate chassis configuration, carrying the dual trapdoor mechanism forward into a different fitment |
| Basket prototype 1 materials | This was the very first design, materializing the dual trapdoor concept along with sequential release |


## Skills demonstrated

- SolidWorks assembly modeling — multi-body mechanism design with mated moving components
- Mechanism design — translating a functional constraint (sequential dual release) into a physical actuation solution
- Iterative design methodology — five-plus revision cycles refining reliability, fitment, and mechanism behavior
- Cross-functional collaboration — integrating mechanical design with sensing, controls, and team system architecture

## Related work

Simulation/FEA portfolio (PyANSYS, DiMSL research): [github.com/anikaitrastogi/Python-ANSYSDiMSL-UCF](https://github.com/anikaitrastogi/Python-ANSYSDiMSL-UCF)
