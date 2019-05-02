# CIti-Bike-in-NYC


Co-participant: Daniel Lee


## Introduction:

Citi bike is a privately owned public bicycle sharing system based in new york city, having stations in Manhattan, Queens, Brooklyn and Jersey city. It was named Citi bike because Citigroup lead the sponsorship. It was first opened in May 2013 with 332 stations and 6,000 bikes. Now, they have 757 active stations with around 12,000 bikes.

As of July 2017, there are 130,000 annual subscribers. Citi Bike riders took an average of 38,491 rides per day in 2016, and the system reached a total of 50 million rides in October 2017

We decided to analyze the Citi bike data because we wanted to bring insights out of something related us since we are living in NYC. We used Citi bike multiple times if there is a heavy traffic or even just to exercise little bit. We wanted to analyze what is going on with the usage of Citi bike data, not limiting ourselves from just using the bike for fun.

## Conclusion:

Limitations: we were not able to analyze the whole year cycle or couple years cycle because the size of the data. The dataset is very clean and well-organized, but contains around 10 NULL values. Out of 1.3 million observations, this is a very miniscule problem. We had a limited GPS data, because the dataset had latitudes and longitudes of where the bikes were checked out and checked in. If we had a full GPS data of the path in fixed intervals, we could have build a plot that shows the actual trip paths of each bikes.

Future directions: It would have been better if we had more features in the dataset. For example, we could have done another analysis if we had the weather data and see the correlation of the bike usage vs temperature or bike usage vs weather conditions. Apart from additional data, if we analyze more than one month of data, we will be able to see more clear trends and have more confidence in our analysis or assumptions.

Lessons learned: A lot of people use the Citi bike than we expected and the age range of users is quite wide. We can clearly see that Citi bike is a favorable public transportation by full-time workers. For the maintenance purposes, Motive could prioritize popular stations for more efficient repairs. This could possibly cut the cost they are spending on precautionary measures.

## Notes:
+ _/analysis_ folder stores the _report.html_, _report.rmd_, _header.html_, _footer.html_, and _style.css_:
	+ _report.html_ is the result of our project
	+ _report.rmd_ is the file that creates the report
	+ _header.html_ contains the stylesheet of our font--[Open Sans](https://fonts.google.com/specimen/Open+Sans) and the [GitHub icon](https://github.com/tholman/github-corners) in the upper-right corner.
	+ _footer.html_ contains the codes for creating the [footer](https://holtzy.github.io/Pimp-my-rmd/#footer_and_header)
	+ _style.css_ contains the stylesheet
+ _/r_ folder stores the codes for collecting data. The raw data is stored under _/data/raw_ folder and the processed data is stored under _/data/tidy_.
+ _/NBA_15years_ stores the codes for creating the shiny app. The link to our shiny app is https://cy2507.shinyapps.io/NBA_15years/.
+ _/image_ folder contains report-decorative images and the screen shots of our shiny app.
