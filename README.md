# MS SQL Project

## Purpose

 Design and implement a relational database that enforces business rules for a travel agency booking system.

## Problem Description

The project concerns a **system supporting the operation of a travel agency** providing tourist services (trip sales) for both **individual and corporate clients**.

## Offer

The agency offers trips to various destinations and countries. Each trip has a defined date, seat limit, and price.  
Trips may include **additional services or attractions**, defined individually for each trip. Each service or attraction has its own price and seat limit, which may be lower than the trip seat limit.

## Clients and Participants

Clients can be individuals or companies. A client is responsible for making reservations and payments.  
One client may book a trip for **multiple participants**, who are the actual attendees of the trip and its attractions.

## Reservations and Orders

During reservation, the client initially provides only the **number of seats** for the trip and selected attractions.  
At least **one week before departure**, the client must provide full participant details (first and last names). Failure to do so results in **automatic cancellation**.

Additional services and attractions can only be ordered together with a trip.  
Reservation changes are allowed up to one week before departure. After this deadline, no changes are possible and the order must be fully paid. Missing payment results in cancellation.

## Notes

The system enforces business rules related to deadlines, seat limits, and payments using database mechanisms.
