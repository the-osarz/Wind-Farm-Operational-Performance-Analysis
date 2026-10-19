# Wind Farm Operational Performance Analysis

## Project Overview

This project explores wind turbine operational performance using a simulated dataset representing six turbines at a wind farm referred to as North Ridge Wind Farm.

The analysis investigates how operational and environmental variables relate to power output and capacity factor. The goal is to identify performance patterns, compare differences between turbines, and understand why no single indicator necessarily explains overall performance.

**Dataset note:** The data used in this project is simulated for analytical practice. It does not represent verified operational records from a real wind farm.

## Objectives

- Examine the relationship between turbine availability and power output.
- Investigate how wind speed relates to power output.
- Explore operational and environmental factors associated with capacity factor.
- Compare turbine downtime with power output.
- Explore potential relationships between temperature, wind direction, and turbine performance.

## Tools Used

- Microsoft Excel — data exploration and analysis.
- Microsoft Power BI — dashboard development and visualisation.

## Key Findings

- **Availability and output:** Higher availability did not consistently correspond to higher power output across all turbines.
- **Wind speed and output:** Turbines with relatively higher average wind speeds generally recorded high output, although differences between turbines were not fully explained by wind speed alone.
- **Capacity factor:** Differences in capacity factor suggest that downtime alone may not explain turbine performance.
- **Downtime and output:** The turbine with the lowest average downtime did not record the highest average power output.
- **Environmental variables:** The analysis did not establish that temperature or wind direction alone explained differences in turbine performance.

These findings are exploratory and describe patterns in the simulated dataset; they should not be interpreted as proof of causation or as conclusions about real wind farm operations.

## Analytical Approach

The project was structured around five hypotheses. Average turbine performance indicators were compared to investigate potential relationships between operational conditions, environmental variables, and power output.

The findings were interpreted by considering where the observed patterns supported the hypotheses and where other variables might also be relevant.

## Limitations

- The dataset is simulated rather than sourced from a real operating wind farm.
- The analysis covers six turbines, limiting the conclusions that can be drawn.
- Differences in turbine rated capacity, measurement definitions, and other technical factors would need to be verified before making stronger comparisons.
- Further statistical testing and additional operational data would be required to assess the strength of the observed relationships.

## Project Files

- `data/` — dataset and Excel workbook.
- `dashboard/` — Power BI dashboard.
- `documentation/` — hypotheses and written analysis.
- `images/` — dashboard preview image.

## Conclusion

This project demonstrates an exploratory approach to renewable energy performance analysis, focusing on turbine-level comparisons, operational indicators, and the interpretation of findings. It also highlights the importance of considering multiple variables and acknowledging data limitations when drawing conclusions about energy asset performance.