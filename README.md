# 🖼️ Image Caption Generator (Vision + NLP using Transformer)

An end-to-end deep learning project that generates captions for images using Computer Vision + Natural Language Processing techniques.  
This project uses **InceptionV3 (CNN)** for extracting image features and a **Transformer-based Decoder** for generating captions.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Pleiades_large.jpg/800px-Pleiades_large.jpg" width="500" alt="example" />
</p>

> Example Caption:  
> **"group of ballerinas in white tutus dresses"**

---

## 🚀 Features

- Extract image features using pre-trained InceptionV3 (CNN).
- Use Transformer Decoder to generate captions.
- Trained on Flickr8k dataset (option to increase dataset size).
- Simple greedy search caption generation.
- Optional beam search for better captions.
- Visualize generated captions along with images.
- Easy to extend to more datasets or Transformer variations.

---

## 📚 Dataset

- [Flickr8k Dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)
- [Flickr8k Captions](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)

You can also easily modify the notebook to use other datasets like [MS COCO](https://cocodataset.org/#home).

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/image-caption-generator-transformer.git
cd image-caption-generator-transformer
