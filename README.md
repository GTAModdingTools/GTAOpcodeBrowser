# GTA Opcode Browser

An interactive web tool for browsing, searching, and exploring GTA script opcodes (SA, VC, GTA3). Loads data directly from the Sanny Builder Library repository.

**🔗 Live Demo:** [https://gtamoddingtools.github.io/GTAOpcodeBrowser/](https://gtamoddingtools.github.io/GTAOpcodeBrowser/)

---

### ✨ Features

*   **Fast Search** - Quickly find opcodes by name or hexadecimal ID with instant results.
*   **Detailed Information** - View opcode ID, name, extension, parameters (input/output), attributes, description, and corresponding engine function.
*   **Customizable Display** - Toggle visibility of parameters, descriptions, unsupported opcodes, and engine functions to suit your needs.
*   **Multiple Data Sources** - Load opcode databases from any compatible JSON file (Sanny Builder structure) or use built-in presets for different game versions:
    *   San Andreas (PC/Mobile)
    *   Vice City (PC/Mobile)
    *   GTA3 (PC/Mobile)
*   **Smart Cards** - Clean, visually distinct cards with support status indicators and extension badges.
*   **Dark Theme** - Easy on the eyes for late-night modding sessions.
*   **Settings Persistence** - Your preferences are saved in your browser's local storage.

### 🛠️ Tech Stack
*   Pure HTML, CSS, and JavaScript — no frameworks, no bloat.
*   Responsive design that works on desktop and mobile.
*   Modern CSS features (variables, grids, animations).
*   LocalStorage API for user preferences.

### 🚀 Usage

1.  Open the [live demo](https://gtamoddingtools.github.io/GTAOpcodeBrowser/) or download `index.html` and open it locally.
2.  Use the search bar to find opcodes (e.g., `WAIT`, `0001`, `0x01F5`).
3.  Switch to the **Settings** tab to:
    *   Change the JSON data source (presets or custom URL).
    *   Toggle which information is displayed on cards.
    *   View database statistics.
4.  Click the copy button (⎘) on any card to copy the engine function name.

### 🔧 Custom Data Source

The tool accepts JSON files compatible with the [Sanny Builder Library](https://github.com/sannybuilder/library) structure. You can host your own JSON and point the browser to it via the Settings panel.

Have fun:)
