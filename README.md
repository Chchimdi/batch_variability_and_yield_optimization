Lot_Variability_Project_Data.csv

Description:
This dataset is designed for a Lot Variability Analysis and Yield Optimization project in semiconductor manufacturing.
It contains data on different batches (lots) of wafers, focusing on key process parameters, machine conditions, and outcomes
like yield and defect rates. The dataset is intended for use in identifying lot-to-lot variability, analyzing key factors affecting
wafer yield, and building predictive models for defect detection and process optimization.

Columns and Descriptions:
Lot_ID:

Description: Unique identifier for each batch of wafers (lot) that undergoes the manufacturing process.
Type: Integer
Wafer_ID:

Description: Unique identifier for each individual wafer within a lot.
Type: Integer
Etching_Temperature_C:

Description: Temperature during the etching process (in degrees Celsius).
Type: Float
Doping_Time_s:

Description: Time spent in the doping process (in seconds).
Type: Float
Chemical_Concentration_ppm:

Description: Concentration of chemicals used during the manufacturing process (in parts per million).
Type: Float
Pressure_Pa:

Description: Pressure applied during different stages of the manufacturing process (in Pascals).
Type: Float
Yield_Percentage:

Description: Yield of functioning chips per wafer (as a percentage). This represents the percentage of wafers in the lot that meet the required quality specifications.
Type: Float
Defect_Count:

Description: Number of defects identified on each wafer.
Type: Integer
Failure_Rate:

Description: Binary indicator of whether a wafer failed to meet the required quality standards.
Type: Integer (0 = no failure, 1 = failure)
Machine_Age_days:

Description: The age of the equipment/machine used in the manufacturing process (in days).
Type: Integer
Task_Status:

Description: Status of the manufacturing task or process step.
Type: String (e.g., 'Completed', 'In Progress', 'Delayed')
Operating_Hours:

Description: Total number of hours the machine has been in operation during the process.
Type: Float
Vibration_magnitude:

Description: The magnitude of vibration detected in the equipment during the process (in arbitrary units).
Type: Float

Usage:
Lot-to-Lot Variability Analysis: Explore variability across different lots and wafers, identifying key factors that affect yield and defect rates.
Predictive Modeling: Build machine learning models to predict wafer failures (Failure_Rate) or yield percentage based on process parameters.
Process Optimization: Analyze which parameters (e.g., etching temperature, doping time) can be optimized to reduce defects and improve yield.
Statistical Process Control (SPC): Use control charts and SPC techniques to monitor and control variations in the manufacturing process.
Predictive Maintenance: Use machine-related data (e.g., Operating_Hours, Vibration_magnitude, Machine_Age_days) to develop predictive maintenance models.
