# Metro-Passenger-Counts-and-Gas-Prices-In-Istanbul-In-2022

### DESCRIPTION
In this work, the relation between passenger counts who uses metro lines in Istanbul in 2022 and gasoline prices in 2022 is being investigated.
For this purpose passenger count data is obtained from Istanbul Metropolitan Municipality Open Data Portal and gasolin price data is gathered from Opet.

In the first section data is being cleaned and pre-processed. And in the second section we visualize the data. Finally in the 3th section we have an conclusion.

Main investigation is about if there is a relation between gas price changes and passenger counts change. 

### DATA
Metro passenger data is gathered from Istanbul Metropolitan Municipality Open Data Portal : https://data.ibb.gov.tr/en/ 
Unfortunately it needed to be download manually, because it throws an max trials exceeded error when we try to download it by urrlib library. 

Here is the csv file link: 

'https://data.ibb.gov.tr/en/dataset/ae3b2e4b-073a-48d0-8ef3-f28f19bcb19c/resource/5c2b78fc-3b68-4722-844f-3051c358a13f/download/2022-yl-rayl-sistemler-istasyon-bazl-yolcu-ve-yolculuk-saylar.csv'

We will use gas prices and try to observe the relation between the passanger counts and gas price changes. For this purpose we will be using data from a company called Opet. 
And here is the link for the data:
https://www.opet.com.tr/akaryakit-fiyatlari-arsivi 
In Istanbul there are two sides of the city. Bosphorus divides the city into 2 main parts. We call one of them European side, and other side we call Anatolian (or Asian) side. Gas prices differs from the parts of the city. (Probably because of the transportation cost) So we are going to use two different gas prices data. 

Files are uploaded to the repo too. 

### EXAMPLES
Some of the images from this work are shown below:

![Image 1](https://github.com/milikest/Metro-Passenger-Counts-and-Gas-Prices-in-Istanbul-In-2022/blob/main/Images/Image%201.png?raw=true)

![Image 2](https://github.com/milikest/Metro-Passenger-Counts-and-Gas-Prices-in-Istanbul-In-2022/blob/main/Images/Image%202.png?raw=true)

And here there is a gif from the visualisations:

<img src="https://github.com/milikest/Metro-Passenger-Counts-and-Gas-Prices-in-Istanbul-In-2022/blob/main/Images/Map%20gif.gif" alt="Map Gif" loop=infinite>

![Map Gif](https://github.com/milikest/Metro-Passenger-Counts-and-Gas-Prices-in-Istanbul-In-2022/blob/main/Images/Map%20gif.gif?raw=true)

This work can be improved by adding different features like; 
- Average salary of employees during the 2022
- Schools education calendar
- National and religional day-offs
- Metro train counts change in 2022
- Road constructions
- Weather events

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### DEPENDENCIES:

- Python     : 3.8
- Pandas     : 1.5.2
- Numpy      : 1.21.6
- Matplotlib : 3.6.2
- Seaborn    : 0.11.2
- Folium     : 0.12.1.post1


