# Book via agent

<img src="https://github.com/khaledkamr/Software-engineering-project/assets/94804298/cca90b94-2cca-4998-be15-7b84a278e955" width="300px">

This activity diagram outlines the process flow for booking and canceling airline tickets via an agent in an airline booking system. The process starts with user authentication and ends with user logout. The steps are as follows:

1. **Login**
   - The user initiates the process by logging into the airline booking system.

2. **Booking via Agent**
   - If the user chooses to book a flight via an agent:
     - **Give Personal Information**
       - The user provides necessary personal details to the agent.
     - **Choose Flight**
       - The user selects the desired flight from available options.
     - **Payment Information**
       - The user enters payment details for the booking.
       - If the payment information is valid:
         - **Book Flight**
           - The flight is booked successfully.
       - If the payment information is invalid:
         - **Re-enter Payment Information**
           - The user is prompted to re-enter payment details and the process checks the validity again.
     - The user is logged out of the system once the booking is complete.

3. **Canceling a Ticket via Agent**
   - If the user chooses to cancel a ticket via an agent:
     - **Give Reservation Information**
       - The user provides reservation details for the ticket they wish to cancel.
     - **Cancel Flight if Available**
       - The system checks if the flight can be canceled.
       - If the cancellation is possible:
         - **Cancel Flight**
           - The flight is canceled successfully.
       - If the cancellation is not possible:
         - **Search for Flights**
           - The user is given the option to search for alternative flights.
     - The user is logged out of the system once the cancellation or search process is complete.

4. **Logout**
   - The user logs out of the system, concluding the session.

This diagram ensures a clear understanding of the steps involved in booking or canceling flights via an agent, highlighting decision points and user interactions with the system.