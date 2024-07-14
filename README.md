# BUSTICKET-RESERVATION-SYSTEM

Features
Trip Management :Users can easily add, modify, and cancel bus trips, specifying essential details such as departure time, pick-up, and drop-off locations, and vehicle information.

Ticket Booking: Passengers can book bus tickets by providing trip details, including pick-up and drop-off locations, departure time, and passenger information.

Cancellation: Passengers can cancel booked tickets if needed, with the system handling seat availability and updates accordingly.

Ticket Details: Passengers can view details of their booked tickets, including trip information and passenger details.

Data Persistence: The system maintains logs of trips and booked tickets, ensuring data integrity and providing a reliable record of transactions.

Implementation
The system is implemented in Python and utilizes object-oriented programming principles. Key components include classes for managing vehicles, trips, locations, and transport services. Data structures like AVL trees are employed for efficient storage and retrieval of trip information. The system's modular architecture allows for easy extension and customization to meet specific requirements.
Usage
First, we store the details of all the buses, including their vehicle number, seating capacity, pick-up location, drop location, and departure time, using the add_trip method.
Next, the user can retrieve a list of all buses operating from the location specified by the user within the time interval provided by the user via the show_trips method.
After viewing available trips, the user can proceed to book a ticket accordingly. Additionally, users have the option to cancel their ticket reservations.
