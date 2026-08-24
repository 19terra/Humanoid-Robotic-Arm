 InMoov Bionic Hand & Forearm — Interactive Assembly Dashboard

A single-page, dependency-light web app for building the InMoov bionic hand & forearm.
It combines a real-time WebGL **STL model viewer** (browse and orbit all 15 printed
parts straight from their actual mesh files), a **guided 4-phase assembly checklist**
with progress tracking, a **drill-bit & adhesives reference matrix**, and an
**AI vision / servo simulator** that mirrors the `$XXXXX` serial protocol used by
OpenCV + CVZone hand tracking to drive the Arduino servos.

No backend, no build step — open `InMoov_Hand_Dashboard.html` in a browser
(keep `inmoov_stl_data.js` alongside it) and start building.

**Features**
- 🧊 Live STL viewer with orbit/zoom/pan + part carousel (Three.js)
- 🛠️ Step-by-step assembly guide with a persistent progress bar
- 📐 Drill bit size lookup + adhesive/tendon/lubricant compatibility guide
- ⚡ Hand-gesture → servo serial protocol simulator with Arduino pin mapping
- ⚙️ Searchable 3D-printing spec table (infill, wall thickness, supports)

Built on the open-source [InMoov project](https://inmoov.fr/inmoov-hand/) by Gaël Langevin.
