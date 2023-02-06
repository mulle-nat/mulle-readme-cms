## Author

{% for author in authors %}
[{{ author.name }}]({{ author.url }}){{ author.organization ? [@" for " stringByAppendingString:author.organization] : "" }}
{% endfor %}