# 🧹 Denoising and Signal Enhancement Notebook

This repository contains a Jupyter Notebook dedicated to **denoising, filtering, and signal/image enhancement** tasks.  
The notebook provides both theoretical explanations and hands-on implementations, making it useful for **students, researchers, and practitioners** working with noisy datasets.

---

## 📌 Features

- **Noise Simulation**
  - Add synthetic noise (Gaussian, Salt & Pepper, etc.) to signals/images.
  - Compare the effects of different noise models.

- **Denoising Methods**
  - Classical filtering (moving average, Gaussian smoothing, Wiener filter).
  - Frequency-domain approaches (FFT-based noise suppression).
  - Advanced denoising (wavelet transform, sparse representations).

- **Performance Evaluation**
  - Signal-to-Noise Ratio (SNR) improvement.
  - Peak Signal-to-Noise Ratio (PSNR).
  - Structural Similarity Index (SSIM) for images.

- **Visualization**
  - Before vs. after denoising comparisons.
  - Frequency spectrum analysis.
  - Interactive plots for better understanding.

---



## 📊 Example Results

| Noise Type        | Input Example | Denoised Output |
|-------------------|---------------|-----------------|
| Gaussian Noise    | ![noisy](docs/gaussian_noisy.png) | ![clean](docs/gaussian_denoised.png) |
| Salt & Pepper     | ![noisy](docs/sp_noisy.png)       | ![clean](docs/sp_denoised.png) |

*(Add sample images in a `/docs` folder to make your README more attractive.)*

---



## 📖 Applications

- **Image Processing**: Removing noise from scanned documents, medical images, or photographs.
- **Signal Processing**: Enhancing audio signals, sensor data, and experimental measurements.
- **Machine Learning Preprocessing**: Cleaning datasets to improve model robustness.
- **Research & Education**: Demonstrating denoising techniques in courses, projects, and experiments.

---

## 🛠️ Technologies Used

- **Python 3.8+**
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [SciPy](https://scipy.org/)
- [scikit-image](https://scikit-image.org/)
- [PyWavelets](https://pywavelets.readthedocs.io/) (optional for wavelet transforms)

---

## 📜 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute this code with attribution.

---

## 🙌 Acknowledgments

- Open-source Python scientific libraries.
- Classic signal and image processing literature.
- Inspiration from real-world noisy datasets and their denoising challenges.

---

## 💡 Contributing

Contributions are welcome!  
If you have suggestions for new denoising techniques, optimizations, or visualizations, feel free to open an **issue** or submit a **pull request**.

---

## 👤 Author

Developed by **Sadra Berangi**  
