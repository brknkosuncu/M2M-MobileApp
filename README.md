# M2M App

* Yazılım stajım için takımla beraber geliştirmiş olduğum bir mobil uygulama.

The purpose of creating this project; to enable mentees to find their mentors.

## Features Included in the Application:
* Mentors-Mentees in contact are listed on the main page. Also tags are listed on the main page
* You can give points to mentors and write comments to people. Mentors are listed as Top Mentors on the homepage according to the points you give.
* You can go to the profile of the mentor or mentee you want and see their information there.
* Users will be able to comment and rate the other users.
* On the profile page, the name of the profile, information about the profile, profile picture, user's rating, comments etc. information is available.
* User login, registration, connect, beign a mentor or a mentee etc. has features.
* You can contact the admin with the FeedBack feature and your feedback will be evaluated.
* Communication in infrastructure is created with REST API. REST API was written by our team.

 ## Used technologies:
* Middle tier: ExpressJS
* Server platform: NodeJS with Sequelize
* Database: PostgreSQL
* HTML Template Engine: Visual Studio Code
* CSS Framework: Bootstrap, Reactstrap etc.
* Programming Language: Javascript, Dart
* Version Control: Git
* Communication: REST API
* Interface Framework: Flutter
* Emulator Provider: Android Studio
* API Test: Postman 

Project setup

• Clone this project your computer.

• Open project folder.Open 2 terminal.

• For first terminal, go to client folder and run `flutter pub get` command.

• For second terminal, go to server folder and run `npm install` command.

• In `/server/database/index.js` file, enter your database informations for connect with database.

• In `.env` file, enter your informations for configuration.

• `JWT_SECRET= enter secret key what you want`

• `SMTP_USER= enter email for admin`

• `SMTP_PASSWORD= enter email password for admin`

• `TO_MAIL= enter email for persons who wants to contact with you`

• When the installations finish, run `npm start` command in the server side terminal. After that, run client side with Emulator or what you want.

• Congrulations, you started application successfully!

# VETAPP

Bu projenin oluşturulmasındaki amaç; menteelerin mentorlarını bulmalarını sağlamak.

## Uygulamada Yer Alan Özellikler:
* Anasayfa'da bağlantı içerisinde olunan mentor-mentee'ler, Tag'ler listelenir.
* Mentor'lere puan verebilir, kişilere yorum yazabilirsiniz. Verdiğiniz puanlara göre Mentor'ler anasayfada Top Mentors olarak listelenir.
* İstediğiniz mentor ya da mentee'nin profiline gidebilir, bilgilerini görebilirsiniz.
* Profil sayfasında profilin adı, profil hakkında bilgiler, profil resmi, kullanıcının puanı, aldığı yorumlar vb. bilgiler bulunuyor.
* Kullanıcı girişi, kayıt olma, mentor ya da mentee olabilme gibi özellikler bulunuyor.
* FeedBack özelliği ile adminle iletişime geçebilir ve geri-dönüşümleriniz değerlendirilir.
* Altyapıda haberleşme REST API ile oluşturulmuş olup. REST API birlikte çalıştığımız takımımız ile beraber yazılmıştır.


## Kullanılan Teknolojiler:
* Orta katman: ExpressJS
* Sunucu platformu: NodeJS
* Veritabanı: PostgreSQL
* HTML Şablon Motoru: Visual Studio Code
* Programlama Dili: Javascript, Dart
* Sürüm Kontrolü: Git
* Haberleşme: REST API
* Arayüz Çatısı: Flutter
* Emülator Sağlayıcı: Android Studio
* API Testi: Postman


Projenin kurulumu

• Projeyi bilgisayarınıza klonlayın.

• Proje klasörünü açın ve iki terminal açın.

• Birinci terminalde client klasörüne gidin ve `flutter pub get` komutunu çalıştırın.

• İkinci terminalde server klasörüne gidin ve `npm install` komutunu çalıştırın.

• `.env` dosyasında konfigürasyon için bilgilerinizi girin.

• Örnek olarak,

• `JWT_SECRET= istediğiniz bir secret key`

• `SMTP_USER= admin için email adresi`

• `SMTP_PASSWORD= admin için email şifresi`

• `TO_MAIL= sizinle iletişim kurmak isteyenler için email adresi`

• Kurulumlar bittiğinde server terminalinde `npm start` komutunu çalıştırın. Daha sonra client terminalinde uygulamayı bir Emülator ile çalıştırın.

• Tebrikler, uygulamayı başarıyla çalıştırdınız!


![alt text](https://github.com/brknkosuncu/M2M-MobileApp/blob/main/server/src/helpers/images/login_page.png "resim 1")
![alt text](https://github.com/brknkosuncu/M2M-MobileApp/blob/main/server/src/helpers/images/main_page.png "resim 2")
![alt text](https://github.com/brknkosuncu/M2M-MobileApp/blob/main/server/src/helpers/images/Screenshot_1660293956.png "resim 3")
![alt text](https://github.com/brknkosuncu/M2M-MobileApp/blob/main/server/src/helpers/images/mentor_page.png "resim 4")
