# Flight-Booking-Price-Prediction

# PROBLEM STATEMENT- The objective is to analyze the flight booking dataset obtained from a platform which is used to book flight tickets. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers.

AGENDA
- Importing the libraries
- Loading the data
- Data visualisation
- Label Encoding
- Feature selection
- Implementing ML algorithm

 ATTRIBUTES AND DESCRIPTION

 1. Airline -          Name of the airline company
 2. Flight -           Plane's flight code
 3. Source City -      City from which the flight takes off
 4. Departure Time -   Time of Departure
 5. Stops -            Number of stops between the source and destination cities
 6. Arrival Time -     Time of Arrival
 7. Destination City - City where the flight will land
 8. Class -            Contains information on seat class
 9. Duration -         Overall amount of time taken to travel between cities in hours.
 10. Days left -       Subtracting the trip date by the booking date.
 11. price -           Ticket price

Steps
1. I started off this project by importing the important libraries required for the project.
2. I Loaded the data and removed unnecessary column from the dataframe.
3. I checked the shape of a dataframe and datatypes of all columns along with calculated the statistical data.
4. Data Visualisation
   - I created a line plot to show variation in price with different airlines.
   - I created another line chart to see if the price of the ticket increases as the days left for departure decreases.
   - Visualised Price range of all the flights and ange of price of all the flights of Economy and Business class using the bar graph.
   - I created multiple subplots for visualization of categorical features with countplot.
5. Feature Selection- Plotting the correlation graph to see the correlation between features and dependent variable. Selected the features using
   VIF where VIF should be less than 5.
6. Linear Regression- Applied standardization and implemented Linear Regression Model to predict the price of a flight.
   - Calculated r2 score, MAPE, MSE. Lower the RMSE and MAPE better the model.


 



