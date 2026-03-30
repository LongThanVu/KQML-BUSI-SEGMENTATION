# KQML-BUSI-Segmentation

**Introduction:**
Breast cancer is one of the leading causes of cancer-related mortality among women worldwide, where early detection and accurate diagnosis are critical for improving survival rates. Automated medical image segmentation plays a vital role in supporting clinicians by enabling precise tumor localization and analysis.

**Method:**
In this work, we perform breast tumor segmentation on the widely used BUSI dataset ([Breast Ultrasound Images Dataset](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)) and propose a novel lightweight hybrid architecture that integrates **U-Net, Kolmogorov–Arnold Networks (KAN), and quantum-inspired components**.

The proposed framework is specifically designed to balance **model efficiency and predictive performance**, aiming to reduce computational complexity and training cost while preserving segmentation accuracy.

**Overall framework**

<p align="center">
  <img src="https://github.com/user-attachments/assets/fa94d261-70e3-48fc-a6b0-fe202a411f06" width="800" alt="KQML-BUSI" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f99a7956-5042-4d79-bbc5-c6ec45547ccf" width="800" alt="KAN-BUSI-Model" />
</p>

**Main contribution:**
* Experimental results demonstrate that our method achieves **competitive performance compared to state-of-the-art (SOTA) approaches**, with quantitative results of **IoU: 70%, Dice: 75%, Precision: 80%, Recall: 79%, and Specificity: 98.58%**.

* Furthermore, we show that the incorporation of **KAN and quantum-inspired techniques** enhances representation capability while significantly reducing model size and computational overhead.

* This study highlights a promising direction toward **efficient, scalable, and resource-aware medical image segmentation**, which is particularly valuable for real-world clinical deployment in low-resource settings.

**Comparision with previous methods:**
| Methods                 | Jaccard (IoU)    | Precision        | Recall           | Specificity      | Dice             |
| ----------------------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| U-net                   | 60.70 ± 2.36     | 71.88 ± 2.41     | 76.30 ± 2.48     | 96.18 ± 0.55     | 70.10 ± 2.20     |
| Att U-net               | 57.09 ± 1.22     | 78.78 ± 4.67     | 66.97 ± 4.08     | 96.87 ± 0.83     | 67.99 ± 1.88     |
| U-net++                 | 61.38 ± 1.73     | 79.68 ± 3.07     | 71.44 ± 2.77     | 97.04 ± 0.54     | 71.58 ± 2.09     |
| U-net3+                 | 63.03 ± 2.79     | 71.89 ± 3.28     | 79.58 ± 2.48     | 96.19 ± 0.68     | 71.85 ± 2.73     |
| Abraham et al.          | 61.62 ± 2.69     | 73.77 ± 2.90     | 76.87 ± 2.58     | 96.40 ± 0.62     | 71.35 ± 2.67     |
| SegNet                  | 67.31 ± 1.87     | 76.09 ± 2.00     | 79.85 ± 1.03     | 96.99 ± 0.53     | 75.64 ± 1.80     |
| SK U-Net                | 68.10 ± 1.63     | 78.62 ± 1.66     | 79.53 ± 1.93     | 97.33 ± 0.45     | 76.92 ± 1.57     |
| RDAU-net                | 63.75 ± 3.36     | 71.25 ± 4.11     | 78.90 ± 1.35     | 96.63 ± 0.76     | 71.94 ± 3.46     |
| AEU-net                 | 64.57 ± 2.91     | 74.44 ± 3.74     | 79.00 ± 2.11     | 96.80 ± 0.54     | 73.47 ± 3.03     |
| AAU-net                 | 68.82 ± 0.44     | 79.61 ± 1.07     | 81.10 ± 0.52     | 97.57 ± 0.24     | 77.51 ± 0.68     |
| NU-net                  | 70.35 ± 1.54     | 79.56 ± 1.17     | 82.46 ± 1.02     | 97.48 ± 0.49     | 78.62 ± 1.38     |
| **Att U-net +**         | **70.90 ± 0.96** | **84.33 ± 0.79** | **81.27 ± 1.53** | **98.92 ± 0.56** | **80.36 ± 0.46** |
| **Our proposed method** | **70.00**        | **80.00**        | **79.00**        | **98.58**        | **75.00**        |


