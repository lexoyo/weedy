---
layout: default

---
<div class="about">

<h1>Le meilleur du CBD, garanti zéro THC</h1>

<ul class="cols3 cols">
<li>
<div class="icon" style="background-image: url({{ "assets/images/best.png" | relative_url }}"></div>

<h3>Le meilleur</h3>

Nous sélectionnons pour vous des produits de qualité ultra-premium, conçus et fabriqués par les producteurs les plus réputés au monde, selon des procédés et savoir-faire à la pointe de l'industrie du CBD.

</li><li>
<div class="icon" style="background-image: url({{ "assets/images/zero-percent-thc.png" | relative_url }}"></div>

<h3>Zéro THC</h3>

Pour vous permettre de ne courir aucun risque en cas de test de dépistage, nos produits ne se contentent pas de respecter le seuil maximal légal des 0.2% de THC: ils sont garantis zéro THC.

</li><li>

<div class="icon" style="background-image: url({{ "assets/images/money-back.png" | relative_url }}"></div>

<h3>Garantie sérénité</h3>

Vous avez changé d'avis ? Renvoyez-nous votre commande,  nous vous rembourserons sans délai, ni question.

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
