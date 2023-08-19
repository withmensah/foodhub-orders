# foodhub-orders
I analyzed the foodhub orders data set from the LightHall Data Analytics Super League to come up with visualizations and recommendations 
## Context

The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## Objective

The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business.

## Data Description

The data contains different data related to a food order. The detailed data dictionary is given below.

### Data Dictionary

- `order_id`: Unique ID of the order
- `customer_id`: ID of the customer who ordered the food
- `restaurant_name`: Name of the restaurant
- `cuisine_type`: Cuisine ordered by the customer
- `cost`: Cost of the order
- `day_of_the_week`: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- `rating`: Rating given by the customer out of 5
- `food_preparation_time`: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
- `delivery_time`: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information.

## Questions

1. What is the average cost of orders?
2. What is the distribution of ratings given by customers?
3. Which cuisine types are most popular among customers?
4. Does the day of the week affect the number of orders placed?
5. How does food preparation time vary across different restaurants?
6. How does delivery time vary across different restaurants?
7. Is there a correlation between food preparation time and delivery time?
8. How much money is earned by the food aggregator from the delivery margin?



## Conclusion and Recommendations

**Observation 1:** It is clear that the American cuisine type is the most popular on the weekends followed by the Japanese, Italian, Chinese, Mexican cuisine types.

**Observation 2:** The top restaurant is Shake Shack with over 200 orders placed.

**Observation 3:** The majority of FoodHub orders are placed on the weekends.

### Recommendations

1. **Weekend Promotions:** We recommend introducing some kind of special promotion, discounts, or limited-time offers for the most popular cuisine type on weekends. This can help drive more orders during weekends and attract customers looking for specific cuisine options.

2. **Personalized Recommendations:** Utilizing customer order data and feedback to offer personalized recommendations to customers based on their preferences can potentially enhance the customer experience and encourage repeat orders.

3. **Restaurants should look into the 'French', 'Southern', 'Korean', 'Spanish', 'Vietnamese' cuisines as they were ordered the least (Perhaps something to do with the preparation?).**

4. **Not much can be said about the ratings because 700+ customers didn't bother to give ratings, however, we recommend maybe giving some incentives to encourage customers to give ratings.**

