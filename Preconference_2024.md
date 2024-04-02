---
layout: page
title: Computational SAN Preconference 2024
year: 2024
featured-image: images/preconference/SANS.png
---

The third Computational preconference will be held at this year's <a href = "https://socialaffectiveneuro.org/preconference-workshop/">SANS</a> meeting in Toronto, Canada. 

The topics covered in the workshop include social reinforcement learning, multivariate pattern classification as applied to complex phenomena like emotional experience, and using automated computer vision to analyze facial expressions.  On-site at the conference, you will put theory into practice with hands-on tutorials and hacking.

**Please watch the pre-recorded talks below before the workshop.**  
Below each video you also find link(s) to relevant workshop materials (e.g. code, data)

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

### 1. Introduction to Reinforcement Learning

**(Video coming)**

**[Tutorial Materials]()**

### 2. Machine learning and neural decoding

**(Video coming)**

**[Tutorial Materials]()**

### 3. Analyzing Facial Expressions

<iframe width="560" height="315" src="https://www.youtube.com/embed/BpZ3EqSxEXk?si=HnyuY6rq7FY_2DwM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**[Tutorial Materials]()**

## Organizing Committee

The CompSAN preconference is being organized by Chelsea Helion (Temple), Kalina Michalska (UCR), and James Thompson (GMU).