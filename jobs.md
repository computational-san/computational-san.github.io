---
layout: page
title: Jobs
---

{% assign positions = site.data.jobs | map: 'Position' | uniq %}

{% for position_type in positions %}
  <section>
    <h2>{{position_type}}</h2>
    <div class="table-wrapper">
      <table>
        <thead>
          <tr>
            <th>Institution</th>
            <th>Description</th>
          </tr>
        </thead>

        <tbody>
          {% for posting in site.data.jobs %}
            {% if posting.Position == position_type %}
              <tr>
                <td><a href="{{ posting.Ad }}">{{ posting.Institution}}</a></td>
                <td>{{ posting.Description }}</td>
              </tr>
            {% endif %}
          {% endfor %}
        </tbody>
      </table>
    </div>
  </section>
{% endfor %}


<h2>Want to be Added?</h2>
Either submit a pull request to our <a href="https://github.com/computational-san/computational-san.github.io">github page</a> after adding your position to the datafile:
<br>
<pre><code>_data/jobs.csv</code></pre>
or email us below.
