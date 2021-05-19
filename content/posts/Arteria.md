---
title: "Arteria"
date: 2021-05-19T10:11:02+02:00
draft: false
image: "img/Arteria/AgriCooperative.png"
---

Between my fisrt and second year at Telecom SudParis I made an internship of two month at Arteria, a subsidiary of RTE.
This startup of 15 employees aim to make profitable the infrastructures of RTE, by reabilitating electrical pylons, and deploying optical fibers and an IoT (Internet of Things) network.

For my internship, I integrated a team of 4 dedicated to provide connected sensors, connectivity and a web interface to agricultors and small cities.
My mission was to design and implement the customers' dashboard on the interface, and to provide the best work I could, I followed those steps:

&nbsp;

### Study of the existing

I started by analysing the different types of clients and data collected, and the existing interface.


## Clients and data

Two main main domains are represented in the inteface: agriculture and smart cities.

In the agriculture, two types of clients exist: the cooperative with data from different farms, and agricultors with less data and more proximate crops.
The cooperative needs to easily see the state of the crops or the silos in the different territories, especially as they may collect their content once they are full.
The agricultors may have different types of activities: some want to see the data from their crops (temperature, humidity, luminosity, CO2), others from their meteo stations (temperature, pression, wind direction and velocity, humidity, pluviometry), or their silos (capacity, occupancy rate, content type), or all that !


For the smart cities, the clients needs to easily understand the data of the different rooms or floors, and have both precise views of each room and a general one of all the building.


## The interface 

The interface was done with Thingsboard, an open-source IoT platform for data visualization and device management.
Therefore, I did not have to code entirelly a new dashboards, and I could customize the exiting and create (through html, css, and javaScript) entirely new widgets.

The interface was at its premice, and only had one type of dashboard for all the agricultors clients.
Appart from the lack of distincion between the activities of the agricultors, at first sigh the client may not see the information he wants.

![Dashboard](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Screenshots/Dashboard1.JPG)


For the widgets, the same one was used to represent the temperature, humidity, and the occupancy rate of a silo; which made it difficult to easily differentiate the values.
Besides, some graphics could be hard to read for customers that are not used to it.

&nbsp;


### Research

After discerning the needs and the existing problems, I made research to look at what was done it terms of dashboard or widgets, and what could be done with thingsboard or by code.
You can see below different moodboards that I created.

<!-- ![Moodboard](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Moodboard.JPG) -->

&nbsp;


### Brainstorming

Once I had all this aspects in mind, I shared them with my tutor, and we reunited for brainstorming sessions.
We used scenarios, personas, and storyboards to obtain a clear view of our objectives.

&nbsp;

### Sketching and Prototyping

After having a clear view of where we were going, I started to sketch the dashboards and widgets I imagined, along with their information architectures.


Once my tutor and I were happy with my ideas, I started to create the dashboards and their widgets on Thingsboard.

To modify or create widgets on the platform, I had to understand the code of the existing ones, and to strenghten my skills in html, css and javascript, to create new ones.  
I also created new icons on Photoshop and Illustrator, to create more representative widgets.
For example, I created the pins' icons on the map widget, to enable the user to recognize what kind of sensors are on this specic site or area.  

![Prototypes](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Widgets/Hand-madeIcons.JPG)

Unfortunately, I was not able to make potential users test my dashboards. 
However I shared my creations with my team of 4, and reajusted them accordingly.

&nbsp;

### Solutions and Sharing

For the agriculture, I conceived 4 types of dashboards, you can swipe bellow to see the different dashboard I produced.

The fisrt one is for a cooperative, and displays a general view of different sites ; if the user clicks on an icon on the map he accesses the specific dashboard of the site.
Then, I made a dashboard for each type of data: the first one is for the monitoring of a meteo statino, the second one for the maintenance of silos (you can see below 2 variants of it), and the third one is for the monitoring of agricultural lands.

The two following dashboards are for the smart cities: one with a general view of a building showing if a sensor detected an anormal situation, if the user clicks on one of the rooms in the hierarchy, he accessses the second dashboard where the data of the different sensors of the room are displayed.


{{< gallery-slider dir="img/Arteria/Solutions/" width="907px" height="450px" >}}


<!-- ![Solutions](https://ceici92.github.io/CeciliasPortofolio/img/Arteria/Moodboard.JPG) -->


Furthemore, not only did I let them those dashboards, but I also prepared a presentation, a document and slides to enable them to change the data and to adapt the dashboards to the new consumers.



