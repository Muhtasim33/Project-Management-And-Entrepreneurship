# FixBondhu: A Location-Based Home Repair Service Platform

FixBondhu is a location-based web platform that connects customers with nearby verified skilled service providers, such as plumbers, electricians, air conditioner technicians, and gas stove repair workers. The platform addresses the common problem of finding a trustworthy technician quickly during household emergencies, such as water leaks, electrical faults, or gas stove failures. By replacing the informal reliance on word-of-mouth or outdated phone numbers, FixBondhu provides a system where customers can view a worker's reliability, current availability, distance, and fair pricing.

## Unique Selling Point
The platform's unique selling point is speed combined with trust, offering the fastest way to find a verified, nearby technician during an emergency.

## Key Features
* **Location-Based Discovery:** Customers can discover available workers around them on a live map, with search results ranked by distance, rating, and availability.
* **Verified Trust System:** Workers create profiles with their skills and service categories, and the system grants a verified badge upon admin approval of their National ID (NID) and skill evidence.
* **Emergency Booking Flow:** Customers can create normal or emergency service requests, attach photos of the issue, and view upfront price and time estimates before booking.
* **Live Request Tracking:** Customers and technicians can track a request through its full lifecycle, from the moment it is sent to its completion.
* **Ratings and Moderation:** Customers can rate and review a worker from one to five stars after a completed service, while administrators handle dispute resolution, moderation, and fraud prevention.

## System Architecture
The platform is built on a three-tier architecture to separate presentation, application logic, and data:
* **Presentation Tier (Web App):** Manages the interfaces for customers, technicians, and administrators, covering the map, profiles, search, and tracking dashboards.
* **Application Tier (Backend / API):** Handles the core business logic, including account verification, location-based matching, status transitions, and role-based access control.
* **Data Tier (Database):** Provides persistent storage for users, worker profiles, service requests, reviews, service categories, and geographic coverage areas.

## Future Scope
* Implementation of in-app online payments and digital invoices to enable cashless transactions.
* Development of native mobile applications for iOS and Android platforms to better support emergency, on-the-go usage.
* Introduction of a smart recommendation feature to automatically suggest the best-matched worker based on distance, rating, and availability.
* Integration of in-app chat and calling functionalities between customers and service providers.
