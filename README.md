# Analysis-of-high-street-vacancy-rates

### Problem Statement:
Vacancy rates provide insights into the economic health of specific property types or classes, such as retail. However, assessing these rates in isolation can be misleading. For instance, a surge in retail vacancy rates might be mistakenly attributed to specific industry shifts, such as e-commerce growth. But, in fact, it might reflect wider economic trends that impact all property classes. A solution is to create a relative vacancy rate ratio that benchmarks vacancies for a property class of interest against a local average.

### Dataset:
This project utilises a **simulated dataset** inspired by vacancy patterns observed in three major UK cities (Bristol, London, and Manchester) across  residential, commercial, high-street retail, and industrial property.

### Methodology:

1. **Feature Engineering**: The vacancy data is enriched with broader economic indicators to offer a comprehensive view of market dynamics. Specifically, I introduce a relative vacancy ratio. This ratio benchmarks the vacancy rates of specific property classes against a local average.

3. **Analysis & Modelling**: I model how the relative vacancy rate responds in each when exposed to an economic shock.

### Results:

![Final Plot](final_plot.png)
The final output of the script displays changes in the relative high-street vacancy rates in three cities in response to an economic shock. The relative high-street vacancy rate, expressed as a ratio, was calculated separately for each city by dividing high-street property vacancy rates by the mean vacancy rates of all other asset classes
