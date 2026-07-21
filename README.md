# Elemental — Client Results Report (design prototype)

A working prototype of a functional-medicine blood-results report, built to make lab
data legible for a client: every marker is plotted against **both** the standard lab
range **and** the practitioner's optimal target, with the interpretation and plan
alongside it.

> **This is a design demo.** The client name and all values are fictional /
> de-identified and are shown only to demonstrate the layout and interactions.

## View it
Open `index.html` in any browser — it's a single self-contained file, no build step,
no dependencies. Or use the live link in the repo's **About** section.

- **Mobile-first** — try it at phone width, or *Add to Home Screen* for the app feel.
- Tap **Why this matters** on a marker (or a supplement) to expand the reasoning.
- Use the **Movement** toggle to compare a marker against a previous round.
- **Cmd/Ctrl-P** renders the same content as a clean, printable PDF.

## What it's exploring
- A per-marker range bar with three distinct zones: **optimal target · standard lab range · outside both**.
- **Summary-first**: the top three priorities before the full 60-marker panel (kills "data overwhelm").
- **Trend across repeat tests** — the report is designed to evolve per client over months and years.
