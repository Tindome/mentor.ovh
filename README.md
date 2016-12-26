# mentor.ovh
First file


Note

{% capture styles %}
  {% include test-main.scss.scss %}
{% endcapture %}
<style>{{ styles | scssify | strip }}</style>

Fonctionne très bien
