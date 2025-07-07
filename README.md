# 🧠 DCGAN Face Generator using PyTorch (CPU-Friendly)

Welcome to the world of AI-generated human faces!

This project is a **Deep Convolutional Generative Adversarial Network (DCGAN)** implemented in **PyTorch**, capable of generating realistic human faces using the **CelebA dataset** — **no GPU needed!** 🧑‍💻✨

<p align="center">
  <img src="https://discuss.pytorch.org/uploads/default/original/3X/6/e/6ec1a5685ba764e3bb313d1d18f2e0357f129d14.png" width="400" alt="DCGAN Architecture">
</p>

---

## 🚀 Why This Project?

🔍 Have you ever wondered how AI can create faces that don’t exist?

This project demystifies that by building a GAN from scratch and training it on thousands of celebrity faces. You’ll see how a random vector of numbers can morph into a completely new human face — pixel by pixel!

---

## 📸 Sample Output

Once training completes, generated faces will be shown **inside the notebook** using matplotlib.

---

## 📂 Project Structure
```
dcgan-face-generator/
├── image_generation.ipynb
├── README.md
└── .gitignore
```
---

## 🧠 What You'll Learn

✅ How GANs work — Generator vs Discriminator  
✅ How to preprocess image data for deep learning  
✅ How to train GANs **on CPU**  
✅ How to visualize generated faces with matplotlib  

---

## 🛠️ Tech Stack

- 🐍 Python 3.x
- 🔦 PyTorch
- 🎨 TorchVision
- 📊 Matplotlib
- 🚀 TQDM

---

## 📦 Installation

```bash
git clone https://github.com/ayu-sh100/dcgan-face-generator.git
cd dcgan-face-generator
pip install -r requirements.txt
```

---

## 🧪 How to Run

1. 📥 **Download** the [CelebA Dataset](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

2. 📂 **Extract the images** into a folder called `face/img_align_celeba/` inside your project directory:

```
dcgan-face-generator/
├── face/
│ └── img_align_celeba/
│ ├── 000001.jpg
│ ├── 000002.jpg
│ └── ...
```

3. ▶️ **Run the Jupyter Notebook**  
Open `image_generation.ipynb` using Jupyter Notebook, Google Colab, or VS Code and execute the cells sequentially.


