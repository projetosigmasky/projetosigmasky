# UAM Airspace Dashboard

## 3D Corridor Designer for Urban Air Mobility

A web-based interactive dashboard for designing and visualizing Urban Air Mobility (UAM) airspace corridors. This tool enables users to upload airspace data, visualize flight networks in 3D, and manage routes for autonomous aerial vehicle operations.

## Features

🌐 **Interactive 3D Visualization**
- Real-time 3D rendering of airspace corridors using Three.js
- Pan, zoom, and rotate to explore airspace design from multiple angles

🗺️ **Map Integration**
- Integrated Leaflet map for geographic reference
- View routes and nodes with geographic context

📁 **Data Import**
- Upload CSV files with network node and edge data
- Support for multiple data formats

📊 **Route Management**
- View and manage multiple flight routes
- Visual representation of network connections
- Interactive corridor analysis

## Usage

1. **Load Data**: Use the sidebar file uploader to load your airspace network data (CSV format)
2. **Visualize**: The dashboard automatically renders your corridors in 3D
3. **Explore**: Use the map and 3D viewport to analyze different aspects of your network
4. **Manage Routes**: Add, remove, or modify routes in the routes panel

## Data Format

The dashboard expects CSV files with the following structure:
- **Nodes**: Contains airspace waypoints with coordinates
- **Edges**: Defines connections between waypoints (flight corridors)

## Technology Stack

- **Three.js**: 3D visualization and rendering
- **Leaflet**: Interactive mapping
- **HTML5/CSS3**: Modern web interface
- **JavaScript**: Interactive functionality

## Getting Started

1. Visit the [live dashboard](https://projetosigmasky.github.io/projetosigmasky/)
2. Upload your airspace network data
3. Start exploring your corridors in 3D!

## Project Information

This project is part of research into Urban Air Mobility (UAM) airspace design and simulation using Bluesky air traffic simulator.

---

**Status**: Active Development 🚀
