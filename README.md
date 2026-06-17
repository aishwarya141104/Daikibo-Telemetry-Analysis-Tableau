# Daikibo Telemetry Analysis using Tableau

## Project Overview

This project analyzes telemetry data collected from four Daikibo factories during May 2021 using Tableau.

### Factories Analyzed

* Daikibo Factory Meiyo (Tokyo, Japan)
* Daikibo Factory Seiko (Osaka, Japan)
* Daikibo Berlin (Berlin, Germany)
* Daikibo Shenzhen (Shenzhen, China)

## Objectives

1. Identify which factory experienced the most machine downtime.
2. Determine which machine types contributed most to the downtime.

## Tools Used

* Tableau Desktop
* JSON Dataset

## Analysis Steps

* Imported telemetry JSON data into Tableau.

* Created a calculated field named **Unhealthy**:

  IF [Status] = "unhealthy" THEN 10 ELSE 0 END

* Built a bar chart for downtime per factory.

* Built a bar chart for downtime per device type.

* Created an interactive dashboard with factory-based filtering.

## Results

* Factory with highest downtime: **Daikibo Factory Seiko (Osaka, Japan)**
* Device type with highest downtime: **LaserWelder**
* Total downtime: **480 minutes**

## Dashboard Screenshot
<img width="1920" height="1020" alt="Dashboard" src="https://github.com/user-attachments/assets/4ebff5bb-c6c7-4e97-a61f-21b4dbc44135" />



## Conclusion

The analysis shows that Daikibo Factory Seiko experienced the highest downtime during May 2021, with LaserWelder machines contributing the most downtime.
