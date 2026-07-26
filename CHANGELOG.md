## 2026.7.2

### Added

- Add an early preview of the Hearth dashboard, opt in by setting `hearth: true` in `configuration.yaml` to get a drawer button that opens it

### Changed

- Bump JS dependencies within semver ranges and fix audit vulnerabilities
- Bump GitHub Actions used by CI workflows

### Fixed

- Recover camera HLS playback after network errors
- Harden auth token handling and redirect back to the ingress path after login
- Set the connected store on the initial websocket connection
- Guard modal state reads against pre-connection undefined states
- Declare mutated component state with $state so updates render
- Reserve a scrollbar gutter in the modal body instead of padding tricks
- Make the sidebar weather responsive


**Full Changelog**: <https://github.com/knowald/ha-fusion/releases/tag/2026.7.2>
