
**CONCURRENT SOCKET SYSTEM**

This is a train ticket booking system where users can search, book, and cancel train tickets. It also handles user authentication and seat availability in real-time.

**Features**

	•	Train Search: Users can search for available trains based on their journey details.
	•	Ticket Booking: Users can book tickets on available trains.
	•	Ticket Cancellation: Users can cancel their bookings.
	•	User Authentication: Users log in securely using hashed passwords (via BCrypt).
	•	JSON Handling: Train schedules and user information are managed using Jackson for parsing and serializing data.
	•	Seat Availability: Real-time updates on seat availability during booking and cancellations.

**How It Works**

	1.	User Authentication: Users sign up with a password, which is hashed using BCrypt to ensure security.
	2.	Train Search: Users enter travel details, and the system shows available trains.
	3.	Booking & Cancellation: Users can book or cancel tickets, and the system updates seat availability in real-time.
	4.	Data Management: Data such as train schedules and user bookings are managed using Jackson for JSON serialization.

**Technologies Used**

	•	Java
	•	BCrypt (for password hashing)
	•	Jackson (for JSON parsing and serialization)

**How to Run**

	1.	Clone the repo:
	2.	Open the project in your IDE.
	3.	Run the main class to start the application.
