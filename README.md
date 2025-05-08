# BetterAutoName-ETABS

A simple ETABS plugin that automatically renames frame elements based on the closest grid point. Compatible with **ETABS v22**.

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
- ✔ Designed for **ETABS v22**.
- ✔ Lightweight and open-source.

---

## 📥 Installation & Usage

1. Download the latest release from the [Releases](https://github.com/RidhoRF/BetterAutoName/releases) tab.
2. Run the plugin while your model is open in ETABS 22.
3. The plugin will process and rename applicable frame elements automatically.

---

## 💬 Feedback & Contributions

Found a bug? Have suggestions for improvements?

Feel free to [open an issue](https://github.com/RidhoRF/BetterAutoName/issues) or submit a pull request. Your feedback is welcome!

---

### 🔗 [GitHub Repository](https://github.com/RidhoRF/BetterAutoName)
