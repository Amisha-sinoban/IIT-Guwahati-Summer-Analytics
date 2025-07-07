# ⚙️ Project Workflow

## 1️⃣ Data Preparation

- CSV data with occupancy, capacity, and timestamp information.
- Replay as a simulated real-time data stream using Pathway.

## 2️⃣ Feature Engineering

- Compute occupancy ratio, queue lengths, and event-based demand signals.
- Calculate geographic proximity for competitive analysis.

## 3️⃣ Model Implementation

- **Model 1**: Simple linear price based on occupancy.
- **Model 2**: Demand-based price using multiple features (occupancy, queue, traffic, events, vehicle type).
- **Model 3**: Competitive price adjustment using nearby lot prices.

## 4️⃣ Price Smoothing & Constraints

- Smooth prices using custom functions (clip or apply).
- Avoid erratic changes; keep variation between 0.5x – 2x base pric
