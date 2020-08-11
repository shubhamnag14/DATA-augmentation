# DATA-augmentation
Data augmentation is the process of increasing the amount and diversity of data. We do not collect new data, rather we transform the already present data.
Data augmentation is an integral process in deep learning, as in deep learning we need large amounts of data and in some cases it is not feasible to collect thousands or millions of images, so data augmentation comes to the rescue. It helps us to increase the size of the dataset and introduce variability in the dataset..

<pre>
<h3>The most commonly used operations are-
1.Rotation
2.Shearing
3.Zooming
4.Cropping
5.Flipping
6.Changing the brightness level
</h3>
</pre>
<pre>
Many augmentation techniques
E.g. affine transformations, perspective transformations, contrast changes, gaussian noise, dropout of regions, hue/saturation changes, cropping/padding, blurring, ...
Optimized for high performance
Easy to apply augmentations only to some imagesEasy to apply augmentations in random order
Support for
Images (full support for uint8, for other dtypes see documentation)
Heatmaps (float32), Segmentation Maps (int), Masks (bool)May be smaller/larger than their corresponding images. No extra lines of code needed for e.g. crop.
Keypoints/Landmarks (int/float coordinates)
Bounding Boxes (int/float coordinates)Polygons (int/float coordinates)
Line Strings (int/float coordinates)
Automatic alignment of sampled random values
Example: Rotate image and segmentation map on it by the same value sampled from uniform(-10°, 45°). (0 extra lines of code.)
Probability distributions as parameters
Example: Rotate images by values sampled from uniform(-10°, 45°).
Example: Rotate images by values sampled from ABS(N(0, 20.0))*(1+B(1.0, 1.0))", where ABS(.) is the absolute function, N(.) the gaussian distribution and B(.) the beta distribution.
Many helper functions

