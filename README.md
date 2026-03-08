# CGMacros Glucose Peak Analysis

This notebook analyzes the continuous glucose monitoring (CGM) data for **patient CGMacros-003** on **2020-03-15** using the CGMacros dataset from PhysioNet.

## Objective

Plot the glucose curve for the selected day and identify major glucose peaks.

## Approach

1. Load and inspect the CGMacros dataset.
2. Convert timestamps and filter data for the target date.
3. Use the **Libre GL** signal as the primary glucose measurement.
4. Visualize the glucose curve across the day.
5. Detect major peaks using `scipy.signal.find_peaks`.

## Output

The notebook produces:

- A full-day glucose curve visualization
- Detected major glucose peaks highlighted on the chart
- A short reflection on the analysis process

## Dataset

CGMacros dataset from PhysioNet:  
https://physionet.org/content/cgmacros/1.0.0/
