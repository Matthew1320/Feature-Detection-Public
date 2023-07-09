# Feature-Detection-Public

As part of my computer vision course, I implemented a feature detection and matching program. The goal of feature detection and matching is to identify a pairing between a point in one image and a corresponding point in another image. These correspondences can then be used to stitch multiple images together into a panorama. In this project, I wrote code to detect discriminating features, which are reasonably in- variant to translation, rotation, and illumination, in an image and find the best matching features in another image.

Features were detected using the Harris Corner Detection method. Then, the detected features were described using the MOPS algorithm, making the feature descriptions reasonably invariant. Finally, the features were matched using either the Sum of Squared Distance (SSD) to match the two closest points or the Ratio test, where the distance is the ratio of the two closest features found by SSD.

Unfortunately, since this is a school project, I cannot show any code of my implementation.
