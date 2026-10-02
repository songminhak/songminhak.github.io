<h2 id="publications">Selected Publications</h2>
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
    <div class="links">
      {% if link.paper %} 
      <a href="{{ link.paper }}" class="btn" target="_blank" rel="noopener">Paper</a>
      {% endif %}
      {% if link.arxiv %} 
      <a href="{{ link.arxiv }}" class="btn" target="_blank" rel="noopener">arXiv</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn" target="_blank" rel="noopener">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn" target="_blank" rel="noopener">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn" target="_blank" rel="noopener">BibTeX</a>
      {% endif %}
      {% if link.notes %} 
      <strong class="publication-highlight">{{ link.notes }}</strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
</li>

{% endfor %}
</ol>
</div>

<p><a href="{{ site.google_scholar }}">View all publications on Google Scholar</a></p>
