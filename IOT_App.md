# Assignment 3 : IOT

This assignment was to create an app that shows the status of a senior person. Movement sensors are set up around the house and send messages to an MQTT Broker which transmits the messages using a lightweight publish-subscribe protocol to the phone. 

I wrote the app using Ionic React.

A report was required, including the following:
- An explaination of two UX Decisions
  - The Senior Status page only shows message updates rather than a visual update (map of the house) as it would require the layout senior's house.
  - The battery status page displays the battery status as percentages as it allows more accurate reading than a progress bar. 
- A Self Designed Screen
  - The Overall Status page shows all the current information about each room (and it's sensor) including the last time updated, the motion status, and the battery status.
- Possible Issues with the System
  - No Movement Detected
    - Seniors tend to spend a large portion of their time either sleeping, outside the house, or performing no-movement activies (like watching tv). This could provide false alerts to the user.
  - Sensor Location
    - The location of the sensors impact the quality of the data they return. A sensor focusing on the door might not see the senior moving on the other side of the room.
  - False Positives
    - Motion sensors are susceptible to false positives from either sudden changes in heat (infrared sensors) or animals/other humans.
- IOT System Architecture
  - The typical architecture (as laid out in books, etc)
  - The given architecture (the motion-sensors, MQTT Broker, and phone)
  - The suggested architecture (how I would update the given architecture to provide more support for the senior)
