# Bike_Sharing
## Overview
While on vacation in New York City using the Citi Bike network to move around the city, the idea came to us to bring a similar business venture to Des Moines, Iowa. Because Citi Bike makes their ride sharing data public, we ventured to examine their data to better understand and explain to potential investors how we would be able to  replicate this model.

Link to Results  https://github.com/Bernest1108/Bike_Sharing-/tree/main/Results

## Results
The data throughout the month of August 2019, a couple of trends became clear.
As far as demographics of the customer base go, most of the customer base consists of regular subscribers, with 81% of the total customer base being subscribers.

![image](https://user-images.githubusercontent.com/100445489/171635874-baa62035-926b-4857-b4f1-390faebb9603.png)


As you can see the customer base leans towards male: 

![image](https://user-images.githubusercontent.com/100445489/171636139-0559c6ba-b3d0-45d0-82cf-928806898707.png)

Assumptions have been made about how the customer base uses the service, firstly that it would primarily used by tourists as a way to move around the city, while still being able to see it. If this would be the case, you most likely would see an up-tick of rides around tourist destinations and more skewed towards weekends or distributed throughout the week. This is not is what is being seen in the data. First, the distribution of what hour of the day that bikes were checked out show a concentration towards weekday rush hours.

![image](https://user-images.githubusercontent.com/100445489/171637280-c6ca4f3a-5bdc-479a-bf19-8ceb5a18ae1c.png)


This pattern remains when you look at the gender breakdown.
![image](https://user-images.githubusercontent.com/100445489/171637549-c6ac86b4-bdf5-4c3e-adc0-61a2ad6b6e74.png)


It may appear as though female riders are not riding during that time because male subset is so much darker, but that is because the total riders skews so much male, that the distribution of color looks off. When male riders are filtered out, we can see the same concentration prominently appear for female customers as well.

![image](https://user-images.githubusercontent.com/100445489/171637838-1c4117bd-a61b-4c17-8d8c-dce5a97717a4.png)


When analyzing the length of time checked out by riders, most check outs are under 20 minutes. Not something that you would expect from a tourist going around the city for a day.
![image](https://user-images.githubusercontent.com/100445489/171638305-82795f67-d2b4-4155-b011-600d82168ac4.png)

Gender breakdown below
![image](https://user-images.githubusercontent.com/100445489/171638731-53f846c2-b024-4268-8375-7d9c2247845b.png)


This is accentuated by the fact that the similar ride heat map repeats itself when looking at customer vs subscriber with the subscribers generally only riding on the weekdays with an up-tick in customer rides on the weekend

![image](https://user-images.githubusercontent.com/100445489/171639017-6ac8bef0-94bd-4f9c-835a-c0447c9f40e4.png)



When reviewing the distribution of rides during the different rush hours across the city, the ending locations for rides in the morning rush hour and the starting locations during the evening rush hour are concentrated in Lower Manhattan where most of the cities corporate jobs are concentrated as well.

Starting locations evening rush hour.
![image](https://user-images.githubusercontent.com/100445489/171639258-2a0274fd-0f9b-41e8-a76c-c20c110d1e2b.png)

Ending locations moring rush hour.
![image](https://user-images.githubusercontent.com/100445489/171639459-3a18d4a9-7d56-4bb4-9173-a5ab68c18e9b.png



## Summary
Due to the distribution of rides occurring and the fact that many of the total customer base are subscribers rather than one time customers, it is clear that the majority of the customers using the services are using the service as a way to commute . This is also supplemented by the fact that most of the rides in evening rush hour start and most of the rides in morning rush hour end in Lower Manhattan, where most businesses are in the city. 

A way to understand the business and the customer base to better adapt the business model to Des Moines, IA would be to cross examine if the rides begin and end close to subway stations as a way to understand if the commuters are using the bikes to supplement the public transit system. Or if they is no real correlation then we might be able to assume that they are using the bikes for their total commute. 

Another area of focus would be understanding why the customer base is largely male during that time. Better understanding that would better prepare the adapatation to Des Moines demographics. 

Thank you









