# Stroke Prediction with SVM

**Tugas Besar Machine Learning** 
oleh 
Gede Bagus Krishnanditya Merta
Raka Aditya Waluya
Dody Adi Sancoko

## Deskripsi Tubes
Proyek ini bertujuan memprediksi risiko stroke menggunakan beberapa metode, yaitu **Support Vector Machine (SVM)**, **K-Nearest Neighboard (KNN)**, **Random Forest (RF)**,. Menggunakan dataset kesehatan (usia, tekanan darah, dll.), model dilatih untuk memberikan klasifikasi: *stroke* atau *tidak stroke*.

## 📂 Isi Repository
- `tubes-ml-stroke-prediction.ipynb` – Notebook analisis data, preprocessing, pelatihan & evaluasi model.
- `svm_stroke_model.pkl` – Model SVM yang sudah terlatih dan disimpan.
- `knn_stroke_model.pkl` – Model KNN yang sudah terlatih dan disimpan.
- `rf_stroke_model.pkl` – Model RF yang sudah terlatih dan disimpan.
- `healthcare-dataset-stroke-data.csv` – Dataset mentah.
- `app.py` – Streamlit untuk menjalankan code dan implementasi model.
- `README.md` – Penjelasan ini.

## 🧰 Instalasi & Setup
1. **Clone repository**  
   ```bash
   git clone https://github.com/BagusKrishna/Tugas-Besar-Machine-Learning.git
   cd Tugas-Besar-Machine-Learning

2. **(Opsional) Install dependensi**  
   ```bash
   pip install streamlit scikit-learn pandas numpy

3. **Jalankan aplikasi Streamlit**  
   ```bash
   streamlit run app.py

Link Google Colab :
https://colab.research.google.com/drive/1f863-DN88TDGLA5yWQZE0xgphLTOWVUu?usp=sharing#scrollTo=5AsYsyEChfch
