{% assign tableItems = include.items | split: ", " %}
{% assign tableFileParam = {{include.file}} %}
{% assign tableFile = site.data[tableFileParam] %}

<p>{{tableItems}}</p>

<table class="grid" style="width: 100%">
    <colgroup>
        <col width="30%" />
        <col width="70%" />
    </colgroup>
    <tbody>
    {% for entry in tableItems %}
        <tr>
          <td>....</td>
          <td>{{ tableFile[entry].authors }}</td>
        </tr>
    {% endfor %}
    </tbody>
</table>
