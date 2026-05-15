{% assign tableItems = include.items | split: ", " %}
{% assign tableFileParam = include.file %}
{% assign tableFile = site.data[tableFileParam] %}

<div class="publications-list mb-5">
  {% for entry in tableItems %}
    <div class="pub-row d-flex flex-column flex-md-row align-items-start mb-4 p-3 bg-white rounded shadow-sm">
      
      {% if tableFile[entry].image and tableFile[entry].image != "" %}
        <div class="pub-image mr-md-4 mb-3 mb-md-0 text-center">
          {{ tableFile[entry].image }}
        </div>
      {% endif %}
      
      <div class="pub-details flex-grow-1">
        <h5 class="pub-title mb-1">{{ tableFile[entry].title }}</h5>
        <div class="pub-authors text-dark mb-1">{{ tableFile[entry].authors }}</div>
        <div class="pub-meta text-muted font-italic">
          {{ tableFile[entry].journal }} {{ tableFile[entry].year }} 
          {% if tableFile[entry].link and tableFile[entry].link != "" %}
            <span class="pub-link ml-2"> •  {{ tableFile[entry].link }}</span>
          {% endif %}
        </div>
      </div>
      
    </div>
  {% endfor %}
</div>

<style>
  .pub-row { border-left: 4px solid #e0eeee; transition: border-left-color 0.2s ease; }
  .pub-row:hover { border-left-color: #008080; }
  
  /* Thumbnail Dimensions constraints */
  .pub-image img { max-width: 130px; height: auto; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.08); }
  @media (max-width: 768px) { .pub-image img { max-width: 100%; max-height: 140px; } }

  /* Substantial Typography Settings */
  .pub-title { color: #111111 !important; font-weight: 600; font-size: 1.15rem; line-height: 1.4; }
  .pub-authors { font-size: 1.05rem; color: #333333 !important; font-weight: 400; }
  .pub-meta { font-size: 0.95rem; }
  
  /* Auto-clean injected raw a-tag styling inside data blocks */
  .pub-meta a { color: #008080 !important; font-weight: 600; text-decoration: none; }
  .pub-meta a:hover { text-decoration: underline !important; color: #005353 !important; }
</style>
