---
layout: default

---
<div class="about">

<h1>CBD ULTRA-PREMIUM, GARANTI ZÉRO THC</h1>

<ul class="cols3 cols">
<li>
<div class="icon" style="background-image: url({{ "assets/images/best.png" | relative_url }}"></div>

<h3>CBD ultra-premium</h3>

Apanage est fier de vous proposer la plus haute qualité de produits CBD existante. Pour cela nous sélectionnons les tout meilleurs producteurs au monde, en termes de savoir-faire, d'innovation, et de réputation.

</li><li>
<div class="icon" style="background-image: url({{ "assets/images/zero-percent-thc.png" | relative_url }}"></div>

<h3>Zéro THC</h3>

Pour vous permettre de ne courir aucun risque en cas de test de dépistage, notre gamme de produits ne se contente pas de respecter le seuil maximal légal des 0.2% de THC: elle est garantie zéro THC.

</li><li>

<div class="icon" style="background-image: url({{ "assets/images/money-back.png" | relative_url }}"></div>

<h3>Garantie sérénité</h3>

Vous avez changé d'avis ? Renvoyez-nous votre commande,  nous vous rembourserons sans délai ni question.

</li>
</ul>

<ul class="cols2 cols">

{% for customer in site.customers %}
  <li>{% include customer.html %}</li>
{% endfor %}

</ul>

<h2>Produits recommandés pour vous</h2>

</div>


{% for product in site.products %}
  {% include product.html %}
{% endfor %}

{% include contact-form.html %}
