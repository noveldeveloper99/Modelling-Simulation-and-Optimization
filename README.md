# Modelling-Simulation-and-Optimization
Semester Project repository

# Traffic Road Simulation and Optimization

## Project Outline

A small village in the commuter belt of a large town shares the local school with a
neighbouring village. The local school is about 1km East of the village on the Old School
Road which connects the two villages in East-West Direction. Years ago, the kids from both
villages could easily walk or cycle to the school.

With the expansion of the commuter belt, the rush hour traffic in the village became
unbearable and a small bypass was constructed that diverted the national road around the
village. The national road now crosses the Old School Road about 700m from the village.
Crossing the national road is dangerous, so the parents now bring their children with the car
to the school. Every morning during a 15-minute peak time shortly before the 9am start of
school 50 cars make the trip from the village to the local school and later back again.
Crossing the national road is not easy, and when too many cars come at once, there is quite
a build-up of a queue on the crossing. The parents learned this the hard way and spread
their schedule, some leaving home as early as 8:30.

The morning rush hour on the national road is from 7:30am to 9:15am. The South bound
traffic flow during this period has increased over the years from 200 veh/h to 300 veh/h, but
this didn’t affect the cross traffic of parents bringing their children to school too much. The
average travel time to the school increased only marginally and is still just under 2 minutes.
And the maximum travel time increased from 3 to 4 minutes. The North bound traffic flow
during the morning appears static at 120 veh/h. The evening rush hour goes in the opposite
direction, but we ignore this, as there is no interference with school traffic in the evening
hours.

North of the village a new estate is planned. Once Phase 1 is finished, the traffic flow in the
morning rush hour is expected to increase to 400 veh/h. Once Phase 2 of the new estate is
finished, the rush hour traffic is expected to increase to 600 veh/h. The building company
has provided lots of glossy material, but local residents are sceptical. Parents are concerned
about the impact on the local school traffic. You are being tasked with investigating if there
is a statistically significant change in the length of the queues of the cars waiting to cross
the national road, and hence in the waiting time at the crossing and the overall traveling
time.                                                                                    ![map](https://user-images.githubusercontent.com/98535942/218255324-f96f0f05-0a6c-4ab8-a9aa-e591ab801b57.png)                              

### Part 1 Baseline Simulation

Create a simulation model of the crossing under the following assumptions:
1. Cars on the national road are travelling at constant speed of 100km/h.
2. On the national road the inter-arrival time of cars in both directions follows an
exponential distribution.
3. Cars on the Old School Road are limited to 50km/h.
4. The inter-arrival time of cars on the Old School Road follows an exponential distribution.
5. Every morning 50 cars make the drive to the school.
6. The simulation runs for 30 minutes
Validate the simulation model by running it with a traffic flow of 200 veh/h and 300 veh/h on the
National Road and check the average and maximum travel times for the 1km distance from the
village to the school. The average travel time should stay just under 2 minutes and the maximum
travel time just under 4 minutes.

### Part 2 Simulation Study
Create a framework for running multiple simulations of 30 minutes each, combine their results
and enable suitable statistical tests.
1. Compare the effects of the higher anticipated traffic flow on the national road of 400
veh/h and 600 veh/h to the effect of the current traffic flow of 300 veh/h on different
variables.
2. Is there a statistically significant effect (p<0.01) on the queue length and the waiting time
at the crossing of the Old School Road and the national road.
3. Your task is to investigate if there is a statistically significant effect of a speed limit of
60km/h or 80km/h on the national road. Formulate your hypothesis and run the
necessary simulations to support or reject your hypothesis and draw your conclusions.

This project is based on the simulation for a rural crossing between a national road in North-
South direction and a local road in East-West direction, as indicated in Figure 1.
Fig. 1: Model of the Cross Road as developed in class. 

### General Remarks

![download](https://user-images.githubusercontent.com/98535942/218255350-d50677b7-4b7c-4d89-8441-3d0bd5eafca6.png)
![download (1)](https://user-images.githubusercontent.com/98535942/218255351-3c3920b1-b9da-4c34-aa01-2cd17fca4b78.png)
![download (2)](https://user-images.githubusercontent.com/98535942/218255352-73dfc387-2147-496e-bf0a-97425296e6da.png)
![download (3)](https://user-images.githubusercontent.com/98535942/218255353-66a5aa08-ee7e-4003-95cb-58f498f3ac42.png)

• For this simulation study you will have to make some assumptions about the
vehicle’s parameters (vehicle size, average and maximum acceleration and
deceleration) and the driver’s behaviour. You have free choice about these
assumptions, but the assumptions you made need to be clearly documented in the
final report.

• The number of vehicles driving to school in the morning is fixed (50) as is the time
period for each simulation run (30 mins). To obtain statistically meaningful results,
you have to run multiple simulations. You argue for the number of simulations you
have chosen.

• Provide suitable graphs for the simulation results (i.e. s/t Graphs, Count Graphs,
queue length, wait time, travel times) and statistical summaries (i.e. histograms, boxplots).

• All graphs included in the report must have their origin in one of the jupyter
notebooks provided. Provide the file name and cell number as part of the figure
caption.

• Use your student ID as initial seed value for all your simulations. Consequently,
everyone will have different albeit somehow similar results and graphs.

• The teaching material used for this course is updated every semester. Code versions
from different semesters may be incompatible. Do not use code from previous
semesters.

• As citation for class material use: C. Horn. Modelling, Simulation, and Optimisation.
Lecture Notes. National College of Ireland. July 2022
Deliverables


