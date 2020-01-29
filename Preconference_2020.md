---
layout: page
title: Computational SAN Preconference 2020
year: 2020
featured-image: images/preconference/SANS.png
---

The second Computational preconference will be held at this year's <a href = "https://www.socialaffectiveneuro.org/conferences.html">SANS</a> meeting in Santa Barbara, CA. 

The goal of this workshop is to provide a general introduction to applying computational approaches to social and affective neuroscience questions. Each speaker will provide an introduction to a specific technique and illustrate how these techniques can be can be used to make inferences about various computational and affective processes. This year, the preconference will focus on two topics: Computational analysis of naturalistic social behavior; and Inferring mental states using Partially Observable Markov Decision Processes (POMDPs). There will be hands on demonstrations of how to apply these methods to real data and also brainstorming sessions for how these techniques might be applied to other datasets.

## Details

<ul>
<li><strong>Date</strong>: 9am - 12pm, May 7nd, 2020</li>
<li><strong>Cost</strong>: $35</li>
<li><strong>Location</strong>: Hilton Beachfront Resort, Santa Barbara, CA</li>
</ul>

## Registration

Registration is first come first serve.  Please fill out this [google form](https://docs.google.com/forms/d/e/1FAIpQLSc6OrZUJjM5wYM2He_hEo45gx9GuIvFziRpj5lpNznGMtdByA/viewform?usp=sf_link) with your registration details.

Then complete your payment using paypal.
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="BUZAJSSHH67GN">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_paynowCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

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

<section>
<div class="table-wrapper">
<table>
<thead>
<tr>
<th>Time</th>
<th>Event</th>
</tr>
</thead>
<tbody>

<tr>
<td>8:45</td>
<td>Registration</td>
</tr>


<tr>
<td>9:00</td>
<td>Welcome Remarks</td>
</tr>

<tr>
<td>9:05</td>
<td>Computational analysis of naturalistic social behavior (Jessy Lauer, Mark Thornton)</td>
</tr>

<tr>
<td>10:20</td>
<td>Break</td>
</tr>

<tr>
<td>10:40</td>
<td>Inferring mental states using Partially Observable Markov Decision Processes (POMDPs) (Vincent Costa, Tessa Rusch)</td>
</tr>

<tr>
<td>12:00</td>
<td>Preconference Over</td>
</tr>

</tbody>
</table>
</div>
</section>

## Organizing Commitee

The CompSAN preconference is being organized by James Thompson (GMU) and Luke Chang (Dartmouth). If you have any questions please contact us using the form below or email jthompsz@gmu.edu