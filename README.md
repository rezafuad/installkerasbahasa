# Cara Install Keras Deep Learning Framework Dengan Backend TensorFlow

Mengapa Anaconda? Bagi Anda yang menggunakan Linux, saya sarankan Anda tidak menggunakan Anaconda tetapi langsung melakukan instalasi paket-paket python yang dibutuhkan. Tetapi, pada sistem operasi windows, proses instalasi manual cukup membingungkan sehingga salah satu solusinya adalah dengan menggunakan Anaconda.

Salah satu keunggulan Anaconda adalah kita dapat membuat beberapa lingkungan virtual yang saling independen sehingga tidak mempengaruhi sistem windows itu sendiri. Paket-paket akan di install pada lingkungan virtual Anaconda.

Berikut merupakan cara instalasi Keras Deep Learning Framework dengan backend TensorFlow pada sistem operasi windows,

## 1. Download Anaconda (version stabil adalah version 5.0.1)

Download file instalasi Anaconda. Saya menggunakan Anaconda versi 5.0.1

<p>
  <img src="https://raw.githubusercontent.com/rezafuad/installkerasbahasa/master/anaconda-download.png" width=50% />
</p>

## 2. Install Anaconda

Jalankan file yang telah diunduh dari website Anaconda dan ikut seluruh instruksi yang diminta.

<p>
  <img src="https://raw.githubusercontent.com/rezafuad/installkerasbahasa/master/anaconda-install.png" width=25% />
</p>

## 3. Update Anaconda

Buka Anaconda terminal dari Menu.

Update software core dari Anaconda dan paket-paket utamanya dengan menggunakan perintah berikut.

```Command Prompt
conda update conda
conda update --all
```

## 4. Install CUDA dan CuDNN

Jika Anda akan menggunakan GPU sebagai media komputasi, maka Anda perlu mengunduh CUDA Toolkit dan CuDNN dari NVIDIA website.
Saat ini TensorFlow hanya mensupport NVIDIA CUDA untuk GPU computing library.

Link Dowload: http://developer.nvidia.com <br/>
Catatan: Anda harus membuat account NVIDIA untuk bisa mengunduh CUDA dan CuDNN.

Untuk lebih jelas silahkan melihat pada halaman TensorFlow berikut:<br/>
https://www.tensorflow.org/install/install_windows


## 5. Setting Anaconda Environment

Buat Anaconda Enviroment baru dengan menggunakan perintah berikut

```Command Prompt
conda create -n keras-tensorflow python=3.6 numpy scipy matplotlib spyder
```
## 6. Install TensorFlow dan Keras

Install tensorflow dengan menggunakan perintah berikut ini

```Command Prompt
pip install tensorflow
```

Atau kalau dengan GPU

```Command Prompt
pip install tensorflow-gpu
```

## 7. Testing Keras

Testing instalasi dengan mengimport keras pada ipython.

```Command Prompt
ipython
```
Lalu import Keras dengan menggunakan perintah berikut,

```Command Prompt
import keras
```

Jika berhasil tanpa error, maka akan muncul tulisan "Using TensorFlow backend.".
