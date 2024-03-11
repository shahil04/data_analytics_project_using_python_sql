#  Airlines Data Analysis using SQL and Python
-------------------------------------------------

### Steps included to Perform Data Analysis

• Understanding the Business Problem

• Importing Libraries

• Database connection to extract data

• Exploring the tables present in the Database to identify key variables

• Analyzing the Key variables

• Creating Report with all the results and analysis for the company

### Business Problem

Our company operates a diverse fleet of aircraft ranging from small business jets to medium-sized machines. We have been providing high-quality air transportation services to our clients for several years, and our primary focus is to ensure a safe, comfortable, and convenient journey for our passengers. However, we are currently facing challenges due to several factors such as stricter environmental regulations, higher flight taxes, increased interest rates, rising fuel prices, and a tight labor market resulting in increased labor costs. As a result, the company's profitability is under pressure, and they are seeking ways to address this issue. To tackle this challenge, they are looking to conduct an analysis of their database to find ways to increase their occupancy rate, which can help boost the average profit earned per seat.

### Main Challenges

1. Stricter environmental regulations: The demand on the airlines industry to decrease its carbon footprint is growing, which has resulted in more stringent environmental laws that raise operating costs and restrict expansion potential.

2. Higher flight taxes: To solve environmental issues and increase money. governments all around the world are taxiing aircraft more heavily, which raises the cost of flying and decreases demand

3. Tight labor market resulting in increased labor costs: The lack of trained people in the aviation sector has increased labor costs and increased turnover rates.

### Objectives

1. Increase occupancy rate: By increasing the occupancy rate, we can boost the average profit earned per seat and mitigate the impact of the challenges we're facing.

2. Improve pricing strategy: We need to develop a pricing strategy that takes into account the changing market conditions and customer preferences to attract and retain customers.

3. Enhance customer experience: We need to focus on providing a seamless and convenient experience for our customers, from booking to
arrival, to differentiate ourselves in a highly competitive industry and increase customer loyalty.

The end goal of this task would be to identify opportunities to increase the occupancy rate on low-performing flights, which can ultimately lead to increased profitability for the airline.



### Basic Analysis

The basic analysis of data provides insights into the number of planes with more than 100 seats, how the number of tickets booked and total amount earned changed over time, and the average fare for each aircraft with different fare conditions. These findings will be useful in developing strategies to increase occupancy rates and optimize pricing for each aircraft. Table 1 shows the aircraft with more than 100 seats and the actual count of the seats.


In order to gain a deeper understanding of the trend of ticket bookings and revenue earned through those bookings, we have utilized a line chart visualization. Upon analysis of the chart, we observe that the number of tickets booked exhibits a gradual increase from June 22nd to July 7th, followed by a relatively stable pattern from July 8th until August, with a poticeable peak in ticket bookings where the highest number of tickets were booked on a single day. It is important to note that the revenue earned by the company from these bookings is closely tied to the number of tickets booked. Therefore, we can see a similar trend in the total revenue earned by the company throughout the analyzed time period. 

These findings suggest that further exploration of the factors contributing to the peak in ticket bookings may be beneficial for increasing overall revenue and optimizing operational strategies.

- Fig 1&2 insert

Figure 2

We were able to generate a bar graph to graphically compare the data after we completed the computations for the average costs associated with different fare conditions for each aircraft. The graph Figure 3 shows data for three types of fares: business, economy, and comfort. It is worth mentioning that the comfort class is available on only one aircraft, the 773. The CN1 and CR2 planes, on the other hand, only provide the economy class. When different pricing circumstances within each aircraft are compared, the charges for business class are consistently greater than those for economy class. This trend may be seen across all planes, regardless of fare conditions.


### Analyzing occupancy rate

irlines must thoroughly analyze their revenue streams in order to maximize profitability. The overall income per year and average revenue er ticket for each aircraft are important metrics to consider. Airlines may se this information to determine which aircraft types and itineraries enerate the most income and alter their operations appropriately. This esearch can also assist in identifying potential for pricing optimization and allocating resources to more profitable routes. The below figure 4 shows me total revenue, total tickets and average revenue made per ticket for each aircraft. 

The aircraft with the highest total revenue is SU9 and from the figure 3 it can be seen that the price of the business class and economy class is the lowest in this aircraft. This can be the reason that most of the people bought this aircraft ticket as its cost is less compared to others. The aircraft with least total revenue is CN1, and the possible reason behind this is it only offers economy class with very least price and it might be because of its poor conditions or less facilities.

The average occupancy per aircraft is another critical number to consider.

Airlines may measure how successfully they fill their seats and discover chances to boost occupancy rates by using this metric. Higher occupancy rates can help airlines increase revenue and profitability while lowering operational expenses associated with vacant seats. Pricing strategy, airline schedules, and customer satisfaction are all factors that might influence occupancy rates. The below figure 5 shows the average booked seats from the total number of seats for each aircraft. The occupancy rate is calculated by dividing the booked seats by the total number of seats. Higher occupancy rate means the aircraft seats are more booked and only few seats are left unbooked.

Airlines can assess flow much their total yearly turnover could improve by providing all aircraft a 10% higher occupancy rate to further examine the possible benefits of raising occupancy rates. This research can assist airlines in determining the financial impact of boosting occupancy rates and if it is a realistic strategy. Airlines may enhance occupancy rates and revenue while delivering greater value and service to consumers by optimizing pricing tactics and other operational considerations. The below figure shows how the total revenue increased after increasing the occupancy rate by 10% and it gives the result that it will increase gradually so airlines should be more focused on the pricing strategies.

### Conclusion

To summarize, analyzing revenue data such as total revenue per year, average revenue per ticket, and average occupancy per aircraft is critical for airlines seeking to maximize profitability. Airlines can find areas for improvement and modify their pricing and route plans as a result of assessing these indicators. A greater occupancy rate is one important feature that can enhance profitability since it allows airlines to maximize revenue while minimizing costs associated with vacant seats. The airline should revise the price for each aircraft as the ower price and high price is also the factor that people are not buying tickets from those aircrafts. They should decide the reasonable price according to the condition and facility of the aircraft and it should not be very cheap or high.

Furthermore, boosting occupancy rates should not come at the price of consumer happiness or safety. Airlines must strike a balance between the necessity for profit and the significance of delivering high-quality service and upholding safety regulations. Airlines may achieve long-term success in a highly competitive business by adopting a data-driven strategy to revenue analysis and optimisation.

aircraft
code	num_seats
 319    116
 320    140
 321    170
 733     130
 763    222
 773	402


### Reference
- Dataset source https://www.kaggle.com/datasets/fiazbhk/airline-data-analysis?resource=download

