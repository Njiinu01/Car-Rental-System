Car Rental System
Overview
This project is a Car Rental System developed using Object-Oriented Programming (OOP) principles in Java. The system includes classes for managing cars, customers, and rental transactions, encapsulating data and behaviors to create a modular and scalable application. The functionalities include car rental, customer management, and rental transactions, with a suite of test cases to thoroughly validate each method's functionality.

Features
Car Management: Add, remove, and search for cars in the rental system.
Customer Management: Add, remove, and search for customers.
Rental Transactions: Rent a car to a customer and track rental information.
Classes
Car
Represents a car available for rental.

Properties
carId: Unique identifier for the car.
brand: Brand of the car.
model: Model of the car.
rentalPricePerDay: Rental price per day for the car.
Methods
getCarId: Returns the car's ID.
getBrand: Returns the car's brand.
getModel: Returns the car's model.
getRentalPricePerDay: Returns the car's rental price per day.
Customer
Represents a customer of the rental agency.

Properties
customerId: Unique identifier for the customer.
name: Name of the customer.
contactNumber: Contact number of the customer.
Methods
getCustomerId: Returns the customer's ID.
getName: Returns the customer's name.
getContactNumber: Returns the customer's contact number.
RentalAgency
Manages the cars and customers, and handles rental transactions.

Methods
addCar(Car car): Adds a car to the agency's list.
addCustomer(Customer customer): Adds a customer to the agency's list.
findCarById(String carId): Finds a car by its ID.
findCustomerById(String customerId): Finds a customer by their ID.
rentCar(String carId, String customerId): Rents a car to a customer.
