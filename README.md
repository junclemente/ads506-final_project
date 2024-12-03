# ADS 506 - Applied Time Series Analysis Final Project

# Installation

To setup and run this project, please follow these steps:

1.  Clone the repository.

2.  Using RStudio, navigate to the project directory.

3.  Open the project file.

# Project Intro / Objective

Our goal is to address real-world challenges faced by the San Diego County Humane Society. Through this project we aim to generate actionable insights that can support staffing decisions, ultimately enhancing the Humane Society’s capacity to respond to animal emergencies.

# Contributors

## Team 1:

-   [Graham Ward](https://github.com/gw-00)
-   [Jun Clemente](https://github.com/junclemente)
-   [Sasha Libolt](https://github.com/slibolt)

# Methods Used

-   Exploratory Data Analysis (EDA)
    -   Categorical Variables
    -   Continuous Variables
    -   Time Series
-   Data Cleaning and Preprocessing
-   Modeling
    -   ACF Plots
    -   PACF Plots
-   Data Partitioning
    -   Seasonal Naïve
    -   Auto ARIMA
    -   Seasonal Auto ARIMA
    -   Auto ARIMA with external factors
    -   Seasonal Auto ARIMA with external factors

# Technologies

-   R
    -   tidyverse
    -   fpp3
    -   gt
    -   tseries
    -   skimr
    -   scales
    -   gridExtra
-   R Studio
-   Google Colab
-   Github

# Project Description

This project uses call log data from the San Diego County Humane Society’s Humane Law Enforcement (HLE) dispatch center. San Diego County citizens contact the dispatch center for animal-related emergencies. Dispatchers triage each call, assign a priority level, and determine the necessary response. Our objective is to forecast staffing demand to enable optimized workforce planning for peak seasons. The current dispatch team consists of 20 employees, with a mix of full and part time roles. Accurate demand forecasting would allow the Humane Society to adjust staffing levels seasonally or explore temporary hiring to ensure prompt and efficient responses during peak periods.

## Data Dictionary


- Start Time (Timestamp): Start of interaction 
- End Time (Timestamp): End of interaction
- Communication Type (Categorical): Communication type
- Sub-Communication Type (Categorical): Sub-Communication type
- Wait Time (Continuous): Time between communication start and connecting with dispatcher (seconds)
- Time Interactive (Continuous): Length of time for communication (seconds)
- Hold Time (Continuous): Length call was on hold (seconds)
- Wrap Up Time (Continuous): After call time to put in notes (seconds)

# License

MIT License

Copyright (c) 2024 Graham Ward, Jun Clemente, Sasha Libolt

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Acknowledgements

[San Diego Humane Society](https://www.sdhumane.org/)
