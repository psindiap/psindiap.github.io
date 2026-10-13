---
layout: academic
title: cv
permalink: /vitae/
nav: true
nav_order: 5
description: "Education, research, engineering, teaching, and service."
---

<a class="download-cv" href="{{ '/assets/pdf/PARTHA_SARATHI_PURKAYASTHA_CV.pdf' | relative_url }}"><i class="fa-regular fa-file-pdf" aria-hidden="true"></i> Download CV <span>(PDF · October 2026)</span></a>

## research interests

AI in Education · AI in Healthcare · Human–AI Interaction · Safety & Security · Agentic AI · LLM Evaluation · Contextual Integrity & Privacy

## education

{% include academic-timeline.liquid entries=site.data.profile.education %}

## publications

{% include academic-publications.liquid %}

## experience

{% include academic-timeline.liquid entries=site.data.profile.experience %}

## teaching

{% include academic-timeline.liquid entries=site.data.profile.teaching %}

## academic service

**Program Committee Member, 2026:** AI4GOOD @ ICML, FAGEN @ ICML, and REALM @ EMNLP.

## awards & recognition

{% include academic-timeline.liquid entries=site.data.profile.awards %}

## projects

{% include academic-timeline.liquid entries=site.data.profile.projects %}

## community activities

{% include academic-timeline.liquid entries=site.data.profile.community %}

## skills

<dl class="skills-list">{% for skill in site.data.profile.skills %}<div><dt>{{ skill[0] }}</dt><dd>{{ skill[1] }}</dd></div>{% endfor %}</dl>

<p>Contact: <a href="mailto:ppurkayastha@ethz.ch">ppurkayastha@ethz.ch</a> · <a href="mailto:parthasarathipurkayastha001@gmail.com">personal email</a></p>
