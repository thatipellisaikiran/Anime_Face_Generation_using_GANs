# Anime Face Generation using GANs

## Project: Anime Face Generation using GANs (Notebook: `gan_anime_faces.ipynb`)

### Project Overview

This project focuses on training a Generative Adversarial Network (GAN) to generate anime-style faces. The implementation is contained within the notebook `gan_anime_faces.ipynb`, which includes:

* Data preparation
* Model definition (Generator and Discriminator)
* Training loop
* Checkpoint saving
* Sample generation and evaluation visualization

---

### Repository Structure

```
├── gan_anime_faces.ipynb     # Main Jupyter notebook
├── README.md                 # Project documentation
```

---

### Dataset

This project requires an image dataset of anime faces (preferably cropped and square images).

#### Common Sources

* Kaggle Anime Face Datasets (search for “anime face dataset” on Kaggle)
* Custom scraped datasets (ensure you have usage rights)

#### Prepare the Dataset

1. Create a `data/` directory in your project root.
2. Place all anime face images (`.jpg` or `.png`) inside `data/images/`.
3. Optionally, preprocess images in the notebook to resize and clean them before training.

**Example Folder Structure:**

```
data/
└── images/
    ├── 000001.png
    ├── 000002.png
    └── ...
```

---

### Inference (Generate New Faces)

Once training is complete, use the Generator model to create new anime-style faces. In the notebook, load the trained Generator checkpoint and run the inference cell to generate and save new images.

---

### Evaluation & Visualization

* The notebook visualizes training progress and generated samples.
* Sample grids are created at checkpoints to evaluate how the Generator improves.
* You can optionally compute evaluation metrics such as FID or Inception Score.

---

### Conclusion

The **Anime Face Generation using GANs** project demonstrates the power of Generative Adversarial Networks in creating realistic and creative visual content. Through this implementation, we observe how deep learning models can learn the underlying distribution of anime face datasets and generate new, unseen faces with similar characteristics. With further training and larger datasets, the model can produce even higher-quality and more diverse results, showcasing the potential of GANs in art, animation, and creative AI applications.

---


