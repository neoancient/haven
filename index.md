---
layout: default
title: Overview
---
_Pirates of Haven_ is a roleplaying game built on the [Fate Core](https://evilhat.com/product/fate-core-system/) system.
The setting is formed from the wreckage of a collision between high fantasy and hard science fiction. The action takes
place in and around _Haven_, a pirate base in the Borderlands that serves as a base of operations for a number of pirate crews.

The setting is heavily influenced by the [Black Ocean series by J. S. Morin](https://www.jsmorin.com/black-ocean/), particularly the ways that magic works
within a futuristic space age setting.

# Table of Contents
- Game Rules
  {% for section in site.data.rules_contents %}
  {% if section.link %}
  - [{{ section.title }}]({{ site.baseurl }}/{{ section.link }})
  {% else %}
  - {{ section.title }}
  {% endif %}
  {% endfor %}
- Reference
  {% for section in site.data.reference_contents %}
  {% if section.link %}
  - [{{ section.title }}]({{ site.baseurl }}/{{ section.link }})
    {% else %}
  - {{ section.title }}
    {% endif %}
    {% endfor %}
