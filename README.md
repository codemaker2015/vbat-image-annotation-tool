# vbat - Box Annotation Tool
Fast and efficient BBox annotation for your images in YOLO and VOC/COCO formats.

| Screenshot 1 | Screenshot 2 |
|:---:|:---:|
| ![Sample](https://github.com/codemaker2015/vbat-image-annotation-tool/blob/master/screenshots/screenshot1.png) | ![Sample](https://github.com/codemaker2015/vbat-image-annotation-tool/blob/master/screenshots/screenshot2.png) |


## USAGE
1. Download the zip.
2. Extract it.
3. Open `index.html` in your browser.
4. Load images and classes and start bboxing!

## CONFIGURATION
1. Open vbat.js.
2. Edit section named `parameters`.

## COMPATIBILITY
All browsers that support ES6 should work. Tested with:

* Chrome
* Firefox

## FEATURES
* **Pascal VOC and COCO format support.**
* Works in your browser on any platform.
* Complete YOLO format support.
* No need for image upload - everything is done locally!
* Zooming and panning images with guidelines for precise bboxing.
* Fast navigation for quick bboxing.
* Auto save in memory in case of accidental refreshes and crashes.
* Ability to crop your bboxes and save the resulting images.
* Information on both image and current bbox.

## CONSIDERATIONS
* Loading many and or big images might take a while. This is because tool needs to figure out image dimensions.  
* Cropping many items might crash your browser.
