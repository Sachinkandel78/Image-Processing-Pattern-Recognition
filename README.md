# Image Processing & Pattern Recognition

Lab exercises for an **Image Processing and Pattern Recognition** course, implemented in Python using **OpenCV**, **NumPy**, and **Matplotlib** inside Jupyter notebooks.

## 📂 Labs & Outputs

### Lab 1 — RGB ↔ Grayscale Conversion
Loading an image, converting between BGR/RGB, and converting to grayscale.

![Lab 1 output](assets/lab1_output.jpg)

---

### Lab 2 — Point Operations (Graylevel Transformations)
Digital negative, intensity slicing, thresholding, and contrast stretching.

![Lab 2 output](assets/lab2_output.jpg)

---

### Lab 3 — Image Arithmetic & Boolean Operations
Addition, subtraction, multiplication, division, and bitwise operations (OR, NOT, XOR, AND) between two images.

![Lab 3 output](assets/lab3_output.jpg)

---

### Lab 4 — Smoothing Filters
Mean, median, and Gaussian blur, compared side by side.

![Lab 4 output](assets/lab4_output.jpg)

---

### Lab 5 — Histogram Equalization
Pixel intensity histograms before and after equalization.

![Lab 5 output](assets/lab5_output.jpg)

---

### Lab 6 — Image Segmentation (Contour Detection)
Original image and its segmented (contour-detected) result.

![Lab 6 output](assets/lab6_output.jpg)

---

### Lab 7 — Digital Image Restoration & Noise Reduction
Smoothing filters, noise injection, and restoration.

![Lab 7 output](assets/lab7_output.jpg)

---

## 📁 File Structure

| Lab | Notebook |
|---|---|
| Lab 1 | `Lab1.ipynb` |
| Lab 2 | `Lab2/Lab2.ipynb` |
| Lab 3 | `Lab 3/Untitled.ipynb` |
| Lab 4 | `Lab4/Lab4.ipynb` |
| Lab 5 | `Lab5/Lab5.ipynb` |
| Lab 6 | `Lab6/Lab6.ipynb` |
| Lab 7 | `Lab7/Lab7.ipynb` |

Each lab folder contains its own notebook and the sample image(s) it operates on.

## 🛠️ Tech Stack

- Python 3
- OpenCV (`opencv-python-headless`)
- NumPy
- Matplotlib
- Jupyter Notebook

## 🚀 Getting Started

```bash
# Install dependencies
pip install opencv-python-headless numpy matplotlib jupyter

# Launch Jupyter
jupyter notebook
```

Then open any lab's `.ipynb` file and run the cells in order. Each notebook loads its own sample image from the same folder, so keep the notebook and its image file(s) together.

## 📌 Notes

- `.ipynb_checkpoints/` folders are Jupyter's autosave checkpoints — not required to run anything, and typically excluded via `.gitignore`.
- Sample images (e.g. `bus.jpeg`, `Pokhara.jpg`, `virat.jpg`, `shiva.jpg`) are course-provided/sourced test images used to demonstrate each technique.
- Output images shown above are exported from each notebook's saved cell outputs. To add or refresh them yourself, save a figure with `plt.savefig("assets/labN_output.jpg")` before `plt.show()`.
