# Ethical Hacker Web Penetration Tests and Bug Bounty
- [IP Çeşitleri](#IP-Çeşitleri)
- [HTML Yazabileceğimiz Yerler](#HTML-Yazabileceğimiz-yerler)
- [HTML](#HTML)
  - [Tag'ler](#Tag'ler)
  - [Head](#Head)
  - [Body](#Body)
  - [Başlık](#Başlık)

# IP Çeşitleri
> ## Public IP 
Kamuya açık IP
> ## Local IP
Modem tarafından bize verilen IP. Modemimizi her resetlediğimizde değişir
---
# HTML Yazabileceğimiz Yerler
> ## 1.Nano
```nano html101.html``` yazarak yeni bir html dosyası açabilir içine yazabiliriz
> ## 2. Geany 
Geany'i sadece ```HTML``` değil başka dilleri yazarkende kullanabiliriz
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
![]()
> ## Tag'ler
```<DOCTYPE html>``` belgenin tipini belirtir. Biz HTML kullanıyoruz demektir
> ## Head
```<HEAD>``` içine "meta data" dediğimiz genel özellikler yazılır
```
<head>
  <title>Kali Linux Website</title>
</head>
```
![]()
> ## Body
```<BODY>``` içine kullanıcının gördüğü elemanları yazarız

```<!--NOT-->``` kullanarak kod içine notlar bırakabiliriz
> ## Başlık 
```<h1>Hello World</h1>``` Başlık olarak büyük ve kalın fontta yazar

```<h2>Hello World</h2>``` Biraz daha küçük boyutta ve kalınlıkta yazar

...

```<h6>Hello World</h6>``` Olabilecek en küçük boyut ve kalınlıkta yazar
