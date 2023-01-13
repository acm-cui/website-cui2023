---
label: Doctoral Consortium
description: The CUI !!conference.year!! Doctoral Consortium is a half-day session where doctorate students of conversational user interfaces can discuss their research with other students and experts within the field

splash_title: Doctoral Consortium<br>at CUI !!conference.year!!

cta:
  text: Apply now
  title: Applications to attend the doctoral consortium are open
  link: https://docs.google.com/forms/d/1VitXQLhYOTkFWvpwv8ecDzpyHtrLFK_6Rp7Q_sWQzXE/viewform?ts=63908015&edit_requested=true 
  
track:
  chairs: dc
  dates: dc

#menus:
#  submit:
#    title: Doctoral Consortium
#    alt: Information about submitting to the posters track at CUI !!conference.year!!
#    weight: 7
#    is_track: true

lastmod: page
---

# Doctoral Consortium

The CUI {{ site.conference.year }} Doctoral Consortium is a half-day session where doctorate students of conversational user interfaces can discuss their research with other students and experts within the field. Doctoral work is important to our rapidly advancing area of research, and we very much look forward to making the Doctoral Consortium a meeting place for students in the field. 


## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>


## About the Doctoral Consortium

The Doctoral Consortium is a unique opportunity for students, at any stage of their doctoral work, to interact with experienced researchers in conversational user interfaces and discuss with peers.  

Senior members of the community will be assigned as mentors for the event. All students and mentors will attend the half-day Doctoral Consortium event in the conference (in-person or virtual), giving students the opportunity to discuss their ongoing research, academic life challenges, and career plans with mentors.  
  
The event will be conducted in hybrid mode, meaning that it is possible to attend in-person or virtual. If possible, physical attendance is recommended to benefit from informal in-person networking. 

### Eligibility

Students conducting research in the field of conversational user interfaces (broadly defined), at any stage of their Ph.D. studies. 
 
## The process

### 1. Prepare your application 

Students are invited to submit an application in extended abstract format for participation.

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates for Microsoft Word and LaTeX") to prepare your submission.  LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"), which we strongly encourage. LaTeX users should have the following document class: <code>\documentclass[sigconf, screen, review]{acmart}</code> for submission.

Word users should use [the double-column "Interim Template"](https://www.acm.org/publications/proceedings-template#h-interim-template "ACM Interim Template for submissions").

The application should be submitted as a single pdf file (max. 2 pages) outlining a research statement which contains the following: 
 
1. A summary of the applicant's research topic  
2. Answers to the following questions:  
	a. How far you are in your PhD?  
	b. What is the motivation for this research?  
	c. What is the expected contribution to the field?  
	d. What progress have you made so far?  
	e. What would you like to learn and discuss during the Doctoral Consortium? 
 
Incomplete applications will be rejected. 

### 2. Submit your application

You should submit your application to this [Google Form](https://docs.google.com/forms/d/1VitXQLhYOTkFWvpwv8ecDzpyHtrLFK_6Rp7Q_sWQzXE/viewform?ts=63908015&edit_requested=true "CUI {{ site.conference.year }} Doctoral Consortium application form"). 


### 3. Selection process – curated

Doctoral Consortium participants will be selected on the basis of their research statement through a curated process where the aim is to establish a participant group with complementary research interests and aims for participation. We aim for an inclusive selection process. 


### 4. Present and discuss your PhD  

As well as taking part in the Doctoral Consortium discussions and presentations, accepted participants are furthermore encouraged to present their thesis as a poster. This poster shall be presented alongside the posters from the poster session at the main conference so that students may receive feedback from conference attendees who are not part of the Doctoral Consortium.

The CUI {{ site.conference.year }} posters chairs will send information about the poster format upon acceptance as the Doctoral Consortium will use the same format. 
 

## Questions?

<p>
{%- for group in site.data.oc -%}
{%- for role in group[1]['roles'] -%}
{%- if role[0] == page.track.chairs -%}
  If you have any questions, please contact the <a href="{{ role[1].email }}" title="Send an email to the CUI {{ site.conference.year }} {{ role[1].label }}">{{ role[1].label }}</a>, 
  {% assign use_and = role[1]['people'] | size | plus: -1 -%}
  {%- for person in role[1]['people'] -%}
      {{- person.name -}}
      {%- if forloop.index == use_and %} and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%}
  {%- endfor %} for support.
  {%- break -%}
{%- endif -%}
{%- endfor -%}
{%- endfor -%}
</p>