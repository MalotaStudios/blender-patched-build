# blender-patched-build

Builds the official Blender release for macOS Apple Silicon on GitHub Actions with the patches in `patches/` applied, and publishes a `.dmg`.

* `patches/graph-editor-trackpad-zoom.patch` – inverts trackpad zoom in 2D editors (Graph Editor, etc.) so it matches the 3D Viewport. Only active when multi-touch gestures are enabled (Preferences ▸ Input ▸ Trackpad).

The app is ad-hoc signed, not notarized. First launch: right-click ▸ Open, or `xattr -dr com.apple.quarantine /Applications/Blender.app`.

Blender is © Blender Foundation, GPL-2.0-or-later. Source: https://projects.blender.org/blender/blender
