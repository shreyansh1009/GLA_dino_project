# Vehicle Management System

This is a simple console-based Vehicle Management System implemented in C++. It allows you to manage a collection of vehicles (cars, motorcycles, and trucks) using Object-Oriented Programming (OOP) principles such as inheritance and polymorphism. Each vehicle is uniquely identified by a vehicle ID.

## Features
- **Add Vehicles**: Add new cars, motorcycles, and trucks to the system.
- **Remove Vehicles**: Remove vehicles from the system using their unique ID.
- **Display Vehicles**: Display details of all vehicles in the system.
- **Search Vehicles**: Search for a vehicle by its unique ID.
- **Update Vehicles**: Update the details of an existing vehicle using its unique ID.

## Class Structure

### Vehicle (Base Class)
- **Attributes**: `id`, `brand`, `year`
- **Methods**:
  - `displayInfo()`: Displays vehicle details.
  - `getId()`: Returns the vehicle ID.
  - `updateInfo()`: Updates the vehicle details.

### Car (Derived from Vehicle)
- **Attribute**: `numDoors`
- **Methods**: `displayInfo()`, `updateInfo()`

### Motorcycle (Derived from Vehicle)
- **Attribute**: `hasSidecar`
- **Methods**: `displayInfo()`, `updateInfo()`

### Truck (Derived from Vehicle)
- **Attribute**: `loadCapacity`
- **Methods**: `displayInfo()`, `updateInfo()`

### VehicleManagementSystem
- **Attributes**: `vehicles` (vector of unique pointers to Vehicle), `nextId` (auto-incrementing ID)
- **Methods**: `addVehicle()`, `removeVehicle()`, `displayVehicles()`, `searchVehicle()`, `updateVehicle()`, `generateNextId()`

---

## Installation and Compilation

Clone the repository:

```bash
git clone https://github.com/shreyansh1009/Vehicle-Management-System.git
cd Vehicle-Management-System
