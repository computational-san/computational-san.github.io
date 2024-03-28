---
layout: page
title: Affiliated Labs
exclude: true
---

<section>
<div class="table-wrapper">
<table>

<thead>
  <tr>
    <th>Lab</th>
    <th>University</th>
    <th>PI</th>
  </tr>
</thead>

<tbody>
  {% for lab in site.data.labs %}
    <tr>
      <td><a href="{{lab.Website}}">{{lab.Name}}</a></td>
      <td>{{ lab.University }}</td>
      <td>{{ lab.PI }}</td>
    </tr>
  {% endfor %}
</tbody>

</table>
</div>

<h2>Want to be Added?</h2>
Either submit a pull request to our <a href="https://github.com/computational-san/computational-san.github.io">github page</a> after adding your lab to the datafile:
<br>
<pre><code>_data/labs.csv</code></pre>
or email us below.
