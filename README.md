# Generalizing-Cardiac-Image-Segmentation-
 Building Machine Learning models that generalize cardiac image segmentation using various MRI scans collected from different clinical centres.
 Based on Multi-Centre, Multi-Vendor & Multi-Disease Cardiac Image Segmentation Challenge (M&Ms)-      https://www.ub.edu/mnms/
 Cardiac MRI scans from two different vendors were taken : 'A' and 'B'.
 Trained a U-Net model on the scans from the vendors A and B and noted he accuracy.
 Concept: Using Fourier Transform, converted scans from vendor 'A'(source images) into style of scans of vendor 'B'(target images).
 Then trained the model on scans of 'B' + the fourier transformed images.
 
