# Project Aircare

Air quality IoT pod, cloud database stream API, and Visualization Tool.

## Motivation

- Identify trouble spots in an urban center and remedy
- http://datasmart.ash.harvard.edu/news/article/how-cities-are-using-the-internet-of-things-to-map-air-quality-1025
- https://www.google.com/search?q=california+wildfires&oq=california+wild&aqs=chrome.0.0j69i60j0l2j69i57j69i60.2981j1j4&sourceid=chrome&ie=UTF-8

## Sensor hardware

Ideas:

- How to DIY a Cheap Air Particulate Sensor #CitizenScience
  I know I’ve spent the last couple of weeks talking about water monitoring devices, so this week I’m changing it up with an air particulate sensor I discovered at Hackster.io. This proje… (44kB)
  Jun 13th, 2016 at 10:30 PM https://blog.adafruit.com/2016/06/14/how-to-diy-a-cheap-air-particulate-sensor-citizenscience/

## Cloud Database

Datum structure
- timestamp (millisecond)
- float: particulate sensor measurement: 0.0 to 1.0 where 1.0 is no light detected
- GPS coords
- float: height above sea level

## Visualization tool

- Meteor 
    - API queries database
    - Google maps API (2D top down view)
    - THREE.js (?) for 3D visualization
    
