{: #citation }
## Cite

{% if page.bibtex %}
  {% highlight bibtex %}
  @inproceedings{ {{ page.bibtex.name }},
    author    = { {{ page.bibtex.author }} },
    title     = { {{ page.title }} },
    year      = { {{ page.bibtex.year  }} },
    month     = { {{ page.bibtex.month }} },
    publisher = { {{ page.bibtex.publisher }} },
    doi       = { {{ page.bibtex.doi }} },
    journal   = { {{ page.bibtex.journal }}}
  }
  {% endhighlight %}
{% endif %}