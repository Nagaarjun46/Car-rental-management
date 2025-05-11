# Car Rental Management
A simple Java console-based application for managing a car rental system. This project allows users to rent and return cars, calculate rental charges, and manage customer and rental data in memory.

📋 Features
Add and manage multiple cars with different brands and pricing.

Rent cars based on availability.

Calculate total rental cost based on the number of days.

Return rented cars.

View rental and return confirmations.

User-friendly menu-based console interface.

🛠️ Technologies Used
Java (Core)

Java Collections (ArrayList)

Command-line interface (CLI)

🧾 How It Works
Start the application

Rent a Car:

Enter your name

Choose from available cars

Specify number of rental days

Confirm the rental

Return a Car:

Enter the car ID to return it

System verifies if the car is rented

Confirms successful return

Exit:

Quit the application

🏁 Getting Started
Prerequisites
Java 8 or above

A Java IDE like Eclipse, IntelliJ, or a terminal with javac

Running the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/car-rental-management.git
cd car-rental-management
Compile the program:

bash
Copy
Edit
javac car_rental_management/*.java
Run the application:

bash
Copy
Edit
java car_rental_management.Main
📂 Project Structure
less
Copy
Edit
car_rental_management/
│
├── Car.java           // Car class with rental logic
├── Customer.java      // Customer information
├── Rental.java        // Stores rental transactions
├── CarRentalSystem.java  // Core logic and menu system
├── Main.java          // Entry point to the application
✨ Future Improvements
Add persistent storage (file/database)

Admin panel to manage cars

GUI-based frontend

Search and filter options for cars

Track rental history per customer

📄 License
This project is licensed under the MIT License.
