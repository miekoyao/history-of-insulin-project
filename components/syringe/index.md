---
title: Syringe & Layer Extraction
author: mieko-yao
# tags:
#   - biology
#   - medicine
#   - big data
---

## Historical Context

{%
  include figure.html
  image="images/injectin_insulin_diagram.jpg"
  caption="Early diagram displaying how to properly inject someone with insulin"
  width="400px"
%}

Following centrifugation, Banting and Best’s tube had 4 distinct layers :

- The top one was clear, and consisted of alcohol holding the insulin in solution. 

- The second layer contained flocculent (fluffy-looking) protein.

- The third layer was a clear watery solution saturated with salt

- The fourth layer contained salt crystals

Banting and Best extracted the layer containing insulin using a glass pipette. The extracted solution was then mixed with pure alcohol, which caused the insulin to precipitate out of the mixture. The insulin was then separated from the alcohol using a Buchner funnel, and then further filtered before it was ready to be administered to test subjects.



## Design Breakdown

For this component, users are working with their mixture once it has completed centrifuging and is separated into distinct layers.

{%
  include figure.html
  image="images/layer_container.jpg"
  caption="Our layer container, with all 4 rows visible"
  width="300px"
%}

This stage has two main components, the layer container and the syringe. The layer container contains 4 rows of LED strips, simulating the 4 layers of the solution after the use of the centrifuge. The layer container contains a vertically standing linear potentiometer with a horizontal plate attached to its lever. As the user puts the syringe into the layer container, the plate will be pushed down, allowing a specific layer to be selected. The goal is to extract the correct layer according to hints given in our audio voiceovers and instruction booklets.

{%
  include figure.html
  image="images/syringe_closeup.png"
  caption="The syringe currently selecting the red layer from the layer container"
  width="300px"
%}

The syringe also contains a linear potentiometer, this one being attached the syringe's plunger. When the plunger is pulled back, the currently highlighted layer from the layer container is selected. An led inside the syringe then glows, indicating the current solution is now inside the syringe.

![](https://www.youtube.com/watch?v=hUvnLN9SgDQ?width=800&height=400)

If the correct layer is selected, then intjecting our animatronic dog Majorie with the syringe will wake her up, indicating that the participant has successfully completed our exhibit. Otherwise, the participant will need to select another layer and try again. Above is a brief video going through this process.




