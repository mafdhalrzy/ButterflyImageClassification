# Proyek Klasifikasi Kupu-Kupu

Proyek ini berisi model Machine Learning untuk mengklasifikasikan 75 spesies kupu-kupu yang berbeda. Model dilatih menggunakan arsitektur EfficientNetB0 dan disebarkan dalam berbagai format.

## Struktur File
- `saved_model/`: Model dalam format TensorFlow SavedModel.
- `tflite/`: Model yang dikonversi ke format TensorFlow Lite (`model.tflite`) beserta file `label.txt`.
- `tfjs_model/`: Model untuk deployment di web menggunakan TensorFlow.js.

## Keterangan
Proyek ini membagi dataset menjadi set Train, Validation, dan Test, melakukan augmentasi data, dan menggunakan teknik transfer learning (fine-tuning) untuk mencapai akurasi yang optimal.
