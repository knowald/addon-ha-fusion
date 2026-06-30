## 2026.3.2

### Changed

- Migrate the app to Svelte 5 runes, converting all components, event handlers, and stores
- Replace svelte-dnd-action with SortableJS for drag-and-drop under Svelte 5
- Exclude legacy Svelte 4 libraries from Vite prebundling so they load in runes mode
- Rewrite the README and refresh the preview screenshot

### Fixed

- Resolve runtime `$effect` loops and reactivity bugs from the runes migration
- Restore drag-drop UI updates and redo history after the migration
- Render a newly added object immediately in the dashboard editor
- Correct drag reorder order and fix a crash on cross-zone item drops

**Full Changelog**: <https://github.com/knowald/ha-fusion/releases/tag/2026.3.2>
