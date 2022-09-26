---
label: Papers
description: "The papers track at CUI !!conference.year!! is for original contributions from a broad range of disciplines including: human-computer interaction, computer science, engineering, speech technology, linguistics, psychology, cognitive sciences, sociology and other cognate disciplines."

splash_title: Papers<br>at CUI !!conference.year!!

cta:
  text: Submissions not open yet
  title: Submissions for the papers track is currently closed
#  link: /2023/submit/pcs/

track:
  chairs: papers
  dates: papers

menus:
  submit:
    title: Papers
    alt: Information about submitting to the papers track at CUI !!conference.year!!
    weight: 0
    is_track: true

lastmod: page
---

# Paper submission information

We invite the submission of research papers, describing original work that has not been previously published, not accepted for publication elsewhere, and not simultaneously submitted or currently under review in another journal or conference (including [the other tracks of CUI {{ site.conference.year }}](/submit/)).

We particularly encourage the submission of high-quality replication studies in addition to well-designed studies with null results. 

Papers are original contributions from a broad range of disciplines including human-computer interaction, computer science, engineering, speech technology, linguistics, psychology, cognitive sciences, sociology and other cognate disciplines. 

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## The process

All submissions will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.

### 1. Prepare your manuscript

Submissions of research papers must be in English, in PDF format, anonymised using the [CHI anonymization policy](https://chi2022.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "CHI 2022 Anonymization Policy"), and approximately **6,000-8,000 words** (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments). Submissions above 8,000 words or below 5,000 words, will be considered for desk rejection. Papers whose lengths are incommensurate with their contributions will be rejected.

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates") to prepare your submission. We strongly encourage use of the Overleaf LaTeX template. LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"). LaTeX users should have the following document class: <code>\documentclass[manuscript, review, anonymous]{acmart}</code>.

Word users should use the double-column "Interim Template" during submission and review and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline.  

ACM's CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.

### 2. Submit your manuscript

You should submit your paper to the [conference submission system]({{ "/submit/pcs/" | relative_url }} "CUI {{ site.conference.year }} submission system"). You must include your title, abstract, author details, and paper as a PDF. Your paper must be anonymised, or it may be desk rejected.

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission").

### 3. Await reviews

All papers will be reviewed by two external reviewers and one ‘Associate Chair’ (2AC), with one ‘Associate Chair’ (1AC) leading the reviewing process and writing a meta review. Reviewers will receive their reviews along with a decision from the reviewing process. Papers for which there is a very high agreement among reviewers regarding recommendation for inclusion in the proceedings will receive early acceptance decisions. All accept decisions are conditional and will be checked by the 1AC before final acceptance.

A small number of papers that may require further revisions will be shepherded (equivalent to major revisions or light revise & resubmit), with 3 weeks allocated for authors to coordinate the revisions with the AC coordinating each paper. This may include targeted revisions to specific parts of the original submission addressing the most significant points raised by the reviewers, or alternative forms as deemed appropriate by the AC.


### 4. Prepare your manuscript for publication

If your paper is accepted, you should de-anonymise it. You must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

At least one author of each accepted paper must register for the conference, otherwise we cannot guarantee publication of your paper. Accepted papers will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>.

You will receive an email from ACM to assign the rights for your paper, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your paper. Accepted papers will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM's guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

### 5. Present your work

Authors will be given an oral presentation slot at the conference. The specific details of this presentation will be provided closer to the conference.

