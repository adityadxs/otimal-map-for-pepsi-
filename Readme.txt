# 🚚 Smart Delivery Route Optimizer

A web-based delivery route optimization system that helps delivery personnel complete deliveries in the most efficient order. The application automatically calculates the optimal route, displays it on an interactive map, tracks completed deliveries, and saves the entire delivery session using Local Storage.

---

## 📌 Project Overview

The Smart Delivery Route Optimizer is designed to simplify last-mile delivery operations. It selects delivery locations, determines the shortest possible delivery sequence, provides real-time navigation support, and allows delivery agents to track their progress throughout the day.

The application uses geolocation, mapping services, and route optimization algorithms to minimize travel distance and delivery time.

---

# ✨ Features

## 📍 Automatic Location Detection
- Detects the driver's current location using the browser's Geolocation API.
- Displays the current position on the map.
- Uses the current location as the starting point for route optimization.

---

## 🗺 Interactive Map
- Built using Leaflet.js with OpenStreetMap.
- Shows:
  - Driver's location
  - Delivery stores
  - Optimized route
  - Route numbering
  - Distance labels

---

## 🚛 Route Optimization
The application automatically calculates the best delivery sequence using the Nearest Neighbor Algorithm.

Benefits:
- Reduces travel distance
- Saves delivery time
- Minimizes fuel consumption
- Updates automatically after every completed delivery

---

## 📦 Store Management

Stores are loaded from a JSON dataset.

The system:
- Randomly selects delivery locations
- Prevents duplicate stores
- Displays store information
- Tracks delivery status

---

## ✅ Delivery Tracking

Each delivery can be marked as completed.

After completion:
- Store changes to Completed
- Route updates automatically
- Remaining deliveries are recalculated
- Distance and ETA refresh instantly

---

## 📊 Live Dashboard

Displays:

- Current Location
- Next Destination
- Remaining Stops
- Completed Deliveries
- Total Distance
- Estimated Time

---

## 💾 Local Storage Support

The application automatically saves:

- Current delivery list
- Completed deliveries
- Route order
- Distance
- Estimated time
- User location
- Travel mode

Refreshing the browser does **not** lose progress.

---

## 🚗 Multiple Travel Modes

Supports:

- Driving
- Cycling

Changing the travel mode recalculates the optimized route.

---

## 📤 Excel Report Export

The application can export delivery reports to Excel using SheetJS.

The report includes:

- Store Name
- Coordinates
- Delivery Status
- Route Order
- Distance
- Estimated Time

---

## 🌐 Google Maps Navigation

Supports:

- Navigate to Next Stop
- Navigate Full Route

Google Maps opens automatically with directions.

---

## 🔔 Notifications

Modern toast notifications provide updates for:

- Route optimization
- Store completion
- Errors
- Location updates
- Session restoration

---

## 📱 Responsive Design

Fully responsive interface supporting:

- Desktop
- Laptop
- Tablet
- Mobile Devices

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript (ES6) | Application Logic |
| Leaflet.js | Interactive Maps |
| OpenStreetMap | Map Tiles |
| OSRM API | Route Calculation |
| Geolocation API | Current Location |
| Local Storage | Session Persistence |
| SheetJS | Excel Export |
| Font Awesome | Icons |
| JSON | Store Dataset |

---

# 📂 Project Structure

```
Smart-Delivery-Route-Optimizer/
│
├── index.html          # Main application
├── stores.json         # Store dataset
├── README.md           # Documentation
```

---

# 🚀 How to Run

## Step 1

Download or clone the project.

```
git clone https://github.com/adityadxs/otimal-map-for-pepsi-.git
```

---

## Step 2

Open the project folder.

---

## Step 3

Run the project using a local server.

Examples:

VS Code Live Server

or

Python

```
python -m http.server
```

or

```
npx serve
```

---

## Step 4

Open

```
http://localhost:8000
```

(or the port provided by your server.)

---

# 📋 Workflow

1. Open the application.
2. Allow location access.
3. Stores are loaded automatically.
4. Click **Optimize Route**.
5. Follow the suggested delivery order.
6. Mark deliveries as completed.
7. Route updates automatically.
8. Export delivery report if required.
9. Close or refresh anytime—progress is restored automatically.

---

# 📈 Advantages

- Faster deliveries
- Lower fuel costs
- Better route planning
- Automatic session recovery
- Easy navigation
- Simple and user-friendly interface
- Works entirely in the browser

---

# 🔮 Future Improvements

- Multiple delivery agents
- Admin dashboard
- Authentication system
- Live traffic integration
- AI-based route optimization
- Vehicle capacity optimization
- Delivery time windows
- Backend database integration
- Cloud synchronization
- Mobile application

---

# 👨‍💻 Developed By

**Aditya Suman**

Project: Smart Delivery Route Optimizer

Built as a logistics optimization solution for improving delivery efficiency using web technologies, interactive mapping, and intelligent route planning.

---

# 📄 License

This project is intended for educational and demonstration purposes.

Feel free to modify and enhance it according to your requirements.