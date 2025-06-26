# SurakshaNet: India's Disaster Response Network

SurakshaNet is a modern, responsive web dashboard for real-time monitoring and instant notifications of natural disasters across India. It provides users with location-based alerts, weather conditions, and notification history, all in a visually appealing interface.

## Features

- **Real-time Location Detection:** Uses browser geolocation and OpenStreetMap reverse geocoding to display the user's current location in India.
- **Weather Dashboard:** Simulated weather data for temperature, humidity, wind speed, pressure, visibility, and UV index.
- **Disaster Alerts:** Simulated alerts for earthquakes, storms, and floods, with browser notifications and notification history.
- **Notification Settings:** Toggle SMS, Email, and Push notifications.
- **Responsive UI:** Clean, modern design with smooth animations and mobile support.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- Internet connection (for geolocation and reverse geocoding)

### Usage
1. **Clone or Download** this repository to your local machine.
2. Open `index.html` in your web browser.
3. Allow location access when prompted for the best experience.

### File Structure
```
SuraksaNet/
├── index.html
└── assets/
    └── National_Disaster_Management_Authority_Logo.png
```

## How It Works
- On load, the app requests your location and displays it using OpenStreetMap's Nominatim API.
- Weather and alert data are simulated for demonstration purposes.
- You can test alerts, refresh data, and toggle notification settings.
- The UI is fully responsive and works on both desktop and mobile devices.

## Customization
- To use real weather or disaster APIs, replace the simulation logic in the JavaScript section of `index.html` with actual API calls.
- Update the logo in the `assets/` folder as needed.

## Credits
- [OpenStreetMap Nominatim API](https://nominatim.openstreetmap.org/)
- [National Disaster Management Authority Logo](https://upload.wikimedia.org/wikipedia/en/6/6b/National_Disaster_Management_Authority_Logo.png)

## License
This project is for demonstration and educational purposes only. No warranty or official affiliation with any government agency.
