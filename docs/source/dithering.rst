Dithering
###########

Dither Type (Dropdown)
**********************

* **Options**:
 * None: No dithering (flat color)
 * Bayer (2x2, 4x4, 8x8): Ordered dithering for smooth transition
 * Cluster (4x4, 8x8): Clustered-dot dithering
 * Floyd-Steinberg (FS1, FS2): Classic error diffusion
 * Median: Median Cut quantization

* **Recommendations**:
 * Bayer/Cluster for retro/console look
 * Floyd-Steinberg for photorealistic
 * Median for painterly or soft images

Dither Strength (Slider)
************************

* **What it does**:
 * Adjusts the intensity of the dithering effect (not available for all types)

* **Default**: 0.2

Target Colors (Integer Input, Median only)
******************************************

* **What it does**:
 * Controls palette size for Median Cut quantization

Distance Metric (Dropdown)
**************************

* **What it does**:
 * Chooses the math used for color comparison (impacts dithering quality)
 * Options: Euclidean, Weighted, Redmean, CIE76, CIE94, CIEDE2000

Alpha Threshold (Integer Input)
*******************************

* **What it does**:
 * Sets the minimum alpha value for a pixel to be considered opaque

* **Default**: 128
