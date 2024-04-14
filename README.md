# Statistics-for-Data-Science-
Unraveling Natural Forces: Climate Change Factors Beyond Human Influence


Introduction
I am currently watching a series on Netflix called Life on Our Planet. It mentions at times that right now only 1% of all species that have ever lived have made it to today, meaning that 99% of all species have gone extinct. Many times, it mentioned that there were mass extinctions brought on by some phenomenon. One such extinction was because of a drop in CO2, and another was because of an increase in CO2. I thought that humans were to blame for what is happening right now to the climate, but throughout the 4.5 billion years of Earth’s history it has mostly been the Earth causing its own demise on the living. I wanted to explore if there are other parts to climate change that we are not taking notice of.
Right now, climate change is an issue of paramount importance in today's world, with the potential to impact ecosystems, economies, and societies worldwide. While I acknowledge the substantial body of research that focuses on human-induced factors contributing to climate change, I also recognize a parallel narrative involving natural forces that significantly influence our planet's climate dynamics. This presents a crucial problem: I believe that understanding and distinguishing between natural climate change factors and human-induced ones is of great importance.
Why should I be interested in this dual-faceted perspective on climate change? Firstly, my interest lies in gaining an understanding of the natural forces impacting climate, which is essential for disentangling their effects from those of human activities. I find it crucial for more accurate modeling and prediction, which in turn informs mitigation and adaptation strategies. Secondly, I believe that investigating natural climate change factors is a quintessential data science problem. It's intriguing due to its inherent complexity and its dependence on robust data analytics.
In this context, I firmly believe that data science plays a pivotal role in deciphering the intricate relationship between natural climate forces and observed climate patterns. It allows me to harness large datasets encompassing diverse variables such as temperature, precipitation, and atmospheric compositions to extract insights, identify trends, and ultimately contribute to the development of proactive climate policies and sustainable practices.
Therefore, my exploration delves into a crucial data science challenge: analyzing and modeling the impact of natural factors on climate change. I believe this is essential, addressing why it matters, and highlighting the significance of this interdisciplinary approach in the broader fight against climate change. 
My specific interests are the movement of the poles, the number of sunspots on the sun, how much CO2 is being produced, and temperatures over time in general. 
Research Questions
1.	How has the Earth’s pole position over time correlates between Earth’s climate?
2.	Are there patterns or cycles in Earth's pole positions that can help us predict future movements and their climatic effects?
3.	Can it be proven that a correlation between variations in solar sunspots and fluctuations in Earth's climate over centuries could exist?
4.	How have variations in solar activity influenced historical climate patterns, and what insights can we gain for future climate predictions?
5.	What are the historical trends in volcanic CO2 emissions, and how do they compare to human CO2 emissions?
6.	Can we quantify the specific contribution of volcanic CO2 emissions to the overall atmospheric CO2 concentration and later climate effects?
7.	What are the key variables affecting the Earth's climate that are driven by natural forces, and how do they interact?
Approach
In my approach I will try to investigate this multifaceted problem statement surrounding “Unraveling Natural Forces: Climate Change Factors Beyond Human Influence.” It will involve the statistical analysis of various natural climate change factors and their impact on our environment.
I will start by gathering datasets on relevant climate variables, such as historical temperature records, solar activity, volcanic emissions, and historical pole positions.
I will conduct exploratory data analysis to better understand the distribution and characteristics of the data.
I will use my research questions as a guidepost while investigating the specific aspects of each natural climate change factor and its influence on Earth’s climate.
I will answer those questions by developing statistical models, including linear regression, multiple regression and logistic regression.
I will perform hypotheses tests to determine the statistical significance of relationships between the climate variables and their potential causal effects.
I will see if my predictive models help in predicting these natural factors change on future climate scenarios.
I will critically analyze my findings, assessing uncertainties in my model and the limitations of the data.
I will write notes on the results and include data visualizations and present my findings in a clear and concise manner.
I will share my findings with my teacher as it is part of my assignment as well as with my small LinkedIn connections.
I will use R and hopefully Python for the data analysis and modeling.
My goal is to use the skills and knowledge to tackle the complexity of these climate change factors. Proving that I have a strong foundation in data science using advanced statistical analysis.
How your approach addresses (fully or partially) the problem.
My approach overall, combines data collection, statistical analysis, hypothesis testing, predictive modeling, and critical evaluation to comprehensively investigate the natural climate change factors beyond human influence. It will show a rigorous and data-driven approach to understanding the complexities of climate change, contributing to the field of data science.
Data  (Minimum of 3 Datasets - but no requirement on number of fields or rows)
•	The movement of the poles: 
o	Speed of movement 1900 to 2020
https://en.wikipedia.org/wiki/North_magnetic_pole#/media/File:North_Magnetic_Pole_Speed.svg
o	Movement of the north pole from 1900 to 2020/2025
https://wdc.kugi.kyoto-u.ac.jp/poles/polesexp.html
o	Model prediction from 2020 to 2025 https://www.ngdc.noaa.gov/geomag/data/poles/WMM2020_NP.xy
Most of this data was uploaded by explorers searching out the magnetic north pole. Other data is predictions of where it will be. The other data is produced by the Graduate School of Science, Kyoto University in Kyoto Japan.
•	The number of sunspots on the sun:
https://www.sidc.be/SILSO/datafiles
This data is trying to show that with sun spots (cooler sun temperatures) the correlation between earth’s temperature.
•	How much CO2 is being produced by volcanoes: 
https://www.climate.gov/news-features/climate-qa/which-emits-more-carbon-dioxide-volcanoes-or-human-activities
This link had a source link that is no longer working. I will do more research to see what has happened. All sources say that this is a constant over time.
•	Temperatures over time in general:
https://www.weather.gov/media/slc/ClimateBook/Annual%20Average%20Temperature%20By%20Year.pdf

