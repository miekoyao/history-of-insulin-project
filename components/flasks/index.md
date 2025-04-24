---
title: Flask Mixing Puzzle
author: mieko-yao
# tags:
#   - biology
#   - medicine
#   - big data
---

For the first interactive component of our project, users pour reagents in and out of flasks to achieve a mixture of specific goal proportions.

{% capture content %}
{%
  include figure.html
  image="images/blue_flask.jpg"
  caption="The largest size flask"
  width="300px"
%}
{%
  include figure.html
  image="images/green_flask.jpg"
  caption="The medium size flask"
  width="300px"
%}
{%
  include figure.html
  image="images/red_flask.jpg"
  caption="The smallest size flask"
  width="300px"
%}

{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}

Above are the 3 flasks partipants will use. The goal for this station is for 