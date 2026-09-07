# Compact Range Picker

Time-range control for the Traffic Statistics dashboard. Replaces the wide
always-open picker with two narrow controls.

- **Right** — typeable start/end fields, `dd-mm-yyyy hh:mm`. Calendar button opens a
  4-step walk: start date -> start time -> end date -> end time.
- **Left** — preset dropdown (Last hour ... Last 6 months, incl. 2 and 4 weeks).
  Picking a preset writes both fields; typing in a field flips the preset to `Custom`.

Single file, no build step, no dependencies. Open `index.html`.
