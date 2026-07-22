# POLYMORPHISM-Traffic-Management-System# Polymorphism - Traffic Management System

## Overview
This repository contains a solution to a case study activity on **polymorphism** in Object-Oriented Programming (OOP). The scenario models a smart city's traffic management system, where multiple intelligent traffic devices respond to a common `activate()` command but each performs a device-specific action.

## Task Summary
- Create a parent class `TrafficDevice` with an `activate()` method.
- Create child classes `TrafficLight`, `SpeedCamera`, and `PedestrianSignal`, each overriding `activate()` with its own behavior.
- Instantiate one object of each class, store them in a single list, and activate them all in a loop **without checking their individual types** — demonstrating polymorphism.
- Extend the system by adding a new `EmergencySiren` class **without modifying the existing activation loop**, showing that the design is open to extension.

## Key OOP Concept Demonstrated
**Polymorphism** — objects of different classes are treated as instances of the same parent class (`TrafficDevice`), and calling `activate()` on each triggers the correct overridden method for that specific subclass, without any conditional type-checking.

## How to Run
```bash
python traffic_management.py
