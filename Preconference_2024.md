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

<iframe width="560" height="315" src="https://www.youtube.com/embed/xPSEuOz5FWo?si=UE2RtQ7BFkTDE70p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/R35RZn5a9PI?si=Pe6yoZcIGJQPrhOg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**[Tutorial Materials](https://www.dropbox.com/scl/fo/eqedsa5m02agd4zao5faj/ALVOcdgMVl0-kitCX3E0zu4?rlkey=8y6mlbcld1oxatcy06mhmx8na&dl=0)**

### 2. Machine learning and neural decoding

**(Video coming)**

**[Tutorial Materials](https://colab.research.google.com/drive/12zggQve_v6wOmN3M2fKxaUnJaUngZp3Z?usp=sharing)**

### 3. Analyzing Facial Expressions

<iframe width="560" height="315" src="https://www.youtube.com/embed/BpZ3EqSxEXk?si=HnyuY6rq7FY_2DwM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**[Tutorial Materials](https://www.dropbox.com/scl/fo/tqg8hzswxdadnsj564q16/h?rlkey=00tup5osbwc4zzczhoko9i58j&dl=0)**

## Organizing Committee

The CompSAN preconference is being organized by Chelsea Helion (Temple), Kalina Michalska (UCR), and James Thompson (GMU).
