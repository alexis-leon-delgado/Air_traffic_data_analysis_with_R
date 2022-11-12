# Air_traffic_data_analysis_with_R

The aim of this work is to manipulate air transport data efficiently. The implemented features are:

1. Detect rerouted flights. These are those flights where the airport of arrival in the planned route is different from the airport of arrival in the actual route.

2. Analyse delays and deviations of non-rerouted flights, in distance and time. The delay of a flight is equal to the difference between the actual and the planned arrival time, as long as it is positive. If the difference is negative or zero, the delay is zero. The distance deviation of a flight is equal to the difference between the actual distance traveled and the planned distance, as long as it is positive. If the difference is negative or zero, the distance deviation is equal to zero. All average delay and deviation values are flight averages.
