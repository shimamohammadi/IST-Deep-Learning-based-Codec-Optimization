# IST-Deep-Learning-based-Codec-Optimization
Six different images from JPEG-AI test was compressed in three diffrent bitrates correspond to low, midium, and high qualities using VAE-Hyper-X codec, where X is the image quality metric used in the optimization. The compressed images are available in Images/.
Decoded images were evaluated by people through a pairwise subjective test via Amazon mechanical Turk (AMT) in three different sessions. The winning frequency of each session was calculated and reported in the results/. 
# Image quality metics:
    - MSE: Mean Squared Error
    - SSIM: Structural Similarity Index Metric
    - MS-SSIM: Multi-Scale Structural Similarity Index Metric
    - FSIM: A feature similarity index for image quality assessment
    - GMSD: Gradient magnitude similarity deviation: A highly efficient perceptual image quality index
    - LPIPS: Image quality assessment: Unifying structure and texture similarity
    - DISTS: Perceptual image quality assessment using a normalized laplacian pyramid
    - NLPD: Normalized Laplacian Pyramid Distance
    - VSI: A visual saliency-induced index for perceptual image quality assessment