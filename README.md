Program Purpose: The purpose of this program is to take the contents from the 'Stations' file, retreive city and state locations, and then use the data from "Complete_Data" file to map the most popular aiports to their cities, states, and number of arrivals/ departures. 

Inputs: User input the number of popular airports they want to learn about.

Expected Output: The program should output two files:
1. Stations_data sorted: Contains three digit airport codes mapped to their city and state locations
2. A tsv file with the most popular arriving airports: contains the code of airport, city, state, and number of arrivals.
3. A tsv file with the most popular departing airports: contains the code of airport, city, state, and number of departures.

Repeated execution: None
Sequential execution: Program executes top to bottom.
Conditional execution: None, other than the output depends on the user's specified number of airports
Reusable: None

Possible Improvements:
- An option for the user to specify the data they want to extract, example: User could also wish to include the number of miles traveled, etc.
- Putting certain steps into functions for better reusability.
- Allow user to specify the names of the columns in the new datasheets. Similarly, allow the user to specify where and how they want to merge the data. Ex: user could merge data to the left instead of to the right for different analysis.
  
