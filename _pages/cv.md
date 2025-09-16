---
title: "CV"
permalink: /cv/
layout: single
classes: wide
---

<style>
  /* Adjust height as you like */
  .cv-frame { width: 100%; height: calc(100vh - 220px); border: 1px solid #e5e7eb; }
  @media (max-width: 800px) { .cv-frame { height: 70vh; } }
</style>

<object
  data="{{ '/assets/CV_JLiu.pdf#zoom=page-width' | relative_url }}"
  type="application/pdf"
  class="cv-frame">
  <!-- Fallback for browsers that block PDF embedding -->
  <iframe
    src="{{ '/assets/CV_JLiu.pdf#zoom=page-width' | relative_url }}"
    class="cv-frame"></iframe>
</object>

<p>
  <a href="{{ '/assets/CV_JLiu.pdf' | relative_url }}">Download CV (PDF)</a>
</p>


{% include base_path %}

<!--
Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
