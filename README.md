# Ethical Hacker Web Penetration Tests and Bug Bounty
- [IP Çeşitleri](#IP-Çeşitleri)
- [HTML Yazabileceğimiz Yerler](#HTML-Yazabileceğimiz-yerler)
- [HTML](#HTML)
  - [Tag'ler](#Tag'ler)
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
- [bWAPP]
  - [bWAPP Kurulumu](#bWAPP-Kurulumu)
  - [Burpsuite] (#Burpsuite)
  - [HTML Injection Reflected](#HTML-Injection-Reflected)
  - [HTML Injection Stored](#HTML-Injection-Stored)
  - [Formlardan Kullanıcı Adı ve Şifre Hackleme](#Formlardan-Kullanıcı-Adı-ve-Şifre-Hackleme)
  - [Dırbuster](#Dırbuster)
  - [iFrame Injection](#iFrame-Injection)

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
> ## Tag'ler
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
![]()

> ## Resim Yerleştirme
- ```<img width="600px" height=""400px" src="<resim URL'si>">```
> ## Buton Yerleştirme
- ```<button>click me </button>``` click me yazılı bir buton eklenir
> ## Footer ve Header
- ```<footer>Copyright ahmetnuysal 2022</footer>``` Sayfanın alt kısımına bilgi eklememizi sağlar

![](https://github.com/ahmetnuysal/Ethical-Hacker-Web-Penetration-Tests-and-Bug-Bounty/blob/b2017b3d14b9e08687e237570ea5efd5c6bf0948/Pictures/WhatsApp%20Image%202022-09-07%20at%2013.57.35.jpeg)
- ```<header>...</header>``` Sayfanın en üstüne bilgi eklememizi sağlar
