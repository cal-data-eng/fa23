---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
currWeekNumber: 1
---

# {{site.title}}: {{site.description}}

{: .mb-2 }
UC Berkeley, {{site.semester}}
{: .mb-0 .fs-6 .text-grey-dk-000 }

# TEST REMOVE THIS AT SOME POINT


[Ed]({{site.course.edstem}}){:target="_blank" .btn .btn-ed .mr-1 }
[Datahub]({{site.course.datahub}}){:target="_blank" .btn .btn-datahub .mr-1 }
[Gradescope]({{site.course.gradescope}}){:target="_blank" .btn .btn-gradescope .mr-1 }
[Extenuating Circumstances (TBD)]({{site.course.extenuating_circumstances}}){:target="_blank .btn .btn-blue .mr-1}

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }
> Welcome to Fall 2023! Course website under construction.


<!--
Welcome to [Week 1](#week-{{page.currWeekNumber}})
!-->


<a name="schedule"></a>
## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}

