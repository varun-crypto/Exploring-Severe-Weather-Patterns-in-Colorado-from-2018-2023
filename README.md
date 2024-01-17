# Exploring Severe Weather Patterns in Colorado From 2018-2023

# Introduction:
Severe weather events pose significant challenges to communities, infrastructure, and public safety. In the context of Colorado, a state known for its diverse geography and weather patterns, understanding the frequency and impact of severe weather occurrences is of paramount importance. This project delves into the comprehensive analysis of severe weather events within specific counties or zones in Colorado, aiming to shed light on their spatial distribution, frequency, and economic consequences.

In this project we start off with some data visualisation to find out the frequency of various severe weathers and after that we identify the percentage of property and crop damage caused due to severe weathers in Colorado. After this we find the variation of magnitude of most frequenlty occured weather event in counties of Denver, Boulder and EL Paso.

Later we move on to do some data analysis to identify the county or zone within Colorado that experiences the highest occurrence of severe weather events, determine the most frequently occurring types of severe weather in that area, and quantify the total property damage attributed to these events. Through data manipulation and insightful visualizations, we seek to provide a holistic perspective on the dynamics of severe weather, aiding in better preparedness, response, and mitigation efforts.

# Question of Interest:
"What is the spatial distribution of severe weather events within specific counties or zones in Colorado, and how can we determine which area experiences the highest frequency of severe weather occurrences, the most frequent types of severe weather events, and the total property damage caused by these events?"

# Dataset
The dataset was taken from the published public Storm Events Database by National Oceanic and Atmospheric Administration (NOAA). The data into this database was entered by NOAA's National Weather Service (NWS).

This dataset contains information of severe weather events occured in various zones and counties in the state of Colorado from 2018 to 2023. It contains information like the type of severe weather event, the begin and end locaiton of the event, property and crop damage caused by a particular event, deaths and injuried caused by the event. This dataset also contains the magnitude of severe weather event.

This dataset allows us to do examination on effect of severe weather events in Colorado.

This dataset has been uploaded to Github, so let's use the url and read it as a pandas dataframe.

# Results

### Visualizations

1. The frequency of various weather events in Colorado from 2018 - 2023

   <img width="599" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/c0b8a4b2-36e8-4148-b335-73673f111a8c">

From the graph we can see that Hail was the most common, followed by Winter Weather and High Wind. Heat, Excessive Heat, Dust Devil and Strong Wind were the rarest. The graph indicates the impact of climate change and the diversity of Colorado’s climate.

2. The percentage of property damage caused by each of the frequently occuring disasters

   <img width="620" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/ce8092d0-02e9-4dde-9e76-19194d993b88">

The pie chart reveals that wildfire was the most damaging severe weather event in Colorado, accounting for almost three-quarters of the total property damage. Hail was the second most damaging event, causing nearly one-fifth of the property damage. Debris flow was the third most damaging event, contributing to 5% of the property damage. Other types of severe weather events, such as flood, tornado, and winter storm, were negligible in terms of property damage, representing only 0.5% of the total.

3. Crop damage percentage by various severe weather events

   <img width="767" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/0489b453-ec79-45c0-8998-4e69562a3641">

   The pie chart reveals that frost/freeze was the most devastating severe weather event for crops in Colorado, causing 94.4% of the total crop damage. This indicates that Colorado’s agriculture is highly vulnerable to low temperatures and frost damage. The other types of severe weather events, such as flash flood, hail, thunderstorm wind, lightning, and tornado, were much less damaging for crops, accounting for only 5.6% of the total crop damage combined. This suggests that Colorado’s crops are more resilient to water and wind related events than to cold related events.

Plotting some visualisations for the variation in magnitude of Hail from 2018 to 2023 in Denver, Boulder and EL Paso counties in Colorado.

1. <img width="481" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/bbf93366-f62c-4f3d-b81a-3f5097d14976">

We can see from the graph that the magnitude of hail was highest in 2018 and 2023, reaching about 2 and 1.7 respectively. It also shows that the magnitude of hail was lowest in 2022, dropping to about 0.7. The graph suggests that there was a cyclical pattern of hail intensity in Denver, with peaks occurring every five years.

2. <img width="504" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/7b7f45d6-3484-4684-adf9-03f01d17e04d">

We can see from the graph that the magnitude of hail was highest in 2018, reaching about 3.0. It also shows that the magnitude of hail was lowest from 2020-2022 dropping to about 1.0. The graph indicates that there was a downward trend of hail intensity in Boulder from 2018 to 2020, followed by a consistant trend from 2020 to 2022 and upward trend from 2022 to 2023.

3. <img width="531" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/88611c3f-07f9-4c4f-b3e7-b2a886ffea7f">

We can see from the graph that the magnitude of hail was highest in 2018, reaching about 4.0. It also shows that the magnitude of hail was lowest and constant from 2021 to 2023, dropping to about 2.0. The graph suggests that there was a downward trend of hail intensity in El Paso from 2018 to 2021, followed by an constant trend from 2021 to 2023.

### Analysis

To start our analysis let's first find out which county/zone in Colorado has the highest severe weather occurrences.

<img width="490" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/c398798d-2cf7-4f42-834b-9397aa22b47e">

We found that El Paso county in Colorado has the highest number of severe weather occurrences.

Now let's check in El PASO which severe weather had the highest number of occurrences.

<img width="686" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/6f67a602-1ba2-44e9-8c2e-cc9a7adcd16e">

We can see that Hail had the highest number of occurrences in El Paso county.

<img width="579" alt="image" src="https://github.com/varun-crypto/Exploring-Severe-Weather-Patterns-in-Colorado-from-2018-2023/assets/69026838/971f55f3-35ad-465b-b3be-5abe495ed97a">

# Conclusion and Bias

We can see from the above analysis that El Paso county in Colorado is most prone to severe weather events, especially hail, which causes significant property damage. This implies that the residents of El Paso county should be prepared for hailstorms and take measures to protect their properties from hail damage. It also suggests that the climate of El Paso county is different from other counties in Colorado, which may have less frequent or less severe weather events.

However, it's important to consider potential biases in these conclusions. Firstly, the data might be limited in scope and not account for all severe weather events accurately. There could be underreporting or insufficient data collection for other types of severe weather incidents. Moreover, there could be bias in the data collection process itself, with variations in reporting or recording severe weather events across different regions and time periods.
