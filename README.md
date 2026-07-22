# Dark Midnight Pink

A high-contrast, distraction-free workspace aesthetic built for Visual Studio Code. Featuring a striking blend of deep midnight bases, vibrant cyber pink accents, and high-readability structural highlights, this extension package includes both **Dark** and **Light** variants for seamless workflow flexibility.

---

## Theme Previews

### Dark Midnight Pink 2.0 (Dark)
![Dark Midnight Pink Preview](./image.png)

### Dark Midnight Pink Light 2.0 (Light Variant)
![Dark Midnight Pink Light Preview](./light.png)

---

## Package Highlights & Themes

This extension package provides two distinct color themes tailored for day-and-night programming sessions:

### 1. Dark Midnight Pink 2.0 (Dark)
* **Pitch-Black Base (`#000000`):** Maximizes panel performance and minimizes eye strain during late-night coding sessions.
* **Vivid Cyber Pink (`#b81858`) & Electric Cyan (`#4edbec`):** Drives immediate visual triage for active focus states, syntax highlights, and Git diagnostics.
* **Deep Plum Structural Architecture (`#471a2c`):** Replaces generic grey panel borders with clean, cohesive visual separation.

### 2. Dark Midnight Pink Light 2.0 (Light Variant)
* **Soft Pink Canvas (`#fdf2f7`):** An eye-friendly, low-glare backdrop designed to maintain high readability and eliminate glare during bright daytime coding.
* **Adapted Magenta & Rose Accents:** Reimagines signature pink and plum accents into crisp, high-contrast dark tones against a soft pink editor canvas.
* **Unified UI Flow:** Maintains the exact structural hierarchy and file status indicators as the dark variant for seamless context switching.

---

## Activation & Quick Start

1. Install **Dark Midnight Pink** directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/).
2. Open your Theme Preferences via **File > Preferences > Theme > Color Theme** (or press `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`).
3. Choose your preferred variant from the dropdown list:
   * **`Dark Midnight Pink 2.0`** *(Dark)*
   * **`Dark Midnight Pink Light 2.0`** *(Light)*

> **Tip:** To automatically switch between the dark and light variants based on your OS settings, add the following to your `settings.json`:
>
> ```json
> "window.autoDetectColorScheme": true,
> "workbench.preferredDarkColorTheme": "Dark Midnight Pink 2.0",
> "workbench.preferredLightColorTheme": "Dark Midnight Pink Light 2.0"
> ```

---

## Customization Overrides

You can further refine specific UI contrast levels locally by overriding key attributes in your `settings.json` file:

```json
"workbench.colorCustomizations": {
  "[Dark Midnight Pink 2.0]": {
    "editor.background": "#000000",
    "statusBar.background": "#000000"
  },
  "[Dark Midnight Pink Light 2.0]": {
    "editor.background": "#fdf2f7",
    "statusBar.background": "#f3c2d8"
  }
}