Required Packages
The required packages I believe I will need to use are dplyr, ggplot2, lubridate, Metrics, readxl, knitr, kable, possibly purr, & tinytex. 
Plots and Table Needs
I believe that I will need time series plots, histograms and density plots, box plots, scatter plots, heatmaps, regression plots, bar charts, tables, correlation matrices, ROC curves.
Questions for future steps
I have not learned the heatmaps, correlation matrices or ROC curves, but I plan to learn them as they will help identify patterns, provide insights into the relationships between variables, and illustrate the model’s performance in predicting binary outcomes.
How to import and clean my data
Data Acquisition
•	I started by downloading data from web sources as PDFs or Excel files.
•	Once I had the data, I opened it or copied it using Microsoft Excel for cleaning.
Data Cleaning in Excel
•	In Excel, I began by removing any empty rows or columns to maintain data integrity.
•	I ensured that the data was consistently formatted, correcting any discrepancies.
•	I organized the data in chronological order based on a "Year" column to facilitate analysis.
Import Data into R
•	To work with the cleaned data in R, I loaded the necessary libraries. For reading Excel files, I used the 'readxl' library.
•	I defined the file path to my cleaned data file.
•	I imported the data into R by reading the Excel file using the 'read_excel' function.
What does the final data set look like?
	The final data set looks like a merged data set where all columns are in line with the rows in the “Year” column.
Questions for future steps
	How could I use R more in the future? I think I could do more data cleaning in R, but Excel is something that I am more familiar with, so I went that route. I could practice with it more often with just random datasets and see what happens.
What information is not self-evident?
	I lack data from volcanoes. I encountered various challenges during my research as I was unable to find the required data due to broken web links and other accessibility issues. The data I was looking for was considered constant and did not change over time, which added to the difficulty of locating relevant information. Despite my efforts, sources and references consistently pointed back to a 1998 study, but unfortunately, no specific data sets were cited or made available for further analysis. It was mentioned that this type of change happens over tens of thousands of years. In light of these obstacles, it became evident that key information essential for my research was not readily accessible. 
