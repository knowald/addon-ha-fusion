## 2026.7.0

### Added

- Add entities list card showing multiple entity states, with wildcard entity selection
- Add white channel sliders to the light modal for RGBW and RGBWW lights
- Add option to hide the camera name overlay

### Changed

- Soften the camera name overlay with less dimming and blur
- Merge the Spotify player large variant into a single component
- Extract a shared scaffold for config panels
- Rewrite the README as a maintained continuation of the original project, with a migration guide
- Add CI workflow, issue templates, and automated release sync to the addon repo

### Fixed

- Fix toggle recursion when pressing group entity buttons
- Show a placeholder instead of a missing weather icon when the state is unknown or unavailable
- Hide the alarm keypad and skip the code when the panel does not require one
- Preserve white channels when picking colors on RGBW and RGBWW lights
- Repair YouTube account linking in the video addon by updating youtubei.js


**Full Changelog**: <https://github.com/knowald/ha-fusion/releases/tag/2026.7.0>
