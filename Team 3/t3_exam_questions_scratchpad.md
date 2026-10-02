# Exam Question Proposals

## General hints:
* Only questions, no answers! Keep answers elsewhere
* No yes-no questions!
* Per week, three questions on three levels (reproduce, apply, analyze)

## Example questions for one week:
* Reproduce: State the Nyquist sampling theorem and describe its significance for image sampling.
* Apply: Given an image containing details up to a specified spatial frequency, determine the minimum sampling frequency needed to avoid aliasing.
* Analyze: Explain how under sampling causes aliasing and compare the resulting image artifacts with those produced by sampling at or above the Nyquist rate.

## Week 2 — Exam Question Proposals:
* Reproduce: Define image exposure and signal-to-noise ratio (SNR), and describe how each affects the quality of a captured image.
* Apply: An imaging system records an image with a given signal level and noise level. Calculate the resulting SNR and determine how the SNR changes when the exposure      time is increased by a specified factor.
* Analyze: Explain how exposure time influences signal, noise, and SNR in image acquisition. Compare the expected image quality for short and long exposures and discuss    the trade-offs involved in choosing the exposure time.

## Week 3 — Homography, Feature Matching and Image Alignment:
* Reproduce: Define homography and state the minimum number of corresponding point pairs required to estimate a planar homography between two images.
* Apply: Two images of the same building facade contain several corresponding feature points. A homography matrix has been estimated from these correspondences. Describe the transformation that should be applied to one image so that its corresponding features coincide with those in the reference image.
* Analyze: Two images contain 40 feature correspondences, but several correspondences are incorrect because of repetitive patterns and mismatched features. Analyze how an incorrect correspondence can affect homography estimation and explain why a robust estimation method is needed.

## Week 4 — Global Alignment Optimization and Stitching:
* Reproduce: What is the purpose of global alignment optimisation in a system that stitches multiple overlapping images?
* Apply: Three overlapping images produce pairwise alignment errors of 1.8 pixels, 3.6 pixels, and 5.2 pixels. How would these error values be used to assess the consistency of the image alignment, and which image pair would require the closest inspection?
* Analyze: During global optimization of a multi-image panorama, improving the alignment between two neighbouring images causes a small increase in the alignment error between another pair of images. Analyze why such a trade-off can occur and how global optimization addresses the alignment of the complete image set.
