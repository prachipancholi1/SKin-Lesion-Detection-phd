
# SKin-Lesion-Detection-phd

This project focuses on classifying skin lesion images into three categories: **psoriasis**, **eczema**, and **keratoses**. It utilizes both traditional machine learning and deep learning approaches to achieve accurate classification.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Getting Started](#getting-started)
- [License](#license)

## Overview

Skin diseases like psoriasis, eczema, and keratoses often exhibit similar visual characteristics, making accurate diagnosis challenging. This project aims to develop models that can distinguish between these conditions using image classification techniques.

## Dataset

The dataset used for this project is sourced from [DermNet](https://dermnetnz.org/), a comprehensive online resource for skin conditions. Images are categorized into three classes:

- **Psoriasis**
- **Eczema**
- **Keratoses**

The dataset is split into training and testing sets with varying ratios (70:30, 80:20, 90:10) to evaluate model performance under different conditions.

## Notebooks

The repository contains several Jupyter notebooks that implement different models and data splits. Each notebook can be directly opened in Google Colab for interactive execution:

### 📘 Open Notebooks in Google Colab
| Notebook Filename                                         | Description                              | Open in Colab Link                                                                                                                                             |
|-----------------------------------------------------------|------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `DermNet_Image_ClassssificationML_70_30.ipynb`            | Machine Learning (70:30 train-test split) | [Open in Colab](https://colab.research.google.com/github/prachipancholi1/SKin-Lesion-Detection-phd/blob/main/DermNet_Image_ClassssificationML_70_30.ipynb)     |
| `DermNet_Image_ClassssificationML_80_20.ipynb`            | Machine Learning (80:20 train-test split) | [Open in Colab](https://colab.research.google.com/github/prachipancholi1/SKin-Lesion-Detection-phd/blob/main/DermNet_Image_ClassssificationML_80_20.ipynb)     |
| `DermNet_Image_ClassssificationML_90_10.ipynb`            | Machine Learning (90:10 train-test split) | [Open in Colab](https://colab.research.google.com/github/prachipancholi1/SKin-Lesion-Detection-phd/blob/main/DermNet_Image_ClassssificationML_90_10.ipynb)     |
| `DermNet_Image_Classssification_70_30_DeepLearning.ipynb` | Deep Learning (70:30 train-test split)    | [Open in Colab](https://colab.research.google.com/github/prachipancholi1/SKin-Lesion-Detection-phd/blob/main/DermNet_Image_Classssification_70_30_DeepLearning.ipynb) |
| `DermNet_Image_Classssification_80_20_DeepLearning_.ipynb`| Deep Learning (80:20 train-test split)    | [Open in Colab](https://colab.research.google.com/github/prachipancholi1/SKin-Lesion-Detection-phd/blob/main/DermNet_Image_Classssification_80_20_DeepLearning_.ipynb) |
| `DermNet_Image_Classssification_90_10_DeepLearning.ipynb` | Deep Learning (90:10 train-test split)    | [Open in Colab](https://colab.research.google.com/github/prachipancholi1/SKin-Lesion-Detection-phd/blob/main/DermNet_Image_Classssification_90_10_DeepLearning.ipynb) 

To open any notebook in Colab, simply click on the corresponding "Open in Colab" link This will launch the notebook in a new browser tab, allowing you to run and modify the code interactively

## Getting Started

To run the notebooks:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/prachipancholi1/SKin-Lesion-Detection-phd.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd SKin-Lesion-Detection-phd
   ```

3. **Install the required dependencies:**

   Ensure you have Python 3.x installed. Then, install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```
   
   *Note: If `requirements.txt` is not provided, manually install the required packages as specified in the notebooks.*

4. **Run the notebooks:**

   Open the desired notebook using Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook
   ```

   Then, navigate to the notebook you wish to run.

## License
This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
