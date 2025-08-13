Palette
########

Palette Color List (Interactive)
*******************************

* **What it does**:
 * Displays all palette colors used for pixel art conversion
 * Each color can be edited using the color picker
 * Palette size is determined by "Color Count"

* **How to add colors**:
 * Change "Color Count" value to add or remove slots
 * Use the Generate Palette button to extract from an image
 * Use Load/Save/Import to manage palettes

Color Count (Integer Input)
***************************

* **What it does**:
 * Sets the number of colors in the working palette
 * Changing this updates the palette list accordingly

* **Recommended**:
 * 8-16 for stylized pixel art
 * 16-32 for more realism
 * 2-6 for a retro/gameboy look

* **Default**: 8

K-means++ (Toggle)
******************

* **What it does**:
 * Enables smart palette initialization for palette generation
 * Often produces more visually pleasing palettes

* **Default**: Enabled

Generate Palette (Button)
*************************

* **Action**:
 * Analyzes the currently selected image and automatically creates a palette
 * Uses K-means clustering if enabled

* **Best practice**:
 * Use for quick palette extraction from references

Load Palette (Button)
*********************

* **Action**:
 * Imports an existing palette from file
 * Supports JSON, GPL, PAL, HEX, TXT, ACT

* **Tip**:
 * For hundreds of beautiful palettes, visit: https://lospec.com/palette-list

Save Palette (Button)
*********************

* **Action**:
 * Exports the current palette to your chosen format
 * Formats: JASC PAL, JSON, GPL, TXT

Clear Palette (Button)
**********************

* **Action**:
 * Removes all colors from current palette

Load Default Palette (Button)
*****************************

* **Action**:
 * Loads the built-in DawnBringer-32 palette
 * Good starting point for most pixel art projects
