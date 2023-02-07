#  [Mekanbul MERN Yığını Uygulaması](https://github.com/asimsinan/abc-clone/wiki/Anasayfa)
Mekanbul insanların konumları civarındaki mekanları, sunduğu imkanları görmelerini, mekanlara yorum yapabilmelerini sağlayan bir web uygulamadır. Uygulamanın aynı zamanda bir admin paneli mevcuttur. Admin mekan ekleme, silme, güncelleme, tüm mekanları görme gibi işlemleri yapabilmektedir.

# Uygulama Özellikleri
Uygulama front-end ve back-end olmak üzere iki kısımdan oluşmaktadır. Frontend ReactJS ile kodlanmıştır. Backend'de NodeJS üzerinde geliştirilmiş REST API çalışmaktadır.
* **Normal Kullanıcı:** Konuma göre mekan listeleme, mekan detaylarını görebilme
* **Kayıtlı Kullanıcı:** Mekana yorum yapabilme, profil görüntüleme, profil güncelleme, şifre yenileme
* **Admin:** Tüm mekanları listeleme, mekan ekleme, mekan silme, mekan güncelleme
* **Varsayılan Rol:** Kullanıcı. Kullanıcılar koleksiyonuna giderek kayıt olduğunuz kullanıcıyı bulup rolünü "admin olarak değiştirerek admin özelliklerine erişebilirsiniz.

* **Front-end:** ReactJS, CSS, JSX, Javascript
* **Back-end:** NodeJS, ExpressJS, Javascript
* **Veritabanı:** MongoDB
* **Veri Modelleme:** Mongoose
* **Kimlik Doğrulama, Güvenlik:** PassportJS, JWT
* **Haberleşme:** REST API, Axios
* **Test:** Mocha,Mochawesome, Chai, Supertest
* **IDE:** Visual Studio Code
* **REST API Client:** Thunder Client
* **REST API Dokumantasyon Aracı:** Swagger
* **Versiyonlama:** Git

## Kütüphanelerin Yüklenmesi

Çalıştırmadan önce gerekli kütüphanelerin yüklenmesi gerekir. Proje klasörü içindeyken terminalde aşağıdaki komutları kullanarak bu kütüphaneleri yükleyin

### `cd frontend && npm install && cd ..`
### `cd backend && npm install && cd ..`
### `npm install`

## Uygulamanın Çalıştırılması
Aşağıdaki komut ile uygulamayı çalıştırabilirsiniz. 

### `npm start`

REST API [http://localhost:5000](http://localhost:3000) adresinde, front-end [http://localhost:3000](http://localhost:3000) adresinde çalışmaktadır.

## Ekran Görüntüleri
Buraya uygulamanın ekran görüntüleri eklenecek.

