A prominent airline company in the Pacific Northwest has accumulated extensive data related to flights and weather patterns and needs to understand the factors influencing the departure delays and cancellations to benefit both airlines and passengers. As the data analyst on the team, you decide to embark on this analytical project.

The aviation industry is dynamic with various variables impacting flight operations. To ensure the relevance and applicability of your findings, you choose to focus solely on flights from the 'pnwflights2022' datasets available from the ModernDive team exported as CSV files. These datasets provide comprehensive information on flights departing in the first half of 2022 from both of the two major airports in this region: SEA (Seattle-Tacoma International Airport) and PDX (Portland International Airport):

flights2022.csv contains information about about each flight including
Variable	Description
dep_time:	Departure time (in the format hhmm) whereNA corresponds to a cancelled flight
dep_delay:	Departure delay, in minutes (negative for early)
origin:	Origin airport where flight starts (IATA code)
airline:	Carrier/airline name
dest:	Destination airport where flight lands (IATA code)
flights_weather2022.csv contains the same flight information as well as weather conditions such as
Variable	Description
visib:	Visibility (in miles)
wind_gust:	Wind gust speed (in mph)
