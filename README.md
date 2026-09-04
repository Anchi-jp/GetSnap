# GetSnap

**Capture oscilloscope and test-instrument screens with a single hotkey.**

GetSnap is a lightweight Windows desktop tool that connects to lab
instruments (oscilloscopes, VNAs, spectrum analyzers, etc.) over
GPIB/USB/LAN via VISA/SCPI, and grabs the screen — or the raw waveform data
— straight to your clipboard, a folder, an Excel sheet, or a CSV file. No
installation: it's a single portable `.exe`.

## Features

- **One-press capture** — customizable global hotkeys or in-app buttons for
  saving to a folder, copying to the clipboard, or pasting directly into
  Excel as a picture.
- **CSV data export** — pull raw waveform data from every enabled channel
  in one click.
- **Legend overlay** — stamp free-text fields (model, condition, notes,
  etc.) onto captured images automatically.
- **DIV Conditions overlay** — auto-append each channel's voltage range
  (and, optionally, the timebase) to the image, queried live from the
  instrument.
- **Print-style background conversion** — flip a dark on-screen display to
  a clean white background for reports, without touching the trace colors.
- **Extensible instrument presets** — built-in support for Tektronix and
  Yokogawa scopes; add or edit SCPI command sets for other vendors directly
  from the UI, no code changes required.

## Getting Started

Download `GetSnap.exe` and double-click it — that's it. See `Manual_JP.pdf`
/ `Manual_ENG.pdf` for full usage details, or `StartGuide_JP.pdf` /
`StartGuide_ENG.pdf` for a quick two-minute overview.

GPIB connections require a VISA runtime such as NI-VISA or Keysight IO
Libraries Suite; USB and LAN instruments work out of the box.

## License

MIT — free to use, modify, and distribute for personal or commercial
purposes, with no royalties or usage fees. 
