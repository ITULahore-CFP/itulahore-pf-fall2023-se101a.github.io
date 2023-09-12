---
layout: home
title: Home
nav_exclude: true
seo: 
  type: Course
  
---
<script>
  document.title = "{{ site.title }}"
</script>

# {{ site.tagline }}
{: .mb-2 }

[//]: # ({{ site.description }})
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## {{ site.title }}

{{ site.description }}