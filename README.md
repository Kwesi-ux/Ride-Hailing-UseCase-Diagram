# Ride-Hailing Application - UML Use Case Diagram

This repository contains the UML Use Case Diagram for a ride-hailing application. The diagram illustrates the interactions between the key actors (Passenger, Driver, and Admin) and the system, along with the core functionalities supported by the application.

## System Overview

The ride-hailing application allows passengers to book rides, drivers to manage ride requests, and administrators to oversee system operations.

## Actors and Their Responsibilities

### 1. **Passenger**
   - **Request Ride**: Passenger requests a ride through the app.
   - **Cancel Ride**: Passenger can cancel a requested ride before it starts.
   - **Pay Fare**: Passenger pays for the completed ride.

### 2. **Driver**
   - **Accept Ride**: Driver accepts a ride request.
   - **Reject Ride**: Driver can reject a ride request.
   - **Start Trip**: Driver starts the ride after passenger pickup.
   - **End Trip**: Driver completes the trip after dropping off the passenger.

### 3. **Admin**
   - **Manage Accounts**: Admin manages passenger and driver accounts.
   - **View Reports**: Admin views reports on system usage and performance.

## Use Cases

### Passenger Use Cases:
1. **Request Ride**: Passenger initiates a ride request, which is sent to nearby drivers.
2. **Cancel Ride**: Passenger can cancel a ride if plans change.
3. **Pay Fare**: Payment is processed after the trip ends.

### Driver Use Cases:
1. **Accept Ride**: Driver chooses to accept a ride request.
2. **Reject Ride**: Driver declines a ride request.
3. **Start Trip**: Trip begins after the driver picks up the passenger.
4. **End Trip**: Trip is marked as completed when the passenger is dropped off.

### Admin Use Cases:
1. **Manage Accounts**: Add, update, or delete accounts of users and drivers.
2. **View Reports**: Monitor application usage, financial transactions, and driver activity.




