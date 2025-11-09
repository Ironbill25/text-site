**[{{ site.title }}]({{ site.baseurl }}/)** 
{% for link in site.nav %}
[{{ link.title }}]({{ site.baseurl }}{{ link.url }}){% unless forloop.last %} | {% endunless %}
{% endfor %}
