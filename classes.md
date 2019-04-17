---
title: Marine Muscle Classes
theme: default
permalink: /classes/
---
# Marine Muscle Classes

Many of our exercise courses offer three levels of expertise: beginner, intermediate, and intense, so you can decide on the right fit. Find out more about our classes below. Go ahead and register to get the workout started!

## Our current class offerings:

<div class="column">
  <div class="row">
  </div>
  <div class="row">
    25%
  </div>
  <div class="row">
    25%
  </div>
  <div class="row">
    25%
  </div>
</div>
### View by title:
{% for class in site.classes %}
<h3>{{ class.title }}</h3>
<p>{{ class.content }}</p>
{% endfor %}

### View by type:
{% assign sorted_classes = site.classes | sort: "type" %}
{% for class in sorted_classes %}
 <h3>{{ class.title }}</h3>
 <p>{{ class.content }}</p>
{% endfor %}

</div>

**and more to come!**

_Have a recommendation? [Tell us all about it!](https://surfgym.com/suggestions)_
