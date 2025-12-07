# Find My Phone - Demo

## Project Overview
A simple demo web application for phone tracking visualization using Leaflet.js maps. This is a static single-page application with no backend, demonstrating a basic login interface and map-based location display.

## Project Type
Static HTML website with:
- Single page application (index.html)
- Leaflet.js for interactive maps
- Pure HTML/CSS/JavaScript (no build system)
- Bengali language content for demo instructions

## Setup
The project runs on a simple Python HTTP server (server.py) that serves the static HTML file on port 5000.

### Development
- Server runs on `0.0.0.0:5000`
- Cache-Control headers disabled for Replit iframe preview
- Workflow: "Start application" runs `python server.py`

### Deployment
- Configured as static deployment
- Public directory: root directory (.)
- No build process required

## Project Structure
```
.
├── index.html       # Main application file
├── server.py        # Development HTTP server
├── README.md        # Original project readme
├── .gitignore       # Python gitignore
└── replit.md        # This file
```

## Features
- Demo login screen (no real authentication)
- Interactive map showing demo location in Dhaka, Bangladesh
- Responsive design
- Bengali/English mixed language support

## Notes
- This is a demo/prototype application
- No real tracking functionality
- No backend or database
- Location is hardcoded (Dhaka coordinates: 23.777176, 90.399452)

## Date
Project imported and configured: December 7, 2025
