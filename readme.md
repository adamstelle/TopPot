PURPOSE:

Allows TopPot store owners to provide basic inputs regarding store activity, and provides them with calculated values for the number of donuts they need to have every hour and day.


What the Program does:

- Prompts the user to enter their store, and a values for few pre-defined attributes of that store.
- Stores each of those inputs from the user into arrays (instances of the constructor object) all store branches, with parameters for all key user inputs (location, the range of hourly foot traffic, the % of people entering the store, and # of donuts sold per person)
- Within the provided range, calculate random hourly values of foot traffic per location.
- Multiply hourly foot traffic by the % entered and avg. # of donuts sold to generate # of total sales per hour, and store these values in an array.
- Output the results of each array into cells of an empty table in the browser. 

Results:
Downtown: [71, 40, 84, 69, 87, 74, 69, 78, 41, 82, 85] 
Capitol Hill: [41, 41, 18, 19, 36, 12, 23, 23, 15, 13, 16]
SLU: [57, 65, 71, 58, 60, 55, 75, 68, 66, 66, 60]
Wedgewood: [232, 144, 140, 216, 216, 176, 168, 240, 140, 120, 208]
Ballard: [21, 13, 13, 55, 40, 36, 50, 55, 28, 17, 20]

Wedgewood wins!