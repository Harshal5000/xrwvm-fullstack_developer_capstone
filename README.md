# Dealership Application - Full-Stack Developer Capstone Project

A comprehensive national car retailer web application developed as part of the IBM Full-Stack Software Developer Professional Certificate Capstone.

## Project Architecture
- **Backend (Django):** Manages user authentication, sessions, car inventory (makes & models), and serves static assets.
- **Frontend (React):** Responsive Single Page Application (SPA) for browsing dealerships, filtering by state, and posting/viewing customer reviews.
- **Database Service (Node.js & Express):** Microservice connecting to MongoDB for dealership locations and review archives.
- **Sentiment Analyzer (Flask & NLTK VADER):** Microservice evaluating sentiment polarity of user reviews.
- **CI/CD & Cloud Deployment:** Automated workflows with GitHub Actions and containerized deployments via Docker and IBM Cloud Code Engine.
