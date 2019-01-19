---
layout: post
author: farz
---

Nah, mari kita mulai dengan install jekyll theme

Pastikan sudah ada dependency yang dibutuhkan, contohnya saya menggunakan theme hacker,
yang berarti pada Gemfile.lock saya harus ada

```
  jekyll-theme-hacker (0.1.1)
  jekyll (~> 3.5)
```
jika belum ada, maka perlu ditambahkan ke Gemfile.lock,
beserta dependency nya yaitu

```
github-pages
jekyll
jekyll-feed
jekyll-seo-tag
jekyll-sitemap
tzinfo-data
wdm (~> 0.1.0)
```

kemudian jangan lupa untuk menambahkan

```
gemspecs
```
pada Gemfile kita, karena seluruh dependency dan bundle yang akan kita install terletak di specs.

Hasilnya dapat kita lihat seperti dibawah


![images](https://raw.githubusercontent.com/farz-hkh/Exercise/master/assets/images/hacker.png)

Selamat, kita akhirnya telah berhasil menginstall jekyll-theme.
