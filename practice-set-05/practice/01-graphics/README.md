# README

## Web Graphics (svg, gif, png)

### Instructions

*Note:* There are not necessarily right or wrong answers for this exercise. It is more about working through the process of editing images, making sure they are exported to a proper format and developing a personal sense of what "looks good" versus the file size of an image.

An HTML document has been provided for you which includes paths to images which have not yet been created. Your task is to export the image into different file formats.

1. Add the `canes-logo.svg` file included in the `01-graphics` folder to line 12 of `index.html`. Use your computer's Finder (macOS) or File Explorer (Windows) to determine the size of this file. Add this information in the paragraph below.

2. Open `canes-logo.svg` in Photoshop. (Do not double-click on the file to open as it will re-direct you to Illustrator!) You will be asked to "Rasterize" the SVG image. Set the Resolution to 72 pixels/inch. Next, set the width to 600 pixels. The height should automatically be re-adjusted to 361 pixels.

3. Using the "Save for Web (Legacy)" panel, export the image three times -- once as a GIF, a PNG-8 and a PNG-24. In each case, make sure the "Transparency" option is selected. Before exporting these files, note the size of the file in the bottom, left corner of the panel. Include this information in the paragraph below each image. Name each exported file according to the filenames specified in `index.html`. (Be sure to save these in the `01-graphics` folder.)

4. When finished, view the completed `index.html` file in your web browser. Inspect the differences in file size and whether there are any discernible quality defects.

*Note:* The SVG will be MUCH larger than your exported images. This is because the SVG is a vector graphic and without specific dimensions, will stretch as big as the vector allows. If you'd like to see the dimensions change, remove the commented out code on lines 6-13. This will not change the size of the `canes-logo.svg`.
