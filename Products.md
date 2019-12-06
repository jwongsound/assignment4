---
layout: page
title: Products & Services
permalink: products
---
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-154149731-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-154149731-1');
</script>

<h1>Explorers Academy’s Products and Services</h1>

<p>It was mentioned that the service-product bundle refers to the offering of many goods and services including what a university has to offer to its students.</p>
<p><strong><em>It consists of three elements:</em></strong></p>

{% for product in site.products %}
<h1>{{ product.title }}</h1>



{{product.content}}
{% endfor %}
