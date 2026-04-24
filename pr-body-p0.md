## Problem
`app.json` configured 8 TabBar icons but `images/` directory was missing, causing build failure.

## Changes
- Added 8 PNG icons (81x81px) under `images/`
- home / job / resume / match, each with inactive and active variants
- Color: `#6c7086` (inactive) / `#89b4fa` (active, Catppuccin Mocha theme)
