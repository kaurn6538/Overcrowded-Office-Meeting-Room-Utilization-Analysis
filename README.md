# Overcrowded Office - Meeting Room Utilization Analysis

## 📊 Project Overview

This Tableau project was developed as part of a case study challenge to investigate and visualize meeting room usage patterns for a law firm facing issues with overcrowded office space. Staff reported difficulties in booking meeting rooms, while partners suspected that rooms were frequently booked but left unused. With the cost of office expansion being high, the firm needed a clear data-driven approach to identify whether additional meeting rooms were necessary.

## 🧠 Problem Statement

- Staff claim there are no available meeting rooms to meet clients.
- Management suspects inefficient utilization: rooms are booked but not actually used.
- Office expansion involves high costs, so an informed decision was needed.

## 🗺️ Visualization Highlights

- Interactive floor plan visualization for **two floors** (Ground and First).
- Comparison of **Booked Utilization** vs. **Actual Utilization** for each meeting room.
- Clear room-level mapping using X-Y plotting and polygons over background floor plan images.

## 🚀 Key Features

- 📌 **Floor Selector:** A parameter (`Select Floor`) is used to switch between Ground and First floor views.
- 🖼️ **Dynamic Backgrounds:** Created a calculated field `Floor Image Selection` connected to the floor parameter to dynamically change the floor plan background.
- 📐 **Polygon Mapping:** Used X and Y coordinates to draw room shapes using the `Path` and `Room` fields with the mark type set to **Polygon**.
- 🎨 **Color Gradient:** Room areas are color-coded based on **Average Utilization**, ranging from low to high usage (0% to 100%).
- 🌀 **Visualization Mode Toggle:** A parameter `Select Visualization` allows switching between Booked vs. Actual utilization views.
- 🧭 **Tooltip Details:** Hovering over rooms displays more insights such as utilization rate.

## 🖼️ Screenshot

![Meeting Room Utilization - Ground Floor](image.png)

## 🛠️ Tools Used

- Tableau Desktop
- Data blending and custom calculations
- Parameters and filters
- Floorplan image mapping via background images
- Polygons with X, Y plotting

## 📁 Project Structure


## 📌 How It Works

1. Floor selection is managed via a **parameter** and a calculated field (`Floor Image Selection`) to toggle background images.
2. Rooms are drawn on the floor plans using polygon shapes derived from X-Y coordinates.
3. Utilization data is plotted using color gradients to quickly identify under/over-utilized rooms.
4. Users can switch between Booked vs. Actual data using the `Select Visualization` parameter.

## ✅ Outcome

This dashboard enables stakeholders to:

- Identify underused rooms that are frequently booked but not used.
- Make informed decisions about office space utilization.
- Avoid unnecessary costs by optimizing current space instead of expanding.

## 🔐 Disclaimer

This project is a **fictitious case study** created for educational purposes. Any resemblance to actual events or organizations is purely coincidental.

---

👤 **Created by:Navdeep Kaur 
📅 **Completed on:4/5/2025 
🛠️ **Built with: Tableau

