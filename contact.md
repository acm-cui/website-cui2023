---
description: Contact details for CUI !!conference.year!!.
lastmod: page
---

# Contact us

{%- for group in site.data.oc -%}
    {%- for role in group[1]['roles'] -%}
        {% if role[1]['contact'] -%}
            <p>
                If you need any help or have questions regarding the conference, please do not hesitate to get in touch with the <a href="{{ role[1].email }}" title="Send an email to the CUI {{ site.conference.year }} {{ role[1].label }}">CUI {{ site.conference.year }} {{ role[1].label }}</a>, 
                {% assign use_and = role[1]['people'] | size | plus: -1 -%}
                {%- for person in role[1]['people'] -%}
                    {{- person.name -}}
                    {%- if forloop.index == use_and %}, and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%}
                {%- endfor -%}.
            </p>
            {%- break -%}
        {%- endif -%}
    {%- endfor -%}
{%- endfor -%}

