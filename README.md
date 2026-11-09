# PolyLightMix – Interactive WebGL 3D Relight & Post-FX Compositor

PolyLightMix is a lightweight, zero-dependency, open-source WebGL relighting and post-processing engine built for 3D artists, architectural visualizers, and digital agencies. Running entirely client-side in any modern web browser, it translates advanced studio relighting pipelines—familiar from industry render engines like Corona Renderer, Indigo, and V-Ray LightMix—into an interactive, hardware-accelerated web experience.

Traditional architectural visualization workflows lock illumination into static 2D images. When clients or stakeholders request lighting revisions—such as testing dusk ambiance, dimming interior pendant fixtures, or checking exterior facade washlights—artists typically face time-consuming re-renders or cumbersome multi-layer PSD files. PolyLightMix removes this bottleneck by allowing real-time compositing of individual light passes using linear mathematical blending (ADD) directly inside the browser viewport.

### Core Capabilities:

* **Real-Time Linear ADD Blending:** Imports raw, isolated lighting passes (e.g., skylight, golden hour sun, interior pendants, accent LEDs, pool lights) and calculates mathematically accurate light summation without dynamic range clipping.
* **Physical Kelvin Color Tuning:** Dynamically shifts color temperatures from warm candlelight (1800K) to deep overcast sky (9500K) using real-time Planckian blackbody-to-RGB conversion, complete with independent 0%–300% intensity sliders.
* **Interactive Click-to-Focus Depth of Field:** Real-time Z-depth sampling allows users to click anywhere on the 3D scene to visually set focal distance, controlling aperture radius and cinematic bokeh blurring on the fly.
* **Cinematic Shading Pipeline:** High-speed highlight bloom extraction, ambient occlusion pass multiplication, and ACES filmic tonemapping preserve fine dynamic range and eliminate blown-out digital highlights.
* **Showroom Autopilot Demo:** Features an integrated self-running showcase sequence that automatically cycles through daylight, golden hour, and blue-hour moods, pausing immediately when a user interacts.
* **Zero Dependencies & Single-File Architecture:** Fully self-contained HTML/CSS/JS architecture with zero external NPM packages or bulky framework overhead.

Engineered for seamless embedding via `<iframe>` or direct script tags into agency portfolios, real estate sales portals, and client presentation platforms. Developed and maintained by Polygon Manufaktur (Hamburg, Germany).
