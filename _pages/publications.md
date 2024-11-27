---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
class: hide-title
---
* Denotes Equal Contribution

<!-- Main Publications Section -->
<div class="section-title">
  Conference Publications
</div>

<div class="publications">
  {% bibliography --group_by none --query @*[keyword=conference]* %}
</div>

<div class="section-title">
  Workshop Publications
</div>

<div class="publications">
   {% bibliography --group_by none --query @*[keyword=workshop]* %}
</div>

<div class="section-title">
  Journal Publications
</div>

<div class="publications">
   {% bibliography --group_by none --query @*[keyword=journal]* %}
</div>


<div class="section-title">
  Papers Under Review
</div>

<div class="publications">
   {% bibliography --group_by none --query @*[keyword=review]* %}
</div>
