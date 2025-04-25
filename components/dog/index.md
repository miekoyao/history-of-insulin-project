---
title: Treating Marjorie with Insulin
author: mieko-yao
# tags:
#   - biology
#   - medicine
#   - big data
---

## Historical Context

{%
  include figure.html
  image="images/bb_and_dog.jpg"
  caption="Banting and Best standing with one of the dogs they tested on"
  width="600px"
%}

Initially, dogs were the primary test subjects used in the experimental trials conducted by Banting and Best. Though these tests eventually led to the discovery of medical insulin, many of the dogs unfortunately did not survive the testing. This raised an ethical debate among activists since many saw this usage of animals as test subjects as cruel or unfair. However, it was because of their work that millions of people now have a treatment to help them live with diabetes.

After their first successful human trial was conducted in January 1922 on 13 year old Leonard Thompson, a different source of insulin was needed in order to distribute on a large scale. It was soon discovered that the pancreas of an adult cow could also be easily used to extract insulin. James Collip, a biochemist, contributed heavily to the purification of insulin from the pancreases of cattle. Pigs were used as well, as they shared a very similar pancreas to humans.  

Eventually, the need for animals was discontinued entirely, with bovine insulin being discontinued in 1988 and porcine insulin in 2006. This was because of the development of DNA recombinant technology, also known as "genetic engineering".  This enabled scientists to insert each of the two subunits of human insulin into different bacteria and grow those bacteria in large tanks.  They could then extract the insulin from the bacteria, combine the two subunits, and "Voila!" they had an identical copy of human insulin.

Fun Fact: Marjorie was the name of the primary dog Banting and Best tested on!

## Design Breakdown

To verify that they have successfully isolated insulin from the previous steps, users will test their extracted mixture by injecting it into Marjorie, an animatronic dog. 

Our dog contains internal motors, allowing for the head/upper body to move up an down. Audio speakers are also attached to simulate what Majorie would really sound like. To inject her with insulin, we added a hall effect sensor to a designated region on the body. This will detect when the magnet on the tip of the syringe is near the injection site.

When the plunger on the syringe is pushed in while in contact with Majorie, we check if the injected solution was the correct layer slected from the previous section. If wrong, Majorie will move her head down and fall back asleep. Participants would then have to retry the layer container section and try another layer until they pick the right one. If correct, she will wake up and bark with joy, congratulating the user on completing our exhibit!
