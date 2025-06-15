# 🌍 Planet Detection.v12-v7.yolov5pytorch

A high-quality image dataset for detecting planetary objects using YOLOv5.

---

## 🇹🇷 Türkçe Açıklama

**Planet Detection.v12-v7.yolov5pytorch**, gezegen tespiti ve sınıflandırması amacıyla hazırlanmış 8 sınıflı bir görüntü veri kümesidir.

### 🔢 Sınıflar:
- Earth
- Jupiter
- Mars
- Mercury
- Neptune
- Saturn
- Uranus
- Venus

### 📦 İçerik:
- 4.298 görüntü
- `train/`, `valid/`, `test/` klasörleri
- YOLOv5 uyumlu `data.yaml` dosyası

### 🛠️ Uygulanan Veri Artırmalar:
- %50 yatay ve dikey çevirme
- 90° dönüş (rastgele)
- %10–30 kırpma
- ±%10 parlaklık & pozlama
- 0–3 px Gauss bulanıklığı
- %1.75 tuz & karabiber gürültüsü

> Bu veri kümesi, yapay zekâ ve görüntü işleme projelerinde kullanılmak üzere optimize edilmiştir.


## 📁 Klasör Şeması:
planet-detection/
├── train/
│ └── images/, labels/
├── valid/
│ └── images/, labels/
├── test/
│ └── images/, labels/
├── data.yaml
└── README.md


---

## 🇬🇧 English Description

**Planet Detection.v12-v7.yolov5pytorch** is an image dataset designed for planetary object detection and classification with 8 labeled classes.

### 🔢 Classes:
- Earth
- Jupiter
- Mars
- Mercury
- Neptune
- Saturn
- Uranus
- Venus

### 📦 Contents:
- 4,298 images
- `train/`, `valid/`, and `test/` folders
- YOLOv5-compatible `data.yaml` file

### 🛠️ Applied Augmentations:
- 50% horizontal and vertical flip
- Random 90° rotations
- Random crop (10–30%)
- Brightness & exposure shift (±10%)
- Gaussian blur (0–3 px)
- Salt & pepper noise (1.75%)

> Optimized for use in AI, astronomy, and computer vision research.

---

## 📁 Folder Structure
planet-detection/
├── train/
│ └── images/, labels/
├── valid/
│ └── images/, labels/
├── test/
│ └── images/, labels/
├── data.yaml
└── README.md


---

## 📌 License

This dataset is released under a **custom license**. Please contact the maintainer if you intend to use it for commercial purposes.

---

## ✨ Maintainer

**Burak Kurt** – [LinkedIn](https://www.linkedin.com/in/burak-kurt) • [GitHub](https://github.com/burakkurt)

---

