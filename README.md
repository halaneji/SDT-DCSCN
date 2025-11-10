# 🧠 Deep Architecture for Super-Resolution and Deblurring of Text Images

This repository contains the official implementation of the paper:

> **Neji, H., Ben Halima, M., Nogueras-Iso, J., Hamdani, T. M., Qahtani, A., Almutiry, O., Dhahri, H., & Alimi, A. M. (2024).**  
> *Deep architecture for super-resolution and deblurring of text images.*  
> *Multimedia Tools and Applications, 83*, 3945–3961.  
> [https://doi.org/10.1007/s11042-023-15340-x](https://doi.org/10.1007/s11042-023-15340-x)

---

## 📝 Introduction

The quality of scanned or photographed text images often suffers from **low resolution**, **blur**, and **noise**, which can severely affect readability and downstream document analysis tasks such as OCR and information retrieval.  

This work proposes a **deep learning architecture** that jointly performs *super-resolution* and *deblurring* to enhance degraded text images. The model integrates convolutional and residual learning strategies to effectively recover fine textual details, improve contrast, and preserve structural sharpness.  

**Key highlights:**
- A unified deep architecture combining **super-resolution** and **deblurring** within a single framework.  
- Incorporation of **residual and skip connections** to preserve text structure and fine details.  
- Extensive experiments on real and synthetic datasets demonstrating superior performance compared to existing approaches.  
- Quantitative improvements in metrics such as **PSNR**, **SSIM**, and OCR accuracy.  

This implementation reproduces and extends the results presented in the paper.

---

## 📚 Citation

If you use this code or ideas from this work in your research, please cite the following paper:

> **Neji, H., Ben Halima, M., Nogueras-Iso, J., Hamdani, T. M., Qahtani, A., Almutiry, O., Dhahri, H., & Alimi, A. M. (2024).**  
> *Deep architecture for super-resolution and deblurring of text images.*  
> *Multimedia Tools and Applications, 83*, 3945–3961.  
> [https://doi.org/10.1007/s11042-023-15340-x](https://doi.org/10.1007/s11042-023-15340-x)

---

**BibTeX:**
```bibtex
@article{Neji2024DeepArchitectureSRDeblurring,
  title   = {Deep architecture for super‐resolution and deblurring of text images},
  author  = {Neji, Hala and Ben Halima, Mohamed and Nogueras‐Iso, Javier and Hamdani, Tarek M. and Qahtani, Abdulrahman and Almutiry, Omar and Dhahri, Habib and Alimi, Adel M.},
  journal = {Multimedia Tools and Applications},
  year    = {2024},
  volume  = {83},
  pages   = {3945--3961},
  doi     = {10.1007/s11042-023-15340-x},
  url     = {https://link.springer.com/article/10.1007/s11042-023-15340-x}
}
