# Electrical-Demand-Calculator
An Excel-based tool for estimating electrical demand using engineered diversity. Incorporates occupancy profiles, degree days, metered data, and renewable energy inputs to improve accuracy over traditional methods. Includes PV, battery, and hot water load modelling (DS439 &amp; HWA/DG1).

## 📘 Overview
This tool introduces a new engineering-led method of calculating the maximum electrical load for buildings. Traditional approaches rely on empirical diversity factors and static assumptions. This Excel tool adopts "Engineered Diversity" — using occupancy profiles, degree-day data, and time-based demand patterns for a more accurate and realistic view of building energy usage.

---

## 🧰 What You'll Need
- Microsoft Excel (desktop recommended)
- Basic understanding of electrical load types (lighting, small power, HVAC, etc.)
- Design-stage inputs for load types, occupancy schedules, HVAC strategy, and sustainability goals

---

## 🧭 Step-by-Step User Guide

### 🔹 1. AMD Tab – Input Load Data
- **Fill out Page 1**:
  - Add room or system names
  - Input load quantities, kW values, and apparent power (kVA)
  - Enter traditional diversity for reference (not used in engineered calculations)
- **Large residential buildings?** Use the flat/apartment section to model a typical unit and scale by quantity.
- **Life Safety Loads**: Add separately with manual diversity (flat or itemised).

---

### 🔹 2. DD Tab – Heating & Cooling Demand (Climate Sensitivity)
- Enter:
  - Maximum heating load (kW)
  - Maximum cooling load (kW)
  - COP (Coefficient of Performance) for both systems
- Choose a location or input custom **heating/cooling degree day** data

This allows your HVAC loads to be adjusted seasonally by local climate.

---

### 🔹 3. AMD Tab – Page 2: Select Occupancy Profiles
- Pick up to 5 occupancy profiles to use in your project (e.g. "Daytime", "Morning/Evening", "Supermarket")
- These profiles define hourly use patterns across weekdays and weekends

---

### 🔹 4. AMD Tab – Page 3: Assign Occupancy Profiles
- For each load item, select one of the profiles from Step 3
- Month-by-month toggle shows load shifts throughout the year based on degree day climate data
- Results include:
  - **Maximum diversified load**
  - **Average diversified load**

---

### 🔹 5. PV Tab – Solar PV & Battery Storage
- Input:
  - System size (kWp)
  - Orientation & tilt
  - Shading factor
- Battery inputs:
  - Charge and discharge thresholds (e.g. charge when load is <30%, discharge at >80%)
  - Outputs show generation and storage month by month

---

### 🔹 6. Building Performance Tab
- View combined outputs:
  - Diversified load
  - Solar PV generation
  - Battery impact
- Outputs visualised month-by-month to guide infrastructure design

---

## ✅ Outputs
- Time-based maximum demand profiles
- Month-by-month diversity-adjusted loading
- Heating/cooling loads aligned with climate
- Solar PV and battery system integration
- EV charging impact simulation (with active/dynamic control assumptions)

---

## 📎 Additional Notes
- The tool includes profiles for:
  - Residential
  - Office / Commercial
  - Education
  - Restaurant
  - Supermarket
  - Student accommodation
- You can adjust or create your own profile sets if you have real-world data.

---

## 🛡️ Licensing
- Excel Tool & Logic: MIT License
- Accompanying Documentation (TM Report): Creative Commons CC BY 4.0
