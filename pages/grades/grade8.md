---
layout: page
title: Grade 8
permalink: /grade8/
page_name: grade8
content_type: class_syllabus
---

## Welcome to Grade 8 learning content.

{% include util/note.html
    note="All the videos are in Nepali."
%}

{% if site.data.secondary.grade8.subjects.size > 0 %}
  <div class="section-index">
    <div class="mt-5">
      <h2>Subjects</h2>
    </div>
    <hr class="panel-line">
    {% for subject in site.data.secondary.grade8.subjects %}
      <div class="entry">
        <h5>
          <a href="{{ site.url }}{{ site.baseurl }}/{{ subject.url }}">{{ subject.title }}</a>
        </h5>
        <p class="mb-0">{{ page.description }}</p>
      </div>
    {% endfor %}
  </div>
{% endif %}