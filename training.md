---
layout: page
title: Training Resources
---

## Summer Schools
<section>
<div class="table-wrapper">
<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
</thead>

<tbody>
  {% for school in site.data.summerschool %}
  <tr>
    <td><a href = "{{ school.Website }}">{{ school.Name }}</a></td>
    <td>{{school.Description}}</td>
  </tr>
  {% endfor %}
</tbody>

</table>
</div>
</section>

## Web Resources
<section>
<div class="table-wrapper">
<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
</thead>

<tbody>
  {% for web in site.data.webresources %}
  <tr>
    <td><a href = "{{ web.Website }}">{{ web.Name }}</a></td>
    <td>{{ web.Description }}</td>
  </tr>
  {% endfor %}
</tbody>

</table>
</div>
</section>

## Want to be Added?
Either submit a pull request to our <a href="https://github.com/computational-san/computational-san.github.io">github page</a> after adding your lab to the datafile:
<br>
<pre><code>_data/webresources.csv</code></pre>
or email us below.
