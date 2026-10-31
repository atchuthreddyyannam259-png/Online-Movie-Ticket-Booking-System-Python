1. Project Description

The Online Movie Ticket Booking System is a console-based application developed using Python and SQLite. It helps users book movie tickets and manage their bookings easily. Users can view available movies, check show timings, book tickets, view booking details, and cancel bookings. The system also calculates the total ticket price automatically.

2. Features

- View Movies: Displays available movies and their ticket prices.
- View Show Timings: Displays the timings of available movies.
- Book Tickets: Allows users to select a movie and enter the number of tickets.
- Price Calculation: Automatically calculates the total ticket price.
- View Bookings:Displays previously stored booking details.
- Cancel Booking: Allows users to cancel a booking using the booking ID.

3. Technologies Used

- Python
- SQLite
- sqlite3 module

 4. How to Run

1. Open Jupyter Notebook.
2. Open the Python program.
3. Execute the program.
4. Select an option from the displayed menu.
5. Follow the instructions to perform the required operation.
6. Select Exit to close the program.

5. Database

The project uses an SQLite database named `movie.db` to store booking information.

A table named `bookings` is created automatically with the following fields:

id: Unique booking ID.
name: Customer name.
movie: Selected movie name.
tickets: Number of tickets booked.
total: Total ticket price.

The database uses SQL commands to insert, retrieve, and delete booking records.

6. Future Enhancements

- Add user registration and login.
- Provide seat selection.
- Include online payment facilities.
- Add a graphical user interface.
- Support multiple theatres and show schedules.
