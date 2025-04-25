---
title: Centrifuge
author: mieko-yao
# tags:
#   - biology
#   - medicine
#   - big data
---

## Historical Context

{%
  include figure.html
  image="images/old_centri.jpeg"
  caption="One of the earliest centrifuges, originally used to seperate the fat from milk!"
  width="600px"
%}

A centrifuge is an instrument designed to separate mixture components based on component size and density by centrifugal force. Under centrifugal force, particles with larger density migrate toward the bottom of the tube to eventually form a pellet; the lighter particles will remain in the supernatant. (A supernatant is a liquid or medium which stays above a pellet after centrifugation and is composed of lighter or smaller materials.)

The centrifuge was a crucial part of the discovery of insulin, as it allowed the insulin to be properly extracted from the solution. Though centrifuges have been updgraded and have evolved over time, the basic principle of centrifugal force has remained the same and is an important part of history.

Fun Fact: The fastest centrifuges spin at over 1 million times the force of gravity!

## Design Breakdown

For the centrifuge, users learn about centrifuge best practices and how it works in the process of extracting insulin.

{%
  include figure.html
  image="images/centrifuge_and_crank.jpg"
  caption="Centrifuge and Hand Crank"
  width="400px"
%}

Our centrifuge consists of two main components, the container and the hand crank. The container is a repurposed rice barrel and the hand crank is custom 3D printed.

{%
  include figure.html
  image="images/inside_centrifuge.jpg"
  caption="View of Inside the Centrifuge"
  width="400px"
%}

The centrifuge contains a motorized spinner where two vials can be placed. As the user spins the hand crank, an electronic signal is sent to the motor to spin the centrifuge. This is to simulate a real world centrifuge from the 1920's by making it appear the hand crank is physically turning the centrifuge.

{%
  include figure.html
  image="images/crank.jpg"
  caption="Close-up View of Hand Crank"
  width="400px"
%}

The hand crank uses a light sensor to detect the rate of motion. This allows us to increase the speed of the motorized centrifuge accordingly, simulating a real world centrifuge.