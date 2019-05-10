# TrafficFlowOptimization
### Machine Learning Project by Pengzi Li, Songjian Li and Muci Yu
## Motivation
Traffic congestion is a condition on traffic networks which occurred when traffic demand approaches the capacity of a road (or of the intersection along the road). There are many downsides of traffic congestion: stressed and frustrated motorists, encouraging road rage and reduced health of motorists; wasted fuel increases air pollution and carbon dioxide emissions which may contribute global warming due to increased idling, acceleration and breaking; interfere with the passage of ambulance; highly chance of vehicle crashes due to tight spacing and constant stopping-and-going; etc. There are many types of places on the road that could cause traffic congestion, and highway tollgates intersection is one of them ("FACT CHECK: Does This Image Show a Traffic Jam on China's 50-Lane Highway?" , 2019).


Highway tollgates are known as bottlenecks in traffic networks. Long queues at toll gates during peak hours can cause severe congestion, which needs effective countermeasures to solve this challenge. Preemptive countermeasure includes accelerating the toll collection process by allocating temporary toll collectors to open more lanes from traffic regulators aspect, and route recommendation for motorists from map application company aspect, etc. However, these countermeasures are valid only if they acknowledge precise predictions for future traffic flow. For example, if heavy traffic flow in the next hour can be precisely predicted, traffic regulators could then immediately deploy additional toll collectors by expanding more lanes so that the traffic flow could divert at upstream intersections. Or the map application can recommend another route that takes less time for motorists to travel to the same destination, which can also eliminate traffic congestion at a certain level. Besides, many factors might affect the pattern of traffic flow: weather conditions, holidays, peak hours, etc. This various possibility makes future traffic flow and ETA (Estimated Time of Arrival) a known challenge. 

## Goal
In this project, we want to design reliable approaches for future traffic flow and ETA prediction by deploying linear regression model and random forest regression model, so that the traffic regulators and map application companies can make their decision based on our prediction model for fewer congestions at tollgates and route recommendations. 

## Model
- Linear Regression
- Random Forest Regression
- Xgboost

## Conclusion
Accurately measuring travel time can help predict congestions in the road network. Such information could be valuable to traffic operators and policy makers. In this study, our models fail to beat the baseline. While this is discouraging, we do investigate the problem and find ways to improve our models in the future. We believe that we should generate more features that have stronger predictive power. Specifically, more features that can accurately capture  traffic condition and route network should be incorporated into the models.

Dataset and description can be found and downloaded [here](https://tianchi.aliyun.com/dataset/dataDetail?dataId=60).
