# SmartFleet-AI
 Gen AI-Powered Intelligent Bus Management
 
🚍 SmartFleet AI – Gen AI Powered Intelligent Bus Management

SmartFleet AI is a Gen AI-powered centralized fleet management system** for government/KSRTC buses. It uses real-time ticket machine data and Gen AI APIs to predict bus occupancy, optimize bus allocation, and dynamically shuffle passengers. This ensures fuel savings, efficient resource usage, and better passenger experience.


📌 Problem Statement

Public bus services lack real-time occupancy tracking and AI-driven fleet allocation, leading to:

* Wastage of fuel due to half-empty buses.
* Overcrowding during high-demand routes.
* Poor passenger experience due to uncertainty in seat availability.


🎯 Solution

SmartFleet AI integrates Gen AI APIs with real-time passenger and route data to:

1. Predict occupancy for upcoming bus stops.
2. Dynamically allocate or merge buses.
3. Provide AI-guided instructions to passengers on which bus to board.
4. Notify transport authorities about fleet optimization opportunities.


🌟 Unique Selling Proposition (USP)

AI-driven decision making instead of static scheduling.
Passenger shuffling guidance in real time.
Fuel optimization through smart allocation.
Predictive pre-booking insights for passengers.
  
🚀 Features

* Real-time passenger count from ticket machines.
* AI-powered bus occupancy prediction.
* Dynamic bus merging & allocation.
* Passenger pre-booking with predicted seat availability.
* Notifications for passengers and operators.
* Analytics dashboard for authorities.

 🔄 Process Flow
Ticket Machine → Real-Time Passenger Count
        ↓
       GPS + Route Data
        ↓
Central Data Hub (Cloud)
        ↓
Gen AI API Engine
   - Predict occupancy
   - Suggest allocation & passenger shuffle
        ↓
Bus Allocation System
   - Merge / Add buses
   - Notify passengers
        ↓
Passenger App / Admin Dashboard

 🖼 Architecture

Frontend: Flutter / React (Passenger & Admin apps)
Backend: FastAPI / Node.js
Database: Cloud SQL / Firebase Firestore
AI Layer: Google Cloud Vertex AI / OpenAI API for reasoning & predictions
Integration: WebSocket / REST APIs for ticket machine + GPS data
Notifications: Firebase Cloud Messaging / Twilio SMS


 🛠 Technologies Used

Google Cloud AI / OpenAI APIs (for Gen AI reasoning)
FastAPI / Node.js (Backend APIs)
Flutter / React (Frontend apps)
Firebase / Cloud SQL (Database)
IoT ticket machine integration (Passenger count data)



💰 Estimated Implementation Cost (Prototype)

Google Cloud Vertex AI / OpenAI API usage: ₹4,150 – ₹8,300
Cloud SQL / Firestore storage: ₹830 – ₹1,660
Mobile app hosting: ₹415 – ₹830
Total Estimated Prototype Cost: ₹5,400 – ₹10,800






