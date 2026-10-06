# GlideMouse releases

GlideMouse is a macOS mouse utility for smooth wheel scrolling and configurable auxiliary mouse buttons. Settings stay on your Mac. This repository hosts release downloads and the update feed, not user settings or signing private keys.

## Current development release

[Download development releases](https://github.com/MinnKhantThuu/GlideMouse-updates/releases)

Version 0.2.1 is a Developer ID signed universal macOS build (Apple Silicon and Intel, macOS 14+). It is a prerelease and is not yet notarized; Gatekeeper may prevent it opening on another Mac. Magic Mouse hardware support and Intel runtime behavior are not yet verified. Existing mappings are retained when upgrading. Accessibility and Input Monitoring are required for mouse actions.

## Updates

The HTTPS appcast is `https://raw.githubusercontent.com/MinnKhantThuu/GlideMouse-updates/main/appcast.xml`.

The feed is initially empty while notarized update releases are prepared. It does not offer the unnotarized development prerelease for automatic installation. The app provides automatic-check and automatic-download/install preferences. Future update archives will be EdDSA signed and Developer ID signed/notarized before they are listed in the feed.

No typed text, device serials, diagnostics, user configuration or private signing key is published here.
