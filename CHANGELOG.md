# Changelog

Changes are listed by public release. The release tag, app assembly version, portable ZIP and installer version are kept in sync.

## [0.1.0-beta.1] — 2026-11-05

**First public Windows x64 beta.**

### Added
- Native Windows clipboard history for Unicode text, HTTP(S) links, single local Explorer files, and supported DIB bitmap images.
- Search and category filters with immediate context-aware previews.
- Optional website and YouTube embedded previews with an external browser fallback.
- Correct clipboard-format copy-back for supported text, local file objects, and DIB images.
- A purple, light/dark, compact two-pane Studio interface with adjustable panel divider.
- Tray icon, Ctrl+Shift+V show/hide shortcut, capture-pause controls and visible feedback.
- Portable self-contained .NET x64 ZIP and a per-user Windows installer.
- Explicit Check updates link to GitHub Releases (opens only on click; no background update requests).

### Privacy
- Capture starts paused, memory-only history (cleared on Exit), bounded items and image memory, respected Windows opt-out metadata.
- Web preview is independently switchable and may contact third parties when enabled.

### Known limitations
- No saved history, multi-file capture, complete media/PDF coverage, signed binaries or automatic updater.
- Some YouTube embeds may refuse playback; WebView2 Runtime is needed for embedded web previews.
- Full live clipboard payload interoperability remains a beta validation task.
