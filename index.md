---
layout: home
title: Home
permalink: /:path/
seo:
  type: Course
  name: Embodied AI Safety 
---

# Embodied Artificial Intelligence Safety 
Spring 2025. 16-886. Monday / Wednesday 11:00-12:20.

![Image](/assets/images/front-fig2.png)

## Announcements 
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Course Overview 
Safety is a nuanced concept. For embodied systems, like robots, we commonly equate safety with collision-avoidance. But out in the “open world” it can be much more: for example, a safe mobile manipulator should understand when it is not confident about a requested task and understand that areas roped off by caution tape should never be breached. However, designing systems with such a nuanced understanding is an outstanding challenge, especially in the era of large robot behavior models. 

In this graduate seminar class, we study the question of if (and how) the rise of modern artificial intelligence (AI) models (e.g., deep neural trajectory predictors, large vision-language models, and latent world models) can be harnessed to unlock new avenues for generalizing safety to the open world. From a foundations perspective, we study safety methods from two complementary communities: *control theory* (which enables the computation of safe decisions) and *machine learning* (which enables uncertainty quantification and anomaly detection). Throughout the class, there will also be several guest lectures from experts in the field. Students will practice essential research skills including reviewing papers, writing project proposals, and technical communication.

### Prerequisites
The course is open to graduate students and advanced undergraduates. While there are no strict prerequisites, familiarity with sequential decision-making, machine learning, optimization, and probability are highly encouraged. Experience with high-level programming languages like Python or MATLAB are also strongly encouraged.




## Schedule (Tentative) 

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Instructors 

<figure style="display: inline-flex;">

<figure>
<img src="/embodied-ai-safety/assets/images/avb.png" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://www.cs.cmu.edu/~abajcsy/"><button type="button" name="button" class="btn">Andrea Bajcsy</button>
</a></figcaption>
</figure>

<figure>
<img src="/embodied-ai-safety/assets/images/kn.jpg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://kensukenk.github.io/"><button type="button" name="button" class="btn">Kensuke Nakamura</button>
</a></figcaption>
</figure>

</figure>