This experience prompted me to reflect on the question, "What information is not self-evident?" In this context, the question serves as a foundation for understanding the challenges I faced. The broken web links and the lack of accessible data highlighted that not all relevant information is readily available or self-evident, emphasizing the importance of data accessibility, citations, and providing necessary context for research purposes. It underlines the significance of clear sourcing and available datasets to support and validate research efforts.
What are different ways you could look at this data?
Time Series Analysis – I'd delve into the historical trends, searching for patterns and cycles in average temperature and sunspot activity over the years to understand any long-term climate changes or cyclical behavior.
Correlation Analysis – I'd calculate the correlation coefficient to assess whether temperature and sunspot activity are related. If there's a positive correlation, I'd infer that higher sunspot activity might be associated with increased temperatures, and a negative correlation could suggest the opposite.
Data Visualization – Using charts and graphs, I'd visualize the data's distribution, aiming to spot trends or irregularities visually. For example, I might look for clusters or outliers in temperature and sunspot data.
Hypothesis Testing – To address specific questions, I'd set up hypotheses and conduct tests, seeking statistical significance. If, for instance, I wanted to test if sunspots influence temperature, I'd use hypothesis tests and p-values to determine if there's substantial evidence supporting my claims.
Forecasting – I'd explore forecasting models to predict future temperature and sunspot activity based on historical data. This can be invaluable for planning and decision-making in response to potential climate changes.
How do you plan to slice and dice the data?
I plan to perform time series analysis to identify long-term trends and patterns in temperature and sunspot data over the years. Additionally, I'll conduct correlation analysis to understand the relationship between these variables. Data visualization will be crucial to create informative charts and graphs to visualize the data's characteristics. I'll also employ hypothesis testing to check for statistical significance in these patterns and use forecasting techniques to predict future trends based on historical data. Slicing and dicing the data based on these methods will help gain insights into climate patterns and their association with sunspot activity.
How could you summarize your data to answer key questions?
To address the key questions related to Earth's climate and its correlation with various factors, I plan to adopt a comprehensive approach. Initially, I will calculate correlation coefficients to assess the relationship between Earth's pole positions and climate data over time. Employing time series analysis will help identify recurring patterns in pole positions and predict their future movements and potential climatic impacts. I will also employ statistical tests and modeling to explore potential correlations between solar sunspots and climate, aiming to gain a deeper understanding of their historical connections. Lastly, through regression analysis and correlation studies, I intend to identify and analyze key natural variables affecting Earth's climate and investigate their complex interactions. This multifaceted strategy will enable me to address the intricate questions surrounding Earth's climate dynamics.
What types of plots and tables will help you illustrate the findings to your questions?
Time Series Plots – These plots will help visualize trends and cyclical patterns in Earth's pole positions and climate variables over time.

Correlation Heatmaps – Heatmaps will show the strength and direction of correlations between different variables, providing insights into relationships among Earth's pole positions, climate factors, and solar sunspots.
Data Visualization Tables –Tables can summarize statistical measures and trends, making it easier to observe key findings.
Regression Plots – These will illustrate the relationships between solar sunspots and climate variables through regression lines and data points.
Do you plan on incorporating any machine learning techniques to answer your research questions? Explain.
I would like to, and I will try as I learn this more in my upcoming exercises. I know that doing some would help me with predictive modeling, pattern recognition, feature importance, classification, data visualization, dimensionality reduction, and model interpretability. 
Overall, I know machine learning can provide valuable insights, help build predictive models, and automate the analysis of large and complex climate datasets. It can aid in addressing my research questions and uncovering hidden patterns in the data, ultimately enhancing my understanding of Earth's climate and its driving forces.
Questions for future steps
As I look ahead, I see several important questions and future directions. One key aspect is expanding the analysis to include a wider range of natural variables, such as solar activity and volcanic emissions, to gain deeper insights into Earth's climate system. Additionally, refining predictive models and data quality will be a focus, along with interdisciplinary collaboration to address climate challenges effectively. Ethical considerations, including equity and environmental responsibility, will remain at the forefront of climate research efforts.
Introduction
Exploring the intricacies of climate change, I delve into Earth's dynamic history where natural forces have significantly shaped climatic patterns. Recognizing the planet's ability to undergo mass extinctions due to both drops and increases in CO2 levels, I wondered beyond the contemporary narrative centered on human-induced climate change. Amidst acknowledging human activities' undeniable impact, I am keen on unraveling the dual perspective that encompasses both natural forces and anthropogenic influences. This approach not only enriches our understanding of Earth's climate dynamics but also holds implications for developing accurate climate models and predictive tools.
This exploration extends beyond curiosity, addressing a critical data science challenge. By employing data science techniques on large datasets containing temperature, Magnetic North Pole movement, and sunspots, I aim to extract insights and contribute to proactive climate policies. My specific focus areas include the movement of poles, the correlation between sunspots and Earth's climate, and broader temperature trends. This journey into the intersection of natural climate forces and observed patterns is driven by a conviction that unraveling these complexities is indispensable for informed decision-making in the face of climate change, contributing meaningfully to global efforts.
The Problem Statement 
Climate change research predominantly focuses on human-induced factors, leaving a significant gap in understanding the impact of natural forces on Earth's climatic dynamics. While there is a wealth of knowledge regarding the influence of human activities on climate change, the role of natural forces, such as shifts in pole positions, solar activity (sunspots) remains underexplored. This gap hinders the development of comprehensive climate models, predictive tools, and effective mitigation strategies. As a result, there is a pressing need to bridge this knowledge gap by conducting a thorough analysis of natural climate change factors to discern their individual contributions and interactions with observed climate patterns. Addressing this gap not only enhances our understanding of Earth's climate history but also informs more accurate modeling and prediction, ultimately aiding in the formulation of proactive climate policies and sustainable practices. This problem statement underscores the urgency of investigating natural climate forces alongside anthropogenic influences for a holistic approach to climate change research.
Addressing The Problem Statement
In addressing the problem statement, I took a comprehensive approach by merging three datasets that capture different natural forces influencing climate change—average temperature, the distance traveled by the North Pole, and the number of sunspots. Merging these datasets based on the common "Year" column allowed me to create a cohesive dataset spanning various natural factors over time.
To ensure the integrity of the analysis, I filtered the merged dataset to include only rows with available data on average temperature and reported kilometers. This step was crucial to focus on the relevant information for exploring the relationships between these variables. The scatter plot and 3D plot generated from this refined dataset visually depict the intricate relationships between the number of sunspots, average kilometers, and average temperature, providing a clearer understanding of their interactions.
By employing data visualization techniques, I aimed to unravel the complex dynamics of these natural climate change factors, as highlighted in the problem statement. This exploration contributes to a holistic understanding of Earth's climate history and lays the groundwork for more accurate modeling and prediction. Ultimately, this analytical approach aligns with the broader goal of informing proactive climate policies and sustainable practices by shedding light on the natural forces influencing climate change.

