{% assign members = "" %}
{% for id in page.members %}
  {% capture members %}{{ members | append: site.app.board[id] | append: "|" }}{% endcapture %}
{% endfor %}
Members: {{ members | split: "|" | sort | join: ", "  }}
