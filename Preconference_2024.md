---
layout: page
title: Computational SAN Preconference 2024
year: 2024
featured-image: images/preconference/SANS.png
---

This year's Computational preconference will be held at this year's <a href = "https://socialaffectiveneuro.org/preconference-workshop/">SANS</a> meeting in Toronto, Canada. 

This highly experienced team has published multiple papers in the social computational space in both general science and cross-psychological area journals like Nature Neuroscience, Science Advances, Psychological Science, and Journal of Experimental Psychology: General. The topics covered in the workshop will reflect the work being done in their respective research programs, including social reinforcement learning, multivariate pattern classification as applied to complex phenomena like emotional experience, and using automated computer vision to analyze facial expressions.

Materials will be provided in advance for review, including pre-recorded talks with the relevant theory. On-site at the conference, you will put that theory into practice with this hands-on computational workshop where attendees will learn how to implement computational methods and evaluate results in small groups.

## Details

<ul>
<li><strong>Date</strong>: 1:30pm - 5:30pm, April 10th, 2024</li>
<li><strong>Location</strong>: Westin Harbour Castle, Toronto, Canada</li>
</ul>

## Speakers
<section>
  {% for speaker in site.data.preconference_speakers %}
    {% if speaker.Year contains page.year %}
      <figure>
      <a href="{{speaker.Website}}"><img src="images/preconference/{{speaker.Picture}}" alt="{{speaker.Name}}" height="300"></a>
      <figcaption><strong><a href="{{speaker.Website}}">{{speaker.Name}}</a></strong><p>{{speaker.Institution}}</p></figcaption>
      </figure>
    {% endif %}
  {% endfor %}
</section>

## Schedule

TBD!

## Organizing Committee

The CompSAN preconference is being organized by Chelsea Helion (Temple), Kalina Michalska (UCR), and James Thompson (GMU).