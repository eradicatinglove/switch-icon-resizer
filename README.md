===========================================
           Switch Icon Resizer
                by The OTher Side
===========================================

This tool allows you to create high-quality
256x256 Nintendo Switch icons from any image.

It requires NO installation, NO Python, and
NO external tools. Just run the .exe and go.

-------------------------------------------
  FEATURES
-------------------------------------------

• Drag & drop any image
• Supports: JPG, PNG, WEBP, BMP, GIF, TIFF,
  ICO, TGA, and more
• Two preview modes:
    1. Preserve (Blur Background)
    2. Cropped Full-Fill
• Preserves full image without cropping
• Modern blurred background effect
• Outputs Switch-compatible icon.jpg
• Optional Game Name and Title ID fields
• Auto-creates output folders
• Light / Dark theme toggle
• High quality JPEG output (85%)
• Fully standalone (no dependencies)

-------------------------------------------
  HOW TO USE
-------------------------------------------

1. Run the EXE:
      Switch_Icon_Resizer.exe

2. Drag and drop an image into the window OR
   click “Select Image.”

3. Choose optional:
      - Game Name
      - Title ID (16-character HEX)

   These control how your folders are named.

4. Choose a mode:
      • Preserve (Blur Background)
      • Cropped Full-Fill

5. Click:
      “Resize to 256x256”

6. The converted icon will appear in:
      /output/
   inside the same folder as the EXE.

-------------------------------------------
  OUTPUT EXAMPLES
-------------------------------------------

If Game Name + Title ID are used:
    output/Game Name/TitleID/icon.jpg

If only Title ID:
    output/TitleID/icon.jpg

If only Game Name:
    output/Game Name/<filename>_256.jpg

If neither is used:
    output/<filename>_256.jpg

-------------------------------------------
  SWITCH HOME MENU COMPATIBILITY
-------------------------------------------

This tool produces:
    icon.jpg   (JPEG format)
    256 x 256 pixels
    High quality (85%)

Compatible with:
• sys-icon
• sys-tweak
• Atmosphere custom content
• LayeredFS / title override

-------------------------------------------
  KNOWN LIMITATIONS
-------------------------------------------

• Blur Preserve mode never crops the image.
  If you want full-fill, choose “Cropped.”

• The Top-Level EXE may take a few seconds
  to start on older PCs (due to PySide6 load).

-------------------------------------------
  CREDITS
-------------------------------------------

Tool and interface by:
    The OTher Side

AI-assisted development through ChatGPT

-------------------------------------------
  NOTES
-------------------------------------------

You may freely distribute this EXE.
No copyright, license, or permission needed.

Enjoy creating clean custom Switch icons!
