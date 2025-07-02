# Deneyap Geliştirme Kartları Arduino Core

[![](https://img.shields.io/badge/ResmiWebsitesi-Geçiş-880414)](https://deneyapkart.org/)  [![](https://img.shields.io/badge/TeknikRehber-Geçiş-487c17)](https://docs.deneyapkart.org/)

Yardıma ihtiyacınız var mı veya bir sorunuz mu var? [![](https://img.shields.io/badge/Forum-Geçiş-167cc9)](https://forum.deneyapkart.org/)

Güçlü işlemcisi, dayanıklı tasarımı ve esnek giriş/çıkış pinleri ile Türkiye'de tasarlanıp üretilen Deneyap Kart; Elektronik Programlama, Nesnelerin İnterneti (IoT) ve Yapay Zeka alanlarında başlangıç seviyesinden endüstriyel uygulamalara kadar her seviyede proje geliştirilmesine imkan tanır.

Deneyap Ailesi'nin en küçük üyesi Deneyap Mini, boyutları küçük ama kabiliyetli bir geliştirme kartıdır. Kablosuz haberleşme (WiFi) arayüzüne sahiptir ve özellikle giriş seviyesindeki kullanıcılar için oldukça uygun bir çözüm olarak sunulmuştur. Elektronik, Robotik ve Nesnelerin İnterneti (IoT) projelerinde rahatlıkla kullanılabilir.

Kartlar hakkında detaylı bilgiye erişmek için, lütfen [Deneyap Kart Teknik Rehberi'ni](https://docs.deneyapkart.org/#deneyap-kart) ve [Deneyap Kart Resmi İnternet Sitesi'ni](https://deneyapkart.org) ziyaret ediniz.

### Geliştirme Durumu

 [![Release Version](https://img.shields.io/github/v/release/deneyapkart/deneyapkart-arduino-core?color=880414)](https://github.com/deneyapkart/deneyapkart-arduino-core/releases/latest/) [![Release Date](https://img.shields.io/github/release-date/deneyapkart/deneyapkart-arduino-core?color=487c17)](https://github.com/deneyapkart/deneyapkart-arduino-core/releases/latest/) [![Downloads](https://img.shields.io/github/downloads/deneyapkart/deneyapkart-arduino-core/latest/total?color=167cc9)](https://github.com/deneyapkart/deneyapkart-arduino-core/releases/latest/) [![Downloads](https://img.shields.io/github/downloads/deneyapkart/deneyapkart-arduino-core/total?color=167cc9)](https://github.com/deneyapkart/deneyapkart-arduino-core/releases/latest/)

## İçindekiler
- [Yükleme Talimatları](#yükleme-talimatları)
- [Sorun Giderme](#sorun-giderme)
- [Deneyap Kart Pin Diyagramı](#deneyap-kart-pin-diyagramı)
- [Deneyap Mini Pin Diyagramı](#deneyap-mini-pin-diyagramı)
- [Deneyap Kart 1A Pin Diyagramı](#deneyap-kart-1a-pin-diyagramı)
- [Deneyap Kart G Pin Diyagramı](#deneyap-kart-g-pin-diyagramı)
- [Deneyap Mini v2 Pin Diyagramı](#deneyap-mini-v2-pin-diyagramı)
- [Deneyap Kart 1A v2 Pin Diyagramı](#deneyap-kart-1a-v2-pin-diyagramı)
- [Deneyap Kart v2 Pin Diyagramı](#deneyap-kart-v2-pin-diyagramı)
- [Deneyap Kart Genişletişmiş Pin Diyagramı](#deneyap-kart-genişletilmiş-pin-diyagramı)
- [Deneyap Mini Genişletişmiş Pin Diyagramı](#deneyap-mini-genişletilmiş-pin-diyagramı)
- [Deneyap Kart 1A Genişletişmiş Pin Diyagramı](#deneyap-kart-1a-genişletilmiş-pin-diyagramı)
- [Deneyap Kart G Genişletişmiş Pin Diyagramı](#deneyap-kart-g-genişletilmiş-pin-diyagramı)
- [Deneyap Mini v2 Genişletişmiş Pin Diyagramı](#deneyap-mini-v2-genişletilmiş-pin-diyagramı)
- [Deneyap Kart 1A v2 Genişletişmiş Pin Diyagramı](#deneyap-kart-1a-v2-genişletilmiş-pin-diyagramı)
- [Deneyap Kart v2 Genişletişmiş Pin Diyagramı](#deneyap-kart-v2-genişletilmiş-pin-diyagramı)

### Yükleme Talimatları
JSON index dosyası: `https://raw.githubusercontent.com/deneyapkart/deneyapkart-arduino-core/master/package_deneyapkart_index.json`

- Son sürüm [Arduino IDE](https://www.arduino.cc/en/software)'yi yükleyin.
- Arduino IDE'yi başlatın ve **Tercihler** pencerisini açın.
- Yukarıda paylaşılan JSON index dosyasına ait adresi, **Ek Devre Kartları Yöneticisi URL'leri** kısmına yapıştırın.
- **Ayarlar > Kart** adımını takip ederek **Kart Yöneticisi**'ni açın ve *Deneyap Gelistirme Kartlari*'nı yükleyin.
- Yükleme tamamlandıktan sonra, **Ayarlar > Kart** adımından *Deneyap Kart*'ı veya ***Deneyap Kart 1A**'ı veya **Deneyap Mini**'yi seçin.

### Sorun Giderme
Herhangi bir hata/sorun bildirmeden önce, lütfen karşılaşılan benzer bir hata/sorun olup olmadığını araştırın. Araştırmanız neticesinde; benzer bir sorunla karşılaşan başka biri olmadığına emin olduğunuz takdirde, [örnek hata bildirme şablonunu](../.github/ISSUE_TEMPLATE/bug_report_tr.md) kullanarak bildirimde bulunabilirsiniz.  

### Deneyap Kart Pin Diyagramı
![PinoutDYDK_TR](DeneyapKart_PinDiyagramı_mpv1.0.png)

### Deneyap Kart Genişletilmiş Pin Diyagramı
![ExPinoutDYDK_TR](DeneyapKart_GenişletilmişPinDiyagramı_mpv1.0.png)

### Deneyap Mini Pin Diyagramı
![PinoutDYM_TR](DeneyapMini_PinDiyagrami_mpv1.0.png)

### Deneyap Mini Genişletilmiş Pin Diyagramı
![ExPinoutDYM_TR](DeneyapMini_GenisletilmisPinDiyagramı_mpv1.0.png)

### Deneyap Kart 1A Pin Diyagramı
![PinoutDYDK1A_TR](DeneyapKart1A_PinDiyagramı_mpv1.0.png)

### Deneyap Kart 1A Genişletilmiş Pin Diyagramı
![ExPinoutDYDK1A_TR](DeneyapKart1A_GenisletilmisPinDiyagramı_mpv1.0.png)

### Deneyap Kart G Pin Diyagramı
![PinoutDYG_TR](DeneyapKartG_PinDiyagrami_mpv1.0.png)

### Deneyap Kart G Genişletilmiş Pin Diyagramı
![ExPinoutDYG_TR](DeneyapKartG_GenisletilmisPinDiyagrami_mpv1.0.png)

### Deneyap Mini v2 Pin Diyagramı
![PinoutDYMv2_TR](DeneyapMini_PinDiyagramı_mpv2.0.png)

### Deneyap Mini v2 Genişletilmiş Pin Diyagramı
![ExPinoutDYMv2_TR](DeneyapMini_GenisletilmisPinDiyagramı_mpv2.0.png)

### Deneyap Kart 1A v2 Pin Diyagramı
![PinoutDYDK1Av2_TR](DeneyapKart1A_PinDiyagramı_mpv2.0.png)

### Deneyap Kart 1A v2 Genişletilmiş Pin Diyagramı
![ExPinoutDYDK1Av2_TR](DeneyapKart1A_GenisletilmisPinDiyagramı_mpv2.0.png)

### Deneyap Kart v2 Pin Diyagramı
![PinoutDYDKv2_TR](DeneyapKart_PinDiyagramı_mpv2.0.png)

### Deneyap Kart v2 Genişletilmiş Pin Diyagramı
![ExPinoutDYDKv2_TR](DeneyapKart_GenisletilmisPinDiyagramı_mpv2.0.png)
