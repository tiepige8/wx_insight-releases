# wx_insight releases

This repository stores public Windows release assets for the wx_insight updater.

It also exposes a jsDelivr-compatible update channel:

- `channel/latest.json`: latest release metadata and integrity information
- `channel/vX.Y.Z/`: immutable versioned update archives

The updater downloads `wx_insight_windows_amd64.exe.zip` and verifies it with
`wx_insight_windows_amd64.exe.zip.sha256` before replacing the local executable.
