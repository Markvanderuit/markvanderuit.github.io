<!-- {% if page.paperurl %}<a href="{{ page.paperurl }} " class="btn">
  <i class="fas fa-fw fa-file-pdf" style="margin-right: 0.5em"></i>Paper
</a>{% endif %}
{% if page.demourl %}<a href="{{ page.demourl }}" class="btn">
  <i class="fas fa-fw fa-code" style="margin-right: 0.5em"></i>Demo
</a>{% endif %}
{% if page.codeurl %}<a href="{{ page.codeurl }}" class="btn">
  <i class="fas fa-fw fa-code" style="margin-right: 0.5em"></i>Code
</a>{% endif %}
<a class="btn" style="padding-right: 1em" onClick="document.getElementById('citation').scrollIntoView();">
  <i class="fas fa-fw fa-quote-left" style="margin-right: 0.5em"></i>Cite
</a> -->

{% if page.paperurl %}<a href="{{ page.paperurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-file-pdf" style="margin-right: 0.25em"></i>Paper
</a>{% endif %}
{% if page.demourl %}<a href="{{ page.demourl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Demo
</a>{% endif %}
{% if page.codeurl %}<a href="{{ page.codeurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Code
</a>{% endif %}
<a style="margin-right: .5em;" onClick="document.getElementById('citation').scrollIntoView();">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Cite
</a>