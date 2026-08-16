## 2026.8.1

### Added

- Hearth: tap a numeric sensor tile or stat readout to open a 24 h history popup with low/high and current value
- Hearth: sensor card thermostat option, a climate entity adds a target readout, plus/minus controls and a dashed target line on the chart
- Hearth: air quality verdicts (GOOD / FAIR / POOR) with banded tracks on CO2, PM2.5 and humidity readouts, custom thresholds via `verdict: { good, fair, max }`
- Hearth: group actions on section headers, All off for lights and Open all / Close all for covers, hidden with `group_actions: false`
- Hearth: card options `tune_button` (restore the per-tile controls glyph), `quick_action` (one-tap Clean/Stop on the vacuum row) and a per-card verdict opt-out

### Changed

- Hearth: tiles open their control popup on long-press or Shift+Enter, the per-tile glyph is gone by default
- Hearth: offline tiles render dashed and muted instead of red, blinds joined the warm palette and show their position
- Hearth: sensor charts draw an area fill, an end dot and a 24 h low/high footer
- Hearth: the media card transport is a 52 px button with amber progress, the vacuum card is a summary row with battery and bin levels
- Hearth: readout tiles whose modal only echoed the state are no longer interactive
- Hearth: an unconfigured rail status widget reports offline dashboard entities instead of a static pill, and the edit toggle is a labeled row
- Bump TypeScript to 6.0 and JS and CI dependencies

### Fixed

- Hearth: fill-screen pages size their columns to the screen, filling cards start at their content height, and the column collapse follows the page width instead of a viewport breakpoint
- Hearth: keep the rail weather widget on one row
- Restore cross-container dashboard dragging and give alt-cloned sections fresh descendant ids
- Declare the fontsource side-effect imports so svelte-check passes under TypeScript 6


**Full Changelog**: <https://github.com/knowald/ha-fusion/releases/tag/2026.8.1>
