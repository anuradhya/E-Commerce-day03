# Spring Boot REST API  

## Overview  
A simple Spring Boot REST API for managing student information with various retrieval endpoints.    

## Endpoints  

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/app/msg` | GET | Returns a welcome message |
| `/app/age/{age}` | GET | Returns a message with the provided age |
| `/app/student` | GET | Retrieves a single student |
| `/app/students` | GET | Retrieves all students |
| `/app/students/{regNo}` | GET | Retrieves a student by registration number |
| `/app/ages` | GET | Retrieves students aged 20-23 |
| `/app/students/gpa` | GET | Retrieves students sorted by GPA |

## Student Model  
- `regNo` (String) – Registration Number  
- `name` (String) – Student Name  
- `age` (Integer) – Student Age  
- `course` (String) – Course Name  
- `gpa` (Double) – Grade Point Average  

## Running the Application  
1. Clone the repository  
2. Build using Maven/Gradle  
3. Run the Spring Boot application  
4. Access endpoints via `http://localhost:8080/app/...`  

## Future Enhancements  
- Add database integration  
- Implement error handling  
- Support POST, PUT, and DELETE requests  
