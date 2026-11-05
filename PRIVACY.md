# Privacy and beta limitations

PASTEFLOW BETA — PRIVACY AND LIMITATIONS

- Capturing is paused until you explicitly turn it on.
- History stores supported copied text, single local file paths and supported
  bitmap pixels in memory only; nothing is automatically synced to an account.
- Windows password and exclusion markers are respected when provided, but
  protected-content detection is not universal. Pause when copying secrets.
- Auto web preview defaults ON. Clicking/selecting URL history may make browser
  network requests, including to third-party resources. Turn Auto web OFF for
  sensitive links. WebView2 browser cache can remain in Windows Temp after a crash.
- A local image-file path can be opened for preview; external network paths
  are intentionally unsupported in the current beta.
- Portable vs. setup: same app behavior. Setup installs per user, adds a Start
  Menu shortcut, optionally creates a desktop shortcut, and supports uninstall.
- No background update checker or automatic update installation.
- No user telemetry, advertising SDK, or Pasteflow cloud server in this beta.
- Existing Windows clipboard content is not imported on app launch.

Beta limitations: no persistent clipboard history; 200 clips; max 256 KiB
per text clip, 4 MiB total text, 36 MiB per DIB image, 96 MiB total image
memory; one local Explorer file at a time; supported uncompressed DIB formats
only; per-video embedding rules may block YouTube playback.

The application and bundled .NET runtime are distributed without a digital
signing certificate in this first beta. Check downloads' SHA256 hashes.
