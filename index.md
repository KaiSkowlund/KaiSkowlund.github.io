# Undergraduate Univerity of Colorado Boulder
<div style="text-align: center;">
  <img 
    src="/img/nz.jpg" 
    alt="Mt. Cook!" 
    width="60%" 
    style="background-color: #fff; 
    padding: 8px; 
    border: 1px 
    solid #ddd; 
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);"
  />
  <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 8px; color: #555;">
    Me at Mt. Cook during my study aboard in New Zealand. 
  </figcaption>

</div>


    
## Contact Information:

- KaiSkowlund@colorado.edu

- [LinkedIn](https://www.linkedin.com/in/kai-skowlund-0a5158358/)

- [GitHub](https://github.com/KaiSkowlund)

- [Instagram](https://www.instagram.com/kai.skowlund/)


## About Me!
I am a fourth-year Geography student at CU Boulder specializing in spatial analysis, remote sensing, and geospatial programming. My work focuses on turning complex geographic data into actionable insights through Python-based automation, machine learning, and modern GIS workflows. I am actively seeking internship and entry-level opportunities with federal agencies, environmental consulting firms, and organizations where spatial thinking drives real decisions.

I'm originally from Durango, Colorado and moved out to Boulder in 2022 to begin my Undergraduate program. I'm an avid outdoorsman, in my freetime you can find me enjoying some fly fishing, kayaking, climbing, or possibly hiking up the next 14er on the bucket list!

I'm excited to improve my python skills in GIS applications in this Earth Data Science course. I'm specifically interested in satellite imagery classification using learning algorithms, as well as creating maps related to resource management. Recently, I have become very interested in forestry and wildfire vulnerability approaches, so I'm hoping to pick up some skills to make me more efficient those type of projects.
Id like to find out how the skills I learn in this course will complement my other skills using GIS software and analyzing imagery. I'm looking to bridge the gap between using the manual tools in ArcGIS Pro and more efficient open source python tools, and the ArcPy module itself in ArcGIS Pro.  

Id like to answer questions about wildfire vulnerability in the Front Range. I'm very interested in mapping and predicting areas of high fuel concentration or optimal conditions for wildfire ignition,  in areas where structure has a high risk of being impacted. After the Marshal Fire in Dec. 2021, and seeing the costly impact on the Superior/Broomfield area, I have been very interested in mitigation and risk management efforts people can take into the future. 


## Map of CU Boulder
<figure style="text-align: center;">
  <embed 
    type="text/html" 
    src="img/boulder.html" 
    width="100%" 
    height="500px" 
    style="border: 1px solid #ddd; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);"
  />
  <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 8px; color: #555;">
    CU Boulder has been my home and place of study for the last 4 years. It is very meaningful to me and my work!
  </figcaption>
</figure>

## Project: Climate Change in Durango, Colorado

Since I grew up in Durango, I analyzed how temperatures in the area have changed over the past century. I used daily temperature records from NOAA's Global Historical Climatology Network for the **Fort Lewis** weather station (USC00053016), located about 11 miles west of Durango.

### Daily Temperatures

<figure style="text-align: center;">
  <img
    src="/img/daily_temp_c.png"
    alt="Daily temperature at Fort Lewis, CO"
    width="90%"
    style="background-color: #fff; padding: 8px; border: 1px solid #ddd; box-shadow: 0 4px 6px rgba(0,0,0,0.1);"
  />
  <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 8px; color: #555;">
    Daily average temperature (°C) at the Fort Lewis station, calculated from each day's maximum and minimum temperatures.
  </figcaption>
</figure>

This plot shows every daily temperature in the record. The repeating peaks and valleys are the seasonal cycle: summer highs near 30°C and winter lows well below freezing. Gaps are periods when the station didn't report data. With this much day-to-day and seasonal variation, a long-term trend is hard to see in daily data alone, so the next step averages the data by year.

### Long-Term Warming Trend

<figure style="text-align: center;">
  <img
    src="/img/annual_temp_trend.png"
    alt="Annual mean temperature trend at Fort Lewis, CO"
    width="90%"
    style="background-color: #fff; padding: 8px; border: 1px solid #ddd; box-shadow: 0 4px 6px rgba(0,0,0,0.1);"
  />
  <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 8px; color: #555;">
    Annual mean temperature (°C) with an ordinary least squares (OLS) line of best fit. Only years with at least 330 days of data were included so incomplete years didn't skew the averages.
  </figcaption>
</figure>

The line of best fit shows an average change of about **0.0141 °C per year**, or roughly **1.41 °C per century**. [Describe the direction, e.g., "Temperatures in the Durango area have warmed over the period of record, with many of the warmest years occurring recently."] This is consistent with statewide trends: Colorado has warmed about 2.5°F since the early 1900s, and six of its eight warmest years on record have occurred since 2012 (Frankson et al., 2022).

Warmer temperatures matter a lot for southwest Colorado. They mean less snowpack, earlier runoff in the Animas River, and drier conditions that raise wildfire risk, all issues I care about as a GIS student focused on natural resources and wildfire.

**Data source:** NOAA National Centers for Environmental Information, Global Historical Climatology Network – Daily, station USC00053016 (Fort Lewis, CO).

**Reference:** Frankson, R., Kunkel, K. E., Stevens, L. E., Easterling, D. R., Umphlett, N. A., Stiles, C. J., Schumacher, R., & Goble, P. E. (2022). *Colorado state climate summary 2022* (NOAA Technical Report NESDIS 150-CO). NOAA/NESDIS. [https://statesummaries.ncics.org/chapter/co/](https://statesummaries.ncics.org/chapter/co/)




  





