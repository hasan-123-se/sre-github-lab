# Online Flat Renting and Accommodation Finding System
## Overview
Students, working professionals, and property owners need a reliable, transparent way to list, discover, and lease residential spaces without relying on expensive middlemen. 
The proposed system will help a student find affordable near-campus housing, contact landlords directly, and secure flats or shared rooms smoothly.
By automating the search and verification process, this platform reduces the time spent physically scouting for accommodation and prevents rental fraud.

## Scope
- In scope: User registration and profile management (Students, Landlords, Guests).
- In scope: Property listing creation with details (rent, location, amenities, images).
- In scope: Advanced search filters (price range, distance from PUCIT, accommodation type).
- In scope: Direct messaging system between tenants and landlords.
- Out of scope: Legal dispute resolution between tenants and landlords.
- Out of scope: Automatic property maintenance and utility bill management.

## Stakeholders
- Student / Tenant: Browses listings, filters accommodations, and contacts landlords to secure rentals.
- Instructor: Evaluates the project's software engineering documentation, architectural design, and final implementation.
- Project maintainer: Manages repository version control, continuous integration, and system updates.

## Functional requirements
- FR-01: The system shall let landlords create, update, or delete property listings with detailed descriptions and pricing.
- FR-02: The system shall display verified accommodation listings matching user-applied search filters.
- FR-03: The system shall enable authenticated students to send direct inquiries to landlords regarding specific properties.

## Nonfunctional requirements
- NFR-01: With 1,000 concurrent active listings, the property search results page shall load within 2 seconds in at least 95 of 100 trials on an agreed test network.
- NFR-02: Every user authentication and booking action shall encrypt personal and payment data using industry-standard TLS protocols.

## Acceptance criteria
- FR-01: Given a property entry with valid title, rent, and address, saving the listing makes it discoverable in the search portal.
- FR-02: Given three listings in the 'Anarkali' area, searching for 'Anarkali' displays exactly those three listings.
- FR-03: Sending a message from a student profile pushes a real-time notification to the designated landlord's inbox.

## Assumptions and open questions
- Assumption A-01: Landlords will provide accurate property images and authentic pricing data without misleading specifications.
- Question Q-01: Should the platform support an integrated digital payment gateway for security deposits, or rely entirely on offline cash transactions?
- Question Q-02: Which web hosting or cloud environment will be used to benchmark and test NFR-01 performance constraints?

## Project status and viewing
This is a documentation-oriented repository outlining the initial software requirements. No deployment pipeline has been configured yet.
Clone the repository and open README.md in your preferred markdown viewer or text editor to inspect updates.

##Author
 - Abubakar Hassan (Roll No: bsef24a537) - Punjab University College of Information Technology (PUCIT)

## Contributing
Create a documentation branch, edit and review README.
