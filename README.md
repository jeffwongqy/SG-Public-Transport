# Singapore Public Transport Infrastructure Expansion & Ridership Performance

<img width="770" height="480" alt="Shutterstock_600492917" src="https://github.com/user-attachments/assets/76241deb-d729-4ca3-a451-97f0f69dacdd" />


## Introduction 

Singapore’s public transport network serves as the backbone of urban mobility, relying on continuous infrastructure development to meet growing commuter demand. Using official longitudinal data from Public Transport Operation and Ridership (Annual) on data.gov.sg, this dashboard investigates a central question: How has Singapore’s public transport infrastructure expansion influenced commuter ridership growth and modal share across MRT, LRT, and public buses?   

To answer this, the analysis explores five key dimensions of network performance:

## 1. Long-Term Ridership Trends: Tracking year-over-year changes in average daily ridership across MRT, LRT, and buses.

<img width="1187" height="495" alt="BQ1" src="https://github.com/user-attachments/assets/78082504-c295-4d3d-a4c1-100e71888170" />

**Insights:**
- In 2024, daily MRT trips grew to 3.41 million, which beats its 2019 peak of 3.38 million. In contrast, daily bus trips reached 3.84 million in 2024, remaining about 6% below their 2019 peak of 4.10 million. For the business, this means operators should focus on expanding train capacity and station retail, as commuters strongly favor rail for post-pandemic travel.
- Between 2014 and 2024, daily MRT ridership grew by roughly 23% (from 2.76 million to 3.41 million), while bus ridership stayed nearly flat (growing only 2% from 3.75 million to 3.84 million). For the business, this shows that buses are shifting from a primary travel mode to a feeder service, meaning bus routes should be redesigned to connect neighborhoods directly to MRT stations rather than competing with rail lines.

## 2. Operational Rail Capacity: Comparing annual kilometres operated between heavy rail (MRT) and light rail (LRT) systems across recent years.

<img width="1189" height="495" alt="BQ2" src="https://github.com/user-attachments/assets/b150e5cc-a290-4f37-b5cb-4fdd5137f998" />

**Insights:**
- Between 2016 and 2025, total MRT operations rose by about 39% from 34.2 million to 47.6 million train-kilometres, whereas LRT operations grew by only 14% from roughly 6.8 million to 7.7 million car-kilometres. For the business, this rapid network expansion increases long-term maintenance expenses and requires higher budget allocations for MRT spare parts and engineering staff.
- In 2025, MRT distance operated (47.6 million kilometres) was more than six times larger than LRT distance operated (7.7 million kilometres), accounting for roughly 86% of all combined rail kilometres. For the business, this means core financial performance, energy consumption, and service reliability targets are heavily driven by MRT operations rather than LRT feeder lines.


## 3. Current Modal Share: Examining the proportional breakdown of daily passenger journeys across MRT, LRT, and buses in 2025.

<img width="844" height="475" alt="BQ3" src="https://github.com/user-attachments/assets/5674e2cc-0cb4-49dc-88a7-c4a2b64962f8" />

**Insights:**
- Public buses capture 50.9% of daily ridership, which is 4.6 percentage points higher than MRT at 46.3%. For the business, this shows that bus networks remain the backbone of daily commuting, meaning fleet reliability and driver retention are critical for maintaining overall fare revenue.
- Combined, public buses (50.9%) and MRT (46.3%) account for 97.2% of all daily trips, leaving LRT with just a 2.8% share. For the business, this indicates that LRT systems serve purely as localized first- and last-mile connectors, so resource allocation and commercial advertising investments should heavily prioritize high-traffic MRT interchanges and bus hubs.


## 4. Bus Ridership Distribution: Analyzing the historical frequency and spread of daily public bus ridership levels across all recorded years.

<img width="1056" height="495" alt="BQ4" src="https://github.com/user-attachments/assets/fb4ea132-d012-4fc6-974a-4667b7087baa" />

**Insights:**
- Out of 31 total recorded years, 16 years (about 52%) saw daily bus ridership fall between 2.78 million and 3.22 million trips, with the single largest cluster of 10 years sitting between 3.00 million and 3.22 million. For the business, this shows that baseline bus demand remains consistently strong at around 3 million daily riders, giving operators a reliable floor for base fleet planning and recurring fare revenue.
- Daily ridership exceeded 3.66 million trips in only 9 years (about 29%), compared to the 22 years (71%) that stayed below 3.66 million. For the business, this means peak passenger volumes occur only during high-growth periods, so operators should use flexible scheduling and modular bus deployment to manage peak demand without over-investing in permanent fleet capacity.

## 5. Infrastructure-to-Demand Impact: Evaluating the correlation between physical rail length expansion and MRT ridership growth over time.

<img width="1368" height="495" alt="BQ5" src="https://github.com/user-attachments/assets/e3b9869a-121e-4083-987a-749201460fd1" />

**Insights:**
- The scatter plot demonstrates a strong positive relationship ($r = 0.917$), where longer rail lengths (scaling up to 272 km) successfully scale average daily MRT ridership to a peak of nearly 3.48 million trips. For the business, this means that strategic capital investments in new line extensions yield predictable, high-volume passenger growth and increased farebox returns.
- Despite having extended rail networks of 230 to 260 km, certain periods experienced significantly lower ridership ranging between 2.0 and 2.7 million daily trips. For the business, this indicates that infrastructure growth is vulnerable to external macro shocks, requiring adaptive operational planning to sustain revenue during unexpected crises.

## References
[1] Singapore Department of Statistics. (2024). Public Transport Operation And Ridership, Annual (2026) [Dataset]. data.gov.sg. Retrieved November 18, 2026 from https://data.gov.sg/datasets/d_ba615ec4cc5d9f5b7800ad82057f36f1/view
[2] Land Transport Authority. (2015). Public Transport Utilisation - Average Public Transport Ridership (2025) [Dataset]. data.gov.sg. Retrieved November 18, 2026 from https://data.gov.sg/datasets/d_75248cf2fbf340de6a746dc91ec9223c/view
