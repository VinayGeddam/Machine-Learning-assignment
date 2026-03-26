# From Pixels to Representations: Autoencoders on MNIST

##  Project Summary
This project investigates how autoencoders can learn compact representations of image data through unsupervised learning.  
- Learning latent representations
- Reconstructing input images
- Analysing how information is compressed and preserved

---

##  Dataset Information
- MNIST handwritten digits dataset
- 70,000 grayscale images (28×28 pixels)
- Classes: digits 0–9

---

##  Model Overview
A convolutional autoencoder architecture is used:

### Encoder
- Convolutional layers
- Downsampling (MaxPooling)
- Compression into latent space

### Decoder
- Upsampling layers
- Reconstruction of original images

---

##  Experiments Conducted

1. Basic autoencoder reconstruction  
2. Latent space visualisation (t-SNE)  
3. Denoising autoencoder  
4. Reconstruction error distribution  

---

##  Visual Outputs
The notebook generates:

- Sample input images  
- Original vs reconstructed comparisons  
- Training loss curves  
- 2D latent space plots  
- Noisy vs denoised outputs  
- Error distribution histogram  
