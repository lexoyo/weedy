---
layout: default

---
<div class="about">

<h1>Le meilleur du CBD garanti zéro THC</h1>

<ul class="cols3 cols">
<li>
<div class="icon" style="background-image: url({{ "assets/images/best.png" | relative_url }}"></div>

<h3>Le meilleur !</h3>

Tous nos produits sont de qualité ultra-premium; ils sont fabriqués par des producteurs haut de gamme, selon des process à la pointe de l’industrie du CBD.

</li><li>
<div class="icon" style="background-image: url({{ "assets/images/zero-percent-thc.png" | relative_url }}"></div>

<h3>Zéro THC !</h3>

Pour vous permettre de ne courir aucun risque en cas de test de dépistage, nos produits ne se contentent pas de respecter le seuil maximal légal des 0.2% de THC: ils sont garantis zéro THC.

</li><li>

<div class="icon" style="background-image: url({{ "assets/images/money-back.png" | relative_url }}"></div>

<h3>Ganrantie sérénité</h3>

Si quoi que ce soit vous déplaît, renvoyez-nous votre commande, et nous vous rembourserons sans délais ni question.

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
