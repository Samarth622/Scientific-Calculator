# Scientific Calculator in Java

## Overview
This project is a **Scientific Calculator** built using **Java and Spring Boot**. It provides basic arithmetic operations along with advanced mathematical functions such as trigonometry, logarithms, and exponentiation.

## Features
- **Basic Operations**: Addition, Subtraction, Multiplication, Division
- **Advanced Functions**:
  - Trigonometric functions: sin, cos, tan
  - Logarithmic functions: log, ln
  - Exponentiation and Square root
  - Factorial calculation
- **Error Handling**: Prevents division by zero and invalid inputs
- **User-Friendly Interface**: Provides a **REST API** and **Graphical User Interface (GUI)** for easy interaction

## Technologies Used
- **Java** (JDK 8 or later)
- **Spring Boot** (For backend logic and API integration)
- **Swing/AWT** (For GUI version, if applicable)
- **JUnit** (For testing mathematical operations)

## Installation & Usage
### Prerequisites
- Install [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- Install [Spring Boot](https://spring.io/projects/spring-boot)

## Example Usage
**REST API Example:**
```
GET /api/calculate?expression=log(100)
Response: { "result": 2.0 }
```

**GUI Example:**
```
Enter operation: sin(30)
Result: 0.5
```

## Future Enhancements
- Improve GUI with **JavaFX**
- Add support for complex numbers
- Integrate a history feature to store previous calculations


