---
layout: default
---
<div class="card">

The last screening of La Cineteca Loca will take place on 21.09.2017.

Thank you all for the great times!

N&eacute;stor, Sondre & Gustavo\\
Bonn 23.09.2016-21.09.2017
{: style="text-align: right"}
Alessandro, Sondre & Gustavo\\
Bonn 01.01.2016-22.09.2016
{: style="text-align: right"}
</div>

# Next screening

{% assign film = site.posts.first %}
{% include film-card.html %}

# Previous screenings

{% for film in site.posts offset:1 %}
{% include film-card.html %}
{% endfor %}
