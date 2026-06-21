# 🦈 Xir Loader

<p align="center">
  <img src="Banners/lateibannerx.png" alt="Xir Loader Banner" width="600"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python Version" />
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Platform Support" />
  <img src="https://img.shields.io/badge/Interface-CustomTkinter-black?style=for-the-badge" alt="UI Framework" />
  <img src="https://img.shields.io/badge/Security-Advanced-red?style=for-the-badge" alt="Security Level" />
</p>

<p align="center">
  📖 <b><a href="README.md">English Documentation</a> | Türkçe Dökümantasyon</b>
</p>

---

## ・Nedir?

**Xir**, tek bir modern istemci üzerinden birden fazla harici h1leyi ve mod yürütücüsünü güvenli gizli ve kalıntı bırakmadan yönetmek, yüklemek ve çalıştırmak için tasarlanmış **gelişmiş bir byp4$$ loader ve süreç koruma sistemidir**. 

Python ve CustomTkinter tabanlı hibrit bir mimariye sahip olan Xir, çalıştığı süreçlerin belleğini korumak, ekran yakalama araçlarından gizlenmek ve sistem üzerinde hiçbir kalıntı bırakmamak üzere optimize edilmiş özel güvenlik katmanları içerir.

---

## ・Öne çıkan Özellikler・

Xir, geleneksel yükleyicilerin ötesinde, tam kapsamlı güvenlik ve arayüz optimizasyonları sunar:

### ・Sade & Dinamik Arayüz
* **Partikül Efektli Arka Plan:** Gerçek zamanlı güncellenen, fare duyarlı dinamik partikül motoru.
* **Yumuşak Geçişli Animasyonlar:** CustomTkinter tabanlı, özel renk interpolasyonu içeren yumuşak geçişli (*Smooth Fade*) butonlar ve açılır menüler (*Dropdown*).
* **Akıllı Çözünürlük Ölçeklendirme:** Farklı ekran çözünürlüklerine tam uyum sağlayan esnek grid yapısı.
* **Özel Pencere Tasarımı:** Windows varsayılan başlık çubuğu yerine tamamen özelleştirilmiş, sürüklenebilir akıcı tasarım (*Borderless Draggable Window*).

### ・Üst Düzey Güvenlik ve Anti-Analiz
* **Gelişmiş Bellek Şifreleme:** AES-CBC şifreleme algoritmalarıyla süreç belleğinin dinamik olarak korunması (*On-the-fly Memory Encryption & Decryption*).
* **Çift Katmanlı Anti-Debug:** Sürekli aktif çalışan hızlı (*0.1sn aralıklı*) ve gelişmiş arka plan izleme iş parçacıklarıyla hata ayıklayıcı (*Debugger*) tespiti.
* **Süreç Askıya Alma Koruması (Anti-Suspension):** İstemcinin analiz edilmesini önlemek amacıyla sürecin dondurulmasını algılayan koruma katmanı.
* **Yapay Bellek Yemleri (Honeypot Decoys):** Bellek dökümü (*Memory Dump*) alan araçları yanıltmak amacıyla belleğe rastgele zaman damgalı sahte hassas veri enjeksiyonu.
* **API Hooking Koruması:** `kernel32.dll` üzerindeki kritik fonksiyonların (`ReadProcessMemory`, `WriteProcessMemory`, vb.) kancalanıp kancalanmadığını tespit eden izleyici.

### ・Derinlemesine İz Temizleme (Clean Utility)
* **Windows Olay Günlüğü Temizliği:** Çalışma esnasında oluşan sistem olay günlüklerinin otomatik temizlenmesi.
* **Prefetch & Son Kullanılanlar Temizliği:** Sistem analiz araçlarının geriye dönük tespit yapmasını engelleyen dizin temizliği.
* **Kayıt Defteri Arındırması:** Windows Kayıt Defteri (*Registry*) üzerinde kalan yürütme izlerinin silinmesi.

### ・Ekran Kaydedici Koruması (Stream-Proof)
* **Ekran Yakalama Bypass:** Discord, OBS, AMD Software, NVIDIA ShadowPlay ve AnyDesk gibi yayın/kayıt platformlarında loader ekranının görünmesini engelleyen Windows API tabanlı görüntü koruması (*Display Affinity Protection*).

---

## ・Teknik Gereksinimler & Kurulum

Projenin sorunsuz çalışabilmesi için sisteminizde Python 3.10 veya üzeri bir sürümün kurulu olması önerilir.

### Gerekli Kütüphaneler
Aşağıdaki kütüphaneler ana istemci ve şifreleme/güvenlik bileşenleri için gereklidir:
```bash
pip install customtkinter pillow pycryptodome psutil wmi win10toast plyer pypiwin32 socketio requests opencv-python pygame
```

### Başlatma
Projeyi derlenmemiş (kaynak kod) modda test etmek veya çalıştırmak için:
```bash
python main.py
```

---

### ⚠️ Önemli Not:
Xir kendini Scanner programlarından gizlemek için kendini python prosesi altında ram üzerinden çalıştırır; bundan dolayı ana dosyanın EXE'ye derlenmesi önerilmez. `setup.py` dosyasını sadece bir kerelik kurulum için kullanın.

---

## ・Dosya Yapısı ve Görevleri

* `main.py`: Kullanıcı arayüzünü (GUI), CustomTkinter animasyon motorunu ve gelişmiş bellek koruma işlevlerini (`SecurityManager`) barındıran ana loader dosyası.
* `setup.py`: Loader'ı sorunsuz şekilde kalıcı olarak hedef bilgisayara kuran, donanım kimliği doğrulamasını (`HWID`), dinamik bağımlılık kontrollerini yapan kurulum dosyası.
* `version.txt`: Derleme sonrası yürütülebilir Setup dosyasına (EXE) meşru bir görünüm kazandırmak amacıyla eklenen Windows Versiyon Bilgi şablonu.
* `req.bat`: Sistem gereksinimlerinin ve Python kütüphanelerinin tek tıkla otomatik kurulmasını sağlayan betik dosyası.

---

## ・Görseller ve Özel Tasarım Duvar Kağıtları

Projenin beraberinde gelen özel tasarlanmış bannerlar ve duvar kağıtlarına aşağıdaki yollardan ulaşabilirsiniz:

### Banners
* **Latei Banner 1 (Ana Görsel):** `Banners/lateibanner.png`
* **Latei Banner 2 (Alternatif):** `Banners/lateibanner2.png`

### Duvar Kağıtları (Wallpapers)
* **Latei Wallpaper 1:** `Wlpp/lateiwallpaper.png`
* **Latei Wallpaper 2:** `Wlpp/lateiwallpaper2.png`
* **Latei Wallpaper 3:** `Wlpp/lateiwallpaper3.png`

---

## ・Kullanım Ayrıntıları

Detaylı kullanım rehberi ve yapılandırma adımları için hazırlanan dökümantasyon sayfasını ziyaret edebilirsiniz:
👉 [Xir Kullanım Kılavuzu & Detaylı Analiz](https://justpaste.it/jufae)

---

## ・Yasal Uyarı

Bu yazılım yalnızca **eğitim, araştırma ve kişisel güvenlik analizi** amacıyla geliştirilmiştir. Yazılımın oyun içi modifikasyonlar veya platform kurallarını ihlal edecek şekilde kullanılması durumunda doğabilecek tüm hukuki sorumluluk tamamen son kullanıcıya aittir. Geliştirici (Latei) herhangi bir kötüye kullanım durumunda sorumluluk kabul etmez.

---
<p align="center">Developed with ❤️ by <b>Latei</b></p>
