---
layout: default
title: "Katalog Panci Shadow Army"
---

# 🍳 Koleksi Dapur Estetik Sultan

Selamat datang di katalog otomatis kami. Klik produk untuk detail dan link Shopee!

---

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; padding: 10px 0;">

  {% for post in paginator.posts %}
  <div style="border: 1px solid #eee; border-radius: 12px; overflow: hidden; background: #fff; box-shadow: 0 4px 15px rgba(0,0,0,0.05); transition: 0.3s;">
    
    <div style="width: 100%; height: 200px; overflow: hidden;">
      <img src="{{ post.image }}" alt="{{ post.title }}" style="width: 100%; height: 100%; object-fit: cover;">
    </div>

    <div style="padding: 15px; text-align: center;">
      <h3 style="font-size: 1.1rem; margin-bottom: 10px; color: #333;">{{ post.title | replace: "PRODUK VIRAL: ", "" }}</h3>
      <p style="font-size: 0.85rem; color: #888; margin-bottom: 15px;">Update: {{ post.date | date: "%d %B %Y" }}</p>
      
      <a href="{{ post.url | relative_url }}" style="display: inline-block; padding: 10px 20px; background: #ee4d2d; color: #fff; text-decoration: none; border-radius: 25px; font-weight: bold; font-size: 0.9rem;">Cek Detail & Beli</a>
    </div>

  </div>
  {% endfor %}

</div>

---
*Sistem ini dikelola otomatis oleh n8n & Shadow Army V8.*
