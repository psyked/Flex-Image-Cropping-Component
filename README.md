Flex-Image-Cropping-Component
=============================

An image cropping component for Flex 3.  The [original website](http://blog.mediablur.com/2008/02/20/flex-image-cropping-component/) ([new link](http://modernminds.wordpress.com/2008/02/20/flex-image-cropping-component/)) that hosted this and its source code disappeared into the ether, so I've saved a copy on GitHub for posterity. This component powers the image cropping functionality of ImageSizer.

# Flex Image Cropping Component | Random Madness

[ImageCropper][1] is a free component (licensed under the [MIT License][2]) for Adobe Flex that allows an image to be cropped by adjusting the position and dimensions of a cropping rectangle that overlays the image.

<!-- ![ImageCropper Component Demo](http://modernminds.files.wordpress.com/2008/02/icdemo.jpg?w=470) -->

The image used as the source for the [ImageCropper][1] may be provided as a `BitmapData` object or as a URL that points to an external image.

The component can return the cropped image as a `BitmapData` object, or it can return a `Rectangle` that defines the cropped area. Retrieving a `Rectangle` from the component is useful if the image will be cropped on a server (perhaps by a Content Management System).

In addition to allowing unconstrained cropping, the component may be configured to constrain the cropping rectangle to an aspect ratio. For example, defining a cropping rectangle with a width of 200 pixels and a height of 100 pixels and then enabling the aspect ratio constraint will result in the cropping rectangle maintaining a 2:1 aspect ratio as it is resized.

The size of the cropping rectangle handles may be modified, as may the color and transparency values used for the handles, the cropping rectangle outline, the mask and the background.

[ImageCropper][1] is copyright © 2008 by Paul Whitelock.

Resources:

  - [ImageCropper Component Demo][1]

 [1]: http://code.mediablur.com/ImageCropper/ImageCropperDemo.html "ImageCropper Component Demo"
 [2]: http://www.opensource.org/licenses/mit-license.php "Read the MIT License"
