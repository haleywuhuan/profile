---
title: "Part1-Introduction to distributed optical fiber sensors"
layout: post
---
Even if you haven't heard of 'distributed optical fiber sensors' before, the name itself provides a clue to its meaning. Essentially, it is a type of sensor that utilizes optical fibers as the sensing medium, operating in a distributed manner. Let's take a few minutes to explain the name word by word.

**Sensor**

When we talk about sensors, images of small electronic devices like thermometers, hydrometers, accelerometers, and CCTV cameras might come to mind. These sensors come in various forms and can measure an array of parameters, including pressure, flow rate, humidity, and temperature, as well as electrical and motion-related parameters like resistance, current, voltage, position, velocity, and acceleration. Typically, these sensors collect signals at specific positions. 

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog1_fig1.jpg" align="center" width="500"></a>
</div>

**Distributed**

How do distributed optical fiber sensors (DOFSs) differ from these electronic sensors? Let's examine the typical signal collected from a DOFS system. Notice that it includes an additional axis called 'distance.' At a specific time, DOFSs gather data from many positions, which is why they are referred to as 'distributed.' You may wonder how long the sensing distance could be. Typically, DOFSs can reach several tens of kilometers, and with advanced technologies, distances over 100 km are also possible.

Let's explore an example scenario: monitoring the strain along the 50 km-long Hong Kong-Zhuhai-Macau bridge. If we were to use strain gauges with a sensor spacing of 10 meters, 5000 sensors would be required. However, by increasing the sensor spacing to 100 meters, only 500 sensors would be needed. It is obvious that increasing the sensor spacing will increase the likelihood of missing important information, as shown in the following illustration. The typical spatial resolution of DOFSs is around several meters to ten meters, this means a single optical fiber can effectively act as thousands of point sensors. Such capability stands as a major advantage of DOFS technology.

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog1_fig2.jpg" align="center" width="650"></a>
</div>

**Optical fiber**     
You may already have some familiarity with optical fiber. The optical fiber you encounter in daily life may come in different packaging forms. However, the fundamental component is the bare optical fiber, while the fillings and jacket are used to protect it. The bare optical fiber is made from thin and transparent glass. Typically, it consists of a core, cladding, and coating. Light travels through the core of the optical fiber-based on total internal reflection. This occurs when light passes from a higher-density medium to a lower-density medium, and the incident angle exceeds the critical angle, causing all the light to be reflected back. As a result, this phenomenon confines the light within the core of the optical fiber, preventing leakage.

The map below shows the extensive network of submarine fiber optic cables, spanning over 1.2 million kilometers and facilitating global interconnection update to 2022. Please note that this map specifically represents submarine cables and does not include the vast network of optical fiber laid underground and connected to homes. Nevertheless, it vividly illustrates the widespread utilization of optical fiber worldwide. As a result, another noteworthy aspect of DOFSs is their ability to harness these extensive fiber-optic cables for sensing purposes. By connecting these world-wide fiber-optic networks with [DOFS interrogators](https://haleyhw.github.io/web/research/), we can turn the communication infrastructure into a global-scale sensing system. 

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog1_fig3.jpg" align="center" width="500"></a>
</div>

<div align="center">
<a href="url"><img src="https://raw.githubusercontent.com/haleywuhuan/profile/master/assets/blog1_fig4.jpg" align="center" width="500"></a>
</div>


[Next Part2](https://haleyhw.github.io/web/Part2-Optical-fiber-communication-system-and-distributed-optical-fiber-sensing-system/)

**Reference**
1. [https://en.wikipedia.org/wiki/Total_internal_reflection](https://en.wikipedia.org/wiki/Total_internal_reflection)
2. [https://www.submarinecablemap.com/](https://www.submarinecablemap.com/)

