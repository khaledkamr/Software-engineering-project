# Online booking

<img src="https://github.com/khaledkamr/Software-engineering-project/assets/94804298/35af8830-9fa0-4b86-ab0e-8c447e895e80" width="300px">

The activity diagram illustrates the process flow of an airline booking system for booking and canceling tickets online. It captures the sequence of actions taken by a user, starting from logging in to logging out, with paths for both booking a ticket and canceling a ticket.

#### Activities and Decision Points:

1. **Login**
   - The process starts with the user logging into the system.

2. **Decision: Booking or Canceling**
   - After logging in, the user has two main options: book a ticket online or cancel an existing ticket online.

#### Booking a Ticket Online Path:

1. **Book Ticket Online**
   - The user initiates the process to book a ticket online.

2. **Enter Personal Information**
   - The user provides the necessary personal information required for the booking.

3. **Choose Flight**
   - The user selects a flight from the available options.

4. **Enter Payment Information**
   - The user enters payment details to proceed with the booking.

5. **Decision: Payment Information Validity**
   - The system checks if the entered payment information is valid.
     - **No**: If the payment information is invalid, the user is prompted to re-enter payment information.
     - **Yes**: If the payment information is valid, the booking process continues.

6. **Book Flight**
   - The flight is successfully booked.

7. **Logout**
   - The user logs out of the system, completing the booking process.

#### Canceling a Ticket Online Path:

1. **Cancel Ticket Online**
   - The user initiates the process to cancel a ticket online.

2. **Enter Reservation Information**
   - The user provides the reservation information required to cancel the ticket.

3. **Cancel Flight if Available**
   - The system checks if the flight can be canceled.

4. **Decision: Cancellation Availability**
   - The system verifies if the flight can be canceled.
     - **Yes**: If the flight can be canceled, the cancellation process proceeds.
     - **No**: If the flight cannot be canceled, the user has the option to search for other flights.

5. **Cancel Flight**
   - The flight is successfully canceled.

6. **Search for Flights**
   - If the flight cannot be canceled, the user is given the option to search for other flights.

7. **Logout**
   - The user logs out of the system, completing the cancellation process.
