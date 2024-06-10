# Book at the counter

<img src="https://github.com/khaledkamr/Software-engineering-project/assets/94804298/10daa554-29db-4490-9a35-0256669290b3" width="300px">

This activity diagram represents the workflow of an airline booking system, illustrating the processes involved in booking and canceling tickets at a counter. The diagram begins with the `login` activity and ends with the `logout` activity, highlighting two primary paths: booking a flight and canceling a ticket.


#### Activities and Decision Points:

1. **Login**
   - The process begins with the user logging into the system.

2. **Decision: Booking or Canceling**
   - The user can choose to either book a flight at the counter or cancel a ticket at the counter.

#### Booking a Flight Path:

1. **Book at Counter**
   - The user initiates the flight booking process at the counter.

2. **Give Personal Information**
   - The user provides personal information required for booking.

3. **Choose Flight**
   - The user selects a flight from the available options.

4. **Payment Information**
   - The user enters payment information to proceed with the booking.

5. **Decision: Payment Information Validity**
   - The system checks if the payment information is valid.
     - **No**: If the payment information is not valid, the user is prompted to re-enter payment information.
     - **Yes**: If the payment information is valid, the booking process continues.

6. **Book Flight**
   - The flight is successfully booked.

7. **Logout**
   - The user logs out of the system, completing the booking process.

#### Canceling a Ticket Path:

1. **Cancel Ticket at Counter**
   - The user initiates the ticket cancellation process at the counter.

2. **Give Reservation Information**
   - The user provides reservation information required for canceling the ticket.

3. **Cancel Flight if Available**
   - The system checks if the flight can be canceled.

4. **Decision: Cancellation Availability**
   - The system verifies if the flight can be canceled.
     - **Yes**: If the flight can be canceled, the cancellation process continues.
     - **No**: If the flight cannot be canceled, the user can search for flights instead.

5. **Cancel Flight**
   - The flight is successfully canceled.

6. **Search for Flights**
   - If the flight cannot be canceled, the user is given the option to search for other flights.

7. **Logout**
   - The user logs out of the system, completing the cancellation process.
