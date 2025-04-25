---
title: Syringe & Layer Extraction
author: mieko-yao
# tags:
#   - biology
#   - medicine
#   - big data
---

## Historical Context

Following centrifugation, Banting and Best’s tube had 4 distinct layers :

- The top one was clear, and consisted of alcohol holding the insulin in solution. 

- The second layer contained flocculent (fluffy-looking) protein.

- The third layer was a clear watery solution saturated with salt

- The fourth layer contained salt crystals

Banting and Best extracted the layer containing insulin using a glass pipette. The extracted solution was then mixed with pure alcohol, which caused the insulin to precipitate out of the mixture. The insulin was then separated from the alcohol using a Buchner funnel, and then further filtered before it was ready to be administered to test subjects.



## Design Breakdown

For this component, users are working with their mixture once it has completed centrifuging and is separated into distinct layers.

This stage has two main components, the layer container and the syringe. The layer container contains 4 rows of LED strips, simulating the 4 layers of the solution after the use of the centrifuge. The layer container contains a vertically standing linear potentiometer with a horizontal plate attached to its lever. As the user puts the syringe into the layer container, the plate will be pushed down, allowing a specific layer to be selected.

The syringe also contains a linear potentiometer, this one being attached the syringe's plunger. When the plunger is pulled back, the currently selected layer from the layer container is selected. An led inside the syringe then glows, indicating the current solution now inside the syringe.
