# IST-Deep-Learning-based-Codec-Optimization

Six different images from JPEG-AI test was compressed in three diffrent bitrates correspond to low, midium, and high qualities using VAE-Hyper-X codec, where X is the image quality metric used in the optimization. The compressed images are available in Images/.<br />
Decoded images were evaluated by people through a pairwise subjective test via Amazon mechanical Turk (AMT) in three different sessions. The winning frequency of each session was calculated and reported in the results/. <br />

- Image quality metics:
  - MSE: Mean Squared Error
  - SSIM: Structural Similarity Index Metric
  - MS-SSIM: Multi-Scale Structural Similarity Index Metric
  - FSIM: A feature similarity index for image quality assessment
  - GMSD: Gradient magnitude similarity deviation: A highly efficient perceptual image quality index
  - LPIPS: Image quality assessment: Unifying structure and texture similarity
  - DISTS: Perceptual image quality assessment using a normalized laplacian pyramid
  - NLPD: Normalized Laplacian Pyramid Distance
  - VSI: A visual saliency-induced index for perceptual image quality assessment

# Citation

```
@INPROCEEDINGS{10018061,
  author={Mohammadi, Shima and Ascenso, João},
  booktitle={2022 Picture Coding Symposium (PCS)},
  title={Perceptual impact of the loss function on deep-learning image coding performance},
  year={2022},
  volume={},
  number={},
  pages={37-41},
  doi={10.1109/PCS56426.2022.10018061}}
```

# Acknowledgements

This work is funded by FCT/MCTES through national funds and when applicable co-funded EU funds under the project DARING with reference PTDC/EEI-COM/7775/2020.
