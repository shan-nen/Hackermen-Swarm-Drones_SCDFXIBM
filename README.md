# Hackermen-Swarm-Drones_SCDFXIBM

Helo! WE are team Hackermen and we tried to come up with a cool solution for this challenge


## *We aim to help SCDF increase their capabilities while becoming more sustainable.*##

8 minutes is all firefighters have to arrive on scene, and this can be made challenging by traffic conditions. Lots of fire extinguishing agents are used to put out fires, giving rise to opportunities to innovate for more environmentally friendly options.

Our solution leverages on drones, A.I, 5G, IoT and soundwave technology to bypass all traffic conditions faced by firefighters to control fires with sound. 

The swarm of smart autonomous drones are capable of tracking fires by flying themselves to the accident site based on GPS tracking and A.I enabled cameras to identify, size and control fires. Through IoT, drones are able to communicate and position themselves in the most optimal position to control the fire with sound until firefighters arrive.

Soundwave firefighting tech which has been proven effective in the U.S to put out fires in a controlled setting works by pushing out surrounding oxygen to break apart the combustion triangle (oxygen, fuel and heat). 

## Solution

1. Connect the drone to IoT devices. The IoT devices are as follows:
  - Thermometer
  - GPS
  - Camera

Note that before the autonomous drones can be used on ground by the firefighters to recognise and control the fire, they have to be trained using images and videos of fire and via simulation a

2. Connect the drone to Cloudant. Cloudant will be used to store the data from the drones. It is chosen as it can store both unstructured and structured data. Unstructed data comes from the videos and the pictures of the fire scene while structured data comes in the form of temperature, GPS location and time stamps

3. The videos are stored in Cloudant and also fed into IBM Watson. IBM Watson analyses the real time data from the fire scene where the drones are scouting. It also enables the fire zones to be recognised.

4. The analytics done by IBM Watson will be fed into a dashboard called Graphana. THe live video feed will also be played on the dashboard to allow command to gain understanding of the on site situation. This dashboard is also available to the firefighters on the ground.

  
## Pitch Video

Here is the link for our pitch video! :)
[title]https://youtu.be/FZ3LmVB_TTc

<a href="https://youtu.be/FZ3LmVB_TTc
" target="_blank"><img src="https://youtu.be/FZ3LmVB_TTc" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


## Architecture of our solution

<img width="895" alt="Screenshot 2021-06-11 at 12 37 36 AM" src="https://user-images.githubusercontent.com/85566578/121563672-3bd46580-ca4d-11eb-81f6-53c9e92a19cf.png">


## Detailed solution

## Getting Started

## What we used in IBM Cloud
- Cloudant
- IBM Watson Machine Learning
- Node Red 







