# **hacktohelp**

## **Dominion Enterprises Hack to Help Hampton Roads**
************************************************
### **Proposal**:

>We should set out to solve the Elizabeth river infrastructure problem using a robot that trolls the path and sends path discovery data <e.g. obstructions, etc.> in real time to a public accessible site.  This site uses the bot data, along with data from fitness tracking APIs and vDOT data, to formulate the best/safest/most scenic route for path users to enjoy.

#### Possible Features
- A system where users can report obstructions along the highlighted route. Then the bot can go out and verify if the obstruction is there and update the route accordingly. This would promote community involvement.
- If there are obstructions on the route then, there should be a little description of the obstruction. (e.g If there's construction going on and it's noisy ... then maybe a person that is jogging might go through there versus a tourist trying to enjoy scenery)

#### Concerns/Problems
- what happens when the bot is disrupted/tampered with during its surveying of a route?

#### to prove concept we may need the following:

##### _hardware_:
--------------------------
- wheels
- housing for computing hardware/sensors
- kinect
- telemetry
- dev board w/ cpu, motor controllers, GPIO, gyro, accelerometer
- long lasting battery
- charging station
- a machine to host the webpage

##### _software_:
-----------------------
###### website:
* website-frontend
* bot-communication-website-backend
* best-path-builder-website-backend
* data-aggregator-website-backend
* data-normalizer-website-backend
* request-for-obstruction-removal-website-backend

###### robot:
* motor-control-robot
* kinect-vision-robot
* bot-communication-robot
* localized-path-discovery-robot
* self-docking-algorithm-robot

##### _Data_:
-----------------------
###### Users:
* Surveys-potential-users
* Market-Research-Past-Projects
* Cost-estimate
* Timeline
