## Indonesian Earthquake

Earthquakes are natural phenomena that have significant impacts on human societies and the environment. Understanding the patterns and characteristics of earthquake occurrences is crucial for disaster preparedness, risk mitigation, and the development of resilient communities. In this project, we explore earthquake data sourced from the Earthquake Repository managed by BMKG (Indonesian Meteorology, Climatology, and Geophysical Agency), an authoritative organization responsible for monitoring seismic activities in Indonesia.

This dataset originates from the Earthquake Repository managed by BMKG, an Indonesian non-departmental government agency. BMKG underwent a redesign of their website in early 2023, resulting in two distinct datasets. The new dataset is sourced from the Preliminary Earthquake Catalog, which incorporates focal mechanism data. It encompasses earthquake event records from November 1, 2008, to December 15, 2023, although the accuracy of some of the latest recorded earthquake events may vary.

In this project, our objective is to analyze and explore the earthquake data to uncover insights into earthquake patterns, characteristics, and their relationships with geographical locations. Specifically, we aim to address several key questions, including:

1. How do earthquake occurrences vary over time based on date, month, and year?
2. Is there a correlation between the depth of earthquakes and the magnitude of earthquakes?"
3. What influence do geographical locations have on the depth and magnitude of earthquakes?
4. Are there any seasonal patterns or trends in earthquake magnitudes over time?

By addressing these questions, we aim to contribute to the understanding of seismic activities, enhance disaster preparedness efforts, and support decision-making processes for mitigating earthquake risks in Indonesia and beyond.

# Objective

1. Analyze the temporal variation of earthquake occurrences based on date, month, and year to identify trends and patterns in seismic activity over time.
2. Investigate the correlation between the depth of earthquakes and the magnitude of earthquakes to determine if there is a relationship between these two factors.
3. Assess the influence of geographical locations on the depth and magnitude of earthquakes to understand how different regions are affected by seismic events.
4. Identify seasonal patterns or trends in earthquake magnitudes over time to determine if there are recurring patterns in seismic activity related to specific seasons or periods.

# Data

This dataset is obtained from the Earthquake Repository managed by BMKG (the Indonesian Meteorology, Climatology, and Geophysical Agency), a non-departmental government agency. BMKG underwent a redesign of their website in early 2023, resulting in the creation of two distinct datasets.

The variables included in this dataset are as follows:

- `tgl`: Date of the event
- `ot`: Timestamp of the event
- `lat`: Latitude of the event epicenter, measured in degrees, ranging from 6N to 11S
- `lon`: Longitude of the event epicenter, measured in degrees, ranging from 142E to 94E
- `depth`: Depth of the event, measured in kilometers
- `mag`: Magnitude of the event, ranging from 1 to 9.5
- `remark`: Flinn-Engdahl regions of the event

Additionally, there is additional data such as magnitude level, and dates will be broken down into day, date, month, year, and hour. These are the variables available in this earthquake dataset.

source:
- https://www.kaggle.com/datasets/kekavigi/earthquakes-in-indonesia/data
- https://bobo.grid.id/read/083582947/mengapa-gempa-dangkal-lebih-merusak-dan-berbahaya-dibandingkan-gempa-lainnya?page=all
- https://www.idntimes.com/news/indonesia/rochmanudin-wijaya/mengenal-sejarah-warna-hingga-arti-skala-mmi-untuk-gempa-bumi

