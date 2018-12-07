# ECE6720_Project
MATLAB GUI to plot Nullcline's for two species biological network. The application will plot the Nullcline and field vectors of 
a two species biological network. The goal of the application is to allow the user to determine equilibrium and stability of 
the network from a plotted graph.The GUI includes important parameters to characterize the network (see below for specifics 
on parameters), plot button, clear button, window where figures will show up, and three pre-programmed networks to 
help the user get started.

Parameters list

kd - Degradation rate of both species S0 and S1 
kaS0 - Activation production rate of species S0
kaS1 - Activation production rate of species S1
kbS0 - Basal production rate of species S0
kbS1 - Basal production rate of species S1
KaS0S0 - Activation binding equilibrium from S0 to S0
KrS1S0 - Repression binding equilibrium from S0 to S1
KaS1S0 - Activation binding equilibrium from S0 to S1
KrS0S0 - Repression binding equilibrium from S0 to S0 
KaS1S1 - Activation binding equilibrium from S1 to S1
KrS0S1 - Repression binding equilibrium from S1 to S0
KaS0S1 - Activation binding equilibrium from S1 to S0
KrS1S1 - Repression binding equilibrium from S1 to S1

**note -- Kx denotes the ratio of the forward and reverse rates (ie Kr = Kr_forward/Kr_reverse)**
**note -- Other parameters that can be found and changed in the code (nc,nr, P0, P1, Ko, Kao)


### Prerequisites

MATLAB
Created on MATLAB 2018.b but should also be compatiable with early version of MATLAB. Has not been tested on early version. 
If you are using an early version please confirm if it works or not. Thanks!

### Running APP

Ensure MATLAB is on the computer -> Download the NullclinePlotter.mlapp file -> Open file in MATLAB's APP Designer 
-> Click run

## Running the tests

Select one of the three pre-programmed two species systems from the drop down menu -> Select plot

Nullcline's/Feild Vectors should show up in the figure window
If no errors are returned the file is working
If errors occur when other parameter values are enter please report it so it can be fixed in other versions

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

MATLAB APP GUIDE 

## Versioning

Version 1
Please add comments and suggest for later versions

## Authors

* **Gavin Yeip** - [gavinyeip](https://github.com/gavinyeip)

See also the list of [contributors](https://github.com/gavinyeip/ECE6720_Project/contributors) who participated in this project.


## Acknowledgments

* Chris Myers
* ECE 6720

