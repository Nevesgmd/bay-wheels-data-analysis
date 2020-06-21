# Analyzing Bay Wheels Trip Data - April 2020
## by Gabriel Medeiros das Neves

This project was developed for the Udacity Data Analyst Nanodegree, in order to demonstrate expertise with Exploratory Data Analysis and Explanatory Data Analysis.

# Table of Contents
1. [Dataset](#data)
2. [Prerequisites to contribute](#requisites)
3. [How to visualize the study](#visualize)
4. [Summary of Findings](#findings)
5. [Key Insights for Presentation](#presentation)
6. [License](#license)


<a name="data"></a>
## Dataset
The data consisted of information about the approximately 84,000 trips made during April 2020. The attributes included the bicycle type, time and date of bicycle rental and return, start and end stations, among others.  
To download the used dataset, as well as datasets from other months and years, click [here](https://s3.amazonaws.com/baywheels-data/index.html).

<a name="requisites"></a>
## Prerequisites to contribute
After downloading/clonning all the files present in this repository, you must choose between one of the following methods. Choose wisely ;)

### Method 1
If you want to contribute, this project requires **Python 3** and its following libraries installed:

* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

Besides, you also need to install a software to use [Jupyter Notebook](https://jupyter.org/).  
I recommend downloading [Anaconda](https://www.anaconda.com/) (Python distribution), which already has all the necessary modules and Jupyter Notebook installed.

### Method 2
You can also decide to use [Google Colab](https://colab.research.google.com/), in this case, all you have to do is open the desired notebook (`.ipynb` file) on Google Colab with your account.


<a name="visualize"></a>
## How to visualize the study
Just open the HTML files. The exploration file contains the entire process of the technical study, while the slide file will open a presentation of the most relevant findings.

<a name="findings"></a>
## Summary of Findings
During exploration, it was observed that most electric bikes (which have a higher demand when compared to docked bikes) were rented by casual users, while most docked bikes were rented by members.  
There was also a clear trend between the number of rentals and the hour of the day, in which the rentals occurrences were more frequent in the afternoon, with a drastic drop after 8 pm that lasted until 6 am.  
Besides that, the ten stations with the highest and lowest number of rentals were identified, and their correlations, distributions or trends with other features (such as rideable type, hour of the day and user account type) were explored.  
Additionally, it was observed that around 99% of trips take less than two hours and that the number of casual users grows a lot on weekends, even without significant increases in the number of rentals. Other correlations between different variables and the time duration of trips were investigated, but no strong correlation was found.

<a name="presentation"></a>
## Key Insights for Presentation
I decided to focus my presentation on explorations related to the number of rentals, imagining it to be the best metric of success. Thus, I tried to share the findings regarding the number of rentals by rideable type, start station, day of the week and hour of the day, as well as the relationships of these features with other features in the dataset.  
Furthermore, I also aimed to demonstrate some of the insights on trip times, however, I decided not to add many plots due to the lack of strong correlations, in order to not over-extend the presentation.

<a name="license"></a>
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
