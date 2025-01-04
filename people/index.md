---
title: People
nav:
  order: 2
  tooltip: 
---

# {% include icon.html icon="fa-solid fa-people-group" %}People

{% include section.html %}

## Principle Investigator

{% include list.html  data="members"  component="portrait"  filters="role: pi" %}

{% include section.html %}

## Current Members

{% include list.html  data="members"  component="portrait"  filters="role: current-phd" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-ms" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-undergrad" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-hs" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-manager" %}


{% include section.html %}

## Alumni

{% include list.html  data="members"  component="portrait"  filters="role: alum" %}

