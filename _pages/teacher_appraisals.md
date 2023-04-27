---
layout: page
permalink: /teacher_appraisals/
title: Teaching Appraisals
description: You can access the full assessment pdf or contact the host by email using the icons below each experience.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
  <table id="experiences" style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
    <tbody>
      {% for post in site.appraisals %}
        {% include archive-single-cv.html %}
      {% endfor %}
    </tbody>
  </table>
</div>