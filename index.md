---
layout: default
title: "Katalog Panci Shadow Army"
---

# 🍳 Koleksi Dapur Estetik Sultan

Selamat datang di katalog otomatis kami. Semua barang di bawah ini adalah rekomendasi terbaik yang lagi viral!

---

## 🛍️ Daftar Produk Terbaru:

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p>Diposting pada: {{ post.date | date: "%d %B %Y" }}</p>
    </li>
  {% endfor %}
</ul>

---
*Sistem ini dikelola otomatis oleh n8n & Shadow Army V8.*
