Image Annotation Tool
=====================

This tool facilitates the annotation of objects in images with bounding boxes. It has been written in Qt, it therefore is portable to different platforms.

Features:
* annotation of objects with bounding boxes
* support for easily modifying, copying and pasting bounding boxes
* zoom in/out
* per object, freely chosen "fix points" can mark additional points on objects (these can be used to align annotated objects more accurately)
* the rotation of an object can be annotated (with fix points)
* each object can have freely chosen properties (numbers, text)
* the tool can even by used to visualize detection results (ordered by a score value)
* a subset of visible objects in an image can be chosen
* support for properties of images (numbers, text)
* selection of objects by filtering over properties
* alignment and extraction of selected objects
* generation of random samples per annotated object by applying various distortion methods

In the Image Annotation Tool, you have a menu help->shortcuts that gives you a short list of the most common short cuts. Otherwise, keep the cursor for a longer while over buttons or text fields (in the extract dialog) to get some more hints and information.

Screenshots
-----------

![Main window with two bounding boxes annotated; for each bounding box alignment points have been specified](https://raw.github.com/alexklaeser/imgAnnotation/master/screenshots/main_window.png)
![Image extraction dialog: filter criteria for objects](https://raw.github.com/alexklaeser/imgAnnotation/master/screenshots/extraction1_object_selection.png)
![Image extraction dialog: parameters for image normalization](https://raw.github.com/alexklaeser/imgAnnotation/master/screenshots/extraction2_normalization.png)
![Image extraction dialog: for the final image extraction, a subset of images can be selected](https://raw.github.com/alexklaeser/imgAnnotation/master/screenshots/extraction3_subset_selection.png)
![Image extraction dialog: sampling parameters for extracted images](https://raw.github.com/alexklaeser/imgAnnotation/master/screenshots/extraction4_resampling.png)
