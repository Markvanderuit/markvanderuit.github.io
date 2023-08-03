{% if post.paperurl %}<a href="{{ post.paperurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-file-pdf" style="margin-right: 0.25em"></i>Paper
</a>{% endif %}

{% if post.demourl %}<a href="{{ post.demourl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Demo
</a>{% endif %}

{% if post.codeurl %}<a href="{{ post.codeurl }}" style="margin-right: .5em;">
  <i class="fas fa-fw fa-code" style="margin-right: 0.25em"></i>Code
</a>{% endif %}