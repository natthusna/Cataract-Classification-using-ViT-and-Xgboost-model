# Klasifikasi Katarak menggunakan Hybrid ViT-XGBoost

Penelitian ini membandingkan model ViT Murni dengan model Hybrid (ViT sebagai ekstraktor fitur dan XGBoost sebagai klasifikator).

## Hasil Penelitian
* [cite_start]**Model Terbaik:** ViT Epoch 2[cite: 868].
* **Akurasi Hybrid:** 99.56%.
* **Stabilitas (5-Fold CV):** ± 0.0017 (Sangat Robust).

## Teknologi
* PyTorch & Timm (ViT)
* XGBoost
* Google Colab