# product-description-template-iu

## Product Description Template IU

This project is a structured **HTML, CSS, and JavaScript product description template system** designed to create visually rich and interactive product pages.

The main goal of the project is to provide a **clean, modular, and scalable folder structure** where:

- Each brand has its own directory
- Each product has its own directory
- Each product directory contains product images and a single HTML file
- HTML, CSS, and JavaScript are written together in one `.html` file
- Code is organized in a clear and consistent order

This structure is ideal for **e-commerce platforms**, **product showcase pages**, and **static product landing pages**.

---

## Project Purpose

- Standardize product description layouts
- Create reusable and maintainable product templates
- Keep brand and product files fully isolated
- Simplify updates and content management
- Allow fast duplication for new brands and products
- Provide a lightweight, framework-free solution

---

## Folder Structure Overview

Each brand has its own folder, and each product is stored as a subfolder inside its brand directory.

product-description-template-iu/
│
├── brand-name-1/
│ ├── product-name-1/
│ │ ├── image-1.jpg
│ │ ├── image-2.jpg
│ │ ├── image-3.png
│ │ └── index.html
│ │
│ ├── product-name-2/
│ │ ├── product-image.jpg
│ │ └── index.html
│ │
│ └── product-name-3/
│ ├── product-image.png
│ └── index.html
│
├── brand-name-2/
│ └── product-name-1/
│ ├── product-image.jpg
│ └── index.html
│
└── README.md

---

## Directory Structure Details

### Brand Directory

- Each brand has a dedicated folder
- Only products belonging to that brand exist inside the folder
- Folder names should follow **lowercase** and **kebab-case** naming conventions

**Example:**

ariete/
kenwood/
lenovo/

---

### Product Directory

- Each product has its own directory under its brand
- All product-specific files are stored here
- Product folders are completely independent from one another
- Product images are stored **directly inside the product directory**

**Example:**

ariete-party-time-krep-makinesi/
kenwood-kvl4100s-chef-xl-mutfak-sefi/
lenovo-legion-tab-zaef0037tr/

---

### Product Images

- All images related to the product are stored in the product directory
- Only image assets should be placed here

**Recommended formats:**

- `.jpg`
- `.png`

**Example:**

product-name/
├── background.jpg
├── phone-background.jpg
├── detail.png
└── index.html

---

## HTML File Structure

Each product directory contains a single `index.html` file.

This file includes:

- CSS styling
- HTML markup
- JavaScript logic

All written in a **clear and consistent order**.

---

## Code Order Inside `index.html`

1. **HTML Structure**
2. **CSS Styles**
3. **JavaScript Logic**

This approach keeps everything **self-contained** and easy to manage per product.

---

## HTML Section

The HTML structure typically includes:

- Product title
- Product description
- Image gallery
- Feature lists
- Interactive elements (tabs, buttons, sliders)

Semantic HTML elements are used whenever possible:

- `<section>`
- `<div>`

This improves **readability**, **accessibility**, and **SEO**.

---

## CSS Section

CSS is written inside a `<style>` tag within the HTML file and handles:

- Layout and positioning
- Typography and color schemes
- Responsive design for mobile and desktop
- Animations and transitions

Styles are written to allow **easy customization per product**.

---

## JavaScript Section

JavaScript is placed at the bottom of the HTML file inside a `<script>` tag.

Typical use cases include:

- Image sliders or galleries
- Tabbed content sections
- Interactive product details
- User-triggered animations

The project avoids unnecessary external libraries to keep pages **lightweight**.

---

## How to Use

1. Create a new brand folder in the root directory
2. Inside the brand folder, create a new product folder
3. Add all product images directly into the product folder
4. Edit the `index.html` file with product-specific content
5. Duplicate existing product folders to speed up new product creation

---

## Advantages

- Clean and predictable folder structure
- Modular and scalable design
- Easy maintenance and updates
- Product-level isolation
- No framework dependency
- Suitable for static and dynamic integrations

---

## Recommended Enhancements

- Extract shared CSS and JavaScript into global files
- Add a build or templating system
- Integrate with a CMS or backend API
- Add multi-language support
- Implement automated product generation scripts

---

## License

This project is intended for **personal or internal use**.  
Commercial usage terms can be defined based on project requirements.

-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-

# product-description-template-iu

## Product Description Template IU

Bu proje, görsel açıdan zengin ve etkileşimli ürün sayfaları oluşturmak için tasarlanmış, **HTML, CSS ve JavaScript tabanlı** bir ürün açıklama şablon sistemidir.

Projenin temel amacı, aşağıdaki özelliklere sahip **temiz, modüler ve ölçeklenebilir bir klasör yapısı** sunmaktır:

- Her markanın kendine ait bir dizini vardır
- Her ürünün kendine ait bir dizini vardır
- Her ürün dizini, ürün görsellerini ve tek bir HTML dosyasını içerir
- HTML, CSS ve JavaScript tek bir `.html` dosyası içinde birlikte yazılır
- Kodlar açık ve tutarlı bir sırayla düzenlenir

Bu yapı;

- E-ticaret platformları
- Ürün tanıtım sayfaları
- Statik ürün landing page’leri

için idealdir.

---

## Projenin Amacı

- Ürün açıklama sayfa düzenlerini standartlaştırmak
- Yeniden kullanılabilir ve sürdürülebilir ürün şablonları oluşturmak
- Marka ve ürün dosyalarını tamamen izole tutmak
- Güncelleme ve içerik yönetimini kolaylaştırmak
- Yeni marka ve ürünler için hızlı çoğaltma imkânı sağlamak
- Framework bağımlılığı olmayan, hafif bir çözüm sunmak

