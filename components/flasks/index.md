---
title: Flask Mixing Puzzle
author: mieko-yao
# tags:
#   - biology
#   - medicine
#   - big data
---

## Historical Context

{%
  include figure.html
  image="images/old_lab.jpg"
  caption="Banting and Best's Laboratory"
  width="600px"
%}

In 1921, Dr. Fredric Banting and Charles Best made a groundbreaking discovery: insulin could be extracted from the pancreas using alcohol. By using pancreatic tissue and a solution consisting of 90% ethyl alcohol, they were able to separate and stabilize the insulin from unwanted impurities. This key advance is what paved the way for insulin as a treatment for diabetes.

The process was later improved by first breaking down the pancreas using slightly acidified acetone before using alcohol to isolate the insulin. 

Fun fact: The ethyl alcohol used in this extraction is the same type found in alcoholic beverages, just in a much purer form! Similarly, acetone is commonly found in items like nail polish remover or paint thinner. 


## Design Breakdown

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
%}

Above are the 3 flasks participants will use. The goal for this activity is for participants to move simulated reagents from flask to flask in order to achieve 4 litres of solution in the largest flask. 

{% capture content %}
{%
  include figure.html
  image="images/blue_flask.jpg"
  caption="Largest flask, highest capacity"
  width="300px"
%}
{%
  include figure.html
  image="images/blue_flask_med.jpg"
  caption="Largest flask, medium capacity"
  width="300px"
%}
{%
  include figure.html
  image="images/blue_flask_low.jpg"
  caption="Largest flask, smallest capacity"
  width="300px"
%}

{% endcapture %}

{%
  include grid.html
  content=content
%}

Amounts of fluid are displayed using rows of LED strips, indicating how much fluid is currently in each container.

{% capture col1 %}
{%
  include figure.html
  image="images/flask_naked_side.jpg"
  caption="Inside of flask, side view"
  width="300px"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/flask_naked_top.jpg"
  caption="Inside of flask, top view"
  width="300px"
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

An ATOM S3 is contained within each flask, providing logic as well as detecting motion of the flasks. When two flasks bump, the ATOM S3’s detect this vibration and allow us to determine which flask is being poured into which.


![](https://www.youtube.com/watch?v=r_z4j_SxFqw?width=800&height=400) 


The above video demonstrates how the flasks interact with each other and shows the simulated transfer of fluid between them.