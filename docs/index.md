# CLC Landing Page

This is the landing page for a future CLC content repository.

## Glossary of terms

{% for word in site.glossary %}
{{ word.output }}
{% endfor %}
