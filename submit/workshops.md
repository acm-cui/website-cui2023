---
label: Workshops
description: CUI !!conference.year!! will feature a dedicated workshops track, allowing attendees to organise focused activities co-located at the conference. We are now open to workshops proposals.

splash_title: Workshops<br>at CUI !!conference.year!!

cta:
  text: Submit now
  title: Submit a workshop proposal by email
  link: 'mailto:cui2023-workshops@cui.acm.org'
  
track:
  chairs: workshops
  dates: workshops

menus:
  submit:
    title: Workshops
    alt: Information about propsing a workshops at CUI !!conference.year!!
    weight: 6
    is_track: true
    sep_before: true

lastmod: page
---

# Workshop proposal submission information

CUI {{ site.conference.year }} will be the first year we have a dedicated workshops track for the conference—workshops at CUI {{ site.conference.year }} will be half-day or whole day workshop, **in-person**. 
 
To propose a workshop, you should write a proposal that the topic and your plans for the workshop. If accepted, you will be expected to lead on the organisation of the workshop. At least one workshop organizer is expected to attend the conference. Workshops can be planned to be fully in-person or in hybrid mode. If workshop organizers are proposing a hybrid setup, we ask to include a description of how they plan to accommodate remote participants for an inclusive and effective workshop experience.

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## The process

All submissions will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.

### 1. Prepare your proposal

Submissions of proposals for workshops must be in English, in PDF format. You should NOT anonymise your workshop proposal. In your proposal you must include a title, abstract, background to your workshop topic, plans for the workshop, how long the workshop will be (half-day or whole day), how you will solicit papers/attendees, how you will create an accessible and inclusive experience, a website address, and biographies for the organisers. Your proposal should be no more than **5,000 words** (including figures, tables, proofs, appendixes, and any other content, excluding references and acknowledgments). 

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates for Microsoft Word and LaTeX") to prepare your submission.  LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"), which we strongly encourage. LaTeX users should have the following document class: <code>\documentclass[sigconf, screen, review]{acmart}</code> for submission.

Word users should use [the double-column "Interim Template"](https://www.acm.org/publications/proceedings-template#h-interim-template "ACM Interim Template for submissions") during submission and review and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline. Word users may be required to reimplement their proposal, if accepted, into the correct document format for the publishing process.

ACM's CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.

### 2. Submit your proposal

You should submit your proposal to the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a>:<br>{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] | replace: "mailto:", "" }}<br>

Please make sure to include your title, abstract, author details, and proposal in PDF.  
 
Proposed workshop topics should be of interest to the conversational user interface research community. Possible topics include, but are not limited to: 

* Design considerations for conversational UX 
* Formatting content for conversation 
* Real-world applications of conversational agents 
* Working with foundational models (e.g., BERT, ChatGPT) 
* Hybrid approaches to voice and text 
* Understanding human conversation 
* Evaluating conversational agent performance 
* Turn-taking and interaction systems 
* Delighting the user with humorous conversation 
* and more... 

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission").

By submitting your article to an ACM Publication, you are hereby acknowledging that you and your co-authors are subject to all [ACM Publications Policies](https://www.acm.org/publications/policies "ACM Publications Policies and Procedures"), including [ACM's new Publications Policy on Research Involving Human Participants and Subjects](https://www.acm.org/publications/policies/research-involving-human-participants-and-subjects "https://www.acm.org/publications/policies/research-involving-human-participants-and-subjects"). Alleged violations of this policy or any ACM Publications Policy will be investigated by ACM and may result in a full retraction of your paper, in addition to other potential penalties, as per ACM Publications Policy.

Sensitive, private and/or proprietary information should not be disclosed prior to publication. Business exposure is reserved for event sponsors only, so advertising materials should not be used in demonstrations. 

### 3. Await reviews

Each submission will be reviewed by one track chair and one expert reviewer through a curated process, in which reviewers will assess the novelty, feasibility, delivery and ability to engage attendees in-person according to the workshop proposal submission. Following a curated selection process, successful submissions will be invited to organize a workshop at CUI {{ site.conference.year }}. Notifications will be given on or before **14th Apri 2023**. 

### 4a. Plan your workshop 

If your workshop proposal is accepted, we ask you to start work on the workshop organisation immediately. 
 
Workshop organization responsibilities include:  
* Setting up a website for the workshop 
* Publicizing the workshop and inviting potential participants to submit 
( Collecting submissions and selecting workshop participants based on the quality of their position papers (with or without external reviews) 
* Running the workshop at the conference (in-person) 
* Optionally, compiling and publishing workshop proceedings 
* Optionally, soliciting and coordinating invited speakers for the workshop 

### 4b. Prepare your proposal for publication

If your proposal is accepted, you must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

Programme Chairs will send information on how to ready your proposal for the publishing process. Word users may be required to reimplement their proposal, if accepted, into the correct document format for the publishing process, while LaTeX users will have to adjust their <code>documentclass</code>.

At least one author of each accepted workshop proposal must register for the conference and attend the conference in-person, otherwise we cannot guarantee publication of your proposal. Accepted proposal will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>. All workshop organisers wishing to attend must register for the conference. 

You will receive an email from ACM to assign the rights for your proposal, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your proposal. Accepted proposals will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM's guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

Please ensure that you and your co-authors [obtain an ORCID ID](https://orcid.org/register "Register for an ORCID ID"), so you can complete the publishing process for your accepted paper. ACM has been involved in ORCID from the start and we have recently [made a commitment to collect ORCID IDs from all of our published authors](https://authors.acm.org/author-resources/orcid-faqs "ACM committment to collect ORCID IDs from all authors"). The collection process has started and will roll out as a requirement throughout 2022. We are committed to improve author discoverability, ensure proper attribution and contribute to ongoing community efforts around name normalization; your ORCID ID will help in these efforts.

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

### 5. Present your work

CUI workshops will be held on 19th July 2023 (first day of the conference). You will be provided details about the timings of your workshop closer to the time by the Workshops chairs.

Your proposal will be published in the CUI Proceedings in the [ACM Digital Library](http://dl.acm.org/ "ACM Digital Library"). [SIGCHI](https://sigchi.org " ACM Special Interest Group on Computer-Human Interaction") participates in the [ACM Open Table of Contents (OpenTOC)](https://www.acm.org/publications/openaccess "ACM Open Access information") service, which means proposals will be freely available from this website for the first year after publication.

## Submissions

<p>
{%- for group in site.data.oc -%}
{%- for role in group[1]['roles'] -%}
{%- if role[0] == page.track.chairs -%}
  Please send your submission to <a href="{{ role[1].email }}" title="Make your submission to the workshop chairs">{{ role[1].label }}</a>.
  {%- break -%}
{%- endif -%}
{%- endfor -%}
{%- endfor -%}
</p>

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



