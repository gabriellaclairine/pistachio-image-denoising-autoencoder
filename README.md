# 🌰 Pistachio Image Denoising with Convolutional Autoencoder

This project applies a **convolutional autoencoder** to reconstruct clean pistachio images from noisy inputs.  
It demonstrates how deep learning can be used for **image denoising, feature extraction, and reconstruction** in agricultural datasets.

---

## ⚙️ Project Workflow

1. **Data Preparation**  
   - Loaded the Pistachio dataset (images of different pistachio classes).  
   - Added synthetic noise to the images for training the denoising task.  
   - Split data into training and testing sets.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized original, noisy, and reconstructed pistachio images.  
   - Checked dataset balance across pistachio categories.  

3. **Modeling (Convolutional Autoencoder)**  
   - **Encoder**: Conv2D + MaxPooling to compress features.  
   - **Decoder**: Conv2D + UpSampling to reconstruct images.  
   - Used dropout to improve generalization.  

4. **Training**  
   - Input: noisy pistachio images.  
   - Output: clean pistachio images.  
   - Optimized with **MSE loss** for reconstruction quality.  

5. **Evaluation**  
   - Compared noisy → reconstructed → original pistachio images.  
   - Monitored training/validation loss.  
   - Assessed how well noise was removed.  

---

## 📈 Results and Conclusion

- The autoencoder was able to **denoise pistachio images** effectively.  
- Key visual features of pistachios were preserved after reconstruction.  
- This approach shows potential for **image cleaning and preprocessing** in agricultural ML tasks.
