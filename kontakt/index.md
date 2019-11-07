---
layout: contacts
description: Chcete se zapojit, nebo jenom vědět co se děje? Kontaktujte Piráty v Ostravě!
keywords: kontakt, adresa, telefon, mail, facebook, kde najdu, kde jsou
# Pokud nechcete, aby se zobrazovalo kontaktní místo, můžete odkomentovat následující řádek:
# noresidence: yes
contentSize: even
---

<div class="o-section-header o-section-header--indented">
  <h1 class="t-h2-alt">Přidejte se</h1>

Zajímá vás co Piráti dělají? Ozvěte se koordinátorovi nebo přijďte k nám
na schůzi (viz <a href="{{ '/' | relative_url }}">krajský kalendář</a>).
</div>

<div class="o-section-header o-section-header--indented">
  <h1 class="t-h2-alt">Materiály ke stažení</h1>

<ul>
  <li><a href="{{ 'assets/pdf/povolebni-strategie.pdf' | relative_url }}" target="_blank">Povolební strategie</a></li>
</ul>
</div>

<div class="o-section-header o-section-header--indented">
  <h1 class="t-h2-alt">Poslanci</h1>

{% assign person = site.people | where_exp: "item","item.uid contains 'lukas.cernohorsky'" | first  %}
{% include people/profile-badge.html item=person imgSize='big' imgStyle='round' class='c-profile-badge--centered' %}
<br>
{% assign person = site.people | where_exp: "item","item.uid contains 'ondrej.polansky'" | first  %}
{% include people/profile-badge.html item=person imgSize='big' imgStyle='round' class='c-profile-badge--centered' %}
</div>