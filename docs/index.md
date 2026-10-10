---
layout: default
title:  Berkeley's Hidden Gems
---

# Berkeley's Hidden Gems

Discover the hidden gems of UC Berkeley! From quiet study spots and creative spaces to academic resources and student support services, explore lesser-known places and opportunities that can make your Berkeley experience even better.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
