# airbnb-clone-project

The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.

Tech Stack
1. Django : A Python framework used to develop RestFul APIs.
2. Django Rest Framework: Provides tools for managing and crating Restful APIs.
3. Celery: Used for hndling asynchronous tasks such as processing payments, notifications etc.
4. Postgres: A relational database used to store data.
5. GraphQL: Allows for flexible and efficient data querying.
6. Redis : Used for caching and session management.
7. Docker : Used for containerization of projects/hosting.
8. CI/CD pipelines: Automated pipelines for testing and deploying of projects.

Project Goals
To create a clone of the airbnb app and in so doing explore the various capabilities of the Django Rest Framework. This project will expose me to integrating API endpoints, handling user authentication, implementing advanced security measures in API development, plan and document complex software projects, understand backend architecture and database design principles 

Database Design
Users: Register users, authenticate users, manage user profile. One to many relationship. A user can list many properties.
Property: Create, Read, Update and delete property enlistings. Will be linked to bookings. One to many relationship because 1 property can have several bookings at different times.
Bookings: Manage all bookings, check ins and check outs.
Payment: manage all payments made for booking of property.
Review System: Create, Update, Delete all reviews given per property. Must be linked to the property in a 1 to many relationship. 1 property can have many reviews.

Feature Breakdown
User management: Allow the registration and Authentication of a user before they access more privileges. Owners of propery will have the ability/role to update their property listings accordingly. Users will have the ability to book and make payment for reservations to be made.
Property Management: This feature will allow for uploading of property per user and overall management of the property.
Booking management: This feature will allow the booking of property by a customer, to be reserved by the owner of the property. It will entail initialising and confirming of payment.
Payment management: Will manage payment for the reservation of property. This will facilitate confirmation that a booking has been made.
Reviews management: Will allow the reviewing of property by users as a means to communicate trust or otherwise to future patrons of the property.

API Security
In order to ensure user data privacy the following willl be used:
1. Token based User authentication, role based permision
2. Rate limiting and throttling to prevent abuse and brute force attacks.
3. Use of HTTPS/SSL to ensure data protection of users data.

CI/CD pipelines
They will allow the continuous integration of new features and changes to the project without affecting the primary site while it's deployed via docker.

