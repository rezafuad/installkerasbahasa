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

Karena Anaconda merupakan console based application, maka seluruh perintah administrasi akan dilakukan dengan menggunakan command prompt. 
Windows 10 menyediakan command prompt yang lebih powerful yaitu Windows Power Shell.
Anda dianjurkan untuk menggunakan Windows Power Shell untuk mengeksekusi dan melakukan administrasi Anaconda.
Buka Windows Power Shell,

<p>
  <img src="https://raw.githubusercontent.com/rezafuad/installkerasbahasa/master/recom-powershell.png" width=10% />
</p>

Update software core dari Anaconda dan paket-paket utamanya dengan menggunakan perintah berikut.

```Command Prompt
conda update conda
conda update --all
```

