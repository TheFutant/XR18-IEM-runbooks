# XR18 IEM Runbooks

Live-sound documentation and configuration for a **6-piece band running a self-contained PA** on a Behringer **XR18** digital mixer, with **in-ear monitors (IEMs)** mixed from the [Mixing Station](https://mixingstation.app/) app and a MIDI footswitch for hands-free control.

Everything here is meant to be grabbed quickly on a practice or gig day — the runbooks are self-contained HTML files you can open straight in a browser (including offline on a phone or tablet).

## Live site

Published via GitHub Pages — **[open the runbooks index](https://thefutant.github.io/XR18-IEM-runbooks/runbooks/)**.

Individual runbooks open live too, e.g. the [PA runbook](https://thefutant.github.io/XR18-IEM-runbooks/runbooks/pa-runbook-eon612.html) or the [stage overview](https://thefutant.github.io/XR18-IEM-runbooks/runbooks/stage-overview.html).

## Contents

### `runbooks/` — open in any browser

| File | What it covers |
|------|----------------|
| [`stage-overview.html`](runbooks/stage-overview.html) | Stage plot and signal flow for the 6-piece, self-contained PA setup |
| [`practice-day-runbook.html`](runbooks/practice-day-runbook.html) | Step-by-step setup and teardown for a practice with the full band present |
| [`pa-runbook-eon612.html`](runbooks/pa-runbook-eon612.html) | Front-of-house PA setup for 2× JBL EON612 + XR18 |
| [`band-iem-setup.html`](runbooks/band-iem-setup.html) | Band-member onboarding sheet — get your IEM mix working from your phone (Mixing Station, Personal Monitoring) |
| [`iem_midi_footswitch_runbook.html`](runbooks/iem_midi_footswitch_runbook.html) | MIDI footswitch wiring and mapping for hands-free IEM control |
| [`mixing-station-config.html`](runbooks/mixing-station-config.html) | Mixing Station app + XR18 configuration reference |
| [`eq-fx-runbook.html`](runbooks/eq-fx-runbook.html) | EQ and effects settings for the XR18 |
| [`band_epk_onepager.html`](runbooks/band_epk_onepager.html) | Band electronic press kit (EPK) one-pager |

### `mixer-scenes/` — XR18 / Mixing Station scene files (`.msz`)

| File | Use |
|------|-----|
| `Base_scene.msz` | Baseline board state — starting point for a session |
| `Gig_nosub.msz` | Gig scene without a subwoofer |
| `Gig_withsub.msz` | Gig scene with a subwoofer |

Load these in Mixing Station to recall a full board configuration.

### `setlist-litmus-test.md`

A shared 0–14 scoring rubric for deciding whether a candidate song belongs on the setlist (10+ = keeper, 7–9 = discuss, under 7 = cut).

## Gear

- **Mixer:** Behringer XR18
- **Control:** Mixing Station app + MIDI footswitch
- **Monitoring:** In-ear monitors (IEMs)
- **PA:** 2× JBL EON612 (optional subwoofer)
