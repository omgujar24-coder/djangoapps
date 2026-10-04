# Project Name: Dealership Review Web Application

**Repository Name:** djangoapps-capstone  
**Author:** Full Stack Developer  
**Course:** IBM Full Stack Software Developer Capstone Project  

---

## Project Overview

The **Dealership Review Web Application** is a full-stack website built using microservices architecture. It allows users to browse nationwide car dealerships, filter them by state, view customer reviews with sentiment analysis, and register/login to post their own reviews with car make and model details.

---

## Tech Stack & Architecture

- **Frontend:** React.js, HTML5, CSS3, Bootstrap
- **Backend (Web Application):** Django (Python)
- **Backend (Dealership & Review Microservices):** Express.js / Node.js
- **Database:** MongoDB (Dealerships & Reviews), SQLite / PostgreSQL (Django User Management & Car Models)
- **Containerization & Deployment:** Docker, IBM Cloud / Kubernetes

---

## Features Implemented

1. **Static Pages & Navigation:**
   - Home, About Us, and Contact Us static pages with responsive UI.
   
2. **User Authentication & Management:**
   - User Registration, Login, and Logout functionality.
   - Django Admin superuser management.
   - Dynamic navbar updating login/logout state.

3. **Car Make & Model Management:**
   - Django Models for `CarMake` and `CarModel`.
   - Registered models with Django Admin.

4. **Microservices Integration:**
   - Node.js Express server to fetch dealerships (`/fetchDealers`, `/fetchDealers/:state`, `/fetchDealer/:id`).
   - REST API helper methods (`get_request`, `post_review`) in Django `restapis.py`.

5. **Review Submission System:**
   - React components for rendering dealership lists and detailed dealer views.
   - Review posting interface allowing logged-in users to submit reviews with purchase dates, car makes, and models.

---

## Local Setup & Installation

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/djangoapps-capstone.git](https://github.com/YOUR_GITHUB_USERNAME/djangoapps-capstone.git)
   cd djangoapps-capstone
