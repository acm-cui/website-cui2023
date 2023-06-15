---
label: Accepted submissions
description: >
  Prior to the release of the full CUI !!conference.year!! programme, we have made avaialble titles of accepted submissions that will be prrsented at CUI this year.
  
#cta:
#  text: View in programme
#  title: Locate the keynote in the conference programme
#  link: /2022/programme/link/keynote

menus:
  programme:
    title: Accepted submissions
    alt: Details of papers, provocations, posters and demos accepted for publication at CUI !!conference.year!!
    weight: 3

---

# Accepted submissions

We are still compiling the CUI {{ site.conference.year }} programme, and are awaiting the finalisation of all papers across all tracks. The following papers have been accepted, although their titles may change during the camera ready process.

## Papers track

<ul>{% for paper in site.data.accepted['papers'] %}
<li>{{ paper | strip_html }}</li>
{% endfor %}</ul>

## Provocations track

<ul>{% for paper in site.data.accepted['provocations'] %}
<li>{{ paper | strip_html }}</li>
{% endfor %}</ul>

## Posters track

<ul>{% for paper in site.data.accepted['posters'] %}
<li>{{ paper | strip_html }}</li>
{% endfor %}</ul>

## Demos track

<ul>{% for paper in site.data.accepted['demos'] %}
<li>{{ paper | strip_html }}</li>
{% endfor %}</ul>
