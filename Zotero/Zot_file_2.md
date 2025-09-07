
***Formatted Bibliography***
{{bibliography}}


{% for annotation in annotations -%} {%- if annotation.annotatedText -%}
« {{annotation.annotatedText}} »([{{annotation.page}}](zotero://open-pdf/library/items/{{annotation.attachment.itemKey}}?page={{annotation.page}}&annotation={{annotation.id}}))


{% endif %}{% if annotation.imageRelativePath %}![[{{annotation.imageRelativePath}}]]{% endif %}{% if annotation.comment %} > >{{annotation.comment}}{%- endif %} {% endfor %}
