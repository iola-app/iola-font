# Font iola

## Workflow

- `iola.sfd` - Font source that you can open with [FontForge](https://fontforge.github.io/)
  - Generate font via `File > Generate Fonts...` with these `Options`:
![Options](/info/options.png)
- `iola.ttf` - Generated font
- `/icons` - Source SVG icons
  - All icons has Artboard size `1024 x 1024` 
  - Edit icons with Adobe Illustrator
  - Export icons via `File > Export > Export As`
    - Click on `Use Artboards`:
    ![Export Step 1](/info/export1.png)
    - Export with these `SVG Options`: 
    ![Export Step 1](/info/export2.png)
- `glyphMap.json` - Glyph Map for further font usage with JavaScript:
  ![glyphMap](/info/glyphMap.png)
