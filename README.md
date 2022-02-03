# San Francisco Housing Analysis

This explores three datasets, all in relation to the the San Francisco Housing market. The sets used are ```housing_per_year.csv```, ```neighborhoods_coordinates.csv``` and ```sfo_neighborhoods_census_data.csv``. We will use all of these data to create a simple proptech application that allows us to better understand trends in the SF housing market and better understand using interactive visualizations.

---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Anaconda (Which includes Jupyter Lab and Pandas)
* Path from pathlib
* hvPlot

---

## Installation and Usage Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Anaconda Installation Files](https://www.anaconda.com/products/individual "Anaconda Installation Files")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 
 
### 2. Install Anaconda

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Anaconda Installation Guide - Windows](https://www.youtube.com/watch?v=g6ln1dAt-RI "Anaconda Installation Video - Windows") 
* [Youtube Video Anaconda Installation Guide - Mac](https://www.youtube.com/watch?v=oWVTO_69U4c "Anaconda Installation Video - Mac")

### 3. Install necessary Libraries and Dependencies

For installing ```hvplot``` please follow the following link to receive guidance 
* [hvPlot Library Installation](https://pypi.org/project/hvplot/ "hvPlot Library Installation") 

### 4. Downloading the Financial Analysis using APIs

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.

![image](https://user-images.githubusercontent.com/94983278/149385012-181d1769-0af6-487e-8e04-823a28f2c3ed.png)

Clone this project's repository from GitHub using the following command 

```git clone https://github.com/epocaterrasus/San-Francisco-Housing-Analysis-Proptech.git```

### 5. Opening the file on Jupyter Notebook

Being in the folder created when you downloaded the repository type ```jupyter lab```, this should open a window in your predetermined browser with Jupyter Lab. In the left corner you can see the files inside the repository, open the ```san_francisco_housing.ipynb``` which contains all steps and notes followed to analyze this dataset pair.

---

## Overview of the Project

In this project imported data from aforementioned .csv files of Santa Francisco housing data, one with the number housing units per year(2010-2016), one with the coordinates (latitude/longitude) of different neighborhoods, and one with the number of housing units, average sale price by square feet, and average rental prices.

In this project we create three plots that each gives different useful insights to better understand SF's housing market. The plots are the following:

* San Francisco Housing Units per year - in this graph we can see that there is a constant increase in the number of available housing units in San Francisco, this fact can lead us to assume that there has been an increase in the construction of new housing units in the area, this as a consequence of a higher demand due to the robust technology workforce based out of the city.

![image](https://user-images.githubusercontent.com/94983278/152398252-5a75d5ce-f08f-426c-be24-aed14af8b15e.png)

* San Francisco Sqft Sale Price vs. Gross Rent - in this graph we can see that although rents have increased dramatically in the time period analyzed, the sales price have not increased as much. This would be an interesting thing to explore further as it may be a good opportunity for a company/REIT to acquire residential property to rent out.

![image](https://user-images.githubusercontent.com/94983278/152399820-d4f811d5-100b-4ddf-b4bc-16d1886cfb60.png)

*San Francisco Sqft Sale Price vs. Gross Rent - same information as the graph below but filtered by neighborhood. You can change the neighborhood using the dropdown menu on the right. This could help us even further analyze which neighborhoods offer the best investment/return for residential rental properties.

![image](https://user-images.githubusercontent.com/94983278/152400576-2d585aef-83c0-45a0-9246-d3aa7e86c083.png)

* San Francisco Rents and Sqft Sale Price by neighborhood visualized in a map. The dot size represents the average Sqft Sale Price (the bigger the dot the more expensive the properties by sqft ). The color represents the average rental price (use the legend on the right for reference)

![image](https://user-images.githubusercontent.com/94983278/152401336-4001fe72-d0a4-4619-a719-a939e37231c0.png)


---

## Contributors

Edgar Pocaterra - epocaterra@protonmail.ch / +1 806 283 5455

---

## License

MIT License

Copyright (c) 2022 epocaterrasus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.