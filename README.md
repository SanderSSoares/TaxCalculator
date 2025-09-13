# TaxCalculator

A Java application to calculate employee taxes and persist the data in a database.  
Built to showcase clean code, database integration, and object-oriented design.

---

## Overview

TaxCalculator is a console-based Java project that:

- Computes tax amounts for employees based on predefined rules  
- Stores employee data and calculations in a relational database  
- Separates logic, persistence, and user interaction for maintainability  

---

## Features

- **Tax Calculation Engine** – adaptable to different rules or jurisdictions  
- **Database Persistence** – employees and tax records stored securely  
- **Object-Oriented Design** – clean packages, reusable classes, easy to extend  
- **System Reliability** – error handling and validation for stable execution  

---

## Technologies & Tools

- **Java** – core programming language  
- **MySQL** (or similar DB) – data persistence  
- **Apache Ant** – build and run automation  
- **Git/GitHub** – version control and collaboration  

---

## Architecture & Design

- Clear separation of concerns (logic vs. persistence vs. user input)  
- Domain model for employees and tax computations  
- Modular packages and reusable components  
- Designed with scalability and clarity in mind  

---

## Getting Started

### Prerequisites
- Java JDK 8+  
- MySQL (or any relational DB)  
- Apache Ant  

### Installation
```bash
git clone https://github.com/SanderSSoares/TaxCalculator.git
cd TaxCalculator
ant build
java -jar dist/TaxCalculator.jar

