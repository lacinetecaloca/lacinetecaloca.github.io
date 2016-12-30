---
layout: default
---
<div class="card">
We meet every Thursday at **19:30**. The film starts at **20:00** ([BYOB](https://en.wikipedia.org/wiki/BYOB)).

Send an email to `la.cineteca.loca[at]gmail.com` to subscribe to our mailing list.

N&eacute;stor, Sondre & Gustavo\\
Bonn 23.09.2016
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
