# Price-Optimization---Rental-cars
When listing a car, a host has the opportunity to set its daily price. In this process, We recommend a price (which the host may accept or ignore) that is designed to optimize the host’s revenue, given various properties of the listing.

1. Based on the data found in `vehicles_booking_history.csv`, produce a well-written function that accepts properties of a listing and returns a daily price that is designed to improve/optimize revenue. Here is a dictionary for the data in the .csv:
 * `vehicle_id` - vehicle's unique ID
 * `date` - calendar date
 * `is_booked` - 1 if the listing is booked
 * `tmv` - true market value of vehicle
 * `category_aggregate` - vehicle category group
 * `demand_supply_ratio` - daily demand (web and app sessions) over supply (count of live listings in the local market, e.g. a city)
 * `price` - vehicle's listed price as of the given date

2. describe metrics and methods to gauge the success of your recomendations. 
