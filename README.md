# UC_Irvine_Machine_Learning_Repository_Household_Power_Consumption
Household Power Consumption

Exploratory data analysis was conducted in R using UC Irvine Machine Learning Repository "Individual Household Power Consumption" data set to examine via visualization any patterns for how household energy usage varies over a 5-day period in February 2007. Global Active Power was examined because it represents the actual consumed/utilized power in an AC circuit. https://en.wikipedia.org/wiki/AC_power


Processing Instructions:
- Jupyter Notebook file is included and well as R script file and PNG file showing histogram plot.
- To read Jupyter Notebook file:
  - Use R for Jupyter Notebook
    - install R essentials packages for use in Jupyter Notebook.
      - at command line enter  conda install -c r r-essentials.
  - install IRKernel, a kernel for R 
    - https://irkernel.github.io/installation/
- Use R Studio or other application to read R script file.

Steps to Transformation:
- Data was downloaded from https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip
- Data was imported for dates 02-01-2007 to 02-05-2007.
- Date and Time variables were combined together and converted into Date/Time class for ease of plotting.
- A simple histogram was plotted using Base plotting package.
- The data is right skewed with a higher frequency of Global Active Power consumption in the 0 to 0.5 kilowatts range for this household over the February 1st to February 5 time period.
