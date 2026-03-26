# ProForge OrcaSlicer Profiles — Installation

Profiles for the **ProForge 300**, **ProForge 4.2**, and **ProForge 5** toolchanger 3D printers.

---

## Step 1 — Copy the profile files

Download and extract the release zip, then copy the `Makertech/` folder and `Makertech.json` into the OrcaSlicer profiles directory for your platform:

> **First time installing OrcaSlicer on a MAC?** Launch OrcaSlicer first and then close it (right click on icon in dock and hit quit) before copying over the files.

| Platform | Path |
|---|---|
| Windows | `C:\Program Files\OrcaSlicer\resources\profiles\` |
| macOS | Right-click `OrcaSlicer.app` → Show Package Contents → `Contents/Resources/profiles/` |
| Linux | `~/.local/share/OrcaSlicer/resources/profiles/` |
| Linux Flatpak | `/var/lib/flatpak/app/com.orcaslicer.OrcaSlicer/current/active/files/share/OrcaSlicer/profiles` |


---

## Step 2 — Add a ProForge printer in OrcaSlicer

**New OrcaSlicer installation** — the setup wizard will appear on first launch. Select **Makertech** from the vendor list, choose your ProForge model, and the Makertech filament profiles will be pre-selected automatically.

**Existing OrcaSlicer installation** — click the printer name dropdown in the top-left of the main window, select **Add/Remove Printers**, then find **Makertech** in the vendor list and select your ProForge model.

---

## Step 3 — Enable Makertech filaments (existing installs only)

When adding a printer to an existing OrcaSlicer installation, filament profiles from the new vendor may not be automatically enabled. You will need to enable them manually:

1. Click the **filament selection** button in the main window
2. In the **Filter items** box enter **Makertech**
3. Check **Makertech PLA**, **Makertech PETG**, and **Makertech ABS**
4. Click **Confirm**

The Makertech filament profiles will now appear in the filament dropdown when a ProForge printer is selected.

---

## Troubleshooting

If Makertech doesn't appear in the printer list, confirm both `Makertech.json` and the `Makertech/` folder are present in the same `profiles/` directory, then restart OrcaSlicer.
