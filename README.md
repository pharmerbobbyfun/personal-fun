# Mexico Vacation App

A shareable, mobile-friendly companion app for our family trip to **Excellence Riviera Cancun** (July 18–24).

Six sections:

- **Overview** — countdown, resort at a glance, late-July weather
- **Dining** — all 9 restaurants + the bars (star the ones to try)
- **Do** — pools, beach, the Miilé spa, activities & nightly entertainment
- **Excursions** — off-resort tours with durations (shortlist them)
- **Pack** — per-person checklists (Shared / Bobby / Vanessa / Ella)
- **Good to Know** — airport transfer, money & tipping, dress code, WiFi, safety, Spanish phrases

Open `index.html`. Everything is a single self-contained page; your picks and checkmarks save in your browser. Published via **GitHub Pages**.

---

## Wrap Studio (`wraps/`)

A second self-contained page for designing custom wraps for the Tesla Paint Shop.
Open `wraps/index.html` (or `/wraps/` once the site is published).

- Pick one of the 12 vehicles; the page detects the template's panels so you can
  click a panel and paint just that one.
- Paint with a solid color, a three-stop gradient, or a generated pattern
  (camo, digital camo, stripes, checker, dots, leopard, waves, carbon, grain),
  plus a photo layer and a text layer.
- "Seam cover" spreads the paint over the template's black panel edges so the
  exported file has no white seams.
- Export writes a PNG at the template's size and automatically scales down if it
  would exceed the 1 MB limit; the file name is trimmed to what the car accepts.

Templates and vehicle renders under `wraps/templates/` are copied from Tesla's
[teslamotors/custom-wraps](https://github.com/teslamotors/custom-wraps)
repository (`template.png` and `vehicle_image.png` for each model).

Getting a finished wrap onto the car: mobile app v4.59.0+ (Creations → Wrap →
Upload) or a `Wraps` folder at the root of a USB drive, then
Toybox → Paint Shop → Wraps.
