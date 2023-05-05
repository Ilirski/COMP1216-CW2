# COMP1216-CW2

Our group's COMP1216 Coursework 2 project.

## System Outline: Online Pharmacy Tracking System
The system being modelled is an Online Pharmacy Tracking System. Pharmacy chain ApotheCare is developing a system to manage the dispensation of medicines for clients who have signed up for the service. Based on a record of prescriptions, this system ensures clients have adequate medicinal supplies on a weekly basis and will respond to them if they are running low or have run out. Clients can book appointments to obtain complete sets of medication at the company’s various pharmacies. Pharmacy administrators need to manage the number of available appointments and update on the medicine stock. For Coursework 2, we have formally model this system using Event-B according to the following requirements.

### Requirements
- REQ 1: The system manages a set of registered users.
- REQ 2: The system should only allow a user to log in to the system using the correct password.
- REQ 3: A logged-in user can log out of the system.
- REQ 4: There are three roles for users: administrator, staff, or client.
- REQ 5: A user can only have one role in the system.
- REQ 6: The root user is the initial administrator.
- REQ 7: A logged-in administrator can register a new user for the role of administrator or staff.
- REQ 8: A client can register an account with the system directly.
- REQ 9: A logged-in user can change their password.
- REQ 10: Each packet of medicine has a name and a batch number.
- REQ 11: Each client has a name, an NRIC (MyKad) number, and a list of prescriptions for medicine.
- REQ 12: Each prescription includes the medicine information and the date the client last received a packet of medicine.
- REQ 13: A client can retrieve their prescriptions from the system.
- REQ 14: A pharmacy has a medicine stock specifying the availability of medicines.
- REQ 15: An administrator can update the medicine stock by adding more medicine batches.
- REQ 16: A pharmacy has a daily number of appointments.
- REQ 17: A pharmacy maintains a list of booked appointments.
- REQ 18: An administrator or a staff can view the client’s details using their NRIC (MyKad) number.
- REQ 19: A client can only book an appointment if a pharmacy has every medicine on their prescription in stock.
- REQ 20: A client is offered the earliest available appointment at any pharmacy.
- REQ 21: If the client rejects the current offer, the system offers the following earliest appointment, that might be at a different pharmacy.
- REQ 22: If the client accepts the current offer, the booking is confirmed.
- REQ 23: At any point during the booking process, the client can abandon the system without completing the booking.
- REQ 24: The booking is stopped if there are no more available appointments within the 7 days from the date of login to the appointment offer.
- REQ 25: A client can view their current booking (if any).
- REQ 26: Rebooking an appointment can be done up to 1 day before the date of the original one.
- REQ 27: Rebooking follows the same rules as booking.
- REQ 28: After re-booking is confirmed, the original appointment becomes available.
- REQ 29: A staff member can update the client’s prescriptions after delivering medicine packets.
- REQ 30: The medicine stock of a pharmacy needs to be updated when the prescription is updated for a client
