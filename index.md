---
layout: default
title: GitHub Training
---

# GitHub Training App (Static)

参加者は PR を通じて **プロフィールページ** を追加します。  
下記一覧にニックネームが表示されれば成功です。

<ul>
{% for member in site.participants %}
  <li><a href="{{ member.url }}">{{ member.title }}</a></li>
{% endfor %}
</ul>
