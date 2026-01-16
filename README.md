# Health-Related-911-Calls-in-Portland-A-Spatial-and-Temporal-Analysis-

Health-Related 911 Calls in Portland
Spatial, Temporal, and Timeliness Analysis (2025)
### Project Overview

This project analyzes health-related 911 calls in Portland using public emergency dispatch data. The goal is to understand when and where health-related emergencies occur and how emergency response timeliness varies by call type and priority level. This analysis focuses on descriptive patterns that reflect real-world emergency demand and system behavior.

### Data Source

The dataset is sourced from the Portland Bureau of Emergency Communications (BOEC) Open Data Portal and contains detailed information on 911 dispatched calls in 2025, including call type, priority level, response time components, and geographic indicators.

### Key Questions

- When do health-related 911 calls most frequently occur, and how do patterns differ between weekdays and weekends?

- Where are health-related 911 calls most concentrated across Portland neighborhoods?

- Do different types of health-related calls experience different response times?

- How do queue, travel, and total response times vary by priority level?

### Methods

- Filtered calls using the IsHealthRelated classification to focus on health-related incidents.

- Conducted temporal analysis by hour of day and weekday vs. weekend.

- Examined spatial distribution using geographic coordinates and neighborhood-level aggregation.

- Analyzed response timeliness by decomposing total response time into queue time and travel time.

- Used summary statistics (medians) and visualizations (line plots, boxplots, and density maps) to compare patterns across groups.

### Key Findings

- Health-related 911 calls follow consistent daily patterns, with lowest volume in early morning hours and peaks in the late afternoon and evening. The temporal distribution of calls is highly similar between weekdays and weekends. While total call volume is slightly lower on weekends, the overall hourly shape remains consistent, suggesting stable underlying demand rather than workday-specific effects.
  
  <img width="900" height="391" alt="Screenshot 2026-01-15 at 6 13 03 PM" src="https://github.com/user-attachments/assets/36b10216-36de-4f51-b4ac-a6d9dbd6131f" />
  <img width="870" height="398" alt="Screenshot 2026-01-15 at 6 13 12 PM" src="https://github.com/user-attachments/assets/1900fee4-f8af-4616-b578-ca2d1c299cbc" />


- Spatial clusters are concentrated in central and western parts of Portland, indicating geographic variation in acute healthcare demand.
  
  <img width="641" height="636" alt="Screenshot 2026-01-16 at 12 44 05 PM" src="https://github.com/user-attachments/assets/01722a45-1a7a-4125-ba5b-a1429a6cea2c" />

- Response times differ by call type: behavioral health calls tend to be handled more quickly, while missing person calls show longer and more variable response times.
  
  <img width="679" height="419" alt="Screenshot 2026-01-15 at 7 33 33 PM" src="https://github.com/user-attachments/assets/2cd37c1d-ed43-4a31-bca4-becab9a7d2d9" />

- Differences in total response time across priority levels are primarily driven by queue time rather than travel time, reflecting dispatch prioritization rather than geographic distance.
  
  <img width="731" height="397" alt="Screenshot 2026-01-15 at 7 50 33 PM" src="https://github.com/user-attachments/assets/9a2b9794-f280-4e1d-b5d1-c7a61d649dc6" />


Notes

This project emphasizes decision-relevant analysis under real-world data constraints. Findings should be interpreted in the context of emergency dispatch workflows and data limitations, particularly for call types with incomplete geographic information.
