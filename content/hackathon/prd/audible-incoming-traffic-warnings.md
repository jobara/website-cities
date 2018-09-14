---
title: "Hackathon Project #1: Audible incoming traffic warnings @ intersections"
---

## Idea

An occupancy sensor (pressure sensor, camera, etc.) in the street that lets people know about someone approaching on a bicycle or car if they're preparing to cross the street and / or currently in the street.

## Use cases

1. Someone who is blind or has low-vision is preparing to cross to the bike lane and would be notified that there is a biker approaching from the left and how much time before the bike/car will pass.
1. Someone is standing in the middle of the street and not paying attention; an electric AV approaches but doesn’t make a sound. This traffic warning notifies the person that there is an AV approaching and guides them off the street.
1. The light is green and the pedestrian has right of way, but there is a car approaching quickly that may run the light. This would notify the pedestrian that it is not yet safe to walk. (Only in a legacy vehicle situation).

## This prototype must include

1. A way to sense or indicate that someone is waiting to cross
1. A way to sense or indicate traffic that is approaching from at least 50m/150ft away (assuming vehicle travelling 40km/hr at outer limit).
1. How far away (in time) the vehicle is
1. Which direction it’s coming from
1. Produce an audible warning signal and description
1. Doesn’t require a phone

## This prototype could optionally include

- This could optionally integrate with the temporary physical tactile crosswalk to notify a biker that they should stop for a pedestrian.
- This could optionally integrate with street lighting that would turn red if the person should not start crossing
- This could optionally integrate with the AR demo to give you an auditory signal when the AR AVs approach you if you’re standing in the middle of the street.

## Major risks to work on/ What do we hope to learn

- Is it annoying to have loud sound coming from the street?
- How often would this trigger in normal traffic patterns?
- Is it annoying if this happens too frequently?
- What happens if there are multiple vehicles (cars or bikes) approaching? How should we describe a line of cars (or normal traffic)?
- Do occupancy sensors do a good job of predicting how long it’ll take for a vehicle to approach?

## Hardware/materials needed

- Occupancy sensor (pressure sensor or camera or radar)
- Traffic sensor (radar or camera or LIDAR)
- LED lights (check out if new lights from chris have arrived and if we can use them for a crosswalk scenario)
- Arduino
- Sound emitting speaker, e.g. https://www.instructables.com/id/Arduino-Basics-Making-Sound/.

## Special skills needed

- Arduino skills / sensors (some light hardware)

[Back to the Hackathon project descriptions]({{< relref "/ideas/hackathon-project-descriptions.md" >}})