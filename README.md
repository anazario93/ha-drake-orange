# Drake Interplanetary Orange

A dark Home Assistant theme inspired by the rugged, utilitarian cockpit MFDs of Drake Interplanetary in *Star Citizen*.

## Design

- Burnt orange primary controls: `#D47725`
- Amber highlights and active indicators: `#F0A43A`
- Warm charcoal and bronze surfaces
- Warm ivory text for contrast
- Oxanium typography

The theme uses native Home Assistant theme variables and does not require card-mod or custom card dependencies.

## Installation

1. Copy `themes/drake_interplanetary_orange.yaml` into your Home Assistant `themes` directory.
2. If your themes are stored in a folder, make sure your configuration includes:

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

3. Reload themes from **Developer Tools → YAML → Reload themes**, or restart Home Assistant.
4. Open your user profile and select **Drake Interplanetary Orange** under Theme.

## Typography

The theme references the Oxanium font family. Add Oxanium as a dashboard font resource if you want the intended cockpit-style typography. The theme remains usable with the system fallback font if Oxanium is not installed.

## Palette

| Role | Color |
|---|---|
| Void black | `#0D0D0B` |
| Gunmetal | `#171512` |
| Dark bronze | `#24201A` |
| Burnt orange | `#D47725` |
| Amber | `#F0A43A` |
| Warm ivory | `#E8E0D2` |
| Muted sand | `#A99A83` |
| Weathered metal | `#766B5B` |
