
# Project Vanguard A/B Testing


![Image du projet](https://github.com/mombolionnel-max/Project_vanguard/blob/main/assets/Image1.png?raw=true)



##### Presented by :
##### Lionnel MOMBO  
##### Rahala MOINDZE




## Content 
   
##### Description
##### Installation and Setup
##### Built with
##### Data Structure
##### Usage and Getting Started
##### Key Analysis Steps
##### Contribution and Enhancements





### Description


We work for the Vanguard investment management company in the Customer Experience (CX) team.
We conducted an A/B Test from 03/15/2017 to 06/20/2017 to evaluate a new digital interface between two customer groups. The Control Group, which is the benchmark group, used the traditional online process; the Test Group used the new, enhanced interface. Both groups followed an identical customer journey, consisting of a startpage, three successive steps, and a confirmation page. The objective of this experiment is to find out whether the new interface offers a better user experience and, above all, a higher conversion rate.




## Installation and Setup

You will need the standard Python environment for data science

"Python (version 3.8 or higher recommended)"

## Built with

![Construit avec](https://github.com/mombolionnel-max/Project_vanguard/blob/main/assets/built.png?raw=true)

[Pandas]https://pandas.pydata.org/    
[matplotlib.pyplot] https://matplotlib.org/   
[seaborn] https://seaborn.pydata.org/   
[numpy] https://numpy.org/  
[scipy.stats]  https://scipy.org/   
[statsmodels]https://www.statsmodels.org/


## Data Structure

df_final_demo :  Demographic profiles (age, gender, account type). Analysis segmentation.   
df_final_web_data_pt_1 :  Online interaction traces (part 1).Building the client journey.  
df_final_web_data_pt_2 :   Online interaction traces (part 2).Building the client journey.  
df_final_experiment_clients  :     Defining the experiment groups.



!! ⚠️ Note: The two files df_final_web_data_pt_1 and df_final_web_data_pt_2 must be merged at the beginning of the analysis before being joined with the other datasets.



## Usage and Getting Started

git clone https://github.com/mombolionnel-max/Project_vanguard.git

cd your_repo_name



## Key Analysis Steps

The code generally follows this workflow:

1.	Data Preparation: Merging the web data and joining all DataFrames.
2.	Cleaning: Handling missing values and formatting variables.
3.	Statistical Test: Using the test like T-test and Z-Test for Proportions to validate the observed difference.
4.	Visualization: Creating bar charts and "funnel" plots to compare the progress of the two groups step-by-step.


## Contribution and Enhancements

All suggestions for code improvements, additional statistical analyses or visualizations are welcome via Pull Requests.
























