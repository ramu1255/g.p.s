# g.p.s# GPS Trilateration Simulator (A6)

## 📍 Project Overview

The **GPS Trilateration Simulator** is a B.Tech Mathematics mini project that demonstrates how an unknown location can be calculated using distance measurements from three fixed towers.

Each distance creates a circle around the corresponding tower. By subtracting pairs of circle equations, the nonlinear equations are converted into a **system of linear equations**. Solving this system gives the estimated position `(x, y)` of the phone.

---

## 🎯 Problem Statement

> 3 cell towers detect your phone at distances d₁, d₂, d₃. Each distance gives a circle equation. Subtract pairs to get linear equations. Solve for (x, y) — your location. Show the 3 circles and your position on a map.

---

## 📐 Mathematical Concept

### System of Linear Equations from Nonlinear Origins

For a tower at `(xᵢ, yᵢ)` and a phone at unknown position `(x, y)`, the distance equation is:

```text
(x - xᵢ)² + (y - yᵢ)² = dᵢ²
