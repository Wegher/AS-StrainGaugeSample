# AS-StrainGaugeSample
Project containing library to configure StrainGauge Modules (X20AIA, X20AIB and X67AI2744) and HMI with mappView to configure X67 modules, written in ST.


## 1. Project Description
The inner libraries were created to generate USINTs and UINTs needed for StrainGauge configuration.
A visualization is created using mappView to allow the configuration through HMI for the X67 using different kind of filters (Standard and Extended Filter, the last has an IIR Filter applied and allows a higher resolution for the Data Rate.
This project was created using Automation Studio (AS) V4.10.3.60 and mappView 5.16.


## 2. How to install and run the project
This project can be opened using AS V4.10.3.60.


## 3. How to use the project
There's a task inside the project called gStrainGaugeConfig.
While in simulation, mappView can be accessed through http://127.0.0.1:81/.
It is possible to change the variables in the HMI and see how the UINTs and USINTs are generated through the watch window.


## 4. Credits
Credits to lunardia for creating the logic for obtaining data from StatusInput.


## 5. How to contribute / To do's
Suggestions are welcome.
The visualization will later be created for X20AIA and X20AIB Modules.