Analysis
Upon analyzing the merged dataset, it becomes apparent that the number of sunspots does not exhibit a strong influence on average temperature, as indicated by the scatter plot and 3D visualization. The points on these plots do not form clear patterns or trends that would suggest a direct correlation between sunspot activity and temperature. This observation aligns with the existing scientific understanding that while sunspots can impact solar radiation, their effect on Earth's climate is relatively minor compared to other factors.
Interestingly, the distance traveled by the North Pole emerges as a more prominent factor influencing climate patterns. The 3D visualization reveal discernible trends, indicating a potential relationship between the distance traveled by the North Pole and changes in average temperature. This finding is noteworthy and warrants further investigation to understand the underlying mechanisms driving this correlation. It suggests that the movement of the poles might play a more significant role in shaping Earth's climate over time, emphasizing the importance of considering diverse natural forces in climate change analyses.
Implications 
The implications of this information are multifaceted. Firstly, recognizing that the number of sunspots doesn't strongly influence average temperature underscores the need for a nuanced understanding of the complex interplay of natural factors in climate change. This insight can guide climate scientists and policymakers to focus on more impactful variables when developing models and strategies to mitigate climate change. It directs attention toward factors with larger influences on Earth's climate, allowing for more targeted and effective interventions.
On the other hand, the observed correlation between the distance traveled by the North Pole and changes in average temperature carries significant implications. If further research confirms and elucidates this relationship, it could reshape our understanding of climate dynamics. Understanding the factors driving the correlation can inform predictions about climate variations and improve the accuracy of climate models. This knowledge is vital for developing adaptive strategies to cope with the potential impacts of climate change on ecosystems, weather patterns, and sea levels.
In a broader context, these implications highlight the importance of a comprehensive and data-driven approach to climate science. By incorporating diverse natural forces into the analysis, scientists can refine their understanding of Earth's climate history, leading to more accurate predictions and informed decision-making. Ultimately, the implications extend beyond the scientific realm, influencing how we approach climate policies, resource management, and efforts to build resilience in the face of a changing climate.
Limitations
Throughout the course of this project, I met several limitations that bear consideration. First and foremost, the data collection process involved gathering information from multiple different sources, each with its own set of methodologies and potential biases. This introduces a level of uncertainty and variability into the dataset, as the reliability of the data hinges on the accuracy and consistency of the sources.
Additionally, the reliance on calculations introduces another layer of potential error. The accuracy of the results is contingent upon the precision of the calculations performed, and any inaccuracies in these computations could propagate through the analysis. Furthermore, the data cleaning process, while necessary for ensuring data integrity, is inherently subjective and can introduce a degree of bias, particularly in decisions about outliers or missing values.
Being a solo endeavor for a school project, the scope and depth of the analysis are constrained by the resources and time available. This limitation may impact the comprehensiveness of the exploration and the depth of insights derived from the data. Moreover, the use of averages, while a common statistical approach, may oversimplify the complex dynamics inherent in climate data.
Lastly, personal biases could inadvertently influence decisions made throughout the project, from data cleaning to interpretation of results. Awareness of these potential biases is crucial for keeping the objectivity and rigor of the analysis. Despite these limitations, this project serves as a valuable exercise in navigating real-world challenges in data science and offers insights that contribute to the ongoing dialogue on climate change.

Concluding Remarks
In conclusion, this analysis highlights the complexity of natural climate change factors and underscores the need to explore various variables to gain a more nuanced understanding. While the number of sunspots may not strongly affect average temperature in this dataset, the intriguing relationship between the North Pole's movement and temperature fluctuations opens avenues for deeper exploration and underscores the value of a multidimensional approach to studying Earth's climate history.

