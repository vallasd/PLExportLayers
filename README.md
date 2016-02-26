# PLExportLayers 

This repo contains two Java Scripts that are made specifically for Adobe Illustrator to help productivity during development.

Demo Video:  https://youtu.be/ktsjBA-Ayxw

## Code Example

### PLExportLayers 
* Exports all layers as individual image files into a chosen directory

### PLExportSublayers 
* Exports sublayers as individual image files into a subdirectory with the same name as a top layer.  If the top layer does not have a corresponding directory, the files under that layer will not be exported. 

### Parameters
* Scaling - Size of export image in respect to current size
* Border Buffer - Number of Pixels left open around image
(Useful if you use thick lines that are being cut when exported)
* Output Directory - Directory where files will be stored
* Export Format - Type of Images Exported
* Transparency - Background Transparency

## Motivation

Increased productivity when developing image sets for projects where the developer wants to work on multiple images in the same space.  Great for developing images for mobile device apps.

## Installation

* Download the jsx files
* Close Adobe Illustrator
* Copy jsx files to Adobe Illustrator Scripts directory 
  (Applications/Adobe Illustrator CS6/Presets/en_US/Scripts on Mac)
* Open Adobe Illustrator
* Open a New or Existing File in Adobe Illustrator (returns error if no file open)
* Click File -> Scripts in Adobe Illustrator

## Tests

None.

## Contributors

David Vallas

## License

MIT
