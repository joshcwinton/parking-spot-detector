# Parking Spot Detector
This repo is a placeholder for an idea I want to implement.

In my neighborhood, it can be difficult to find open parking spots, particularly in front of my house.

I thought it would be interesting to develop a system that monitors the parking spot in front of my house and sends me a notification on my phone when the spot becomes available.

My general idea is that the system will have a Raspberry Pi with a camera attatched to it, pointed out my front window. The Raspberry Pi will run some image processing software that takes a picture of the spot every minute or so. The picture will be run through some classification algorithm that outputs positive or negative for the presence of a car. When the signal is poisitve, then a message/notification will be sent to my phone. 

I'm going to start out by making everything custom for me and my system but I would like to eventually turn it into something anyone can use if they have the right hardware.
