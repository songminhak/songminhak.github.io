<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>
<p style="font-size: 13px; margin-top: -10px; margin-bottom: 15px;"><em>(* denotes equal contribution)</em></p>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
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
      <a href="{{ link.paper }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Paper</a>
      {% endif %}
      {% if link.arxiv %} 
      <a href="{{ link.arxiv }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">arXiv</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

{% endfor %}
</ol>
</div>
