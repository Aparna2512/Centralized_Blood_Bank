Centralized Blood Bank Management System

Problem Overview

Traditional blood donation awareness relies on media like radio, newspapers, or TV.
Current manual systems face issues in managing donor records, leading to data loss or duplication due to human error.
Lack of a centralized donor database complicates blood searches during emergencies.
Donors’ past donations are not tracked across different banks; new donations are treated as first-time donations without previous records.
Manual systems struggle to monitor blood stock levels, expiry, and minimum thresholds.

Project Overview

Objective: Digitize and streamline blood bank operations across India.

Goal: Simplify emergency blood searches and maintain records of donors, recipients, programs, and blood stocks.

Project Structure

Django (Framework)
Frontend:

Informational pages (Home, About, etc.)
User module: Register, login, logout
Docs page: Two variations
Search pages
List view for other modules

Backend:

Modules: User, Blood Bank, Blood Packets, Blood Donation Events, Donation Requests
Search features
Orders module

Database: PostgreSQL

Testing:

Models, views, URLs
API views testing
Django debug toolbar

Documentation:

Swagger integration
General project documentation

Deployment:

Using nginx server

Mock Application:

Built using Django
External Services Consumed
Facebook: Social sharing for donors to inspire others, with interaction features (like, share, comment).
Paypal: Provides an online payment gateway for users to purchase blood packets from local blood banks.

APIs Exposed

Donor CRUD: List of registered donors with city-based filtering.
Blood Bank and Blood Packets CRUD: List of registered blood banks and inventories, with city-based filtering.
Blood Donation Event CRUD: List of all registered blood events with details.
City-wise Donors: Filtered list of blood donors by city.
City-wise Blood Banks: Filtered list of blood banks by city.