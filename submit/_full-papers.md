---
label: Full papers
description: "The Full papers track at CUI !!conference.year!! is for original contributions from a broad range of disciplines including: human-computer interaction, computer science, engineering, speech technology, linguistics, psychology, cognitive sciences, sociology and other cognate disciplines."

splash_title: Full papers<br>at CUI !!conference.year!!

cta:
  text: Submissions not open yet
  title: Submissions for the full papers track is currently closed
#  link: /2023/submit/pcs/

track:
  chairs: full_papers
  dates: full_papers

menus:
  submit:
    title: Full papers
    alt: Information about submitting to the full papers track at CUI !!conference.year!!
    weight: 0
    is_track: true

lastmod: page
---

# Full paper submission information

We invite the submission of full research papers, describing original work that has not been previously published, not accepted for publication elsewhere, and not simultaneously submitted or currently under review in another journal or conference (including the other tracks of CUI {{ site.conference.year }}).

We particularly encourage the submission of high-quality replication studies in addition to well-designed studies with null results. 

Full papers are original contributions from a broad range of disciplines including: human-computer interaction, computer science, engineering, speech technology, linguistics, psychology, cognitive sciences, sociology and other cognate disciplines. 

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## The process

All full papers will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.

### 1. Prepare your manuscript

Submissions of full research papers must be in English, in PDF format, anonymised using the [CHI anonymization policy](https://chi2022.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "CHI 2022 Anonymization Policy"), and approximately 6,000 words (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments).

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates") to prepare your submission. Word users should use "Submission Template" during submission and review, while LaTeX users should have the following document class: <code>\documentclass[manuscript, review, anonymous]{acmart}</code>. LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/gallery/tagged/acm-official "ACM authoring templates on Overleaf").

ACM's CCS concepts and keywords are not required for review but may be required if accepted and published by the ACM.

### 2. Submit your manuscript

You should submit your paper to the [conference submission system]({{ "/submit/pcs/" | relative_url }} "CUI {{ site.conference.year }} submission system"). You must include your title, abstract, author details, and paper as a PDF. Your paper must be anonymised, or it may be desk rejected.

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission").

### 3. Await reviews

For 2022 the review process will be slightly modified, transitioning away from a submit-review-rebut process. Instead, a shepherding process is introduced that implements a "light revise & resubmit". With this, we expect to further increase the quality of the CUI proceedings, while at the same time reducing the burden on both authors and reviewers. Papers for which there is a very high agreement among reviewers regarding recommendation for inclusion in the proceedings will receive early acceptance decisions and will no longer be required to submit a rebuttal (this is the equivalent of "conditionally accepted").

A small number of papers that may require further revisions will be shepherded (equivalent to major revisions or light revise & resubmit), with 3 weeks allocated for authors to coordinate the revisions with the associated chair (AC) coordinating each paper. This may include targeted revisions to specific parts of the original submission addressing the most significant points raised by the reviewers, or alternative forms as deemed appropriate by the AC (such as a detailed proposal of how such revisions may be carried out – details that the previous rebuttal would not have had the space for).

### 4. Prepare your manuscript for publication

If your paper is accepted, you should de-anonymise it. You must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

At least one author of each accepted paper must register for the conference, otherwise we cannot guarantee publication of your paper. Accepted full papers will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>.

You will receive an email from ACM to assign the rights for your paper, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your paper. Accepted papers will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM's guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

### 5. Present your work

Authors will be given an oral presentation slot at the conference. The specific details of this presentation will be provided closer to the conference.

