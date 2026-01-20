# Event Management & Ticketing System (MongoDB)

## Project Description
This project implements a backend MongoDB schema for an Event Management & Ticketing System. It demonstrates database design, CRUD operations, indexing, and aggregation pipelines using MongoDB.

## Technologies Used
- MongoDB
- MongoDB Compass
- MongoDB Shell (mongosh)
- GitHub

## Database
Database Name: `ticketingSystem`

## Collections
- **Users**: userId, name, email, phone, role, createdAt  
- **Events**: eventId, title, description, categoryId, dateTime, venue, organizerId, price, totalTickets, availableTickets, status  
- **Tickets**: ticketId, eventId, userId, bookingDate, quantity, totalAmount, status  
- **Categories**: categoryId, name, description  

## Features
- Full CRUD operations on all collections
- Ticket booking and cancellation
- Indexes for performance optimization
- Aggregation reports (ticket sales, revenue, attendees, category-wise events)

## Author
Yash Raj  
MongoDB Assignment
