---
layout: post
title: Project &#35;3 (Proposal)&#58; ARray of Things 
categories: [CS491, Projects]
permalink: cs491/projects/03-proposal
---

***ARray of Things*** is our proposal for the third project, for our Virtual and Augmented Reality class at UIC.

## Table of contents

{::options toc_levels="1..3" /}

1. table of contents
{:toc}

## Project Description

The [Array of Things](https://arrayofthings.github.io/) is a collaborative effort among leading scientists, universities, local government, and communities to collect real-time data on urban environment, infrastructure, and activity for research and public use.

With the help of this project, we are going to visualize some of the data, sourced from the Array of Things database, **in AR**. Residents of Chicago will be able to use this application to gain a better understanding of the weather, cloud cover, traffic, and air quality, at various locations in the city, throughout the day. The following features are planned to be developed by the project deadline:

- View sensor nodes, within a given radius from the user's location, by pointing the camera in the direction of the nodes
- Choose the type of sensor data to display (e.g. weather, cloud cover, air quality)
- Choose the date and time of day for which the data is to be viewed
- View raw sensor values for a given node by tapping the sensor marker on the screen
- Compare the current value of a sensor with a value obtained in the past from the same node
- Compare the values obtained from a sensor, at a given time, with those obtained from another sensor
- Sensor data will be available in real-time (internet connection required)

[Click here](https://documentcloud.adobe.com/link/track?uri=urn%3Aaaid%3Ascds%3AUS%3A569dd7c0-eed1-4586-beee-64e2c613b904) to view the pen-paper mockups for the app.

Users will be able to view the following types of data:

1. Weather
   1. Temperature
   2. Humidity
   3. Pressure
2. Cloud Cover
   1. Light intensity
   2. Infra-red light
   3. Ultra-violet light
3. Air Quality
   1. Carbon Monoxide (CO)
   2. Hydrogen Sulphide (H2S)
   3. Ozone (O3)
   4. Sulphur Dioxide (SO2)
   5. Nitrogen Dioxide (NO2)

## Why AR is beneficial here?

This app will provide its users ***on-the-go*** access to various types of environmental data for their neighborhood and the nearby areas. Using the camera to locate the nearby sensors will be much more intuitive than selecting them on a map. Additionally, viewing the sensor using the camera, and seeing the relevant information pop-up near the sensor-marker, will give the users a better sense of direction and location of the sensors. Furthermore, fairly quick comparisons can be made between the nearby sensors by just moving the camera around.

## Planned Hardware Support

- Either iPhone or Android phones

## Tools &amp; Libraries

Depending on finalized hardware support, the following types of libraries will be needed:

- Augmented Reality SDK &ndash; ARKit/ARCore
- Networking Library for API calls &ndash; Alamofire/Volley

## Team

- [Mayank K Rastogi](https://mrasto3.people.uic.edu) 
- [Shreyas Kulkarni](https://skulka26.people.uic.edu/AboutMe.html)

---

## References / Inspiration

- [Array of Things](https://arrayofthings.github.io/) &ndash; a networked urban sensor project that’s changing our understanding of cities and urban life