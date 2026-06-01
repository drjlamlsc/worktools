# Worktools

A small hub of browser-based clinical utilities for daily use. Everything runs entirely client-side — no server, no data leaves the machine.

## Tools

- **[Case Note Formatter](tools/case-note-formatter.html)** — paste raw case notes with month/day/year headers and get clean, chronologically-sorted output with MSE and management sections separated.
- **[Session Recorder](tools/session-recorder.html)** — tag a patient-list screenshot by age / diagnosis / follow-up interval, track session financials, and export to CSV.
- **[Prescription Calculator](tools/rx-calc.html)** — parse free-text prescriptions into a dispensation list with tablet counts, optimal strength combinations, brand/generic forcing, and cost totals. Custom drugs are stored in the browser (`localStorage`).

> The Prescription Calculator was originally a local Flask app; the calculation engine has been ported 1:1 to client-side JavaScript so it runs fully in-browser, with the drug formulary embedded. Output was verified to match the original Python across 39 prescription cases and 10 autocomplete queries.

## Usage

Open `index.html` in any modern browser, or visit the GitHub Pages site if enabled.
