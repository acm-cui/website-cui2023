---
label: Volunteer for the Programme Committee
description: CUI !!conference.year!! is looking for volunteers for the Papers Programme Committee!

splash_title: Volunteer as an Associate<br>Chair for CUI !!conference.year!!

cta:
  text: Volunteer now
  title: Volunteer as an Associate Chair on the CUI !!conference.year!! Programme Committee
  link: https://forms.office.com/r/gpGr1n37Yq

track:
  chairs: papers

menus:
  organisers:
    title: Volunteer as an AC
    alt: CUI !!conference.year!! is looking for volunteers for the Papers Programme Committee!
    weight: 4
    sep_before: true
---

# Apply to be an Associate Chair

CUI {{ site.conference.year }} is looking for Associate Chairs (AC) for the CUI {{ site.conference.year }} Programme Committee! The deadline for applications is the **15th December 2022**.

For 2023 we are adopting the CHI AC+reviewer model for CUI for the first time.

## About the role

CUI Program Committee (PC) members will be assigned around 6 submissions as part of the peer review process over several months early in {{ site.conference.year }}. Each PC member will be the primary associate chair (1AC) for about half the submissions assigned to that PC member, and secondary (2AC) for the other half. The process for PC members will begin around 15 February (submission deadline), and finish on 27 April.


## Papers reviewing process

Note that CUI submissions are typically around 8,000 words in length excluding references, with longer papers being considered for desk rejection unless the length is commensurate to the contribution or the methodological approach. More details about the CUI conference can be found on the [papers track page]({{ "/submit/papers/" | relative_url }} "Papers track at CUI {{ site.conference.year }}"). For additional details you are also welcome to contact us, the CUI papers chairs (Joel E Fischer, Donald McMillan, and Jaisie Sin) at cui2023-papers@conversationaluserinterfaces.org 


<div class="text-center mb-3">
<a href="https://forms.office.com/r/gpGr1n37Yq" class="my-3 btn btn-lg btn-dark text-light border" title="Volunteer as an Associate Chair on the CUI !!conference.year!! Programme Committee">Volunteer now →</a>
</div>

<p>
{%- for group in site.data.oc -%}
{%- for role in group[1]['roles'] -%}
{%- if role[0] == page.track.chairs -%}
  For additional details you are also welcome to contact us, the CUI <a href="{{ role[1].email }}" title="Send an email to the CUI {{ site.conference.year }} {{ role[1].label }}">{{ role[1].label }}</a> (
  {% assign use_and = role[1]['people'] | size | plus: -1 -%}
  {%- for person in role[1]['people'] -%}
      {{- person.name -}}
      {%- if forloop.index == use_and %}, and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%}
  {%- endfor %}).
  {%- break -%}
{%- endif -%}
{%- endfor -%}
{%- endfor -%}
</p>

