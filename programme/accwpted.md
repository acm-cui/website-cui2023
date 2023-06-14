---
label: Accepted papers
description: >
  Prior to the release of the full CUI !!conference.year!! programme, we have made avaialble titles of accepted publications.
  
#cta:
#  text: View in programme
#  title: Locate the keynote in the conference programme
#  link: /2022/programme/link/keynote

# menus:
#   programme:
#     title: Accepted papers
#     alt: Details of papers accepted for publication at CUI !!conference.year!!
#     weight: 3
---
We are still compiling the CUI {{ site.conference.year }} programme, and are awaiting the finalisation of all papers across all tracks. The following papers have been accepted, although their titles may change during the camera ready process.

# Papers track

{% for paper in site.data.accepted['papers'] %}
 * {{ paper }}
{% endfor $}

# Provocations track

{% for paper in site.data.accepted['provocations'] %}
 * {{ paper }}
{% endfor $}
