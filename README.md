# Midnight Cyberpunk (Two)

A ruthless, distraction-free **pitch-black workspace** featuring striking neon pink accents, electric cyans, and deep plum structural styling. Built specifically for developers who demand high scannability, deep screen contrast, and zero compromises on pure `#000000` dark-mode aesthetics.

---

##  Core Features

*   **Absolute Black Backdrop:** Maximizes OLED panel performance and drastically reduces eye strain during late-night programming sessions by locking the editor, sidebar, terminals, and panels to pure black.
*   **High-Scan Code Diagnostics:** Errors, warning hooks, and Git status states map to a vivid, high-contrast neon palette so you can triage line items instantly.
*   **Immersive Panel Architecture:** Completely eliminates generic grey boundaries. Floating widgets, the command center, autocomplete lists, and interactive terminals blend seamlessly into a single unified workspace layout.

---

## Preview 
![Theme Showcase](./image.png)

## Theme Palette Reference

| Spectrum Component | Hex Code | Visual Layout Assignment |
| :--- | :--- | :--- |
| **Midnight Base** | `#000000` | Code Canvas, Sidebar, Terminals, Output Frames |
| **Cyber Pink** | `#b81858` | Active Focus Highlights, Tab Highlights, Buttons |
| **Electric Cyan** | `#4edbec` | Match Highlighting, Suggestion Matches, Git Modifications |
| **Deep Plum** | `#471a2c` | Structural Borders, Active Cell Segments, Closed Frames |
| **Muted Rose** | `#7a5c6c` | Gutter Assets, Inactive File Items, Breadcrumb Resting States |

---

##  Activation Instructions

1. Install the extension directly from the VS Code Marketplace.
2. Navigate to your Theme Preferences via **File > Preferences > Theme > Color Theme** (or use the shortcut `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`).
3. Select **Midnight Cyberpunk (Two)** from the dropdown list.
4. *Optional:* If your interface elements do not dynamically repaint immediately on launch, reload your environment window layout completely via the Command Palette (`Ctrl+Shift+P` -> `Developer: Reload Window`).

---

##  Customization Hooks

Want to tweak the contrast limits further to fit your specific monitor profile? You can override any key locally inside your user profile `settings.json` file using the `workbench.colorCustomizations` block:

```json
"workbench.colorCustomizations": {
    "[Midnight Cyberpunk (Two)]": {
        "editor.background": "#000000",
        "statusBar.background": "#000000"
    }
}