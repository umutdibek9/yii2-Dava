# yii2-Dava
yii2 framework kullanılarak basit bir modül oluşturma

Dava Module
Projenin amacı
Projenin amacı internet programcılığı dersinde öğrendiğimiz bilgileri kullanarak kendimize ait bir modül yazmaktır.
Öncelikle vagrant makinemizi çalıştırmak için "vagrant up" komutunu aşağıdaki resimdeki gibi giriyoruz.

![image](https://user-images.githubusercontent.com/100231266/158452774-65b9c829-200f-4505-bb04-de6a18070232.png)

Bir sonraki aşama ssh komutunu aşağıdaki gibi terminale yazıyoruz.

![image](https://user-images.githubusercontent.com/100231266/158452808-54fb3ffe-6e74-43d0-9581-85b4ef5f8bdc.png)

Bir sonraki aşama cd komutunu aşağıdaki gibi terminale yazıyoruz.

![image](https://user-images.githubusercontent.com/100231266/158452840-b045835a-eaf9-4fda-a9e5-a886f2255f64.png)

Bu aşamadan sonra terminale "composer require --prefer-dist umutdibek/yii2-dava"dev-main"" komutunu aşağıdaki gibi yazıyoruz.

![image](https://user-images.githubusercontent.com/100231266/158452870-d58e3127-a548-4c9c-8b5a-b0a642a2f513.png)

Bir sonraki aşama terminale "php yii migrate/up --migrationPath=@vendor/umutdibek/yii2-dava/src/migrations" komutunu aşağıdaki gibi yazmaktır.

![image](https://user-images.githubusercontent.com/100231266/158452893-8776fbc3-b7c1-4fae-938d-63b877f0d193.png)

Bundan sonra backend klosörünün içine girip main.php dosyasını açıyoruz.15. ve 16. satırı resimdeki yazılan kodları yazıyoruz.

![image](https://user-images.githubusercontent.com/100231266/158452927-cfd19482-0969-4ec4-864a-2f6f5e64a300.png)

Önceki aşamaları gerçekleştirdikten sonra interneti açıp "http://advanced/backend/web/index.php?r=dava/dava/index" resimdeki gibi yazıyoruz.

![image](https://user-images.githubusercontent.com/100231266/158452958-e1ab8efc-bd56-4ab4-90da-9346b161a7ec.png)

İnterneti açıp sayfaya ulaşıldıktan sonra dava ekranımız gelmektedir.Bu ekranda dava dosyaları tutulması için 'create' tuşuna basılmalıdır.Silinenleri görüntülemek için ise 'silinen' butonuna basılmalıdır.

![image](https://user-images.githubusercontent.com/100231266/158452979-af841e89-ac8d-4017-807a-3e76df2fb09c.png)

Create tuşuna basılırsa aşağıdaki resim gibi ekran gelmektedir.Bu ekranda kayıt tutulabilmektedir.
