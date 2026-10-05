# GSM Tetiklemeli Mekanizmalar - Adli Bilişim İnceleme Raporu

## 1. Giriş ve İnceleme Amacı
Bu çalışma, hücresel ağlar üzerinden gelen çağrı/SMS sinyallerini fiziksel bir tetikleyiciye dönüştüren donanımsal düzeneklerin adli bilişim analizi ve tespit yöntemlerini kapsar.

## 2. Donanımsal Müdahale (Hardware Tampering) Belirtileri
- **Devre Kartı İncelemesi:** GSM modülünün (SIM800L vb.) haberleşme hatlarına (TX/RX) dışarıdan yapılan lehlemeler ve ek hatlar.
- **Güç Hattı Tespiti:** Hat üzerinden gelen akım dalgalanmalarını süzmek için eklenmiş yetkisiz kondansatör ve röle devreleri.

## 3. Adli Bilişim Kanıt Toplama (Artifact Collection)
1. **SIM Kart İncelemesi:** HLR/VLR kayıtları, SMSC bilgileri ve SIM kart içerisindeki silinmiş mesaj/arama dökümlerinin adli imajının alınması.
2. **Fiziksel İzler:** Devre kartı üzerindeki lehim kalıntıları, parmak izi ve seri numarası takibi.

## 4. Tehdit İstihbaratı (CTI) Göstergeleri (IoC)
- Standart dışı frekans bantlarında gerçekleşen kısa süreli sinyal patlamaları.
- Belirli numaralardan gelen ve anında sonlandırılan "Çaldır-Kapat" (Zero-Call) sinyal kalıpları.
