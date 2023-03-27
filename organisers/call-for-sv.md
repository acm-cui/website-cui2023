---
label: Student Volunteers
description: We're looking for students to volunteer to support the running of CUI !!conference.year!!.

title: Student Volunteering
splash_title: Student Volunteering<br>at CUI !!conference.year!!

cta:
  text: Volunteer now
  title: Become a CUI !!conference.year!! Student Volunteer
  link: https://docs.google.com/forms/d/e/1FAIpQLScmZ-sO_uquP0tzLG0xD0niM7zyHWC0bmiy3s9AGrrYMgZ6Fw/viewform

menus:
  organisers:
    title: Call for Student Volunteers
    alt: We're looking for students to volunteer to support the running of CUI !!conference.year!!.
    sep_before: true
    weight: 4
---

{%- for group in site.data.oc -%}
	{%- for role in group[1]['roles'] -%}
		{% if role[0] == 'sv' -%}
			{% assign email = role[1]['email'] | replace: "mailto:", "" %}
			{%- break -%}
		{%- endif -%}
	{%- endfor -%}
{%- endfor -%}

## Join us as a Student Volunteer!

Student volunteers (SV) are an essential part of a successful conference. At CUI, you will help the organisation and make sure that everything runs smoothly during the conference. 

You must be enrolled as a student during the summer term of {{ site.conference.year }}. We are more than happy to accept undergrad, graduate, and PhD students. What matters most is that you are friendly and enthusiastic about being part of the CUI organization!

The Student Volunteer chairs will select a maximum of 6 SV giving priority to students applying from underrepresented communities and the global south. In addition, we will select 4 students to be put on the waitlist. 

The call for SV will open on **Monday 27th March 2023** and will be closed on **Monday 24th April 2023**. 

**We will mainly be accepting IN-PERSON SVs for this year’s conference, however, we may end up needing one SV to complete remote-only tasks.** SVs can state their preference during application. 

The selection result will be announced on **Monday 8th May 2023**. Once you have a confirmed spot and registration is open you will be required to register. You will receive instructions on how to do this after your application is confirmed. If you are placed on the waitlist and a spot becomes available, you will be informed about this immediately.


<div class="text-center mb-3">
<a href="https://docs.google.com/forms/d/e/1FAIpQLScmZ-sO_uquP0tzLG0xD0niM7zyHWC0bmiy3s9AGrrYMgZ6Fw/viewform" class="my-3 btn btn-lg btn-dark text-light border" title="Become a CUI {{ site.conference.year }} Student Volunteer">Volunteer now →</a>
</div>

## Important Dates

SV call open: **Monday 27th March 2023**<br>
Close lottery: **Monday 24th April 2023**<br>
Announce results: **Monday 8th May 2023**<br>
<em class="small"><br>All dates/deadlines are at <a href="https://time.is/Anywhere_on_Earth" title="The current time in 'Anywhere on Earth'">23:59 Anywhere on Earth</a></em>


## What Will I Do When I Volunteer?
For CUI {{ site.conference.year }} SVs, you will agree to:
* In-person SVs: Work at least 16 hours (if you are presenting a paper, we will make sure you do not have volunteer duties during that time)
* Show up on time to tasks
* Attend an orientation session Wednesday morning
* Arrive at the conference by **Wednesday morning** at the latest **(in-person SVs only)**

In return, we commit to:
* Waive your registration fee
* Provide meals during the conference (coffee breaks and lunch)
* Free SV t-shirt to be collected on site

If you need to reach us, please always use the [{{ email }}](mailto:{{ email }}) address so that the two of us receive it. Reply-to-all on our correspondence so we all stay in the loop and can better help you.


## Frequently Asked Questions

**Q:** Where can I find the form to apply?<br>
**A:** We will make the form available on this page.

**Q:** I know the deadline for the application is passed,can I still be considered?<br>
**A:** Unfortunately, we will not be able to consider applications after the deadline has passed to make it fair for everyone who applied on time..

**Q:** I want to skip orientation, or work way less than 16 hours, or arrive later or leave earlier, can I still be an SV?<br>
**A:** Unless there are exceptional circumstances, no exceptions are made. If you have a very good reason that comes up after you already received a spot that means you won’t be able to fullfill your commitment, please send us an e-mail ([{{ email }}](mailto:{{ email }})) immediately and we will try to work with you as good as we can to accommodate your situation.

**Q:** I didn’t get your emails and/or forgot to register by the deadlines you guys sent us and I lost my spot as an SV, can I get it back?<br>
**A:** If this is due to serious and unexpected circumstances, please communicate them to us (to [{{ email }}](mailto:{{ email }})). We will try to be flexible, but if one of the SVs in the waiting list has already accepted, you may not get your spot back.


**We are looking forward to meeting all of you!**

<p>
{%- for group in site.data.oc -%}
	{%- for role in group[1]['roles'] -%}
		{% if role[0] == 'sv' -%}
			{%- assign use_and = role[1]['people'] | size | plus: -1 %}
			{%- for person in role[1]['people'] -%}
				{{- person.name -}}
				{%- if forloop.index == use_and %}, and {% else -%}{%- unless forloop.last -%}, {% endunless -%}{%- endif -%}
			{%- endfor -%}
			<br>
			CUI {{ site.conference.year }} {{ role[1].label }}
			<br>
			{{ role[1]['email'] | replace: "mailto:", "" }}
			{%- break -%}
		{%- endif -%}
	{%- endfor -%}
{%- endfor -%}
</p>