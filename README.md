Capstone Project – Summer Analytics 2025

Urban parking spaces are often either overcrowded or underutilized due to static pricing. This project implements a real-time dynamic pricing engine for 14 parking lots using real-world data. We build three increasingly intelligent pricing models based on the following features: Occupancy rate, Queue length, Vehicle type, Nearby traffic, Special events & Competitor prices

Tech Stack : Python 3, Pandas, NumPy – for data processing, Pathway – for real-time data simulation and ingestion, Bokeh or Matplotlib – for real-time visualization, Geopy – for distance calculations between parking lots & Google Colab – for development and execution

Project Workflow
Data Loading
Load the dataset containing occupancy, vehicle types, queue lengths, special days, etc.

Model 1: Linear Pricing
Simple price increases proportionally with occupancy ratio.

Model 2: Demand-Based Pricing
Computes a weighted demand function using occupancy, queue length, traffic level, vehicle type, and special day flags. Prices scale with normalized demand and are clipped within bounds (0.5x to 2x).

Model 3: Competitive Pricing
Calculates distances between lots and adjusts prices based on competitor proximity and pricing.

Real-Time Simulation
Powered by Pathway, the system processes time-stamped records in order, enabling real-time pricing logic.

Visualization
Prices over time and across lots are displayed using interactive graphs via Bokeh.

