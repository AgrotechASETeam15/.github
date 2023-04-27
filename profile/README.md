# Agrotech_ASE_Project

A project based on smart garden automation that was developed using the full Software Development Lifecycle using the incremental waterfall methodology and utilizing the concepts of software engineering such as requirement gathering, specifications, software design and architecture, implementation, testing, deployment and maintenance.

The project has the features of smart garden such as Drip Irrigation for watering the plants, Pesticide for protecting the plants and green house to grow delecate plants. The soil moisture is measured using soil moisture sensor for drip irrigation. The pesticide level can be measured using soil NPK sensor. The green house has safety features such as temperature control, exhaust and smoke detector in case of any fire or disaster.

The following video demonstrates the working of smart garden with all the three functionalities integrated in a green house protoype:



https://user-images.githubusercontent.com/77005472/234641762-df07535c-b491-4964-9a3e-2e32efa407c7.MP4


## Drip Irrigation:
The Drip Irrifation module consists of a solution in which soil moisture sensor is attached to every plant or every group of plants having same characteristics. When there is sufficient moisture for the plant or the group of plants the water-valve will get closed for that plant or group of plants.
Tinker Cad was used to create the simulation for the drip irrigation module. Thingspeak is used for communicating the values of sensor to monitor in the web application.
The bulb in the circuit represents a water-valve which automatically gets closed when there is sufficient moisture for the plant.


https://user-images.githubusercontent.com/77005472/235002014-bee4871b-d195-4fc3-a0a3-bd2883e29037.webm


https://user-images.githubusercontent.com/77005472/235004268-cf23d065-a600-4b71-ac53-ed8fff8772fc.mov



## Pesticide
In this module the soil NPK sensor is not attached to every plant, rather they are inserted at the beginning and end of the garden and sometimes in the middle depending upon the length of the garden.
Soil fertility level is measured by calculating the average from the soil NPK sensors and the pesticide valve is opened or closed based on the required fertility.


https://user-images.githubusercontent.com/77005472/235002643-5a0a42b8-6724-4391-9176-6c1bd616e594.webm


https://user-images.githubusercontent.com/77005472/235004283-982bfb24-e703-4be6-9e32-121cce7402fa.mov



## Greenhouse
The greenhouse is used for growing delecate plants whicha re sensitive to extreme sunlight or wind. The greenhouse is a protected environment in whihc humidity, temperature, soil moisture, light density and soil fertility are measured for growing delecate plants. It is a closed environment to protect plants from extreme heat, wind, snow and rain.


https://user-images.githubusercontent.com/77005472/235004085-f8a4b955-6447-43f0-bac4-d9aacf542936.webm

