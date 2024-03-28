---
layout: page
title: Events
exclude: true
---

<section>
  <div class="table-wrapper">
    <table>
      <thead>
        <tr>
          <th>Date</th>
          <th>Event</th>
          <th>Description</th>
        </tr>
      </thead>

      <tbody>
        {% for event in site.data.events %}
            <tr>
              <td>{{ event.Date }}</td>
              <td><a href="{{ event.Website }}">{{ event.Name}}</a></td>
              <td>{{ event.Description }}</td>
            </tr>
        {% endfor %}
      </tbody>
    </table>
  </div>
</section>

<h2>Want to be Added?</h2>
Either submit a pull request to our <a href="https://github.com/computational-san/computational-san.github.io">github page</a> after adding your event to the datafile:
<br>
<pre><code>_data/events.csv</code></pre>
or email us below.
