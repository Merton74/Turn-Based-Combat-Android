# Turn-Based-Combat-Android
🇹🇷 MIT App Inventor ile geliştirilmiş, God of War temalı sıra tabanlı 2D dövüş oyunu. | 🇬🇧 A 2D turn-based battle app set in the God of War universe, built with MIT App Inventor. Features enemy AI and dynamic UI.

# God of War: 2D Turn-Based Battle 🪓

🇹🇷 **[Türkçe Çeviri Aşağıdadır]** | 🇬🇧 **[English Version Below]**

---

## 🇹🇷 Türkçe 

### 📜 Proje Hakkında
Bu proje, **MIT App Inventor** kullanılarak geliştirilmiş, *God of War* evreninde geçen sıra tabanlı (turn-based) bir 2D dövüş oyunudur. Oyuncular favori karakterlerini seçerek yapay zeka (AI) tarafından kontrol edilen rastgele bir düşmana karşı taktiksel bir düelloya girerler. Proje; veri yönetimi, algoritma tasarımı ve dinamik kullanıcı arayüzü (UI) konularındaki yetkinlikleri sergilemek amacıyla tasarlanmıştır.

### 🚀 Öne Çıkan Özellikler
*   **Karakter Seçimi:** Kratos, Freya veya Atreus karakterleri arasından seçim yapabilme.
*   **Anti-Mirror Match Sistemi:** Oyuncunun kendi karakterinin kopyasıyla savaşmasını (örn: Kratos vs Kratos) engelleyen akıllı eşleştirme algoritması.
*   **Düşman Yapay Zekası:** Zamanlayıcı (Timer) tabanlı, rastgele karar mekanizmasına sahip ve oyuncunun hamlesinden sonra otomatik devreye giren düşman NPC sistemi.
*   **Dinamik Can Barları:** Alınan hasara göre anlık olarak (piksel bazlı) güncellenen, görsel olarak duyarlı sağlık göstergeleri.

### 💻 Teknik Altyapı ve Konseptler
Bu projede aşağıdaki yazılım ve algoritma konseptleri aktif olarak kullanılmıştır:
*   **Local Storage (TinyDB):** Giriş ekranı (Screen1) ile savaş arenası (Screen2) arasında karakter verilerinin ve durumlarının (state) güvenli bir şekilde aktarılması.
*   **UI Scaling & Clamping:** Can değerinin 0'ın altına düşmesini engelleyen "Emniyet Kemeri" (Clamping) kuralı ve can barı genişliğinin cihaz ekranına göre asimetrik kaymaları önleyerek yeniden ölçeklendirilmesi.
*   **Order of Operations (İşlem Sırası):** Kod bloklarının yukarıdan aşağıya okunma prensibi göz önünde bulundurularak, arayüz hatalarını önleyen hatasız (bug-free) dizilim mimarisi.

### 📸 Ekran Görüntüleri
[Giriş Ekranı] <img width="381" height="678" alt="image" src="https://github.com/user-attachments/assets/f1632cd6-e2e2-4b53-ae33-bd8aee7708fd" />
 
![Savaş Arenası] <img width="384" height="673" alt="image" src="https://github.com/user-attachments/assets/caa4ddc6-9307-4787-8b52-46d1a56d5bdf" />


### ⚙️ Kurulum ve Test Etme
1.  **Android Cihazlar İçin:** Depodaki `.apk` dosyasını indirip Android cihazınıza kurarak doğrudan oynayabilirsiniz.
2.  **Geliştiriciler İçin:** `.aia` kaynak dosyasını indirip kendi [MIT App Inventor](http://ai2.appinventor.mit.edu/) hesabınıza "Import" ederek blok kodlarını ve UI tasarımını inceleyebilirsiniz.

---

## 🇬🇧 English

### 📜 About the Project
This project is a turn-based 2D fighting game set in the *God of War* universe, developed using **MIT App Inventor**. Players choose their favorite character and engage in a tactical duel against a randomly assigned, AI-controlled opponent. This project is designed to demonstrate proficiency in data management, algorithm design, and dynamic user interface (UI) rendering.

### 🚀 Key Features
*   **Character Selection:** Choose between Kratos, Freya, and Atreus to battle.
*   **Anti-Mirror Match System:** Smart matchmaking algorithm that prevents the player from fighting a clone of their own character (e.g., preventing Kratos vs Kratos).
*   **Enemy AI:** A Timer-based NPC system with randomized decision-making logic that automatically triggers after the player's turn.
*   **Dynamic Health Bars:** Visually responsive health indicators that update instantaneously (pixel-based) according to the damage dealt.

### 💻 Technical Architecture & Concepts
The following software and algorithmic concepts were actively implemented in this project:
*   **Local Storage (TinyDB):** Secure transfer of character data and state between the character selection screen (Screen1) and the battle arena (Screen2).
*   **UI Scaling & Clamping:** Implementation of value clamping logic to prevent HP values from dropping below zero, alongside dynamic recalculation of health bar widths to prevent UI overlapping and layout shifts.
*   **Order of Operations:** Flawless block arrangement architecture, built with sequential code execution principles in mind to prevent runtime UI bugs.

### 📸 Screenshots
![Main Menu] <img width="381" height="678" alt="image" src="https://github.com/user-attachments/assets/f1632cd6-e2e2-4b53-ae33-bd8aee7708fd" />
![Battle Arena] <img width="384" height="673" alt="image" src="https://github.com/user-attachments/assets/caa4ddc6-9307-4787-8b52-46d1a56d5bdf" />

### ⚙️ Installation & Testing
1.  **For Android Devices:** Download the `.apk` file from this repository and install it on your Android device to play directly.
2.  **For Developers:** Download the `.aia` source file and "Import" it into your own [MIT App Inventor](http://ai2.appinventor.mit.edu/) account to inspect the block logic and UI design.

---
*Developed by [Senin Adın/Kullanıcı Adın]*
