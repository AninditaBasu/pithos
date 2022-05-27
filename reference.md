---
nav_order: 4
---

# Tide tables

The following table lists the two high tides of the day at 15.2993° N, 74.1240° E.

<table>
<tr>
<th>Date</th><th>First high tide</th><th>Second high tide</th>
</tr>
{% for item in site.data.tides %}
<tr><td>{{ item.date }}</td><td>{{ item.first_tide }}</td><td>{{ item.second_tide }}</td></tr>
{% endfor %}
</table>