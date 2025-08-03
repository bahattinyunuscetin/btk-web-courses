# 🎨 BTK Akademi CSS Projeleri 

Merhaba! 👋 Bu klasör, [BTK Akademi](https://www.btkakademi.gov.tr/) üzerinden tamamladığım **CSS (Cascading Style Sheets)** eğitiminde geliştirdiğim projeleri içermektedir. Bu projeler, web sayfalarını sadece iskelet değil; **şık, düzenli ve kullanıcı dostu hale getirmek** için CSS’in gücünü göstermeyi amaçlamaktadır.

---

## 🎯 CSS Nedir?

**CSS (Basamaklı Stil Şablonları)**, HTML ile yapılandırılmış web sayfalarına **renk, biçim, hizalama, aralık, animasyon ve genel görünüm** kazandırmak için kullanılan bir stil dilidir. HTML içeriktir, CSS sunumdur. 🤝

CSS ile:

* Arka plan renkleri, yazı tipleri, kenar boşlukları belirlenir.
* Sayfa düzeni grid veya flexbox sistemleriyle oluşturulur.
* Responsive (mobil uyumlu) tasarımlar yapılabilir.
* Hover efektleri, geçiş animasyonları uygulanabilir.

---

## 🔍 CSS'in Kullanım Yöntemleri

1. **Inline CSS:** HTML etiketi içine yazılır.

```html
<p style="color: red;">Kırmızı yazı</p>
```

2. **Internal CSS:** `<style>` etiketi ile HTML dosyasının `<head>` bölümünde tanımlanır.

```html
<style>
p {
  color: blue;
}
</style>
```

3. **External CSS:** Harici bir `.css` dosyası oluşturulur ve HTML’e linklenir (tavsiye edilen yöntem).

```html
<link rel="stylesheet" href="style.css">
```

---

## 🧱 Temel CSS Kavramları

### 📌 Seçiciler (Selectors):

* `*` → Tüm öğeleri seçer
* `p`, `div`, `h1` → Etiket seçici
* `.className` → Sınıf seçici
* `#idName` → ID seçici
* `element:hover`, `element:first-child` → Pseudo-class’lar

### 🎨 Özellikler (Properties):

* `color`, `background-color`, `font-size`, `font-family`
* `margin`, `padding`, `border`, `width`, `height`
* `display`, `position`, `z-index`, `overflow`

### 📐 Düzen Sistemleri:

* **Flexbox:** Yatay/dikey hizalama için birebir
* **Grid:** Karmaşık düzenler için güçlü yapı

---

## ✨ CSS ile Yapılabilecekler

* Kapsayıcı kutular oluşturmak (`div` + `box-shadow`, `border-radius`)
* Buton tasarımları
* Navigasyon menüleri
* Responsive tasarımlar (`@media` ile)
* Hover efektleri (`transition`, `transform`)
* Basit animasyonlar (`@keyframes`)

---

## 💡 Proje Örnekleri (Bu Klasörde Yer Alabilir):

* **Kişisel profil kartı**
* **Modern blog yazı şablonu**
* **CSS ile yapılmış buton seti**
* **Responsive grid tabanlı galeri**
* **Form tasarımı**
* **Flexbox ile hizalanmış içerik bölümleri**

---

## 📌 CSS Öğrenirken Dikkat Edilmesi Gerekenler:

* CSS dosyasını doğru linklemeyi unutma! 🔗
* Class ve ID seçiminde tutarlılık önemli
* Kapsayıcı kutuların iç içe geçmiş yapısını iyi analiz et
* Mobil uyumluluğu baştan düşün (responsive mindset)
* Gelişmiş stiller için önce temeli sağlam öğren

---

## 📈 CSS ile Kariyer Adımları

CSS bilmek sadece frontend geliştirici olmak için değil; UX/UI tasarımcı, web tasarımcısı, hatta WordPress tema geliştiricisi olmak için de şart.

CSS bilmeden HTML eksik kalır; HTML + CSS bilmeden de frontend olmaz. Bu yüzden bu klasör önemli bir temel taşıdır! 🧱

---

> 🎁 *Tasarım senin imzan, stil senin imzanın rengi olsun!*
> Kodla, boz, güzelleştir, tekrarla. 🔁

**👨‍💻 Hazırlayan:** Bahattin Yunus Çetin
📅 Eğitim Platformu: [BTK Akademi](https://www.btkakademi.gov.tr/)

---

📌 Bu README, sadece CSS projelerini kapsamaktadır. HTML ve JavaScript için ayrı klasörler ve açıklamalar hazırlanacaktır.

İyi çalışmalar, güzel stiller! 🌀
