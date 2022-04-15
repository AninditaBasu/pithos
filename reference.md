# Tide tables

<table>
<tr>
<th>Date</th><th>First high tide</th><th>Second high tide</th>
</tr>
{% for item in site.data.tides %}
<tr><td>{{ item.date }}</td><td>{{ item.first_tide }}</td><td>{{ item.second_tide }}</td></tr>
{% endfor %}
</table>