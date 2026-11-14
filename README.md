# Temporal horizons — Module XI

Standalone interactive extract of Module XI, "Temporal horizons", from the Chronowave Dynamics Temporal Engine: a single-file compendium of 17 interactive modules about the author's temporal framework. The full compendium, its manual and its edit log are in [chronowave-compendium](https://github.com/Ajuntanaga/chronowave-compendium). The module's own heading on the page reads: "Where the cubic exponent meets its evidence".

## Use it

Download or clone this repository, then open [`Module_XI_Temporal_Horizons.html`](Module_XI_Temporal_Horizons.html) from disk in a current browser (GitHub only shows its source). There is no build step and nothing to install. Math (KaTeX 0.16.9) and fonts load from cdnjs and Google Fonts, so equations and typography need a connection.

## Files

| File | What it is |
|---|---|
| [`Module_XI_Temporal_Horizons.html`](Module_XI_Temporal_Horizons.html) | The module: one page with the shared styles, this module's section and the script statements it needs. |
| [`Module_XI_Manual.md`](Module_XI_Manual.md) | This module's part of the compendium's plain-text manual (extracted from rev b90 and hand-patched, so it may lag the page). |

The other two files are this README and a `.gitignore`.

## Where it comes from

Made on 2026-11-14 from rev b91 of the compendium page (commit `6cf22d4` of chronowave-compendium) by the scripts in the `tools/split` folder of that repository (added in later commits). The section markup, the styles and the script statements are copied from the page without change. What differs is the page title and description, a short header and footer line and the link to the manual.

## Checks and limits

- A scripted headless-Chromium test loaded the page, moved every slider, select and checkbox, clicked every button and sent pointer, wheel and key events to every canvas: 117 actions (slider moves, clicks, and pointer, wheel and key events), 3 canvases, no uncaught exception and no console error. It is a smoke test: this extract was not compared with the original module for identical behaviour, and nothing here has had an independent review.
- The framework is the author's own and still in progress; Module XVII of the compendium (also a repository of its own, [chronowave-verdicts-and-rulings](https://github.com/Ajuntanaga/chronowave-verdicts-and-rulings)) carries the page's own verdicts and open rulings.
- No license: all rights are reserved by default, beyond viewing and forking on GitHub; a license is the author's decision.
