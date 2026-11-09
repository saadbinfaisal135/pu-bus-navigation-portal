# Campus Navigation Portal & University Bus Tracking System

An interactive, web-based transit navigation portal designed for university campus navigation and real-time bus route tracking. The application combines geospatial visualization with a robust backend architecture to deliver accurate route mapping, scheduled arrivals, and dynamic administrative control.

<img width="1336" height="530" alt="image" src="https://github.com/user-attachments/assets/c2038a9c-c88b-4613-8ff6-fc2e1b9ef2a0" />

## 📌 Project Overview

Navigating large university campuses and tracking daily transit schedules often presents logistical challenges for students and staff. This project addresses these bottlenecks by integrating spatial data management with modern web technologies:

- **Interactive Campus Navigation:** Provides detailed spatial orientation across campus buildings, road networks, and key transit hubs.

<img width="1353" height="607" alt="image" src="https://github.com/user-attachments/assets/3e27ac66-74ea-47b3-a78a-e898a3f86f14" />

<img width="1350" height="607" alt="image" src="https://github.com/user-attachments/assets/be71fbc1-a2bd-4d82-993a-cf9a7474bdd3" />

- **Real-Time Bus Tracking:** Displays live transit routes, designated stops, and scheduled timings.

<img width="1352" height="613" alt="image" src="https://github.com/user-attachments/assets/23ff58e2-e2bc-4414-a93b-035bbc7f73d4" />

<img width="1197" height="663" alt="image" src="https://github.com/user-attachments/assets/4fb5a5c0-677d-453b-acb5-74347a9f5ef7" />


- **Dynamic Administrative Dashboard:** Centralized interface to manage bus routes, schedules, and active transit operations.

<img width="1355" height="599" alt="image" src="https://github.com/user-attachments/assets/ee4cf05d-566b-4b76-9138-361f57082765" />

<img width="1071" height="840" alt="image" src="https://github.com/user-attachments/assets/b375e21b-caf1-4b6f-bb0c-3efffc3776c2" />

<img width="1249" height="568" alt="image" src="https://github.com/user-attachments/assets/723917ab-9481-45a5-a30c-4eeb2e166f83" />

<img width="1257" height="542" alt="image" src="https://github.com/user-attachments/assets/91560656-4a72-488f-ad85-d519840813f7" />

<img width="1324" height="750" alt="image" src="https://github.com/user-attachments/assets/07231b55-189c-4c1e-a3fd-8703c76996be" />

---

## 🛠️ Architecture & Tech Stack

### Frontend & Spatial Mapping
- **React.js:** Component-driven, responsive user interface.
- **Leaflet.js:** Lightweight interactive web mapping library for rendering geospatial layers, waypoints, and transit paths.
- **HTML5 & CSS3:** Semantic markup and modular layouts.

### Backend & Ingestion Pipelines
- **Node.js & Express.js:** RESTful API server handling client requests, transit data ingestion, and routing logic.
- **PostgreSQL & PostGIS:** Relational database storage powering spatial queries, user authentication, and schema integrity.

<img width="2698" height="674" alt="image" src="https://github.com/user-attachments/assets/eeb475a1-f376-4303-98d2-0005949e7269" />

<img width="1331" height="1031" alt="image" src="https://github.com/user-attachments/assets/69b93e3a-5165-441c-ad86-282da061b8b2" />

---

## ⚙️ Key Technical Features

1. **Geospatial Route Visualization**
   - Ingests and renders transit vector coordinates directly onto a dynamic Leaflet base map.
   - Smooth rendering of multi-point bus routes and stop waypoints.

2. **Relational Database Schema Design**
   - Structured PostgreSQL schemas optimized for user authentication, role-based access (Student/Admin), and transit metadata (buses, drivers, routes, schedules).
   - Efficient data querying to minimize server response latency during high-traffic transit hours.

3. **Data Ingestion & In-Transit Logic**
   - Endpoints designed using Express.js to parse and update route telemetry in real time.
   - Robust error handling and validation pipelines to prevent data inconsistency.

---

## 🚀 Getting Started Locally

### Prerequisites
- Node.js (v18+ recommended)
- PostgreSQL (with PostGIS extension enabled)
- npm or yarn

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/saadbinfaisal135/pu-bus-navigation-portal.git](https://github.com/saadbinfaisal135/pu-bus-navigation-portal.git)
   cd pu-bus-navigation-portal
