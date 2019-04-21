---
title: Marine Muscle Classes
theme: default
permalink: /classes/
---
# Marine Muscle Classes

Many of our exercise courses offer three levels of expertise: beginner, intermediate, and intense, so you can decide on the right fit. Find out more about our classes below. Go ahead and register to get the workout started!

## Our current class offerings:

<div class="viewalpha" markdown="1">

### View A-Z:
{% for class in site.classes %}
<h4>{{class.title}}</h4>
<p>{{class.content}}</p>
{% endfor %}

</div>

<div class="viewtype" markdown="1">
### View by type:

  {% assign sorted_classes = site.classes | sort: "type" %}
  {% for class in sorted_classes %}
  <h4>{{ class.title }}</h4>
  <p>{{ class.content }}</p>
  {% endfor %}

</div>


**and more to come!**

_Have a recommendation? [Tell us all about it!](https://surfgym.com/suggestions)_
