# User Stories

Format: As a [type of user], I want [goal], so that [reason or benefit].
1. As a student or tutor, I want to register an account so that I can access the tutoring system.
- AC1: Given valid registration details, when the user submits the registration form, then the system creates and securely stores the account.
- AC2: Given invalid or incomplete registration details, when the form is submitted, then the system displays an appropriate error message.

2. As a student, tutor, or admin, I want to log in so that I can access the functions allowed for my role.
- AC1: Given valid credentials, when the user logs in, then the system grants access to the verified account.
- AC2: Given invalid credentials, when the user attempts to log in, then the system denies access.

3. As a student, I want to browse available tutors so that I can select a suitable tutor.
- AC1: Given available tutor records, when the student browses tutors, then the system displays tutor details and available time slots.
- AC2: When the student searches for tutors, then the system displays matching available tutors, if any.

4. As a student, I want to book a tutor's available time slot so that I can attend a tutoring session.
- AC1: Given an available tutor and time slot, when the student selects the tutor, date and time, then the system allows the student to proceed with booking and payment.
- AC2: When payment is successfully completed, then the system confirms the booking and generates a QR code for the session.

5. As a student, I want to pay for a tutoring session so that my booking can be confirmed.
- AC1: The system allows the student to make payment using a card, online banking or QR payment.
- AC2: When payment fails, the system does not treat the booking as paid or confirmed.

6. As a student, I want to receive session reminders so that I know the details of my upcoming tutoring sessions.
- AC1: The system generates a reminder notification containing the relevant session details.
- AC2: If notification delivery fails, the system retries sending the notification.

7. As a student, I want to view my upcoming sessions and enter a virtual classroom so that I can attend lessons online.
- AC1: The system displays the student's upcoming booked sessions.
- AC2: The system provides a way for the student and tutor to connect in a virtual classroom.

8. As a student, I want to receive a personalized learning summary and quiz so that I can review what I learned.
- AC1: The system retrieves completed tutoring session data and uses available lesson content, notes or transcripts for analysis.
- AC2: The system generates a personalized learning summary and an interactive quiz based on the discussed topic.

9. As an administrator, I want to manage student and tutor accounts so that I can oversee system users.
- AC1: The administrator can view and manage user account data.
- AC2: The administrator can approve qualified tutor registrations and remove tutor accounts that do not comply with system rules.