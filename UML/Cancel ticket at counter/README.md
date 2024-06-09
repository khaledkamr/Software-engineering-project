# Use case modeling
## Use case description
### 5. Cancel ticket at counter:
| Function    | Cancel ticket at counter |
|-------------|--------------------------|
| Description | This use case involves the process of canceling a ticket at a physical counter, where counter staff interact with the ticketing system to process the cancellation. |
| Input | To cancel a ticket at the counter, the counter staff relies on a simple set of inputs. The customer provides the Ticket ID associated with the ticket they wish to cancel. Optionally, the counter staff may request additional customer information for identity verification. These inputs are essential for the counter staff to initiate the cancellation process within the ticketing system accurately. |
| Output | After canceling a ticket at the counter, the system provides the customer with a clear confirmation of the canceled ticket. If a refund is applicable, the system also communicates the relevant refund details to the customer. Concurrently, the counter staff ensures that details of the canceled ticket are securely stored within the system for future reference. These straightforward outputs serve to inform the customer about the cancellation status and maintain organized records within the system. |
| Action | To cancel a ticket at the counter, the staff, logged in, takes the customer's request. They enter the Ticket ID, check its validity, and if valid, update it to "canceled." The system might start a refund. The staff confirms the cancellation to the customer, keeps a record, and that's it. If the ticket can't be canceled, both know, and if there are tech issues, the staff follows the right steps. It's a straightforward process for canceling a ticket at the counter. |
| Pre-condition | Counter staff is logged into the ticketing system. Post condition Counter staff receives a customer’s request to cancel a ticket |
| Post condition |  Counter staff receives a customer’s request to cancel a ticket. |