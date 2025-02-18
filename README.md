 Flight_Ticket_Booking
 Simple Airline Booking System

 Overview
The Simple Airline Booking System is a GUIbased application developed using Python and Tkinter, with SQLite for database management. This system allows users to search for flights, book tickets, and cancel reservations seamlessly.

 Features
 Flight Booking: Users can search and book flights based on their boarding location, destination, travel date, and class preference.
 Flight Search: Users can check available flights for different routes and timings.
 Reservation Cancellation: Users can cancel their booked flights by providing their last fourdigit citizenship number.

 Technologies Used
 Python: Core programming language for the application.
 Tkinter: Used for building the graphical user interface.
 SQLite: Database used for storing and managing flight and booking data.

 Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/ramana11234/Flight_Ticket_Booking.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Flight_Ticket_Booking
   ```
3. Ensure you have Python installed (recommended: Python 3.x).
4. Install required dependencies (if any):
   ```sh
   pip install tk
   ```
5. Run the application:
   ```sh
   python main.py
   ```

 Usage
1. Launch the application by running `main.py`.
2. Choose an action from the main menu:
    Book a flight
    Search available flights
    Cancel a reservation
3. Follow the onscreen instructions to complete your desired action.

 Database Schema
The application uses SQLite with the following tables:
 eco: Stores flight details including boarding location, destination, day, time, class, and fare.
 economic2: Stores economic class bookings.
 common2: Stores business class bookings.

 Known Issues & Improvements
 The system does not handle duplicate bookings efficiently.
 The UI can be enhanced for better user experience.
 Error handling needs improvements to manage incorrect user inputs.

 Contribution
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

 License
This project is licensed under the MIT License. See the `LICENSE` file for details.

 Contact
For any questions or suggestions, please reach out via GitHub Issues.


Developed with ❤️ using Python & Tkinter

