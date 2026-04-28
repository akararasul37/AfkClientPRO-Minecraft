# AFKClient Gelişmiş Minecraft Otomasyon ve Yönetim Paneli
<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/34348d3d-4cba-4382-a907-3bb26304d4a3" />


AFKClient, Minecraft oyuncuları ve sunucu yöneticileri için geliştirilmiş, yüksek performanslı ve çoklu hesap desteğine sahip profesyonel bir otomasyon istemcisidir. **Electron.js** tabanlı modern arayüzü ve **Mineflayer** motoru ile oyun içindeki rutin işleri tamamen otonom hale getirir.

> **Not:** Bu depo, projenin yeteneklerini sergilemek amacıyla hazırlanmış bir portfolyo sunumudur. Kaynak kodları gizli tutulmaktadır.

---

## 🌟 Öne Çıkan Özellikler

### 🤖 Gelişmiş Otomasyon Sistemleri
*   **Akıllı Maden (Auto-Mine):** Hedef blokları otomatik tespit eder ve kırar. Sunucu korumalarını aşmak için gecikme ve doğrulama kodu (CAPTCHA) desteği sunar.
*   **Otonom Satış (Auto-Sell):** Belirlenen aralıklarla envanterdeki eşyaları otomatik olarak sunucu marketine satar.
*   **Minyon Besleyici (Auto-Feeder):** Sunucu tabanlı minyonları veya botun kendisini otomatik olarak besleyerek süreklilik sağlar.
*   **Özelleştirilebilir Komutlar:** Giriş komutları, sunucu değiştirme ve periyodik mesaj gönderme özellikleri.

### 📊 Çoklu Hesap ve Grup Yönetimi
*   **Sınırsız Hesap Desteği:** Aynı anda onlarca botu tek bir panelden yönetin.
*   **Gelişmiş Gruplandırma:** Hesapları sunuculara veya görevlere göre gruplandırarak toplu komut gönderin.
*   **Profil Kayıt Sistemi:** Tüm bot ayarlarını (IP, Port, Sürüm, Proxy) yerel olarak şifreli şekilde saklar.

### 🌐 Ağ ve Güvenlik
*   **SOCKS5 Proxy Desteği:** Her bot için farklı bir IP atayarak hesap izolasyonu sağlar.
*   **Microsoft Auth Desteği:** Modern ve güvenli giriş yöntemleri ile uyumlu.
*   **VDS Lisans Sistemi:** HWID (Donanım Kimliği) tabanlı özel bir lisanslama ve kimlik doğrulama sunucusu entegrasyonu.

### 👁️ Görsel Denetim
*   **3D Dünya Görünümü:** `prismarine-viewer` entegrasyonu sayesinde botların bulunduğu ortamı tarayıcı veya panel üzerinden 3D olarak izleyin.
*   **Anlık Sohbet ve Log:** Tüm botların sohbet geçmişini filtreleyebilir, toplu veya bireysel mesaj gönderebilirsiniz.

---

## 🛠️ Teknik Altyapı (Tech Stack)

Proje, modern web teknolojileri ile düşük seviyeli oyun protokollerinin birleşimiyle oluşturulmuştur:

*   **Runtime:** [Node.js](https://nodejs.org/)
*   **Framework:** [Electron.js](https://www.electronjs.org/) (Cross-platform Masaüstü Uygulaması)
*   **Bot Motoru:** [Mineflayer](https://github.com/PrismarineJS/mineflayer)
*   **Rendering:** [Prismarine-Viewer](https://github.com/PrismarineJS/prismarine-viewer) (Three.js tabanlı 3D görünüm)
*   **UI/UX:** Vanilla CSS (Modern Dark Theme), Dynamic DOM Manipulation
*   **Auth:** Custom VDS API (Express.js tabanlı lisans sunucusu)
*   **Veri Yönetimi:** Local JSON Persistence & IPC (Inter-Process Communication)

---

## 📸 Uygulama Görüntüleri
Ana Panel
<img width="1385" height="838" alt="image" src="https://github.com/user-attachments/assets/971670a1-ef01-43fc-8636-d369016752b6" />

---

Bot Yönetimi
<img width="1088" height="610" alt="image" src="https://github.com/user-attachments/assets/56ddf4e4-af04-4923-8e59-cc5820bd15d7" />

---

3D Viewer
<img width="348" height="321" alt="image" src="https://github.com/user-attachments/assets/b74ffa4f-9ab8-4124-8493-26757ea4d393" />


---

## 🛡️ Güvenlik ve Gizlilik

AFKClient Pro, güvenlik odaklı geliştirilmiştir:
- **Sandbox Yapısı:** Electron'un güvenlik standartlarına uygun `contextIsolation` ve `preload` mekanizması kullanılır.
- **HWID Kontrolü:** Lisansların izinsiz paylaşımını önleyen donanım kilidi.
- **Proxy İzolasyonu:** Her botun ağ trafiği birbirinden tamamen bağımsızdır.

---

## 👨‍💻 Hakkında

Bu proje, karmaşık ağ protokolleri, çoklu işlem yönetimi ve modern kullanıcı arayüzü tasarımı konularındaki yetkinliklerimi göstermek amacıyla geliştirilmiştir. 

**Geliştirici:** [akararasul]  
---
*Yasal Uyarı: Bu yazılım yalnızca eğitim ve test amaçlıdır. Minecraft sunucularının kullanım şartlarına uygun hareket etmek kullanıcının sorumluluğundadır.*
