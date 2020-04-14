# R-Programming-Project
# Topic - Global Terrorism Attacks Analysis
This is an analysis of all global terrorism attacks that took place worldwide between the period of 1975-2018.

# Details of files attached
Terrorism analysis.R           - R analysis file

terrorism.rar                  - Dataset

MiniProjectPresentation.mp4    - Persentation Video

Global_Terrorism_R_report.pdf  - Book Report

Outputs for Experiments        - Exps Outputs

R_lab_journal.pdf              - Journal 

# Dataset - used
The Global Terrorism database (GDS) is an open-source database including information on terrorist attacks around the world from 1970 through 2018. The dataset I am using contains around 1,90,000 terrorism attacks worldwide that took place from 1970 to 2018 except 1993.
Dataset can also be accessed from https://start.umd.edu/gtd/

# Steps

--> Trimming of Dataset
The dataset will be trimmed from the existing 137 columns to 17 columns only by following command

terrorism <- terrorism[,c("iyear","imonth", "iday", "country_txt", "region_txt", "provstate", "city", "latitude", "longitude", "attacktype1_txt", "targtype1_txt", "corp1", "target1", "natlty1_txt", "gname", "weaptype1_txt", "weapsubtype1_txt")]

--> Installation of Packages and Libraries
The following libraries will be installed and initialized in R studio before performing the analysis.
Ggplot2,
Dplyr,
Ggthemes, 
Rworldmap, 
Reshape2, 
xlsx.

--> Plotting of Data
Columns will be iniatialized in variables, 
Using geom_line, geom_plot and geom_bar, 
Visualising the graphs and plots, 
Rworldmap and Ggthemes will visualize the data on map.

--> Plots Visualised
Line Plot, 
Bar Plot, 
Multile Plots, 
Histogram,
Heatmap.

# Conclusion
According to the analysis performed Outcome achieved via entire analysis are

Globally, terrorist attacks have increased dramatically since 2010

Central America was very unstable starting from the late 1970’s, it got better with time.

Middle East, North Africa and South Asia had a relative quiet past until around 1980.

Baghdad has become one of the most dangerous cities since 2015.

The most commonly used attack tactic from 1970 to 2018 involved bomb and explosives, followed by armed assault.

Iraq, Afghanistan and pakistan, India have suffered the most from terrorism.
