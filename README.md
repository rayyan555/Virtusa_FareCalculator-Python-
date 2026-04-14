# FareCalc – Travel Fare Optimizer

This is a simple Python program built for a ride-sharing scenario (CityCab).
It calculates the total ride fare based on distance, vehicle type, and time of travel.

The main idea of this project is to simulate how real cab apps adjust pricing during peak hours.

---

##  Features

* Calculates fare based on distance (per km rate)
* Supports multiple vehicle types:

  * Economy
  * Premium
  * SUV
* Applies surge pricing during peak hours (5 PM to 8 PM)
* Handles invalid vehicle types
* Displays a clear ride receipt

---

##  How it Works

1. User enters:

   * Distance (in km)
   * Vehicle type
   * Travel hour (0–23 format)

2. The program:

   * Picks the rate from a dictionary
   * Calculates base fare
   * Checks if the time is between 17 and 20
   * Applies 1.5x surge if it is peak time

3. Finally, it prints the ride details and total fare

---

##  Example


Enter distance (in km): 10

Enter vehicle type (Economy/Premium/SUV): Premium

Enter hour of travel (0-23): 18

----- Ride Receipt -----

Distance: 10.0 km

Vehicle Type: Premium

Travel Hour: 18

Surge Pricing Applied: Yes (1.5x)

Total Fare: ₹ 270.0


---

##  Concepts Used

* Dictionary (for storing rates)
* Functions (for modular code)
* Conditional statements (if-else)
* User input handling
* Basic error handling (`if-in` check)

---

##  Notes (while entering the details)

* Time should be entered in 24-hour format
* Vehicle type is case-sensitive (must match exactly)
* Surge pricing is only applied between 17 and 20

---

##  Author

Rayyan A

BE CSE (AIML)

Email: rayyanibnrahman903@gmail.com
---


