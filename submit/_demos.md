---
label: Demos
description: The Demos track at CUI !!conference.year!! allows authors to present interactive contributions aiming to tackle challenges and show progress in the field of conversational user interfaces.

splash_title: Demos at CUI !!conference.year!!

cta:
  text: Submissions not open yet
  title: Submissions for the demos track is currently closed
#  link: /2023/submit/pcs/
  
track:
  chairs: short_papers
  dates: short_papers

menus:
  submit:
    title: Demos
    alt: Information about submitting to the demos track at CUI !!conference.year!!
    weight: 3
    is_track: true

lastmod: page
---

# Demo submission information

Demos are interactive contributions aiming to tackle challenges and show progress in the field of Conversational User Interfaces. Authors should submit an extended abstract detailing their demo for the review process.

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## The process

All demo papers will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.


### 1. Prepare your manuscript and video

Submissions of extended abstracts for demos must be in English, in PDF format, anonymised using the [CHI anonymization policy](https://chi2022.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "CHI 2022 Anonymization Policy"), and approximately 3,000 words (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments).

You should include a description of the system, a description of the problem(s) it addresses, a discussion regarding its novelty and/or applied context, a discussion regarding the technology’s relevance to the CUI community, a description of the planned presentation, and details about how online attendees will interact with the demonstration. Your description of the planned presentation should focus on how you will provide an engaging interactive experience for your audience.

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates") to prepare your submission. Word users should use "Submission Template" during submission and review, while LaTeX users should have the following document class: <code>\documentclass[manuscript, review, anonymous]{acmart}</code>. LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/gallery/tagged/acm-official "ACM authoring templates on Overleaf").

ACM's CCS concepts and keywords are not required for review but may be required if accepted and published by the ACM.

You should also prepare a 2 minute (max) video demonstration of your demo.

### 2. Submit your manuscript and video

You should submit your extended abstract and video to the [conference submission system]({{ "/submit/pcs/" | relative_url }} "CUI {{ site.conference.year }} submission system"). You must include your title, abstract, author details, and paper as a PDF, and your video showreel. Your paper and video must be anonymised, or it may be desk rejected. 

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission").

### 3. Await reviews

Each submission will be reviewed by one track chair and one expert reviewer through a curated process. Following a curated selection process, successful submissions will be invited to present at CUI {{ site.conference.year }}.In curating the program creativity in delivery, feasibility, novelty, and ability to engage attendees in-person and online will be assessed. Our aim is to deliver an array of captivating demonstrations that showcase the diverse research arenas contributing to the conversational user interface research community. Sensitive, private and/or proprietary information should not be disclosed prior to publication. Business exposure is reserved for event sponsors only, so advertising materials should not be used in demonstrations. 

### 4. Prepare your manuscript for publication

If your demo is accepted, you should de-anonymise it. You must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

At least one author of each accepted demo must register for the conference, otherwise we cannot guarantee publication of your paper. Accepted demo extended abstract will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>.

You will receive an email from ACM to assign the rights for your paper, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your paper. Accepted papers will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM's guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

### 5. Present your work

Authors be given the opportunity to present their demo during a dedicated session. The specific details of this presentation will be provided closer to the conference.