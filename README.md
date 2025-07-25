# Vehicle Routing Problem (VRP) for Humanitarian Aid Delivery using Genetic Algorithm

This project applies a **Genetic Algorithm (GA)** to solve the **Vehicle Routing Problem (VRP)** for optimizing aid delivery logistics in the aftermath of an earthquake.

## 🌍 Project Context

Designed for **post-earthquake emergency response**, the system determines optimal delivery routes to supply aid to affected locations efficiently, considering constraints such as:
- Vehicle capacity
 -Distance

## 🧬 Genetic Algorithm Approach

The Genetic Algorithm is implemented to:
- Generate a population of feasible delivery routes
- Use crossover, mutation, and selection operators
- Minimize total distance
- Output the best-performing route(s)

## 📊 Features

- ✅ Solves VRP with constraints
- ✅ Supports **multiple delivery locations and vehicles**
- ✅ **OD matrix** input (imported)
- ✅ **Route visualizations** on a map (via Matplotlib)
- ✅ Export of final routes and performance metrics

## 📁 Input & Output

- **Input**: List of affected locations, vehicle constraints and OD matrix
- **Output**: Optimized routes (visual + textual)

## 🛠 Technologies Used

- **Python**
- **Matplotlib / Folium** (for route display)
- **Pandas, NumPy**
- **Genetic Algorithm from scratch** (or adapted from GitHub)
- **GIS tools** (for real-world data input, optional)



The system has been tested using sample earthquake-affected areas with:
- 2 depot
- 12 vehicles
- 649 demand points



