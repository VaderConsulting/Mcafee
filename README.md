# Mcafee

CSC VB6 McInfo (`McInfo.exe`) inventory reporter for McAfee VirusScan. Reads engine/product/serial/virus-definition keys under `Software\McAfee\VirusScan`, checks the McAfee service via Service Control Manager, parses the last scan summary for infected-file counts, and writes a hostname status report.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `McInfo` (`Mcinfo.vbp`) | VB6 | WinForms exe | McAfee VirusScan inventory reporter |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Mcinfo.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Mcafee`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
