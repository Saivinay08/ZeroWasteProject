# ZeroWasteProject
## Problem Statement
Every day, massive quantities of edible food are wasted while millions of people remain food-insecure. This is often due to a lack of coordination between food donors (restaurants, individuals, events) and recipients (NGOs, shelters, etc.). ZeroWaste is a scalable, intelligent web platform designed to bridge this gap using real-time location and managing logistics.
## Objective
To develop a centralized food donation and rescue platform that:
- Minimizes food wastage
- Empowers real-time connections between donors and receivers
- Leverages technology to automate pickups and manage logistics

##  Key Features

###  Donor Panel
- Register via email
- Post food availability,quantity
- Track donation status (Pending → Accepted → Picked → Verified)

###  Receiver Panel (NGOs / Volunteers)
- Role-based registration & verification
- View donations on an interactive map
- Filter by food type, freshness
- Accept or request pickups
- Confirm delivery with optional rating

###  GeoMap Dashboard
- Google Maps / OpenStreetMap integrated   
- Live pickup routing using Google Directions API

## Tech Stack Used

### Frontend:
- HTML, CSS, JavaScript
- EJS (Embedded JavaScript templates)
  
### Backend:
- Node.js
- Express.js
  
### Database:
- Firebase Realtime Database (for real-time data sync and scalability)

### APIs and Services:
- Google Maps API (location display)
- Google Directions API (pickup routing)
- Firebase Authentication

##  Workflow

1. User Registration:  
   - Donors, receivers register via email/OAuth.

2. Food Donation Posting (Donor):  
   - Enter food details,quantity and donor's address.

3. Real-Time Visibility (Receiver):  
   - Nearby NGOs/volunteers see available donations on a live map with filtering options.

4. Pickup and Routing:  
   - Once accepted, live pickup route is shown using Google Directions API.