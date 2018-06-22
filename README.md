[![License](https://img.shields.io/cocoapods/l/SwiftyXMLParser.svg?style=flat)]

# ExportLayers 

```
This repo contains a javascript made specifically for Adobe Illustrator to help productivity during 
development.  This script will export each layer as an individual image to the directory you choose.  
It also can create all images required for an iOS project (@2x, @3x, and AppIcon) based on the 
configuration and layer names.

Demo Video:  https://youtu.be/ktsjBA-Ayxw
```

### Parameters

```
* Scaling - Size of export image in respect to current size
* Border Buffer - Number of Pixels left open around image.  Use for aliased images.
* Output Directory - Directory where files will be stored
* Export Format - Type of Images Exported
* Transparency - Background Transparency
* AntiAliasing - 
* iOS - Will automatically produce @2x, @3x images.  Any layer with "appicon" or "appIcon" in the name 
will produce all iOS required AppIcon images for the given layer. 
```

## Motivation

```
Increased productivity when developing image sets for projects where the developer wants to work 
on multiple images in the same space.  Great for developing images required for mobile device apps.
```

## Installation

```
* Download the jsx files
* Close Adobe Illustrator
* Copy jsx files to Adobe Illustrator Scripts directory 
  (Applications/Adobe Illustrator CS6/Presets/en_US/Scripts on Mac)
* Open Adobe Illustrator
* Open a New or Existing File in Adobe Illustrator (returns error if no file open)
* Click File -> Scripts in Adobe Illustrator
```

## Contributors

```
David Vallas (david_vallas@yahoo.com)
```

## License

```
MIT
```
