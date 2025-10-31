# Pix2Pix: Image-to-Image Translation using Conditional GAN

##  Project Overview
This project implements an **Image-to-Image Translation** model using a **Conditional Generative Adversarial Network (cGAN)** architecture known as **Pix2Pix**.  
The model is trained to translate input images to target images (e.g., edges → photos, maps → buildings) using paired datasets.

---

##  Objective
The goal of this project is to develop a deep learning model capable of learning a mapping from input to output images using supervised learning and adversarial training.

---

##  Technologies Used
- **Python**
- **TensorFlow 2.x**
- **Keras**
- **Matplotlib**
- **Google Colab**

---

##  Dataset
Dataset used: **Facades Dataset**  
Source: [Berkeley Pix2Pix Datasets](http://efrosgans.eecs.berkeley.edu/pix2pix/datasets/)  
This dataset contains building facade labels and their corresponding real-world images.

---

##  Model Architecture
The **Pix2Pix** framework consists of:
1. **Generator (U-Net):** Translates the input image into an output image.
2. **Discriminator (PatchGAN):** Determines if the generated image is real or fake.
3. **Loss Functions:**
   - **Adversarial Loss:** Encourages the generator to create realistic outputs.
   - **L1 Loss:** Ensures the output image is structurally similar to the target.

---

##  How to Run
1. Open the provided `.ipynb` notebook in **Google Colab**.
2. Run all cells (`Runtime → Run All`).
3. Wait for training to complete (short demo version runs 1 epoch).
4. View the generated output comparison:
   - **Input Image**
   - **Ground Truth**
   - **Generated Output**

---

##  Results
After training, the model can generate realistic building images from simple facade sketches.  
Example output shows:
- Left: Input Image  
- Center: Ground Truth  
- Right: Model Generated Image  

---

## 🏁 Conclusion
The Pix2Pix model successfully demonstrates the concept of **conditional image generation** using **GANs**.  
With extended training and more data, it can perform complex image translation tasks like:
- Sketch → Real Image  
- Day → Night  
- Map → Satellite View  

---

##  Author
**Yash Tondlekar**  
Final Year – B.Tech Electronics & Telecommunication Engineering  
Dr. Babasaheb Ambedkar Technological University, Lonere  

