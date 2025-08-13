Sampling & Filters
###################

Scale Mode (Dropdown)
**********************

* **Options**:
 * "Relative": Scales based on original size (recommended for most cases)
 * "Absolute": Sets exact pixel dimensions

* **Best practice**:
 * Use "Relative" for batch or quick workflow
 * Use "Absolute" for precise output sizes

Scale X / Scale Y (Sliders)
****************************

* **What it does**:
 * Sets how much to scale the width/height of the image in "Relative" mode

* **Range**:
 * 0.01 to 1.0 (1.0 = no scaling)
 * **Default**: 0.25

Absolute Width / Height (Inputs)
********************************

* **What it does**:
 * Sets exact pixel size in "Absolute" mode
 * Use for fixed-resolution spritesheets or tiles

* **Range**:
 * 1 to 8192

Sampling Method (Dropdown)
***************************

* **Choices**:
 * Nearest (blocky, classic pixel look)
 * Bilinear, Bicubic, Lanczos (softer, more accurate)
 * Cluster (experimental)

X Offset / Y Offset (Sliders)
*****************************

* **What it does**:
 * Fine-tune image offset before processing
 * Useful for aligning sprites

Blur (Slider)
*************

* **What it does**:
 * Adds pre-filtering blur to the image
 * Can soften noisy or dithered images

Sharpen (Slider)
****************

* **What it does**:
 * Applies sharpening to enhance edges before pixel art conversion
