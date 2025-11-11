
<p align="center">
  <img src="docs/Haweia.png" alt="Haweia Banner" width="100%">
</p>

# HAWEIA – CPIT 251 Group Project  
*A Java console-based system for cultural tourism in Saudi Arabia*

Haweia is an academic project developed for **CPIT-251**, focusing on software development using **OOP, UML Modeling, Waterfall methodology, and Testing**.  
The system provides a simplified prototype of a tourism platform where users can explore events, buy local products, enroll in volunteer opportunities, and manage their bookings.

---

## ✅ Project Overview

The system supports Saudi Arabia’s Vision 2030 by offering users access to:

- Events and festivals  
- Volunteer opportunities  
- Local stores and traditional products  
- Cultural and historical information  

This project follows the **Waterfall methodology** and includes the full software development lifecycle:  
Requirements → Design → Implementation → Testing → Documentation.

---

## ✅ Key Features (Java Implementation)

### 1. Buy Local Products
- Search for a product  
- Add to cart  
- Confirm purchase  
- Update cart  

### 2. Favorite Events
- Search events by ID  
- Add event to favorites  

### 3. Enroll in Volunteer Opportunities
- Check requirements  
- Enroll user  
- Update opportunity capacity  

### 4. Cancel Opportunity / Booking
- Limit cancelations per user  
- Update capacity  
- Return success/fail result  

### 5. Payment & Booking (Prototype)
- Book event  
- Make payment for a product/event  

All methods were documented and unit-tested.

---

## ✅ System Architecture

We used the **Repository Pattern**, ensuring:
- Clean structure  
- Separation of concerns  
- Data integrity  
- Maintainability  

---

## ✅ UML Diagrams  
(Diagrams exist inside the project report PDF)

Includes:
- Use Case Diagrams  
- Sequence Diagrams  
- Class Diagram  
- Software Architecture Diagram  

---

## ✅ Testing (JUnit)

We created and executed tests for the 4 main methods:

- `addToFavoriteEvent()`  
- `addToCart()`  
- `enrollOpportunity()`  
- `cancelOpportunity()`  

Each test includes:
- Valid case  
- Invalid case  
- Boundary case (if applicable)

---

📄 **Full Project Report:**  
[Click here to view](docs/Haweia%20%20CPIT-251%20Project%20report_compressed.pdf)

---

## ✅ Notes
This project was developed as part of the **CPIT-251** course at King Abdulaziz University.  
It focuses on applying core concepts from:
- Object-Oriented Programming (OOP)
- UML modeling and software design
- Waterfall development methodology
- Unit testing using JUnit

The system is a console-based academic project intended to demonstrate  
requirements analysis, design diagrams, Java implementation, and test coverage.
