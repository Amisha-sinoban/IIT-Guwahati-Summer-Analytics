# 🚗 Dynamic Pricing for Urban Parking Lots

## 🌟 Overview

This project was built as a part of **Summer Analytics 2025 Capstone Project** hosted by Consulting & Analytics Club × Pathway.  
The goal is to create a dynamic pricing engine for urban parking lots, optimizing occupancy and maximizing revenue using real-time data and intelligent models.

---

## 🧑‍💻 Tech Stack

- **Python (3.12+)**
- **Pandas & NumPy** — data preprocessing and calculations
- **Pathway** — real-time data stream processing
- **Bokeh & Panel** — real-time visualization
- **Google Colab** — development and execution environment

---

## 🏗️ Architecture Diagram

```mermaid
flowchart TD
    A[CSV Data Source] -->|Replay CSV| B[Pathway Data Stream]
    B --> C[Feature Engineering & Windowing]
    C --> D1[Model 1: Linear Pricing]
    C --> D2[Model 2: Demand-Based Pricing]
    C --> D3[Model 3: Competitive Pricing]
    D1 & D2 & D3 --> E[Real-Time Price Output]
    E --> F[Visualization Panel]
