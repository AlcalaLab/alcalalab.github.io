---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
<!-- , and their backgrounds range from pure computer science to experimental biology -->

Our lab is currently made up of a talented mix of undergraduate and graduate students. If you're interested in joining this diverse and dynamic team, please reach out!

{%
  include button.html
  icon="fa-solid fa-image"
  text="Photos"
  link="/team/photos"
%}
{%
  include button.html
  icon="fa-solid fa-people-group"
  text="Alumni"
  link="/team/alumni"
%}
{%
  include button.html
  icon="fa-solid fa-door-open"
  text="Join us"
  link="/team/join"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: active, role: pi" %}

{% include list.html data="members" component="portrait" filters="group: active, role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}
