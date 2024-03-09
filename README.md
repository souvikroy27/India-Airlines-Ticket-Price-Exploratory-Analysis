# India-Airlines-Ticket-Price-Exploratory-Analysis
## Objective
In this project, we study the data which is in tabular format using various Python libraries like Pandas, Numpy, Matplotlib and Seaborn and done an exploratory data analysis for ticket prices to better understand the factors affecting them in India

We study different columns of the table and try to co-relate them with others and find a relation between those two.

We try to find and analyze those key factors like class of travel, duration of fight, etc. which helps us understand the pricing of tickets to plan and schedule our air travel in efficient way.

## About Dataset
The dataset includes details on the ticket booking alternatives available through the website "Easemytrip" for flights between India's top 6 metro cities. Following are the key features of the dataset corresponding to 50 days of data from February 11 to March 31 of 2022.

## Exploratory Data Analysis results

![1](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/823351ee-395c-4f3d-ae6f-4901a4e2f3f5)
From the above figure, we can see 'Vistara' has maximum no. of fights followed by 'Air India' while 'Spice Jet' has least no. of flights.

![2](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/bed8c4ca-a9a8-4caf-a216-2958b9128653)
From the above figure, we can see 'Economy' class tickets usually cost between 2500 - 22500 while 'Business' class tickets usually cost between 25000 - 95000.

![3](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/7e49cdbf-a992-4660-96d4-ce4ac43276e4)
From the above figure, we can see that availabilty of 'Economy' tickets is almost twice than availibitly of 'Business' class tickets which is explained by the fact that only 2 airlines - 'Air India, Vistara' offer 'Business' class tickets while all airlines offer 'Economy' class tixkets.

![4](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/08558e1f-796e-4618-9ff5-0088803b8463)
From the above figure, we see the distribution of ticket price varying with duration of flight. More no. of green and brown points in the figure is explained by the fact that 'Vistara' and 'Air India' have maximum no. of flights.

![image](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/0b42d477-a3a0-4ad1-845d-9064347efd32)
From the above figure, we can conclude that 'Air Asia' offers the cheapest 'Economy' class tickets while 'Indigo, 'Go First', 'Spice Jet' are almost similarly priced. Meanwhile 'Air India' and 'Vistara' are priced much higher than other 4 airlines which can be explained on the basis that 'Air India' and 'Vistara' are both FSCs while rest are LCCs. 'Business' class tickets for 'Vistara' cost much higher than 'Air India' which can be due to better service, quality of seats available on 'Vistara' as compared to 'Air India'

![6](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/5dfa42d8-8025-478b-833f-7df5853e4fc8)
From the above figure, we can conclude that ticket price rise slowly till 20 days from the date of flight, then rise sharply till the last day, while dramatically reducing just 1 day before the date of flight. This can be explained by the fact that people usually buy flight tickets within 2-3 weeks of flight which generates more profits for airlines. On last day, prices show dramatic reduction as airlines hope to fill the flight completely due to increase the load factor and decrease the operational cost per passenger.

![8](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/0adfcbfe-d4b6-46d5-b1b6-570a3e792d77)
From the above figure, we can see that the relationship is not linear but can be approximated by second degree curve. We can see linear growth in prices as duration of flight increases till 20 and then lowering again. Some outliers may be affecting the curve.

![9](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/96e6367c-de69-4d4c-87e8-48af8ba062d4)
From the above figure, we can conclude that flights departing late at night are cheapest while those arriving early morning and late night are cheap too. Flights departung in afternoon are relatively cheap as well.

![10](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/2dde475c-e2ad-480f-8de1-8ff3e2eebaea)
From the above figure, we can conclude that Non-Stop flights are generally the cheapest while One-Stop flights are more expensive and 2+ stop flights are most expensive which can be explained on basis that as one undertakes more flights to fly to destination, it costs more. 'Air Asia' seems to be an exception in this case which shows little variation in prices between its Non-Stop, One Stop and 2+ Stop flights.

## Dashboard

![Airline](https://github.com/souvikroy27/India-Airlines-Ticket-Price-Exploratory-Analysis/assets/162815026/bb1ec269-b3ae-4fd8-b8f4-bbbd5599c2b0)

## Conclusion
(1) 'Air Asia' offers the cheapest flight tickets while flying Economy class while 'Air India' is cheapest while flying Business class.

(2) Booking tickets 3-7 weeks before travel will be cheaper than buying them within 3 weeks of travel as prices rise rapidly in 2-20 days period. Tickets can be cheap when bought just 1 day before however they 
    might not be as cheap as when bought more than 3 weeks before.
    
(3) Ticket price grow linearly with duration of flight peaking when duration of flight reaches 20 hours. However due to some outliers they again fall for for flights with duration of more than 20 hours. Relation     can be approximated by 2nd degree curve.

(4) Flight departing late at night and arriving early morning or late at night are cheapest.

(5) Flight prices increase with increase in number of stops.
