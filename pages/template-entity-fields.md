<table class="table">
    <thead>
      <tr>
        <th>Name</th>
        <th>Type</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
	{% for field in entitydef.fields %}
      <tr>
        <td>{{ field.name }}</td>
        <td>{{ field.type }}</td>
        <td>{{ field.description }}</td>
      </tr>
	{% endfor %}
	</tbody>
</table>