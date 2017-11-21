# Deep Traffic

### [Deep Learning for Self Driving Cars](https://selfdrivingcars.mit.edu/deeptraffic/)


[DeepTraffic](https://selfdrivingcars.mit.edu/deeptrafficjs/) is a gamified simulation of typical highway traffic. The task is to build a neural agent – more specifically design and train a neural network that performs well on high traffic roads. The neural network gets to control one of the cars (displayed in red) and has to learn how to navigate efficiently to go as fast as possible. The car already comes with a safety system, so you don’t have to worry about the basic task of driving – the net only has to tell the car if it should accelerate/slow down or change lanes, and it will do so if that is possible without crashing into other cars.


---
## Leader Board

The aim is to get as high speed as 80 mph where the bes submission acheived 73.73mph. Whereas the maximum speed at time of submission at leaderboard was 76.26mph.

## Model Architecutre

The three top model acheived highest speed [64 mph](https://github.com/hamzafar/deep_traffic/blob/master/deepTraffic_64.js),
[70mph](https://github.com/hamzafar/deep_traffic/blob/master/deepTraffic_70.js) 
and [73mph](https://github.com/hamzafar/deep_traffic/blob/master/deepTraffic_73.js).

The following are the key parameters that lead to 73mph:
1. Increase the input of agents as 
    lanesSide = 3;
    patchesAhead = 50;
    patchesBehind = 10;
