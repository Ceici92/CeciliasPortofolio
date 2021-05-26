---
title: "Customers' Dashboards"
date: 2021-05-19T10:11:02+02:00
draft: false
image: "img/Arteria/AgriCooperative.png"
---

- **The company:**

Between my first and second year at Telecom SudParis I made an internship of two month at Arteria, a subsidiary of RTE.
This start-up of 15 employees aim to make profitable the infrastructures of RTE, by rehabilitating electrical pylons, and deploying optical fibers and an IoT (Internet of Things) network.


- **My mission:**

For my internship, I integrated a team of 4 people dedicated to provide connected sensors, connectivity and a web interface to farmerss and small cities.
My mission was to design and implement the customers' dashboard on the interface, and to do so I followed those steps:

&nbsp;

## Study of the existing

I started by analysing the different types of clients and data collected, and the existing interface.


### Clients and data

Two main domains are represented in the interface: **agriculture** and **smart cities**.

> In the **agriculture**, two types of clients exist: the cooperative with data from different farms, and farmerss with less data and more proximate crops.
The cooperative needs to easily see the state of the crops or the silos in the different territories, especially as they may collect their content once they are full.
The farmerss may have different types of activities: some want to see the data from their crops (temperature, humidity, luminosity, CO2), others from their weather stations (temperature, pression, wind direction and velocity, humidity, pluviometry), or their silos (capacity, occupancy rate, content type), or all that !


> For the **smart cities**, the clients are mostly city councils. 
They install captors in an entire building to regulate the energy consumption. 
Thus, they need to instantly see the state of the entire building, but also to be able to navigate and have a precise view of each floor or each room.


### The Thingsboard's interface 

The interface was done with Thingsboard, an open-source IoT platform for data visualization and device management.
Therefore, I did not have to code entirely new dashboards, and I could customize the exiting and create (through html, css, and javaScript) entirely new widgets.

The interface was at its premise and only had one type of dashboard for all the clients.
Apart from the lack of distinction between the activities of the farmerss, at first sigh the client may not see the information he wants.

![Dashboard](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Screenshots/Dashboard1.JPG)


For the widgets, the same one was used to represent the temperature, humidity, and the occupancy rate of a silo; which made it difficult to easily differentiate the values.
Besides, some graphics could be hard to read for customers that are not used to it.

&nbsp;


## Research & Brainstorming

After discerning the needs and the existing problems, I made research to look at what was done it terms of dashboard or widgets, and what could be done with thingsboard or by code.


<!-- ![Moodboard](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Moodboard.JPG) -->

Once I had all these aspects in mind, I shared them with my tutor, and we reunited for brainstorming sessions.
We used scenarios, personas, and storyboards to obtain a clear view of our objectives.

&nbsp;

## Sketching and Prototyping

After having a clear view of where we were going, I started to sketch the dashboards and widgets I imagined, along with their information architectures.


Once my tutor and I were happy with my ideas, I started to create the dashboards and their widgets on Thingsboard.


- **New Icons:**

I also created new icons on Photoshop and Illustrator, to create more representative widgets.
For example, I created the pins' icons on the map widget, to enable the user to recognize what kind of sensors are on this specific site or area.  

![Prototypes](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Widgets/Hand-madeIcons.JPG)


- **New Widgets:**

To modify or create widgets on the platform, I had to understand the code of the existing ones, and to strengthen my skills in html, css and javascript, to create new ones.  

![Prototypes](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Widgets/Widgets.JPG)


Unfortunately, I was not able to make potential users test my dashboards. 
However I shared my creations with my team of 4, and readjusted them accordingly.

&nbsp;


## Solutions

You can find below the dashboards I produced.

- I conceived 4 types of dashboard for the **agriculture**:

>The first one is for a cooperative, and displays a general view of different sites, if the user clicks on an icon on the map, he accesses the specific dashboard of the site.
Then, there are one dashboard for each type of data: the first one is for the monitoring of a weather station, the second one for the maintenance of silos (you can see below 2 variants of it), and the third one is for the monitoring of agricultural lands.


- The last two dashboards are for the **smart cities**: 
 
>One with a general view of a building showing if a sensor detected an anormal situation, if the user clicks on one of the rooms in the hierarchy, he accesses the second dashboard where the data of the different sensors of the room are displayed.


{{< gallery-slider dir="img/Arteria/Solutions/" width="907px" height="450px" >}}


<!-- ![Solutions](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Moodboard.JPG) -->


