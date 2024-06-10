![class diagram](https://github.com/khaledkamr/Software-engineering-project/assets/94804298/c365b1a1-322e-4144-b08d-527c51296c48)


The class diagram for the airline booking system represents the structure and relationships between various entities within the system. It includes the following primary classes: `User`, `Customer`, `Travel Agent`, `Counter`, and `Flight`.

#### Relationships:

- **Inheritance**:
  - The `Customer`, `Travel Agent`, and `Counter` classes all inherit from the `User` class, indicating that they share common attributes and methods related to user functionalities.

- **Associations**:
  - **Customer to Flight**: A customer can book a flight, represented by an association with a multiplicity of 1 to 1.
  - **Travel Agent to Flight**: A travel agent can book a flight, represented by an association with a multiplicity of 1 to 1.
  - **Counter to Flight**: A counter staff member can book a flight, represented by an association with a multiplicity of 1 to 1.

- **Aggregation**:
  - **User to Travel Agent**: There is an aggregation relationship where a user can act as a travel agent, managing various tasks associated with flight bookings and customer service.

This class diagram effectively illustrates the core components and their interactions within the airline software system, providing a comprehensive overview for development and implementation.