---

## Klasör Yapısı Genel Bakış

Her markanın kendine ait bir klasörü vardır ve her ürün, ilgili marka klasörü altında ayrı bir alt klasör olarak tutulur.

product-description-template-iu/
│
├── marka-adi-1/
│ ├── urun-adi-1/
│ │ ├── gorsel-1.jpg
│ │ ├── gorsel-2.jpg
│ │ ├── gorsel-3.png
│ │ └── index.html
│ │
│ ├── urun-adi-2/
│ │ ├── urun-gorseli.jpg
│ │ └── index.html
│ │
│ └── urun-adi-3/
│ ├── urun-gorseli.png
│ └── index.html
│
├── marka-adi-2/
│ └── urun-adi-1/
│ ├── urun-gorseli.jpg
│ └── index.html
│
└── README.md

---

## Dizin Yapısı Detayları

### Marka Dizini

- Her marka için ayrı bir klasör bulunur
- Bu klasörün içinde yalnızca o markaya ait ürünler yer alır
- Klasör adları **küçük harf** ve **kebab-case** formatında olmalıdır

**Örnek:**

ariete/
kenwood/
lenovo/

---

### Ürün Dizini

- Her ürün, markaya ait klasör altında kendi dizinine sahiptir
- Ürüne ait tüm dosyalar bu dizinde yer alır
- Ürün klasörleri birbirinden tamamen bağımsızdır
- Ürün görselleri **doğrudan ürün klasörü içinde** bulunur

**Örnek:**

ariete-party-time-krep-makinesi/
kenwood-kvl4100s-chef-xl-mutfak-sefi/
lenovo-legion-tab-zaef0037tr/

---

### Ürün Görselleri

- Ürüne ait tüm görseller ürün klasörü içinde saklanır
- Bu dizin içerisinde yalnızca görsel dosyalar bulunmalıdır

**Önerilen formatlar:**

- `.jpg`
- `.png`

**Örnek:**

urun-adi/
├── arkaplan.jpg
├── mobil-arkaplan.jpg
├── detay.png
└── index.html

---

## HTML Dosya Yapısı

Her ürün dizini içinde tek bir adet `index.html` dosyası bulunur.

Bu dosya aşağıdaki bölümleri içerir:

- CSS stilleri
- HTML yapısı
- JavaScript mantığı

Tüm bu bölümler **açık ve tutarlı bir sırayla** yazılır.

---

## `index.html` İçindeki Kod Sıralaması

1. **HTML Yapısı**
2. **CSS Stilleri**
3. **JavaScript Mantığı**

Bu yaklaşım, her ürün sayfasının **tamamen bağımsız** ve **kolay yönetilebilir** olmasını sağlar.

---

## HTML Bölümü

HTML yapısı genellikle aşağıdaki bileşenleri içerir:

- Ürün başlığı
- Ürün açıklaması
- Görsel galerisi
- Özellik listeleri
- Etkileşimli bileşenler (sekme, buton, slider vb.)

Mümkün olduğunca **semantik HTML etiketleri** kullanılır:

- `<section>`
- `<div>`

Bu sayede:

- Okunabilirlik
- Erişilebilirlik
- SEO

iyileştirilmiş olur.

---

## CSS Bölümü

CSS, HTML dosyası içerisinde `<style>` etiketi içinde yazılır ve aşağıdaki konuları kapsar:

- Yerleşim ve konumlandırma
- Tipografi ve renk paletleri
- Mobil ve masaüstü için responsive tasarım
- Animasyonlar ve geçiş efektleri

Stiller, ürün bazında **kolay özelleştirilebilir** olacak şekilde yazılır.

---

## JavaScript Bölümü

JavaScript kodları, HTML dosyasının en alt kısmında `<script>` etiketi içinde yer alır.

Tipik kullanım alanları:

- Görsel slider veya galeriler
- Sekmeli içerik alanları
- Etkileşimli ürün detayları
- Kullanıcı tetiklemeli animasyonlar

Proje, sayfaların hafif kalması için gereksiz harici kütüphanelerden kaçınır.

---

## Nasıl Kullanılır?

1. Ana dizinde yeni bir marka klasörü oluşturun
2. Marka klasörü içinde yeni bir ürün klasörü oluşturun
3. Ürün görsellerini doğrudan ürün klasörü içine ekleyin
4. `index.html` dosyasını ürün bilgileriyle düzenleyin
5. Yeni ürünler için mevcut ürün klasörlerini kopyalayarak hızlıca çoğaltın

---

## Avantajlar

- Temiz ve öngörülebilir klasör yapısı
- Modüler ve ölçeklenebilir tasarım
- Kolay bakım ve güncelleme
- Ürün bazlı izolasyon
- Framework bağımlılığı yok
- Statik ve dinamik entegrasyonlara uygun

---

## Önerilen Geliştirmeler

- Ortak CSS ve JavaScript dosyalarının ayrıştırılması
- Build veya templating sistemi eklenmesi
- CMS veya backend API entegrasyonu
- Çoklu dil desteği eklenmesi
- Otomatik ürün oluşturma script’leri

---

## Lisans

Bu proje **kişisel veya dahili kullanım** amacıyla hazırlanmıştır.  
Ticari kullanım şartları, proje gereksinimlerine göre tanımlanabilir.
