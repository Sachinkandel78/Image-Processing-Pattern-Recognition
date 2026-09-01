# Image Processing & Pattern Recognition

Lab exercises for an **Image Processing and Pattern Recognition** course, implemented in Python using **OpenCV**, **NumPy**, and **Matplotlib** inside Jupyter notebooks — covering the core building blocks of digital image processing, from color-space conversion through filtering, segmentation, and restoration etc.

---

## 🧠 Overview

| | |
|---|---|
| **Language** | Python 3 |
| **Libraries** | OpenCV, NumPy, Matplotlib |
| **Environment** | Jupyter Notebook |
| **Labs** | 7 |

---

## 📸 Lab Outputs

### Lab 1 — RGB ↔ Grayscale Conversion
Loading an image, converting between BGR/RGB color spaces, and converting to grayscale.

![Lab 1 Output](All%20lab%20Output/lab1_output.jpg)

---

### Lab 2 — Point Operations (Graylevel Transformations)
Digital negative, intensity slicing, thresholding, and contrast stretching.

![Lab 2 Output](All%20lab%20Output/lab2_output.jpg)

---

### Lab 3 — Image Arithmetic & Boolean Operations
Addition, subtraction, multiplication, and division between two images, plus bitwise operations (OR, NOT, XOR, AND).

![Lab 3 Output](All%20lab%20Output/lab3_output.jpg)

---

### Lab 4 — Smoothing Filters
Mean, median, and Gaussian blur filters compared side by side.

![Lab 4 Output](All%20lab%20Output/lab4_output.jpg)

---

### Lab 5 — Histogram Equalization
Pixel intensity histograms before and after equalization, to improve image contrast.

![Lab 5 Output](All%20lab%20Output/lab5_output.jpg)

---

### Lab 6 — Image Segmentation (Contour Detection)
Original image alongside its segmented, contour-detected result.

![Lab 6 Output](All%20lab%20Output/lab6_output.jpg)

---

### Lab 7 — Digital Image Restoration & Noise Reduction
Applying smoothing filters, injecting noise, and restoring a clean image.

![Lab 7 Output](All%20lab%20Output/lab7_output.jpg)

---

## 📁 Repository Structure

```
Image-Processing-Pattern-Recognition/
├── All lab Output/                              # Output images shown above
│   ├── lab1_output.jpg
│   ├── lab2_output.jpg
│   ├── lab3_output.jpg
│   ├── lab4_output.jpg
│   ├── lab5_output.jpg
│   ├── lab6_output.jpg
│   └── lab7_output.jpg
├── Image Processing and Pattern Recognition/     # Notebooks & sample images
│   ├── Lab1.ipynb
│   ├── Lab2/
│   │   ├── Lab2.ipynb
│   │   └── bus.jpeg
│   ├── Lab 3/
│   │   └── Untitled.ipynb
│   ├── Lab4/
│   │   ├── Lab4.ipynb
│   │   └── Pokhara.jpg
│   ├── Lab5/
│   │   ├── Lab5.ipynb
│   │   └── virat.jpg
│   ├── Lab6/
│   │   ├── Lab6.ipynb
│   │   └── shiva.jpg
│   └── Lab7/
│       ├── Lab7.ipynb
│       └── Pokhara.jpg
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- pip

### Installation

```bash
pip install opencv-python-headless numpy matplotlib jupyter
```

### Run a lab

```bash
jupyter notebook
```

Open any lab's `.ipynb` file and run the cells in order — each notebook loads its own sample image from the same folder, so keep the notebook and its image file(s) together.

## 🛠️ Concepts Covered

- Color space conversion (BGR, RGB, Grayscale)
- Point/graylevel transformations
- Image arithmetic & Boolean (bitwise) operations
- Spatial filtering (mean, median, Gaussian)
- Histogram equalization
- Image segmentation via contour detection
- Noise modeling and image restoration

## 📌 Notes

- `.ipynb_checkpoints/` folders are Jupyter's autosave checkpoints — not required to run anything and safe to exclude via `.gitignore`.
- Sample images (e.g. `bus.jpeg`, `Pokhara.jpg`, `virat.jpg`, `shiva.jpg`) are course-provided/sourced test images used to demonstrate each technique.
- If an image above doesn't render, double-check the filename inside **`All lab Output/`** matches exactly (case-sensitive), including the `.jpg` extension.

## 👤 Author

**Sachin Kandel**
[GitHub](https://github.com/Sachinkandel78) · [Portfolio](https://www.sachin0010.com.np/)
