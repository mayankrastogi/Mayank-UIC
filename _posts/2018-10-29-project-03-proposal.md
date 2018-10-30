---
layout: post
title: Project &#35;3 (Proposal)&#58; Array of Things VR 
categories: [CS491, Projects]
permalink: cs491/projects/03-proposal
---

***Array of Things VR*** is our proposal for the third project, for our Virtual and Augmented Reality class at UIC.

## Table of contents

{::options toc_levels="1..3" /}

1. table of contents
{:toc}

## Project Description

The [Array of Things](https://arrayofthings.github.io/) is a collaborative effort among leading scientists, universities, local government, and communities to collect real-time data on urban environment, infrastructure, and activity for research and public use.

With the help of this project, we are going to attempt to visualize some of the data, sourced from the Array of Things database, **in VR**.

Within the scope of the project, data from various sensors, installed throughout the city of **Chicago**, will be visualized on a **3D map** of the city, in **VR**.

- The user will be able to compare **3 months** worth of data at any sensor node
- The data maybe fetched in real-time, but for the scope of this project, the **data will be packaged within the app**
- The data will be available on a **daily level**

> The time-span of the data, as well as the level, may be changed during the development, depending on a reasonable storage-space occupied by the data, since it will need to be packaged along with the application.

We plan to visualize the following data:

- Light Intensity
- Sound Levels
- Temperature
- Precipitation

> Other kinds of data may be added subject to roadblocks faced during the development and availability of time.

Data visualization libraries are not readily available for Unity. Hence, we might need to build a basic visualization library as part of this project, which might further impact the number of features in the app that can be finished by the project deadline.

## Why VR is beneficial here?

Visualizing data in VR will enable the user to visit a particular area on the map, and recreate the conditions of that place, at a given time. *The idea is to create a **fun** and **interactive** way of visualizing geospatial data, overlaid with related visualizations*.

Our premise is, that visualizing data in VR will help **increase the depth of insights**, gained by the user, over traditional visualization methods. 

## Planned Hardware Support

- [HTC Vive](https://www.vive.com)

## Tools &amp; Libraries

- [Unity](https://www.unity3d.com) &ndash; Game Engine
- [VRTK](https://vrtoolkit.readme.io/) &ndash; Virtual Reality Toolkit for Unity
- [Mapbox](https://www.mapbox.com) / [WRLD](https://www.wrld3d.com) &ndash; For rendering 3D maps within Unity
- [VisLab](https://github.com/varuneagle555/V3) &ndash; Data visualization library for Unity

## Team

- [Mayank K Rastogi](https://mrasto3.people.uic.edu) 
- [Shreyas Kulkarni](https://skulka26.people.uic.edu/AboutMe.html)

---

## References / Inspiration

- [Array of Things](https://arrayofthings.github.io/) &ndash; a networked urban sensor project that’s changing our understanding of cities and urban life
- [Data Visualization in VR](https://www.youtube.com/watch?v=wacNaAVGXdU), by Nirvaniq Labs
- [Exploring Data in Virtual Reality](https://www.youtube.com/watch?v=wi3_91hwq0w): Comparisons with 2D Data Visualizations, by Patrick Millais, Simon Jones, Ryan Kelly