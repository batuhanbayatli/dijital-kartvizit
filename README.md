# 🚀 Dijital Kartvizit // Akıllı Acente Asistanı
> **bGroup // SigortamRahat × DATEX Tasarım**  
> *Sigorta Acenteleri İçin Veritabanısız, URL Tabanlı Mobil Kartvizit ve Otomatik A4 Vitrin Posteri Üreticisi*

<p align="left">
  <a href="https://dijital-kartvizit-coral.vercel.app/"><img src="https://img.shields.io/badge/Canlı%20Demo-Vercel-2563eb?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Canlı Demo"></a>
  <img src="https://img.shields.io/badge/Ecosystem-bGroup-0f172a?style=for-the-badge" alt="bGroup">
  <img src="https://img.shields.io/badge/Partners-SigortamRahat%20%C3%97%20DATEX-2563eb?style=for-the-badge" alt="Marka İş Birliği">
  <img src="https://img.shields.io/badge/Architecture-Serverless%20%2F%20URL--State-059669?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge" alt="License">
</p>

---

## 📌 Proje Özeti

**Dijital Kartvizit**, sigorta acentelerinin ve finansal danışmanların günlük operasyonlarındaki "IBAN paylaşma, ofis konumu gönderme, WhatsApp iletişim hattı yönlendirme" trafiğini tek bir akıllı bağlantıda toplayan **veritabanısız (serverless / state-in-url)** bir mikro-SaaS aracıdır.

Sistem, sunucuda hiçbir kişisel ya da finansal veri depolamaz; tüm acente bilgilerini doğrudan güvenli URL parametreleri üzerinde kodlar. Tek tıkla üretilen bağlantı sayesinde hem mobil cihazlarda akıcı çalışan bir dijital kartvizit hem de ofis vitrinine asılabilecek yüksek çözünürlüklü A4 QR poster elde edilir.

---

## ✨ Öne Çıkan Özellikler

* 🔒 **%100 Veri Gizliliği (Stateless & Serverless):** Hiçbir veritabanı veya sunucu kaydı tutulmaz. Bilgiler yalnızca bağlantının kendi içinde parametrik olarak taşınır.
* 💳 **Tek Tıkla IBAN Kopyalama:** Mobil kartvizite dokunan müşteri, acentenin IBAN numarasını panoya anında kopyalar.
* 📍 **Canlı Navigasyon Köprüsü:** Girilen açık adres tek tıkla Google Maps rota yönlendirmesine dönüşür.
* 💬 **Doğrudan WhatsApp İletişimi:** Önceden tanımlanmış teklif mesajıyla anında WhatsApp görüşmesi başlatır.
* 🖨️ **Otomatik A4 Vitrin Posteri:** `@media print` CSS mimarisi sayesinde ofis camına veya masasına asılabilecek QR kodlu A4 posteri tek tuşla yazdırır.
* 📱 **Uygulama Görünümlü Mobil Tasarım:** Bağlantı açıldığında editör gizlenir ve doğrudan akıcı bir native mobil kartvizit arayüzü sunulur.

---

## 🛠️ Teknoloji Yığını

* **Arayüz / Tasarım:** Semantic HTML5, Tailwind CSS (Clean SaaS UI)
* **İkonografi:** Lucide Icons CDN
* **QR Kod Motoru:** QRCode.js (İstemci taraflı vektörel render)
* **Mantık & Durum Yönetimi:** Vanilla ES6+ JavaScript & URLSearchParams API
* **Dağıtım / CI-CD:** Vercel Edge Network

---

## 🚀 Yerel Kurulum ve Çalıştırma

```bash
# Repoyu klonlayın
git clone [https://github.com/batuhanbayatli/dijital-kartvizit.git](https://github.com/batuhanbayatli/dijital-kartvizit.git)

# Proje dizinine geçin
cd dijital-kartvizit

# index.html dosyasını doğrudan tarayıcınızda açın veya canlı demoyu ziyaret edin:
# [https://dijital-kartvizit-coral.vercel.app/](https://dijital-kartvizit-coral.vercel.app/)
