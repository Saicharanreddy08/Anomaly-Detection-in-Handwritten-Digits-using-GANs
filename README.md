# Anomaly Detection in Handwritten Digits – A GAN-based Approach

This project implements **anomaly detection** in handwritten digit images using a **Generative Adversarial Network (GAN)**.  
Digits **0–4** are treated as *normal data*, while digits **5–9** are considered *anomalies*.  
The GAN learns the distribution of normal digits and identifies deviations as anomalies.

---

## 🚀 Features
- Preprocessing of MNIST dataset (0–9 digits)
- Training a GAN on normal digits (0–4)
- Detection of anomalies (5–9) based on reconstruction error
- Visualization of training and anomaly detection results
- Interactive UI to test the model on custom digit inputs

---

## 🛠️ Tech Stack
- **Python**
- **PyTorch / TensorFlow** (choose based on your implementation)
- **NumPy, Pandas**
- **Matplotlib / Seaborn**
- **Next.js + TailwindCSS (UI components)**

---

## 📂 Project Structure
├── app/ # Next.js application
├── components/ # Reusable UI components
├── hooks/ # Custom React hooks
├── lib/ # GAN model, utils, digit recognition
├── styles/ # Global CSS and Tailwind setup
├── notebooks/ # Jupyter notebooks for model training & testing
├── package.json # Project dependencies
└── README.md # Project documentation


## 📊 Results
- GAN successfully distinguishes between normal and anomalous digits.
- Visual comparisons of generated vs. anomalous samples.
- Detection accuracy improves with more training epochs.

---

## 🚦 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/murthypendyala/Anomaly-Detection-in-Handwritten-digits-A-GAN-based-approach.git
   cd Anomaly-Detection-in-Handwritten-digits-A-GAN-based-approach
Install dependencies:
pip install -r requirements.txt

Train the model:
python train.py

Run the UI:
npm install
npm run dev


📌 Future Work
Extend to other anomaly detection datasets.

Improve GAN stability with WGAN/Autoencoder hybrids.

Deploy as a full web app for real-time digit anomaly detection.

👤 Author
Murthy Pendyala
📧 Mail ID: nanipendyala8601@gmail.com
🌐 LinkedIn: www.linkedin.com/in/murthy-pendyala
