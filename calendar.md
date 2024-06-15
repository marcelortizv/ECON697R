---
layout: page
title: Modules
description: Listing of course modules and topics.
---

# Modules

🚨 Disclaimer: The content presented herein primarily comprises a condensed review of the material mentioned in [References](http://marcelortiz.com/courses/ECON697R/#references), supplemented with additional insights. These notes are crafted to serve as supplementary materials for self-directed learning purposes. It is crucial to note that this compilation is not designed to substitute any existing text or course materials. Its intent is solely to provide additional support for individual learning journeys. All errors are my responsibility.


{% for module in site.modules %}
{{ module }}
{% endfor %}
