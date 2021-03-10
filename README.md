# Energy - Efficient Scheduling Algorithm to Reduce CPU Power Consumptions for Periodic Tasks in Real - Time Embedded System

## Project Overview

* Implemented Dynamic Voltage and Frequency Scaling (ES - DVFS) and Dynamic Global Energy - Efficent Scheduling Based on the Actual Execution Time (DGAET) by reading papers
* Compared these two algorithms

## Environment SetUp

* Python 3.7
* Visual Studio Code

## Description of Input Data

* As for the input data of both ES – DVFS and DGAET algorithms, three tasks sets with execution time, deadline and period (𝐶𝑖,𝐷𝑖,𝑇𝑖) are asked from the user, where 𝐶𝑖=execution time, 𝐷𝑖 = deadline, 𝑇𝑖 = period and 𝑖 = 3. 
* The execution time must be smaller than both deadline and period, and deadline also must be smaller than period. 
* Therefore, the input task set must be in 𝐶<𝐷<𝑇. 
* Moreover, execution time, deadline and periods of each task must not be same. 
* It is also assumed that all the periods must be in periodically.
* In this work, for both algorithms, the resource of the system is assumed as battery, so it is asked from the user as constant value.
* The battery units must be reasonable with the task sets which are going to be scheduled. The user must put energy units between 20 units and 50 units.

## Algorithm Description

* ES - DVFS from paper, [Energy efficient scheduler of aperiodic jobs for real-time embedded systems](https://www.researchgate.net/publication/304191974_Energy_efficient_scheduler_of_aperiodic_jobs_for_real-time_embedded_systems)
* DGAET from paper, [Energy-efficient scheduling with reliability guarantee in embedded real-time systems](https://www.sciencedirect.com/science/article/abs/pii/S2210537916300075)

## Simulation Result for ES - DVFS

![image](https://user-images.githubusercontent.com/50255936/110669185-0b3f1e80-8207-11eb-9630-4ec2dea991df.png)

## Simulation Result for DGAET
![image](https://user-images.githubusercontent.com/50255936/110669279-227e0c00-8207-11eb-8c1e-863611a645f5.png)
