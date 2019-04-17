---
Title: Home
Layout: default
---

# Surf Gym is a concept workout space that brings the maritime to your workout time.

<div class="content-right" markdown="1">
## Our amenities include:
- [Sand Resistance Training]({{ "/resistance_training/" | relative_url }})
- [Solar Endurance Tanning Beds]({{ "/tanning_beds/" | relative_url }})
- [Beach Volleyball Courts]({{ "/volleyball_courts/" | relative_url }})
- [State of the Art Wave Pool]({{ "/wave_pool/" | relative_url }})

</div>

<div class="img-left" markdown="1">
## Join us for Marine Muscle themed classes like:

{% for class in site.classes %}
<h2>{{ class.title }}</h2>
<p>{{ class.content }}</p>
{% endfor %}

Want to know more about the classes we offer? Visit our [Marine Muscle]({{ "/classes/" | relative_url }}) page to register.

</div>

<div class="clearfix"></div>
