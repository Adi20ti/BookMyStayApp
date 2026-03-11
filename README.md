# BookMyStayApp

A Core Java based Hotel Booking Management System developed to demonstrate real-world application of object-oriented programming and data structures through incremental use cases.

---

## Running Procedure

1. Open terminal in the project folder
2. Compile the program:

   javac RoomInventory.java UseCase3InventorySetup.java

3. Run the program:

   java UseCase3InventorySetup

4. The application displays centralized room inventory information on the console.

---

## Flow of Project

The project is developed incrementally through structured use cases.

**Flow of Use Case 3:**

System starts  
↓  
Inventory component is initialized  
↓  
Room availability stored in centralized HashMap  
↓  
Availability retrieved through inventory methods  
↓  
Inventory updates performed in controlled manner  
↓  
Updated inventory displayed  
↓  
Application terminates safely

Each use case gradually improves system design, scalability, and maintainability.

---

## Objective

- To replace scattered availability variables with centralized inventory management
- To demonstrate how HashMap solves real-world state management problems
- To ensure inventory consistency using a single source of truth
- To encapsulate inventory operations within a dedicated component
- To design a scalable system for future room types and booking features

---

## Topics Covered

- HashMap data structure
- Key-value mapping
- Constant-time lookup (O(1))
- Encapsulation
- Separation of concerns
- Centralized state management
- Constructor-based initialization
- Controlled state updates
- Modular class design
- Inventory abstraction principles

---

## Use Case Included

### Use Case 3: Centralized Room Inventory Management

This use case demonstrates:

- Creating a dedicated RoomInventory class
- Centralizing availability data using HashMap
- Managing availability through controlled methods
- Eliminating inconsistent scattered variables
- Providing a scalable design for future expansion

This use case establishes a reliable inventory foundation required for booking and search features.

---

## Version Information

Application Version: 3.1  
This version is a refactored implementation of inventory management.

---

## Limitations of Previous Use Case

Use Case 2 stored availability in independent variables.  
This approach does not scale and increases the risk of inconsistent system state as system complexity grows.