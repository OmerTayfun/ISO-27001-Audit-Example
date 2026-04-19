<div align="center">

[![ISO 27001 Annex A](https://img.shields.io/badge/ISO%2FIEC%2027001%3A2022-Annex%20A%20Denetim%20K%C4%B1lavuzu-0A2342?style=for-the-badge&logo=shield&logoColor=white)](https://omertayfun.github.io/ISO-27001-Audit-Example/)
[![Kontrol Sayısı](https://img.shields.io/badge/93%20Kontrol-4%20Tema-1565C0?style=for-the-badge)](https://omertayfun.github.io/ISO-27001-Audit-Example/)
[![Canlı Demo](https://img.shields.io/badge/🌐_Canlı_Demo-Görüntüle-2E7D32?style=for-the-badge)](https://omertayfun.github.io/ISO-27001-Audit-Example/)

# ISO/IEC 27001:2022 · Annex A Denetim Kılavuzu

**93 kontrol, 93 denetim sorusu.** ISO/IEC 27001:2022 Annex A'nın her kontrolü için denetim amacı, açık uçlu denetçi soruları, aranan kanıtlar ve gerçek hayattan alınmış tipik bulgu/öneri çifti.

[🌐 Canlı Demo](https://omertayfun.github.io/ISO-27001-Audit-Example/) &nbsp;·&nbsp; [📋 Ana Rehber](https://omertayfun.github.io/ISO-27001-Audit-Process/)

</div>

---

## 📌 Proje Hakkında

Bu kılavuz, ISO/IEC 27001:2022 Annex A'yı **denetçi perspektifinden** ele alan interaktif bir referans aracıdır. Sertifikasyon denetimi hazırlığı yapan BGYS sorumluları, iç denetçiler ve denetlenen taraflar için hazırlanmıştır.

Her kontrol kartı dört bileşenden oluşur:

```
📋  Denetim Amacı    →  Kontrolün neyi sağlaması gerektiği
❓  Denetçi Soruları →  Sahada kanıt çıkartan açık uçlu sorular
📁  Aranan Kanıtlar  →  Denetçinin masaya koymasını beklediği belgeler
🔴  Bulgu + Öneri    →  Sık karşılaşılan gerçek bulgular ve çözüm önerileri
```

---

## 🗂️ Kapsam

| Tema | Kontrol | İçerik |
|------|---------|--------|
| **A.5 Organizasyonel** | 37 | Politikalar, roller, tedarikçi, olay yönetimi, iş sürekliliği, mahremiyet |
| **A.6 Kişilerle İlgili** | 8 | Tarama, sözleşmeler, farkındalık, disiplin, uzaktan çalışma |
| **A.7 Fiziksel** | 14 | Güvenli alanlar, giriş kontrolü, ekipman, temiz masa, imha |
| **A.8 Teknolojik** | 34 | Erişim, MFA, log, yedek, ağ, şifreleme, güvenli geliştirme, DLP |

---

## 🔍 Öne Çıkan Özellikler

- Her kontrol için **gerçek hayattan tipik bulgu örneği** — soyut kural değil, sahada karşılaşılan somut sorunlar
- **Kanıt odaklı denetçi soruları** — "evet/hayır" değil, belge ve kayıt çıkartan açık uçlu sorular
- **Aksiyon odaklı öneriler** — "politika yazın" değil, uygulanabilir teknik ve süreç çözümleri
- Tema filtreleme (A.5 / A.6 / A.7 / A.8) ve arama özelliği
- Detaylı / Kompakt görünüm ve Koyu / Açık tema seçeneği
- [Ana Denetim Rehberi](https://omertayfun.github.io/ISO-27001-Audit-Process/) ile entegre — 8 aşamalı süreç, RACI haritası ve risk matrisiyle birlikte kullanılabilir

---

## 📋 Örnek Kontrol Kartları

### A.5.17 · Kimlik Doğrulama Bilgileri

> **Denetçi Sorusu:** MFA hangi sistemlerde zorunlu? Parola politikası NIST ile uyumlu mu?
>
> **Aranan Kanıt:** Parola politikası, MFA kapsam raporu, secret yönetim sistemi
>
> **Tipik Bulgu:** İnternet'e açık admin paneli MFA'sız; parola minimum 8 karakter.
>
> **Öneri:** Tüm admin ve uzak erişimlerde phishing-resistant MFA (FIDO2); şifreler ≥14 karakter veya passkey.

---

### A.8.11 · Veri Maskeleme

> **Denetçi Sorusu:** Non-prod ortamda gerçek üretim verisi var mı? Maskeleme aracı hangisi?
>
> **Aranan Kanıt:** Maskeleme config, örnek non-prod verisi, erişim logu
>
> **Tipik Bulgu:** Test ortamında üretim PII'si maskelenmeden kullanılıyor.
>
> **Öneri:** Synthetic data + deterministic masking; gerçek veri non-prod'a asla kopyalanmasın.

---

### A.8.29 · Geliştirme ve Kabul Testi

> **Denetçi Sorusu:** Pentest sıklığı nedir? Bug bounty programı var mı?
>
> **Aranan Kanıt:** Pentest raporları, bounty istatistikleri, düzeltme kanıtı
>
> **Tipik Bulgu:** Kritik uygulama yıllık external pentest'ten geçmemiş.
>
> **Öneri:** Yılda 1 external pentest + sürekli bug bounty; kritik bulgu → acil patch SLA.

---




---

## 🔗 İlgili Çalışmalar

| Proje | Açıklama |
|-------|----------|
| [ISO 27001 Denetim Rehberi](https://omertayfun.github.io/ISO-27001-Audit-Process/) | 8 aşamalı denetim süreci, RACI, risk matrisi, bulgu sınıflandırması |
| [KVKK Gap Analizi Aracı](https://omertayfun.github.io/kvkk-gap-analysis/) | 139 soruluk interaktif uyumluluk değerlendirme platformu |


---

## 👤 Yazar

**Ömer Tayfun DEVEÇEKER**<br>
Bilgi Güvenliği Uzmanı

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ömer-tayfun-deveçeker-6500928a/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/OmerTayfun)

---

## 📚 Kaynak

ISO/IEC 27001:2022 · Bilgi Güvenliği Yönetim Sistemleri — Annex A

---

<div align="center">
<sub>Bu kılavuz ISO/IEC 27001:2022 Annex A'yı denetçi perspektifinden özetler. Tam normatif metin için standardın kendisine başvurun. Denetim senaryoları kapsamınıza göre uyarlanmalıdır.</sub>
</div>
