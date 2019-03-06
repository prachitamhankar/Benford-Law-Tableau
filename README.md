# Benford-Law-Tableau
Analyzing Fraud detection using Benford’s Law in Tableau

## About

Law of Anomalous behavior or the first digit law states that in real-life data the leading or the left most digit is likely to be small. The smallest number 1 appears as the leftmost digit for about 30 percent of the time while the number 9 appears less than 5 percent.  This is used to detect frauds by the first digit frequency distribution of data by the anomaly in the results. 

### Steps Followed

I have used Tableau’s Superstore Sales Data to check if the data is fabricated or genuine. To ensure if the data is free from any accounting fraud and is genuine, I followed the below steps:

1) Extracted the data from the source and visualized the data showing the sales and extracting the left most value by creating a calculated field. 

2) Found the frequency of each left most digit finding the number of records.

3) Applied Benford’s law to visualize the best possible fit for the data.

4) I created a visualization of data showing the different categories of products and used reference line distribution to ensure if it observes the Benfords’s Law. 

5) Thus, the dataset is closer to the Benford distribution as it lies below or above the 20 percent threshold that I have created. 

Superstore data consisting of Sales and the left most digit :

![image_descript](https://github.com/prachitamhankar/Benford-Law-Tableau/tree/master/images/1.png)


### Prerequisites

You will need following softwares:

```
Pentaho
Python > 2.7
Matplotlib, seaborn, mapbox
```

## Acknowledgments

* I have used the dataset provided by [US Bureau of Transportation](https://www.bts.gov/topics/airlines-and-airports/origin-and-destination-survey-data)

