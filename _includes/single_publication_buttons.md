{% if page.paperurl %}<a href="{{ page.paperurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-file-pdf" style="margin-right: 0.25em"></i>Paper
</a>{% endif %}
{% if page.demourl %}<a href="{{ page.demourl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Demo
</a>{% endif %}
{% if page.codeurl %}<a href="{{ page.codeurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Code
</a>{% endif %}
{% if page.journalurl %}<a href="{{ page.journalurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-link" style="margin-right: 0.25em"></i>Journal
</a>{% endif %}
<a style="margin-right: .5em;" onClick="document.getElementById('citation').scrollIntoView();">
  <i class="fas fa-fw fa-solid fa-quote-left" style="margin-right: 0.25em"></i>Cite
</a>