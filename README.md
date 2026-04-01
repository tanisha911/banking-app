# Banking Application REST API

## Project Description

This project is a backend service for a banking application built using Spring Boot and Spring Data JPA. 
It provides RESTful APIs to manage bank accounts and perform core financial operations.

## Features

### Account Management

* Create new bank accounts
* Fetch account details by ID
* Retrieve all bank accounts
* Delete accounts

### Financial Operations

* Deposit money into an account
* Withdraw money with balance validation

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* MySQL
* Maven
* Lombok
* Postman

## Architecture

The application follows a layered architecture:
* Controller
* Service
* Repository
* Entity
* DTO

## Key Concepts
* DTO (Data Transfer Object) pattern
* Exception handling for edge cases
* Clean separation of concerns

## How to Run
1. Clone the repository
2. Open in IntelliJ
3. Configure MySQL in application.properties
4. Run the application
5. Test APIs using Postman

## API Base URL
http://localhost:8080/api/accounts

## Author
Tanisha
