# yeah 
Txte de ma page

{{ site.description }}

<h1>{{ page.title }}</h1>
<ul>
{% for page in site.pages %}
<li>
    <a href="{{ page.title }}">{{ page.title }}</a>
</li>
{% endfor %}
</ul>