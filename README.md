# 🧠 GAN - Generative Adversarial Network

This project implements a **Generative Adversarial Network (GAN)** to generate synthetic images of celebrity faces. GANs are a class of machine learning frameworks where two neural networks (a generator and a discriminator) compete with each other to produce increasingly realistic outputs.

---

## 📦 Dataset

We used the **Celebrity Face Image Dataset** from Kaggle:
👉 [Kaggle Dataset Link](https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset)

---

## 🔧 Project Files

- `GAN_model.ipynb`: Main Jupyter Notebook that builds and trains the GAN model
- `README.md`: Project description and visuals
- `LICENSE`: Open source license

---

## 📊 Training Overview

During training, the **generator** learns to produce increasingly realistic face images, while the **discriminator** tries to detect whether an image is real or generated. Over time, the generator gets better at "fooling" the discriminator.

### Discriminator and Generator Loss During Training:

![Discriminator Generator Loss](https://github.com/altanulaszohre/GAN/assets/111522957/02af6fdb-69a1-4ed5-a519-25e1bae600ca)

---

## 🎨 Generated Results

Sample results from the generator at different stages of training:

![Generated Faces](https://github.com/altanulaszohre/GAN/assets/111522957/1cde7355-891d-49db-b8cf-c11357c7de6b)

![Output Samples 1](https://github.com/altanulaszohre/GAN/assets/111522957/a50043dc-8f03-424c-aad7-73855672f972)

![Output Samples 2](https://github.com/altanulaszohre/GAN/assets/111522957/edc23a6e-baf7-4ad6-9c54-7cae2a272db8)

![Output Samples 3](https://github.com/altanulaszohre/GAN/assets/111522957/5c941d4e-27c6-4ca4-905a-e562be01a44f)

![Final Outputs](https://github.com/altanulaszohre/GAN/assets/111522957/482c8f6b-f53b-4f53-a1d9-f004ff7af426)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/GAN.git
   cd GAN
   ```

2. Install dependencies:
   ```bash
   pip install tensorflow keras matplotlib numpy
   ```

3. Download the dataset from Kaggle and place it in the appropriate directory.

4. Open and run the notebook:
   ```bash
   jupyter notebook GAN_model.ipynb
   ```

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## 🙌 Acknowledgments

- [Ian Goodfellow](https://en.wikipedia.org/wiki/Ian_Goodfellow), inventor of GANs
- [Kaggle Celebrity Dataset](https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset)
- TensorFlow and Keras frameworks
