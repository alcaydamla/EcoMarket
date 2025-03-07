# 🛒 EcoMarket

EcoMarket, **PHP ve MySQL** kullanılarak geliştirilmiş, **çok kullanıcılı, web tabanlı** bir bilgi sistemidir.  
Bu sistem, **son kullanma tarihi yaklaşan ürünlerin indirimli fiyatlarla satılmasını sağlayarak**, **marketteki israf oranını azaltmayı** ve **tüketicilerin daha uygun fiyatlarla alışveriş yapmasını** amaçlamaktadır.  

---

## Özellikler  
  ✔ Tarihi yaklaşan ürünler öncelikli olarak listelenir, böylece kullanıcılar ilk olarak bu ürünleri görebilir.
  ✔ Kullanıcıların indirimli ürünleri görüntüleyip satın alabilmesi
  ✔ Marketlerin indirimli ürünleri listeleyebilmesi
  ✔ Son kullanma tarihi yaklaşan ürünlerin indirimli satışa sunulması
  ✔ Kullanıcı girişi ve kimlik doğrulama
  ✔ PHP & MySQL ile dinamik ve güvenli bir yapı

---

## Teknolojiler  
- **Backend:** PHP  
- **Database:** MySQL  
- **Frontend:** HTML, CSS, JavaScript  

---

## Kurulum  
Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:  

```bash
# Repoyu klonla
git clone https://github.com/alcaydamla/EcoMarket.git
cd EcoMarket

# PHP çalıştırma
php -S localhost:8000

# MySQL veritabanını içe aktar
mysql -u root -p < database.sql
