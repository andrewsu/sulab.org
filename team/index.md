---
title: Team
nav:
  order: 3
  tooltip: Meet the team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of a talented mix of graduate students, postdoctoral researchers, programmers, and staff, and their backgrounds range from pure computer science to experimental biology.  If you're interested in joining this diverse and dynamic team, please reach out!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: active, role: pi" %}

{% include list.html data="members" component="portrait" filters="group: active, role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}The Wu Lab

Our lab works very closely with the lab of Professor Chunlei Wu, another faculty member here at Scripps. We collaborate on many projects and many of our individual lab members seamlessly transition between project teams. Learn more about the Wu Lab at [wulab.io](https://wulab.io). 

{% include list.html data="members" component="portrait" filters="group: cwu-lab, role: pi" %}
<br/>
{% include list.html data="members" component="portrait" filters="group: cwu-lab, role: ^(?!pi$)" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

We have been lucky to have a fantastic group of individuals come through the lab, and many have gone on to even bigger and better things. Here are some of our past lab members.

{% include list.html data="members" component="portrait" filters="group: alum" style="small" %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
