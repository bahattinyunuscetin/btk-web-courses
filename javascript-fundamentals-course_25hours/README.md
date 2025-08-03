# ⚙️ BTK Akademi JavaScript Projeleri - Detaylı README

Merhaba! 👋 Bu klasör, [BTK Akademi](https://www.btkakademi.gov.tr/) üzerinden aldığım **JavaScript** eğitimi kapsamında geliştirdiğim projeleri içermektedir. Bu projeler sayesinde, web sayfalarına sadece iskelet (HTML) ve stil (CSS) değil, **zeka ve etkileşim** de kazandırdım. 💡

---

## 🧠 JavaScript Nedir?

**JavaScript**, web sayfalarını dinamik, etkileşimli ve akıllı hale getiren bir programlama dilidir. Tarayıcılar tarafından çalıştırılır ve kullanıcı ile anlık etkileşime giren olayları yönetir (tıklama, yazı yazma, sürükleme vb.).

Web’in ruhu, HTML + CSS’in motoru, interaktifliğin adı: **JavaScript** 🚀

---

## 🔍 JavaScript Ne İşe Yarar?

* Butonlara tıklanınca bir şeylerin olması
* Form verisi doğrulama
* Açılır menüler, karusel slaytlar
* Oyun mantıkları, sayaçlar, geri sayımlar
* API’lerle veri çekme (fetch/AJAX)
* DOM manipülasyonu (sayfa içeriğini dinamik değiştirme)

---

## 🔤 Temel Sözdizimi ve Yapılar

### Değişken Tanımlama:

```js
let mesaj = "Merhaba!";
const sabit = 42;
var eskiStil = true;
```

### Koşullu İfadeler:

```js
if (puan >= 50) {
  console.log("Geçtin!");
} else {
  console.log("Kaldın :(");
}
```

### Döngüler:

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

### Fonksiyonlar:

```js
function selamla(isim) {
  return `Merhaba, ${isim}!`;
}
```

### Olaylar (Events):

```js
document.querySelector("button").addEventListener("click", function() {
  alert("Butona tıkladın!");
});
```

---

## 🌍 DOM Nedir?

**DOM (Document Object Model)**, HTML sayfasının JavaScript tarafından erişilebilen bir temsilidir. Sayfadaki her öğeye erişebilir, değiştirebilir, silebilir ya da yenisini ekleyebilirsin.

Örnek:

```js
document.getElementById("baslik").innerText = "Yeni Başlık!";
```

---

## 🔧 Proje Örnekleri (Bu klasörde yer alabilir):

* **Sayaç (Counter) uygulaması**
* **Basit hesap makinesi**
* **Form doğrulama scripti**
* **Random şifre oluşturucu**
* **Fareyle renk değiştirme efekti**
* **DOM üzerinden yapılmış interaktif liste**
* **Zamanlayıcı (Timer)**

---

## ⚠️ Öğrenirken Bunlara Dikkat!

* `console.log()` en iyi dostundur. 🧠
* `undefined`, `null`, `NaN`, `==` vs `===` gibi konulara dikkat et!
* Tarayıcı konsolunu bol bol kullan.
* DOM elementlerini seçmeden önce DOM yüklendi mi emin ol (`DOMContentLoaded`).

---

## 🚀 JavaScript ile Geleceğe Hazırlık

JavaScript bilmek frontend dünyasının kapılarını açar: React, Vue, Angular, Node.js… Hepsi JS temeliyle çalışır.

Ayrıca JS ile oyun geliştirebilir, mobil uygulama yazabilir, hatta sunucu tarafı programlama bile yapabilirsin.

---

> ✨ *Kod yazmak mantıklı düşünmenin bir yoludur, JavaScript ise bunu etkileşimli yapmanın adıdır.*

Kodla, test et, boz, öğren, düzelt, tekrar et. 🔁

**👨‍💻 Hazırlayan:** Bahattin Yunus Çetin
📅 Eğitim Platformu: [BTK Akademi](https://www.btkakademi.gov.tr/)


