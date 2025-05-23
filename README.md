# BetterAutoName

A simple ETABS plugin that automatically renames frame elements based on the closest grid point. Compatible with **ETABS v22** and now **ETABS v21 (standalone version)**..

---

## 🔍 Overview

**BetterAutoName** helps structural engineers keep their models organized by applying a structured naming convention to frame elements using the grid system.

Only **Unique Names** are renamed — ensuring your model labels and sections remain untouched.

---

## 🧩 Naming Convention

Renamed elements follow this pattern:
{Story}_{SectionName}_{Grid}_{Suffix}


- `Story`: The level or story name in ETABS.
- `SectionName`: The name of the frame section (e.g., `W250x33`).
- `Grid`: The closest intersection point from your defined grid (e.g., `A-3`, `C-5`).
- `Suffix`: A unique identifier added **only if** the element does not align exactly with the grid (e.g., `1`, `2`, etc.).

---

## ✅ Features

- ✔ Automatically renames **frame elements** based on grid locations.
- ✔ Works even when elements are not perfectly aligned — assigns the **nearest grid**.
- ✔ Adds suffixes for **non-grid-aligned** or **secondary beams**.
- ✔ Compatible with **ETABS v22** and **ETABS v21 (standalone version)**.

---
## 📅 Changelog

### 📌 09 May 2025
- 🚀 **Frist Realese**: Added **v0.1** supporting **ETABS v22**
### 📌 17 May 2025
- 🐞 **Bug Fixes**: Fixing error **v0.1** in grid alignment detection.
- 🛠️ **New Feature**: Added **Tolerance to nearest grid** in **v0.1** for adjust grid alignment detection.
- 🖥️ **New**: Added **standalone version v0.1** supporting **ETABS v21**.
### 📌 23 May 2025
- 🚀 **Realese**: Added **v0.1** supporting **SAP2000 v26**
---

## 📥 Installation & Usage

1. Download the latest release from the [Releases](https://github.com/RidhoRF/BetterAutoName/releases) tab.
2. Run the plugin while your model is open in ETABS.
   - Use the regular version for ETABS 22.
   - For the standalone version for ETABS 21 make sure you Activate instance for API.
3. The plugin will process and rename applicable frame elements automatically.

---

## 💬 Feedback & Contributions

Found a bug? Have suggestions for improvements?

Feel free to [open an issue](https://github.com/RidhoRF/BetterAutoName/issues) or submit a pull request. Your feedback is welcome!

---

### 🔗 [GitHub Repository](https://github.com/RidhoRF/BetterAutoName)
