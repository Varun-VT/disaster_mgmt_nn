
#Disaster Management
Problem Statement- After a storm/ floods hit the surface, authorities do not have track of the actual locations of critical infrastructure like roads etc. So they have to rely on volunteers to map out the affected areas and prepare a map which they can use to plan out the relief measures on the ground. So, if technology can help create the post- disaster hit map for us then we can decrease our response time significantly and help those in need.

Automatic Detection of critical infrastructure in flooded area using Deep learning
Due to storms/ heavy rainfall/ cloud burst critical infrastructure like roads, rail lines, canals can be affected/ destroyed. This leads to stoppage of essential supplies which are required for the very survival of human beings. But due to the unwanted disruptions to the critica supply chains, authorities cannot deliver the required help which is needed at the earliest and start the rehabilitation process as soon as possible.

Concept-Training a neural network to identify affected infrastructures alignment so that rehabilitation of that structure can be done with the least resources and in minimum possible time.

Algorithm-
1- Using pre-disaster satellite images to get the co-ordinates/ alignment of critical infrastructure like electric grid, roads, canal linings, houses, hospitals etc
2- Using post- disaster satellite images to get condition of the ground after the disaster over the same area
3- Get the flooded area by substracting both the above images. The critical infrastructure in this area would be flooded
4- Feeding this data into a CNN as it's good in image segmentation which is our problem here


Data- We can use high quality satellite image data from Mapbox from a variety of locations. 

Deployment- We can use javascript framework for displaying maps, which supports desktop and mobile browsers so that competent authorities can make use of it. 
