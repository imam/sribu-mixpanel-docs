# Sribu & Sribulancer Mixpanel Guidelines
---

# Introduction
Mixpanel merupakan sebuah tracker yang Sribu dan Sribulancer pakai. Melakukan kesalahan ketika menggunakan Mixpanel amatlah mudah, dikarenakan fleksibilitas yang tinggi dan penggunaannya yang jauh dari kata restriktif, mengharuskan adanya Guideline tersendiri bagi Sribu & Sribulancer untuk buat agar tiap event yang dibuat dapat konsisten dan mudah untuk digunakan oleh tim yang membutuhkan.

# Guide dalam membuat event

## Buat event dengan nama yang jelas

Berikut adalah guideline untuk pembuatan nama atas aksi-aksi yang umum: 

| Nama aksi | Event Mixpanel |
|-----------|----------------:|
|Submit sebuah entitas baru | "New {nama entitas} Submit"|
|Link menuju sebuah halaman | "Link To {nama alias halaman}"|

### Jika event yang dibuat berupa link menuju sebuah halaman, maka lihat nama alias halaman di [Pages.md](pages.md)

Contoh event membuat link menuju halaman "Job Post", namakan eventnya "Link To Job Post"

# Artikel yang berhubungan dengan Mixpanel

- https://medium.com/this-is-how-i-saas/ten-ways-to-get-mixpanel-right-the-first-time-717c87ca041

# [List Mixpanel Event](pages.md)
