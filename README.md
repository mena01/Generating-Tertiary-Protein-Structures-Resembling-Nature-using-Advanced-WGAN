# Generating-Tertiary-Protein-Structures-Resembling-Nature-using-Advanced-WGAN

## Generating Tertiary Protein Structures Resembling Nature using Advanced Generative Adversarial Networks

 In the field of molecular chemistry, the functions, interactions, and bonds between proteins depend on their tertiary structures. Proteins naturally exhibit dynamism under different physiological conditions, as they alter their tertiary structures to accommodate interactions with other molecular partners. We have leveraged significant advancements in Generative Adversarial Networks (GANs) to generate tertiary structures that closely mimic the natural features of real proteins, such as the backbone and local and distal characteristics. Our research has led to the development of stable model ROD-WGAN, which is capable of generating tertiary structures that closely resemble those found in nature.We have made four contributions to achieve this goal: (1) Utilizing Ratio Of Distribution (ROD) as a penalty function in the Wasserstein Generative Adversarial Networks (WGAN), (2) Developing a GAN network architecture that fertilizes the residual  block in generator, (3) Increasing the length of the generated protein structures to 256 amino acids, and (4) Revealing consistent correlations through Structural Similarity Index Measure (SSIM) in protein structures with varying lengths. These models represent a significant step towards robust deep-generation models that can explore the highly diverse set of protein molecule structures that support various cellular activities. Moreover, they provide a valuable source of data augmentation for critical applications such as molecular structure prediction, inpainting, dynamics, and drug design.

- The dataset directory provides a PDB id for proteins, code to download PDB files, and code to generate a distance matrices "training data set".


- The Network_Weights directory provides the weights of the generator network to generate distance matrices for the protein structure.

- The three files represent the network architecture of ROD_WGAN 64aa, ROD_WGAN 128aa, and ROD_WGAN 256aa that generate distance matrices of proteins structure. To run as an example, just set the path of the Network_Weights directory.
- 
![heatmap_](https://github.com/mena01/Generating-Tertiary-Protein-Structures-Resembling-Nature-using-Advanced-WGAN/assets/73284871/bb9c4709-f3fb-48c8-9e2d-facfce01f41d)

### We use the ADMM algorithm to fold the generated distance matrix.

![Fold_](https://github.com/mena01/Generating-Tertiary-Protein-Structures-Resembling-Nature-using-Advanced-WGAN/assets/73284871/c83c1c09-a3e9-45c6-bb40-8c6117871b5c)


#### We provide the generator network and its weight. In addition, the R code of folding protein structure.

#### The dataset directory provides a PDB id for proteins, code to download PDB files, and code to generate a distance matrices "training data set".








