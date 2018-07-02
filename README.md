# Sribu & Sribulancer Mixpanel Guidelines
---

# Introduction
Mixpanel merupakan sebuah tracker yang Sribu dan Sribulancer pakai. Melakukan kesalahan ketika menggunakan Mixpanel amatlah mudah, dikarenakan fleksibilitas yang tinggi dan penggunaannya yang jauh dari kata restriktif, mengharuskan adanya Guideline tersendiri bagi Sribu & Sribulancer untuk buat agar tiap event yang dibuat dapat konsisten dan mudah untuk digunakan oleh tim yang membutuhkan.

# Guide dalam memberikan alias ke halaman

## Halaman yang terikat dengan model

Jika sebuah halaman terikat dengan model, maka alias yang dibuat adalah proses yang dilakukan ke model tersebut, ditambah nama modelnya (`{proses} {model}`). Contohnya `Create Public Job`, `Edit Member`.

# Guide dalam membuat event

## Buat event dengan nama yang jelas

Berikut adalah guideline untuk pembuatan nama atas aksi-aksi yang umum: 

|Nama aksi |Event Mixpanel | Contoh | 
|-----------|----------------|------|
|Submit sebuah entitas baru | "New {nama entitas} Submit" | "New Public Job Submit"|
|Link menuju sebuah halaman | "Link To {nama alias halaman}" | "Link To Create Public Job" |

# Artikel yang berhubungan dengan Mixpanel

- https://medium.com/this-is-how-i-saas/ten-ways-to-get-mixpanel-right-the-first-time-717c87ca041

# [Daftar Aksi Mixpanel Di Sribulancer](pages.md)
