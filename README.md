# 🎓Akıllı Yoklama Sistemi

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-Veri%20Analizi-150458?logo=pandas&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow(PIL)-Görüntü%20İşleme-yellow)
![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-orange)

Bu proje, sınıf yoklama kağıtlarını tarayarak öğrencilerin katılım durumunu **Yapay Zeka ve Görüntü İşleme (Image Processing)** teknikleriyle otomatik olarak analiz eden ve sonuçları **Excel** formatında raporlayan bir masaüstü uygulamasıdır.

## 🚀 Projenin Amacı
Klasik kağıt tabanlı yoklamaların sisteme girilmesi zaman alıcı ve hataya açıktır. Bu proje:
1.  Yoklama kağıdının görüntüsünü analiz eder.
2.  İmzaların atılıp atılmadığını (dolu/boş kutucuk) tespit eder.
3.  Sınıf listesiyle eşleştirip **"Geldi/Gelmedi"** verisini Excel'e işler.

## ✨ Temel Özellikler

* **🖥️ Modern Arayüz:** `CustomTkinter` kullanılarak geliştirilmiş, karanlık mod destekli kullanıcı dostu arayüz.
* **👁️ Akıllı Görüntü İşleme:**
    * **CLAHE Teknolojisi:** Düşük ışıkta veya gölgeli çekilen fotoğraflarda kontrastı otomatik dengeler.
    * **Perspektif Bağımsız:** Kağıt üzerindeki tablo yapısını dinamik olarak algılar.
* **📊 Excel Entegrasyonu:**
    * Dışarıdan sınıf listesi (`.xlsx`) yüklenebilir.
    * Sonuçlar detaylı bir Excel raporu olarak kaydedilir.
* **⚡ Hata Toleransı:** Liste yüklenmese bile "Otomatik İsimlendirme" moduyla çalışmaya devam eder.

## 🧠 Kullanılan Teknolojiler

Python: Ana programlama dili.
OpenCV: Görüntü işleme, tablo tespiti ve piksel analizi.
Pandas: Excel veri manipülasyonu ve raporlama.
CustomTkinter: Modern masaüstü grafik arayüzü (GUI).
Pillow (PIL): Görüntülerin arayüzde gösterilmesi.

---

## 🛠️ Kurulum ve Çalıştırma

Projeyi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

### 1. Gereksinimleri Yükleyin
Proje klasöründe terminali açın ve gerekli kütüphaneleri tek komutla yükleyin:

```bash
pip install -r requirements.txt

Ardından Akıllı Yoklama Sistemi proje dosyasını Jupyter Notebook ile açın.
