---
title: Tag
keywords: tag
sidebar: left-navigation-sidebar
toc: false
permalink: components/tag.html
folder: components
summary:
---

Tags are used to represent contextualizing information. They can be useful to show applied filters, selected values for form field or object metadata.

<hr>

{% capture default-alert %}
<span class="fd-tag" role="button">Bibendum</span>
<span class="fd-tag" role="button">Lorem</span>
<span class="fd-tag" role="button">Dolor</span>
<span class="fd-tag" role="button">Filter</span>
{% endcapture %}

{% include display-component.html component=default-alert %}
