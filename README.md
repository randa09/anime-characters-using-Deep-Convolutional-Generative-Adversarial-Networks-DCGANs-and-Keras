# 🌸 anime characters using Deep Convolutional Generative Adversarial Networks (DCGANs) and Keras 🌸

![Project Banner](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-GPXX0XCEEN/images/face_cartton.png)

> Membuat karakter anime dengan Deep Convolutional Generative Adversarial Networks (DCGAN) menggunakan Keras, membantu menghasilkan avatar secara otomatis untuk aplikasi seperti game dan desain grafis.

---

## 📜 Daftar Isi
1. [Tentang Proyek](#tentang-proyek)
2. [Teknologi yang Digunakan](#teknologi-yang-digunakan)
3. [Penjelasan Detail](#penjelasan-detail)
4. [Instruksi Penggunaan](#instruksi-penggunaan)
5. [Hasil](#hasil)

---

## 📘 Tentang Proyek

Proyek ini memanfaatkan **Deep Convolutional Generative Adversarial Networks (DCGAN)** untuk menghasilkan gambar anime yang realistis. DCGAN merupakan kombinasi dari Convolutional Neural Networks (CNNs) dan Generative Adversarial Networks (GANs) yang menggabungkan kekuatan keduanya untuk menghasilkan gambar berkualitas tinggi. Dalam proyek ini, kami menggunakan Keras dengan backend TensorFlow untuk membangun DCGAN dan melatih model pada dataset anime.

**Tujuan**:
- Memahami konsep dasar GAN dan DCGAN.
- Mengimplementasikan DCGAN untuk menghasilkan gambar karakter anime.
- Mengamati proses pelatihan DCGAN dan memahami eksplorasi variabel laten untuk hasil yang beragam.

---

## 🚀 Teknologi yang Digunakan

| Teknologi | Deskripsi | Logo |
|-----------|-----------|------|
| **Python** | Bahasa pemrograman utama untuk implementasi model dan pengolahan data. | ![Python](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png) |
| **TensorFlow & Keras** | Framework deep learning untuk membangun dan melatih model. | ![TensorFlow](https://upload.wikimedia.org/wikipedia/commons/2/2d/Tensorflow_logo.svg) |
| **NumPy** | Perpustakaan numerik untuk manipulasi data. | ![NumPy](https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg) |
| **Matplotlib** | Perpustakaan visualisasi untuk memantau hasil pelatihan dan output model. | ![Matplotlib](https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg) |

---

## 📂 Penjelasan Detail

Proyek ini terdiri dari beberapa tahapan untuk membangun dan melatih model DCGAN:

### 1. **Struktur Dasar GAN**
   - **Generator** dan **Discriminator** diperkenalkan dalam bentuk GAN sederhana untuk memahami komponen utama.

### 2. **Pemuatan & Pratreatment Data**
   - Mengimpor dataset gambar anime, melakukan pemrosesan data agar siap dilatih.

### 3. **Desain Model DCGAN**
   - **Generator**: Membuat gambar dari noise acak menggunakan layer konvolusional.
   - **Discriminator**: Mengklasifikasikan gambar sebagai nyata atau palsu, dilatih bersama generator dalam pengaturan adversarial.

### 4. **Fungsi Loss dan Optimizer**
   - Menggunakan Binary Cross-Entropy untuk loss pada generator dan discriminator, dengan Adam optimizer untuk pelatihan yang efisien.

### 5. **Proses Pelatihan**
   - Generator dan Discriminator dilatih secara iteratif, dengan Generator berusaha untuk menghasilkan gambar yang semakin realistis seiring bertambahnya iterasi.

---

## 📝 Instruksi Penggunaan

### Langkah 1: Instalasi
Pastikan Anda telah menginstal pustaka berikut:

```bash
pip install tensorflow keras numpy matplotlib.

## 📝 Langkah 2: Eksekusi Notebook

Untuk menjalankan notebook ini, ikuti langkah-langkah berikut:

1. **Buka Notebook**: Buka notebook bernama `deep_convolutional_generative_adversarial_networks_(dcgans).ipynb` di Jupyter Notebook atau JupyterLab.
   
2. **Jalankan Setiap Cell**: Lakukan eksekusi pada setiap cell secara berurutan untuk:
   - **Memuat Data**: Cell pertama akan mengimpor dataset gambar anime yang diperlukan dan melakukan proses prapemrosesan.
   - **Mendefinisikan Model DCGAN**: Bagian berikutnya akan mendefinisikan struktur generator dan discriminator menggunakan Keras.
   - **Melatih Model**: Cell berikutnya akan melatih model dengan iterasi yang cukup untuk menghasilkan gambar yang semakin realistis.

3. **Monitor Proses Pelatihan**: Saat proses pelatihan berlangsung, notebook akan menampilkan gambar karakter anime yang dihasilkan secara bertahap. Dengan bertambahnya epoch, gambar akan terlihat semakin nyata dan detail.

## 🎨 Langkah 3: Lihat Hasil

Setelah pelatihan selesai, Anda dapat melihat hasil gambar karakter anime yang dihasilkan oleh DCGAN pada beberapa tahap:

| Generasi Awal | Generasi Lanjutan |
|---------------|-------------------|
| ![Generasi Awal](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-GPXX0XCEEN/images/face_cartton.png) | ![Generasi Lanjutan](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-GPXX0XCEEN/images/face_cartton.png) |

Dengan semakin banyak epoch, kualitas gambar akan meningkat, menyerupai gaya karakter anime dalam dataset pelatihan.

---

Dibuat dengan ❤️ oleh MUHAMMAD IRANDA

