---
title: Marine Muscle Classes
theme: default
permalink: /classes/
---
# Marine Muscle Classes

Many of our exercise courses offer three levels of expertise: beginner, intermediate, and intense, so you can decide on the right fit. Find out more about our classes below. Go ahead and register to get the workout started!

## Our current class offerings:

### View by title:

<div class="flex-container" markdown="1">

 <div>
 ![boxing]({{"/assets/images/boxing.jpg" | relative_url }} )

 Want a demanding workout that will train you in cardio, coordination, and posture? Mantis Shrimp Boxing is the class for you. Work with our trained instructors to perfect your punches. The intermediate and intense levels are great for those wanting to learn self-defense, as this course will teach you evasive maneuvers.
 </div>

 <div>
 ![beach yoga]({{ "/assets/images/beach_yoga.jpg" | relative_url }})
 In this class, we bring the benefits of toning your muscles and increased metabolism due to the warm workout environment. As one of our most popular classes, new members enjoy taking the beginning level of this class. Not to worry, there are no sulfurous vents in our class spaces, just intense heat to help you get rid of those pesky toxins!
 </div>

 <div>
 ![shark waves]({{ "/assets/images/shark_waves.jpg" | relative_url }})
 One of our most demanded classes, so spots will fill up as quick as a shark smells its prey! Our Shark Surfing classes take place in our state-of-the-art wave pool, specially designed for surfing. In our beginner level class, instructors will give you basic lessons on how to balance on your board, then move onto how to ride higher and stronger waves as you progress. Bring your own wetsuits or rent one from our inventory. Availability of sizes will vary the day of class, so you have the option of reserving one with registration.
 </div>

 <div>
 ![weights]({{ "/assets/images/weights.jpg" | relative_url }})
 Our Whale Weight Lifting courses offers a few specializations. You can choose a course that will get your to your deadlift goal, or bench press those pounds. Weight Training has the benefit of gaining bulk muscle, so you can be as graceful and powerful as a blue whale. We welcome members of all skill levels, as there are machines and weight styles for everyone.
 </div>

</div>

### View by type:

  {% assign sorted_classes = site.classes | sort: "type" %}
  {% for class in sorted_classes %}
  <h3>{{ class.title }}</h3>
  <p>{{ class.content }}</p>
  {% endfor %}


**and more to come!**

_Have a recommendation? [Tell us all about it!](https://surfgym.com/suggestions)_
