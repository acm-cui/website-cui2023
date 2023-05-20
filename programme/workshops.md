---
label: Workshops
description: Workshops hosted at the ACM Conversational User Interfaces (CUI) !!conference.year!! conference.

title: Workshops
splash_title: Workshops at CUI !!conference.year!!

menus:
  attend:
    title: Workshops
    alt: Workshops hosted at CUI !!conference.year!!.
    weight: 0
  programme:
    title: Workshops
    alt: Workshops hosted at CUI !!conference.year!!.
    weight: 3
---

CUI {{ site.conference.year }} is delighted to hosted five topical workshops at the conference this year. Attendance at workshops requires [conference and workshop registration]({{"/attend/registration/" | relative_url}}) prior to the conference. Each workshop may have its own criteria for attendance (e.g., the submission of a position paper), thus you are advised to check details posted by workshop organisers in advance of the conference.

{% for workshop in site.data.workshops %}

{% if forloop.index0 > 0 %}

<br>
{% endif %}

## {{ workshop.title }}
<em>{{ workshop.datetime }}</em>{% if workshop.url %} &bull; [Workshop Website]({{ workshop.url }} "{{ workshop.title}}"){% endif %}

{{ workshop.description}}

Organised by {{ workshop.organisers }}

{% endfor %}

