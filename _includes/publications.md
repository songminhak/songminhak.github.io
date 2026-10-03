<h2 id="publications">Selected Publications</h2>
<p class="publications-all-link"><a href="{{ site.google_scholar }}">View all publications on Google Scholar →</a></p>
<small class="publications-note">(* denotes equal contribution)</small>

<div class="publications">
<ol class="bibliography">

{% assign selected_publications = site.data.publications.main | where: "selected", true %}
{% for link in selected_publications %}

<li>
      <div class="title"><a href="{{ link.arxiv }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      {% if link.footnote %} 
      <div class="author">{{ link.footnote }}</div>
      {% endif %}
      <div class="periodical"><em>{{ link.conference }}</em></div>
      {% if link.workshop %} 
      <div class="periodical"><em>{{ link.workshop }}</em></div>
      {% endif %}
</li>

{% endfor %}
</ol>
</div>
