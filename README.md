# one month summer internship diary

<img src="https://i.hizliresim.com/govcaai.png" align="right" width ="400" height ="100">

## tech i learn

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

## -----day 00------ 18.07.2022

- oryantasyon
- staj yetkilisinin önerdiği dökümanları inceleyip gerekli kurulumları yaptım.
  (node.js&vscode için eklentiler)
- front-end'de react çalışacağım için javascript ile değişkenler ve de dom kavramlarını öğrenip üzerinden geçtim.

## -----day 01------ 19.07.2022

- back-end çalışmalarım için python 3.10.5 versiyonunu yükledim.
- mysql ve workbench kurulumunu yaptım.
- django kullanarak örnek projeyi ile oluşturdum.

## -----day 02------ 20.07.2022

- django model yapısınıı inceledim.
  - https://docs.djangoproject.com/en/4.0/topics/db/models/
- model yapısıyla class'lar oluşturarak veri tabanı bağlantısını yaptım.
- Verilen dökümantasyonlar üzerinden python bilgilerimi tazeledim.
- Projede kullanılacak olan mysql veritabanı için workbench yerine vscode içindeki eklentiyi kurdum.
  - https://marketplace.visualstudio.com/items?itemName=Oracle.mysql-shell-for-vs-code
- Django için aşağıdaki eklentiyi kurdum.
  - https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django
- Django ile models yapısı üzerinde alıştırmalar yapmaya devam ettim.
  - https://docs.djangoproject.com/en/4.0/ref/databases/#mysql-notes
- django admin paneli düzenledim ve veritabanına kayıtlar ekleyerek crud işlemlerini gerçekleştirdim.
- dinamik verilerle render admin panel ve veritabanı ilişkili sayfalar oluşturdum.
- One to Many Relation ile uygulamalar yaparak etkileşimli sayfalar oluşturdum.
  - https://docs.djangoproject.com/en/4.0/topics/db/examples/one_to_one/

## -----day 03------ 21.07.2022

- Front-End tarafında react ile real dom&virtual dom yapısını inceledim.
- Callback Functions / async-await, Promises ve Array Functions konularını gözden geçirdim.
- React projemi oluşturdum =>
  - https://create-react-app.dev/docs/getting-started/
  ```sh
    yarn create react-app hello-react
    cd hello-react
    yarn start
  ```
 ## -----day 04------ 22.07.2022
- Django Many to Many Relation kavramlarıyla uygulamalar yaparak etkileşimli sayfalar oluşturdum.
  - https://docs.djangoproject.com/en/4.0/topics/db/examples/many_to_one/
  
 ## -----day 05------ 25.07.2022
-  Many to Many Relation yapısıyla ilgili aldığım hataları veritabanı kısmında düzelttim.
  - https://docs.djangoproject.com/en/4.0/topics/db/examples/many_to_one/

 ## -----day 06------ 26.07.2022
- Django Many to Many Relation ile oluşturduğum sayfalara url yönlendirmelerini yaparak view.py içinde düzenlemeler yaptım.
  - https://docs.djangoproject.com/en/4.0/topics/db/examples/many_to_one/
  
 ## -----day 07------ 27.07.2022
- Django View Layer yapısını inceledim.
  - https://docs.djangoproject.com/en/4.0/topics/http/views/
- Class ve Template View üzerined çalışıp Class Based View yapısını inceledim.
  - https://docs.djangoproject.com/en/4.0/topics/class-based-views/

 ## -----day 08------ 28.07.2022
  - Yapacağımız projen belirlendi ve kullanacağımız teknolojilerle gruplara ayrılıp görev dağılımı yapıldı.
  - ``Görev
	Bir havayolu şirketinin havalimanına eleman taşıması için kullanılacak web application. Web sitesi panel olarak kullanılacak. Web sitesinde admin için giriş ekranı, sürücü ekleme, yolcu ekleme ekranı, görev ekleme ve görev izleme ekranı olacak. Görev oluştururken başlangıç ve son durak seçilecek. Sürücü ve yolcular göreve eklenecek. Görev ekranında bir harita üzerinden yolcuların konumlarını ve sürücünün konumunu görülebilecek. Hangi yolcular arabaya alınmış görülebilecek. Mobil üzerinde sadece sürücü için giriş ekranı olacak. Sürücüye atanmış olan görevler listenecek ve sürücü bu görevleri kabul veya red edebilecek. Sürücünün aktif konumu backende her 1-5 saniyede bir gönderilecek. Uygulama üzerinden kendi konumunu durakların konumunu ve yolcuların konumunu görebilecek. Yolcunun yakınına gelirse o yolcuyu aldım olarak işaretleyebilecek. Durak yakınlarında da vardım diyebilecek.``
 
 ## -----day 09------ 29.07.2022
  - Front-End olarak bir dashboard arayüzü kodlamamız istendi. Projenin ihtiyaçları doğrultusunda hem mobil hem web için Adobe Xd üzerinden bir tasarım oluşturdum.
  - Tasarımı Figma'ya aktararak ekip arkadaşlarımla paylaştım.
 
 ## -----day 10------ 01.08.2022
  - Tasarımı staj görevlisine göstererek onayını aldıktan sonra kodlamaya başladık.
  - Front-End kısmında React ile beraber Material UI kütüphanesini kullandık.
  	- [https://mui.com/](https://mui.com/)
 
 ## -----day 11------ 02.08.2022
  - Dashboard'ın anasayfasını kodlamaya başladım.
  - Projenin ihtiyaçlarına göre Sürücüler, Yolcular ve Görevler olarak oluşturduğum sidebar'ı böldüm.
  - <img src="https://i.hizliresim.com/djfiy0l.png" align="center">
 
 ## -----day 12------ 03.08.2022
  - Anasayfayı şekillendirerek gerekli kısımları ekledim. Geçici olarak dolu gözümesi için [FakerJs](https://fakerjs.dev/) kütüphanesini kullandım.
    - <img src="https://i.hizliresim.com/b8wrja4.png" align="left" width ="80%" height ="100%">
    - <img src="https://i.hizliresim.com/5w59bv2.png" align="right" width ="80%" height ="100%">
 
 ## -----day 13------ 04.08.2022
 
 ## -----day 14------ 05.08.2022
