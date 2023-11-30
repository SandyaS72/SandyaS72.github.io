{% assign tableItems = include.items | split: ", " %}
{% assign tableFileParam = {{include.file}} %}
{% assign tableFile = site.data[tableFileParam] %}

<table class="grid" style="width: 100%">
    <colgroup>
        <col width="30%" />
        <col width="70%" />
    </colgroup>
    <tbody>
    {% for entry in tableItems %}
        <tr>
          <td>{{ tableFile[entry].image }}</td>
          <td>{{ tableFile[entry].title }}<br/>
              {{ tableFile[entry].authors }}<br/>
              {{tableFile[entry].journal}} {{tableFile[entry].year}} 
              {% if tableFile[entry].link != empty %}{{ tableFile[entry].link }}{% endif %}</td>
        </tr>
    {% endfor %}
    </tbody>
</table>