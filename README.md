<p align="center">
  <img width="286.2" height="327.6" alt="logo" src="https://github.com/user-attachments/assets/6c917fc5-e283-48b9-97f8-883dfd4beeef" />
</p>

# 📱 Subly Frontend - Abonelik Takip Mobil Uygulaması

Subly, kullanıcıların dijital aboneliklerini kolayca **yönetebileceği**, **istatistiklerle takip edebileceği** ve zamanı geldiğinde **bildirimlerle uyarı alabileceği** bir mobil uygulamadır.

Bu frontend proje, React Native kullanılarak geliştirilmiştir ve backend kısmıyla tamamen entegredir. Hem iOS hem de Android için optimize edilmiştir.

---

## 🎯 Uygulama Özellikleri

- 🔐 Giriş & Kayıt ekranı
- 📋 Abonelikleri listeleme ve düzenleme
- ➕ Yeni abonelik ekleme
- 📊 Harcama istatistiklerini grafiklerle gösterme (aylık trend & kategori dağılımı)
- 🔔 E-posta & sistem bildirimleri ile abonelik hatırlatmaları
- 🌐 Çoklu dil desteği
- 📤 Verileri dışa aktarma

---

## 🖼️ Arayüzden Görseller
<p align="center">
  <img src="https://github.com/user-attachments/assets/f34a4dcf-e39a-4364-ae9d-2079ce3b78c7" width="190" style="margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/b9dc0ee5-60f5-44e9-a9ab-7c20ecdf9192" width="190" style="margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/8e93166a-ea1a-49d7-8219-8f2070e5f5fb" width="190" style="margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/01d894ad-48a5-49ac-9676-f41547d8f92d" width="190" style="margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/9b9376d8-c108-4b9b-9962-8e83df08e1ab" width="190" />
</p>

---

## 🧪 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| **React Native** | Mobil uygulama çatısı |
| **Expo** | Hızlı geliştirme ve test ortamı |
| **React Navigation** | Sayfalar arası geçiş |
| **Redux Toolkit** | Global state yönetimi |
| **i18n** | Çoklu dil desteği |
| **Axios** | API çağrıları için |

---

## ⚙️ Kurulum

1. Depoyu klonla:

```bash
git clone https://github.com/mustafa-tezcan/subly-frontend.git
cd subly-frontend
```

2. Paketleri yükle:

```bash
npm install
```

3. Gerekli çevresel değişkenleri `.env` dosyasına ekle:

```
API_URL=https://your-api-url.com
```

4. Uygulamayı başlat:

```bash
npx expo start
```

---

## 🔧 Geliştirme Önerileri / İyileştirmeler

- ✅ **Dark mode** desteği eklenebilir.
- ✅ Bildirimler için **push notification** entegrasyonu yapılabilir.
- ✅ UI bileşenlerinde **TypeScript** ile daha güvenli yapı kurulabilir.
- ✅ Formlarda yup + formik ile **gelişmiş doğrulama** eklenebilir.
- ✅ PWA desteği ile web üzerinden de çalışabilir hale getirilebilir.
- ✅ Erişilebilirlik (accessibility) için testler yapılabilir.

---

## 🔄 Backend Entegrasyonu

Tüm abonelik verileri ve hatırlatmalar, [subly-backend](https://github.com/mustafa-tezcan/subly-backend) API’si ile senkronize çalışır.

---

## 📄 Lisans

MIT Lisansı © 2025 Mustafa Tezcan

---

## ✉️ İletişim

GitHub: [@mustafa-tezcan](https://github.com/mustafa-tezcan)  
Mail: mustafa@example.com
