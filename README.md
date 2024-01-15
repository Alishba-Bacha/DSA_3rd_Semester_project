                    Airline Reservation System

Introduction:
Airline Reservation Systems play a pivotal role in the aviation industry, facilitating the efficient management of flights, passenger reservations, and overall travel logistics. This report delves into the analysis and assessment of a C++ implementation of an Airline Reservation System. The project encompasses a range of functionalities, including city and flight data management, reservation creation, route finding, and passenger information tracking. The objective of this report is to comprehensively examine the structure, functionality, and potential improvements of the system, shedding light on its strengths and areas for enhancement. By exploring the code's data structures, algorithms, and user interface, we aim to provide valuable insights into the design and performance of the Airline Reservation System implemented in C++.
Algorithm:
Initialization:
1.	Initialize City List:
•	Create an array cityList to store city information.
•	Set each city's departure and arrival lists to nullptr.
2.	Initialize Flight List:
•	Create an array flightList to store flight information.
•	Set flightCount to 0.
City and Flight Management:
1.	Read Flight Data:
•	Manually add flight information using the MakeFlightNode function.
•	Populate the flightList array with flight data.
City and Flight Display:
•	Implement functions to display information about cities, flight departures, and flight arrivals.
Reservation System:
1.	Make Reservation:
•	Prompt the user for passenger and trip details.
•	Use the findRoute function to determine the route between the departure and destination cities.
•	Create a new reservation using the MakeReservation function.
•	Add the reservation to the linked list.

2.	Print Reservation Schedule:
•	Display all reservations in the system using the PrintSchedule function.

3.	Delete Reservation:
•	Prompt the user for the reservation number to delete.
•	Find and delete the reservation from the linked list.
Route Finding and Shortest Path:
1.	Find Route:
•	Search for a direct flight or connecting flights between two cities using the findRoute function.
Shortest Path:
•	Implement Dijkstra's algorithm to find the shortest path between two cities, considering flight departure and arrival times.
User Interface:
1.	User Menu:
•	Implement a user menu with options to display cities, flight information, departure and arrival lists, make reservations, view schedules, delete reservations, and more.
2.	User Input Handling:
•	Validate user inputs and handle errors appropriately
