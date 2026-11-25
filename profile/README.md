<!--
  Org profile — shown on https://github.com/OpenLyceum
  The full list of simulations lives in the catalog (www.openlyceum.com, built
  from Baton/structure/repos.json). Don't add a full table here.
  When adding a sim: bump the N in the badge and the "Browse all N" link.
  Add it to an "Explore" line only if it should be a highlight.
-->

<div align="center">

**Interactive physics, astronomy, and chemistry for the browser**

Open-source [SceneryStack](https://scenerystack.org/) simulations, with shared CI, docs, and accessibility across the fleet.

[**Browse all 84 simulations →**](https://www.openlyceum.com/)
&nbsp;·&nbsp;
[Clone the workspace](https://github.com/OpenLyceum/OpenLyceum)
&nbsp;·&nbsp;
[Contribute](https://github.com/OpenLyceum/.github/blob/main/CONTRIBUTING.md)

<br />

![84 simulations](https://img.shields.io/badge/84-simulations-0f2744?style=flat-square)
![SceneryStack](https://img.shields.io/badge/SceneryStack-TypeScript-1a4a7a?style=flat-square)
![Vite](https://img.shields.io/badge/build-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![License](https://img.shields.io/badge/license-AGPL--3.0-2d6a4f?style=flat-square)

<br />

<a href="https://openlyceum.github.io/OpticsLab/"><img src="https://www.openlyceum.com/assets/OpticsLab.webp" width="160" alt="Optics Lab" /></a>
<a href="https://openlyceum.github.io/Zenith/"><img src="https://www.openlyceum.com/assets/Zenith.webp" width="160" alt="Zenith" /></a>
<a href="https://openlyceum.github.io/QubitSketch/"><img src="https://www.openlyceum.com/assets/QubitSketch.webp" width="160" alt="Qubit Sketch" /></a>
<a href="https://openlyceum.github.io/TrackLab/"><img src="https://www.openlyceum.com/assets/TrackLab.webp" width="160" alt="Track Lab" /></a>
<a href="https://openlyceum.github.io/DopplerEffect/"><img src="https://www.openlyceum.com/assets/DopplerEffect.webp" width="160" alt="Doppler Effect" /></a>

</div>

---

## Explore

- **Physics:** [Optics Lab](https://openlyceum.github.io/OpticsLab/) · [Track Lab](https://openlyceum.github.io/TrackLab/) · [Doppler Effect](https://openlyceum.github.io/DopplerEffect/) · [Qubit Sketch](https://openlyceum.github.io/QubitSketch/) · [Special Relativity](https://openlyceum.github.io/SpecialRelativity/) · [AC Phasor](https://openlyceum.github.io/ACPhasor/)
- **Astronomy:** [Zenith](https://openlyceum.github.io/Zenith/) · [Transit Hunter](https://openlyceum.github.io/TransitHunter/) · [HR Diagram](https://openlyceum.github.io/HRDiagram/) · [Stellar Wobble](https://openlyceum.github.io/StellarWobble/) · [Habitability Lab](https://openlyceum.github.io/HabitabilityLab/)
- **Chemistry:** [Titration Lab](https://openlyceum.github.io/TitrationLab/) · [MolScope](https://openlyceum.github.io/MolScope/) · [Lewis Structures](https://openlyceum.github.io/LewisStructures/) · [Electron Configuration](https://openlyceum.github.io/ElectronConfiguration/) · [Spectroscopy Lab](https://openlyceum.github.io/SpectroscopyLab/) · [Stereochemistry](https://openlyceum.github.io/Stereochemistry/)
- **Earth science:** [Plate Tectonics](https://openlyceum.github.io/PlateTectonics/)

Every simulation, with screenshots and descriptions, is in the [**catalog**](https://www.openlyceum.com/).

## For developers

[Almanach](https://openlyceum.github.io/Almanach/) (SceneryStack knowledge base) · [Baton](https://github.com/OpenLyceum/Baton) (catalog, CI, fleet scripts) · [SceneryStackTemplate](https://github.com/OpenLyceum/SceneryStackTemplate) (start a new sim)

```bash
git clone https://github.com/OpenLyceum/OpenLyceum.git
cd OpenLyceum && ./bootstrap.sh --simulation
cd <SimName> && npm start
```

<sub>Some simulations began as rebuilds of PhET Interactive Simulations or Nebraska Astronomy Applet Project labs. See each repo's README for attribution.</sub>
