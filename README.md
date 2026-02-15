
# Industrial Steel Shed Design using SAP2000


**Instructor:** Prof. Dhiman Basu  


---

# Project Overview

This project focuses on the structural design and analysis of an industrial steel shed located in Ahmedabad. The design integrates theoretical steel design concepts with practical structural modelling using SAP2000.

The objective was to develop a safe, economical, and code-compliant industrial shed considering multiple loading conditions and structural requirements.

The project includes:

- Structural modelling
- Load calculation
- Member design
- Connection design
- Finite Element Analysis using SAP2000

---

# Problem Statement

The industrial shed was designed based on the following requirements:

## Site Requirements

- Plot Area: **2000 m²**
- Aspect Ratio (L/W): **2.0**
- Column Height: **2.5 m**
- Truss Height: **3 m**
- Road alignment along longer dimension.

## Structural Components

- Tension Members
- Compression Members
- Beams
- Columns
- Purlins
- Base Plate
- Bolted Connections

**(Ref: [Project Report – Section 1.0](/Shed%20Design.pdf))*

---

# Geometry and Layout

## Finite Element Model

![Finite Element Model](Images/Finite%20Element%20Model.png)

## 3-D Sectional View

![3-D Sectional View](Images/3-D%20Sectional%20View.png)

## Axial Force Model

![Axial Force Model](Images/Axial%20Force%20Model.png)

## Shear Force Model in y-z direction

![Shear Force Model in y-z direction](Images/Shear%20Force%20Model%20in%20y-z%20direction.png)

## Shear Force Model in x-z direction

![Shear Force Model in x-z direction](Images/Shear%20Force%20Model%20in%20x-z%20direction.png)

## Bending Moment Model in x-z direction

![Bending Moment Model in x-z direction](Images/Bending%20Moment%20Model%20in%20x-z%20direction.png)

## Bending Moment Model in y-z direction

![Bending Moment Model in y-z direction](Images/Bending%20Moment%20Model%20in%20y-z%20direction.png)


---

# Design Standards

The design follows Indian Standard codes:

- IS 800 – Steel Design Code
- IS 875 Part 1 – Dead Loads
- IS 875 Part 2 – Live Loads
- IS 875 Part 3 – Wind Loads
- IS 808 – Steel Sections

---

# Load Calculations

## 1. Dead Load

- Roof sheeting weight = 0.15 kN/m²
- Total Dead Load = 15.52 kN

Dead loads include self-weight and permanent structural components.

---

## 2. Live Load

- Roof slope angle ≈ 14.9°
- Live Load = 0.651 kN/m²
- Total Live Load ≈ 67.36 kN

---

## 3. Wind Load

Based on IS 875 Part 3:

- Basic wind speed = 39 m/s
- Design wind speed = 41.22 m/s
- Design wind pressure ≈ 734 N/m²

Wind force calculation:

  F = (Cpe - Cpi) × Pd × Area

Resultant Wind Load ≈ -99.04 kN

**(Ref: [Project Report – Section 5.0 Page: 5-6](/Shed%20Design.pdf))*

---

# Load Combinations

The following combinations were applied:

1. 1.5 DL + 1.5 LL  
2. 1.5 DL + 1.5 WL  
3. 1.5 DL - 1.5 WL  
4. 1.2 DL + 1.5 LL + 1.2 WL  
5. 1.2 DL + 1.5 LL - 1.2 WL  
6. 0.9 DL + 0.9 WL  
7. 0.9 DL - 0.9 WL  

---

# Structural Modelling (SAP2000)

The structure was modelled using finite element analysis in SAP2000.

### Analysis Outputs:

- Axial Force Diagram
- Shear Force (YZ)
- Shear Force (XZ)
- Bending Moment Diagram

**(Ref: [See report figures pages 7–12](/Shed%20Design.pdf))*

---

# Section Properties

Selected structural sections include:

- ISMB 450
- ISLB 350
- ISMB 400
- Angle 200×200×25
- ISLB 75

Section selection considered:

- Strength
- Stability
- Economic efficiency

---

# Structural Design

## 1. Tension Member Design

Steps followed:

- Calculate required gross area
- Bolt design check
- Shear capacity check
- Block shear check
- Rupture and yielding verification

Final selected section: Angle 200×200×25.

---

## 2. Compression Member Design

Design involved:

- Slenderness ratio calculation
- Buckling classification
- Design compressive strength
- Capacity verification

Section verified safe under design load.

---

## 3. Beam Design

Checks performed:

- Section classification
- Shear strength
- Flexural strength
- Lateral support considerations

Beam satisfies design requirements.

---

## 4. Column Design

Parameters considered:

- Axial load + bending moment
- Effective length
- Buckling resistance

Final section selected based on IS800 criteria.

---

## 5. Base Plate Design

Includes:

- Bearing pressure check
- Plate thickness calculation
- Anchor bolt consideration

---

## 6. Purlin Design

Purlins designed to transfer roof loads safely to main trusses.

---

# Connection Design

## Beam-Column Connection

![Beam Column Connection](Images/Column-Beam%20Connection.png)

## Truss Member Connections

![4 Truss Members Connection](Images/Connection%20of%204%20truss%20members.png)

![3 Truss Members Connection](Images/Connection%20of%203%20truss%20members.png)

**(Ref: [Project Report – Section 6.0](/Shed%20Design.pdf))*

---

# Results and Conclusions

- All structural members satisfy IS code requirements.
- SAP2000 analysis provided accurate force distribution.
- Structure is safe under combined loading conditions.
- Design demonstrates practical implementation of steel design principles.

**(Ref: [Project Report – Section 7.0](/Shed%20Design.pdf))*

---
