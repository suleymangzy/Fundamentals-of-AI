# 🐍 Python ve Temel Python Kütüphaneleri

Bu sayfa, Python programlama dili ve temel kütüphaneleri hakkında **kapsamlı ve uygulamalı** bir rehber sunar. İçerikler, Burdur Mehmet Akif Ersoy Üniversitesi Yazılım Mühendisliği Bölümü'nde Doç. Dr. Sedat Metlek tarafından hazırlanan ders notlarına dayanmaktadır.

-----

## 📑 İçindekiler

  * **▶️ Bölüm 1: Python'a Giriş**

      * [Python Temelleri](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Python/FundamentalsOfPython.ipynb)
      * [Veri Tipleri](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Python/DataTypesOfPython.ipynb)
      * [Uygulamalar ve Örnekler](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Python/FirstApplications.ipynb)
      * [Döngüler](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Python/Loops.ipynb)
      * [Fonksiyonlar](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Python/Functions.ipynb)

  * **▶️ Bölüm 2: NumPy**

      * [NumPy Kütüphanesi](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/NumPy/)

  * **▶️ Bölüm 3: Pandas**

      * [Pandas'a Giriş](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Pandas/Pandas.ipynb)
      * [Veri Bilimi İçin Pandas](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Pandas/PandasForDataScience.ipnyb)
      * [Veri Görselleştirme İçin Pandas](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/Pandas/PandasForDataVisualization.ipynb)

  * **▶️ Bölüm 4: Veri Görselleştirme**

      * [Veri Görselleştirme Temelleri](https://www.google.com/search?q=Python%2520and%2520Core%2520Python%2520Libaries/DataVisualization/DataVisualization.ipynb)

-----

### İçerik Detayları

-----

### 🐍 Bölüm 1: Python

#### **📚 Python'a Giriş**

  * 📝 Değişken Adı Belirleme Kuralları
  * 💡 Değişken Kullanımında İpuçları

#### **🔢 Python'da Veri Tipleri**

  * **`String`** Veri Tipleri
  * **`Sayısal`** Veri Tipleri:
      * `int`
      * `float`
      * `complex`
  * **`Dizi Oluşturan`** Veri Tipleri:
      * `list`
      * `range`
      * `tuple`
  * **`Küme Oluşturan`** Veri Tipleri:
      * `set`
      * `frozenset`
  * **`Binary`** Veri Tipleri:
      * `bytes`
      * `bytearray`
      * `memoryview`
  * **`Mantıksal`** Veri Tipi: `bool`
  * **`Adresleme`** Veri Tipi: `dictionary`
  * Temel Operatörlerin Kullanımı

#### **🚀 Uygulamalar**

  * **String İşlemleri:**
      * ⚙️ Uygulamalar ve Metotlar (`split`, `upper`, `strip`, `replace`, `find`, `index`)
  * **List Uygulamaları:**
      * ➕➖ Eleman Ekleme/Silme
      * 📋 Listeyi Kopyalama ve Sıralama
      * 📊 Diğer Metotlar (`min`, `max`, `count`)
  * **Koşul İfadeleri:**
      * `if`, `elif`, `else` Blokları
      * 🔗 İç İçe Koşul Blokları
      * ➡️ `and` ve `or` Operatörleri ile Koşullar

#### **🔄 Döngüler**

  * **`for` Döngüsü:**
      * String ve Dictionary üzerinde kullanım
      * `range()` metodu
  * 💻 Döngü uygulamaları

#### **🔧 Fonksiyonlar**

  * Fonksiyon Tanımlama ve Çağırma
  * 📥📤 Parametre Gönderme ve Geriye Değer Döndürme
  * **Lambda Fonksiyonları:**
      * Tanımlama ve Kullanım Amacı
  * **`map()`** ve **`filter()`** Fonksiyonları
  * **Fonksiyon Kapsamı (Scope):**
      * Yerel (`Local`) ve Global (`Global`) değişkenler
      * İç içe fonksiyonların kapsamı

-----

### 🤖 Bölüm 2: NumPy

  * **NumPy'a Giriş**
  * 🧩 NumPy Örnekleri
  * Varyans ($σ²$ veya $s²$) ve Standart Sapma ($σ$ veya $s$)
  * 📐 Matris Çarpma Koşulları

-----

### 🐼 Bölüm 3: Pandas

#### **Pandas'a Giriş**

  * **Pandas Veri Yapıları:**
      * **Seriler:** Oluşturma, İndeksleme, Dilimleme ve Değer Atama
      * **Veri Çerçeveleri (DataFrame):** İndeksleme, Sütun İşlemleri (Ekleme, Silme, Adlandırma)
  * **Veri Setini Tanıma:**
      * 🔍 `head()`, `info()`, `describe()`
      * `shape`, `columns`, `dtypes` özellikleri
  * **Veri Okuma ve Yazma:**
      * 📂 CSV ve Excel dosyalarından okuma ve bu formatlarda yazma

#### **🧹 Veri Temizleme ve Düzenleme**

  * **Eksik Verilerle Başa Çıkma:**
      * ❌ Silme ve Doldurma (`ffill`, `bfill`)
  * **Veri Türlerini Dönüştürme**
  * **Sütunları Şekillendirme:**
      * Birleştirme, tekrarlayan verileri kaldırma

#### **📊 Veri Bilimi İçin Pandas**

  * Veri Analizi ve İstatistiksel Hesaplamalar
  * Veri Gruplama (`groupby`) ve Toplulaştırma
  * ⬇️⬆️ Veri Sıralama ve Filtreleme
  * 🤝 Veri Çerçevelerini Birleştirme

#### **📈 Veri Görselleştirme İçin Pandas**

  * Temel Grafik Türleri:
      * 📉 Çizgi Grafiği (`Line Plot`)
      * 📊 Sütun Grafiği (`Bar Plot`)
      * Histogram
      * 📍 Nokta Grafiği (`Scatter Plot`)
      * 📦 Kutu Grafiği (`Box Plot`)
      * 🥧 Pasta Grafiği (`Pie Plot`)
      * Alan Grafiği (`Area Plot`)
      * Yoğunluk Grafiği (`Density Plot`)
  * 🧊 3D Grafik Örnekleri
  * **İleri Düzey Pandas:**
      * ⏳ Zaman Serileri Analizi
      * Çoklu İndeksleme
      * 🚀 Büyük veri kümelerinde performans optimizasyonu

-----

### 🖼️ Bölüm 4: Veri Görselleştirme

#### **Seaborn Kütüphanesi**

  * **Seaborn ve Matplotlib İlişkisi**
  * **Veri Görselleştirme Örnekleri:**
      * 📦 Kutu Grafikleri
      * 🗺️ Isı Haritaları (`Heatmap`)
      * 📈 Regresyon Modelleri
  * **Seaborn Stil ve Temaları:**
      * 🎨 Stil ve Tema Ayarları
      * Grafiklerin renk paletlerini değiştirme
      * Çizgi stilleri ve arka plan özelleştirme
  * **Veri Keşfi ve Analizi:**
      * 🔭 Dağılım görselleştirmeleri (`Histogram`, `Yoğunluk Grafiği`)
      * 🤝 Değişkenler arası ilişkileri gösterme (`Nokta Grafiği`, `Regresyon Grafiği`, `Matris Grafiği`)