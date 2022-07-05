# Image_Stitching

This is a program that takes as input two images that are related by a rotation homograph, a right (uttaver-right.jpg), left. (large2-uttowerdeft.jpg) and creates a single panoramic image (same size as large?-uttowerleft.jpg) as output. This is done by warping the right into the left image. findhomography method of RANSAC algorithm was used to compute the homography and then warperspective routine was used with the computed homography to warp the right image into an image of the same size as the left image.


![FinalMergedOutput](https://user-images.githubusercontent.com/71871468/177402338-6e80c181-fd32-40df-876e-9928139c7a7e.png)
