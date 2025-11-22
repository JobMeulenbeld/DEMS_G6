# General battery control papers

## Effect of Daily Forecasting Frequency on Rolling-Horizon-Based EMS Reducing Electrical Demand Uncertainty in Microgrids. 
The effect of forecasting on EMS planning in general.
https://www.mdpi.com/1996-1073/14/6/1598#:~:text=With%20regard%20to%20microgrids%2C%20forecasting,robust%20and%20reliable%20methods%2C%20according

## Multi-Objective Optimized Operation of Energy Storage Devices. 
Shows how a single battery can be divided into “virtual storage devices,” each serving its own objective (e.g., peak shaving, market participation). Useful for understanding multi-use battery operation.
[Multi-Objective_Optimized_Operation_of_Energy_Storage_Devices](./Multi-Objective_Optimized_Operation_of_Energy_Storage_Devices.pdf)

## Forecast the Grid-Oriented Battery Operation to Enable a Multi-Use Approach
This paper uses forecasting to determine the free flexibility of a battery: when it must serve grid purposes and when it can be used for other objectives (market/system services). A good example of forecast-based multi-use strategies. [forecast-the-grid-oriented-battery-operation](./nykamp-et-al-2017-forecast-the-grid-oriented-battery-operation-to-enable-a-multi-use-approach-and-discussion-of-the.pdf)

## Effect of Daily Forecasting Frequency on Rolling-Horizon-Based EMS Reducing Electrical Demand Uncertainty in Microgrids
This paper investigates how often an EMS should update its forecasts within the day. Although it deals with power profile forecasts, its findings are relevant: updating forecasts more frequently (up to every half-hour) improved the EMS’s ability to follow the planned grid exchange profile, thereby reducing demand uncertainty.
https://www.mdpi.com/1996-1073/14/6/1598#:~:text=In%20this%20paper%2C%20different%20update,the%20considered%20case%20study%20for

# More specific to our case
## Fill-Level Prediction in Online Valley-Filling Algorithms for EV Charging
Introduces the fill-level concept: instead of forecasting full load profiles, the algorithm predicts a single scalar that represents an optimal charging profile. Highly relevant for the idea of forecasting aggregated metrics rather than detailed power trajectories.
[Fill-level_prediction_in_online_valley-filling_algorithms_for_electric_vehicle_charging](./Fill-level_prediction_in_online_valley-filling_algorithms_for_electric_vehicle_charging.pdf)

## Optimizing Electric Vehicle Charging Through a Real-Time Control Mechanism
Combines predictive scheduling with a real-time control layer that adjusts based on deviations in PV or demand.
A key insight: although minute-by-minute charging power is uncertain, the total energy requirement (kWh) of an EV is known.
This allows the controller to adapt EV charging power in real time while still meeting energy deadlines. This concept may translate to battery energy forecasting.
[Optimizing_Electric_Vehicle_Charging_Through_A_Real_Time_Control_Mechanism-15](./Optimizing_Electric_Vehicle_Charging_Through_A_Real_Time_Control_Mechanism-15.pdf)

## Forecast-based Energy Management Systems
Here they developed a predictive EMS for a PV-battery home system that explicitly uses day-ahead and even two-day-ahead energy forecasts in its optimization logic. Their approach was twofold: (a) a fuzzy logic EMS that adjusts battery charging in real-time using the next day’s kWh forecast, and (b) a day-ahead optimization (MILP) that plans battery and energy exchange for the next 24–48 hours.
https://www.academia.edu/144946938/Forecast_based_Energy_Management_Systems#:~:text=by%20storing%20the%20following%20day%27s,stored%20to%20supply%20load%20during

## Practical Validation of Multi-Objective Battery Control (Layered Control)
Demonstrates a layered EMS structure using a forecasted flexibility volume, and a real-time safety/constraint layer.
Highly relevant for thinking about how an EMS could use an energy forecast safely and effectively.
[Practical_Validation_of_Multi_Objective_Battery_Control-2](./Practical_Validation_of_Multi_Objective_Battery_Control-2.pdf)
