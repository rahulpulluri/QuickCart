# QuickCart

Developed a microservices application with services for User Authentication, Ticket Creation, Order Creation, Payment, and Timed Expiration. Users can list and purchase event tickets. When a user attempts to purchase a ticket, it is 'locked' for 15 minutes to allow payment processing. If the payment is not completed within this time, the ticket unlocks. Ticket prices can be edited if they are not locked.

## Tech Stack

**Architecture:** Microservices

**Backend Server:** Node.js, Express.js 

**Frontend:** React.js

**Payment Processing:** Stripe

**Data Modeling:** Redis

**Deployment:** Docker, Kubernetes
