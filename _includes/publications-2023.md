{% assign tableItems = include.items | split: ", " %}
{% assign tableFileParam = {{include.file}} %}
{% assign tableFile = site.data[tableFileParam] %}

<table class="grid" style="width: 100%">
    <caption>{{include.caption}}</caption>
    <colgroup>
        <col width="30%" />
        <col width="70%" />
    </colgroup>
    <tbody>
    {% for entry in tableItems %}
        <tr>
          <td>....</td>
          <td>{{ tableFile[entry].title }}<br/>
          {{tableFile[entry].authors}}{{tableFile[entry].journal}}{{tableFile[entry].year}}</td>
        </tr>
    {% endfor %}
    </tbody>
</table>