# ✋ Vision Generative Model - ASL Alphabet Conditional Image Generation

This project was developed as part of the **Generative AI Solutions** module.

The goal of this assignment is to design and train a **conditional generative vision model** to generate images of American Sign Language (ASL) alphabets.  
The model learns to generate realistic hand-sign images conditioned on a given alphabet class label.

The dataset consists of 28×28 grayscale images representing 24 ASL alphabet categories.  
For this assignment, the model focuses on generating images from **10 assigned alphabet classes**.

---

## 🎯 Project Objective

The objective of this project is to:

- build a conditional generative model for ASL alphabet image generation
- generate visually accurate and diverse images conditioned on class labels
- experiment with model architectures and hyperparameters
- evaluate the quality of generated images for the selected alphabet classes

---

## 🧱 Key Tasks

- Load and explore the ASL alphabet image dataset
- Visualise and understand the data distribution
- Design and train a conditional generative model
- Generate new ASL alphabet images using:
  - random noise vectors
  - class label conditions
- Compare model performance through qualitative results

---

## 👩‍💻 My Role

This is a paired coursework project for the **Generative AI Solutions** module.

I was responsible for:

- implementing my own conditional generative model for comparison
- preparing and preprocessing the ASL image dataset
- performing exploratory data visualisation
- tuning hyperparameters and analysing training behaviour
- generating and evaluating class-conditioned ASL images

---

## 🛠️ Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib

---

## 🧠 What this project demonstrates

- building conditional generative models for computer vision tasks
- applying deep learning techniques to image generation
- conditioning generative models on categorical labels
- analysing model behaviour and training stability
- evaluating generative results through visual inspection

---

## ▶️ Methodology

1. **Dataset loading and exploration**
   - Loaded the ASL dataset and visualised samples from each class
   - Verified image dimensions and label consistency

2. **Model design**
   - Built a conditional generative model architecture
   - Used class labels as additional input to both the generator and discriminator

3. **Training and optimisation**
   - Started with a baseline model
   - Experimented with hyperparameters such as learning rate, batch size and latent dimension
   - Monitored training behaviour and adjusted configurations accordingly

4. **Evaluation**
   - Generated new images using random noise and selected class labels
   - Visually compared generated samples across the 10 assigned alphabet categories

---

## 📌 Notes

Only the 10 assigned alphabet classes were used for image generation, as specified in the assignment requirements.

---

This project was completed as part of the **Generative AI Solutions** module and demonstrates my ability to design, train and evaluate conditional generative vision models for structured image generation tasks.

