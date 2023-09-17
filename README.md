# Extract-Time-Series-Features
## Horizontal Visibility Graph and Natural Visibility Graph



### Introduction:
This project aims to extract time series features from human activity monitoring data collected from 15 subjects. The dataset includes accelerometer data for activities such as walking, running, climbing up, and climbing down. Two specific tasks will be performed to analyze and extract insights from this data.

### Model Objective:
1. **Task 1**: Applying a **Natural Visibility Graph (NVG)** and **Horizontal Visibility Graph (HVG)** to the accelerometer data, computing the average degree, network diameter, and average path length for each time series. The results will be tabulated, and scatter plots will be generated to visualize the relationship between average degree and network diameter, with points colored according to different activities.
2. **Task 2**: Focuses on computing permutation entropy and complexity for the accelerometer data, considering all three directions. Parameters like embedded dimension, embedded delay, and signal length will be varied, and scatter plots will be created to show the relationship between permutation entropy and complexity, with points colored based on different activities.

### Challenges Addressed:
This project addresses the challenges of feature extraction from time series data for human activity monitoring. It explores two graph-based methods and permutation entropy, providing insights into how these features can help distinguish between different activities. It also considers the impact of varying parameters on feature extraction.

### Model Documentation:
The project is implemented as a Python notebook, and detailed documentation of the code and methodology can be found in the notebook attached to the GitHub Repository. 
