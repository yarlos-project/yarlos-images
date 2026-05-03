# YarlOS Assets & Branding

This repository serves as the central storage for all visual assets, logos, and iconography used across the **YarlOS** ecosystem. It acts as a single source of truth for system themes, `.desktop` entry icons, and educational environment branding.

## 🎨 Design Standards

- **Format:** All icons must be in `.svg` format for crisp scaling.
- **Canvas:** Use a square ViewBox (e.g., `0 0 512 512`).
- **Colors:** Follow the official YarlOS palette for consistency.

## 📂 Repository Structure

- **/logos** – Primary YarlOS brand marks
- **/icons** – Scalable application icons for system integration
- **/wallpapers** – Official desktop backgrounds
- **/assets** – UI elements and miscellaneous graphics

## 🚀 System Integration

To ensure icons are recognized by the system UI, install them into the standard Linux icon directory.

### Manual Installation

```bash
git clone https://github.com/yarlos-project/yarlos-images.git
cd yarlos-images
sudo cp -r icons/* /usr/share/icons/
```

### Branding Notice

The "YarlOS" name and logo are part of the project's identity and may not be used for redistribution, branding, or derivative distributions without permission.

Use of these assets must not imply endorsement or official affiliation with the YarlOS Project.
