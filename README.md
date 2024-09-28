You are tasked with developing a Spring Boot CRUD application for managing trainer job notifications. 
This system will allow users to create, view, and retrieve job notifications based on the job ID.

In this case study, you will use Spring Boot to build a system where job postings can be created, 
retrieved as a list, and fetched individually by their job ID.

Problem Statement:

Your task is to implement a Trainer Job Notification system using the following core components:

1. JobNotificationService:
   - Responsible for managing job notifications (such as adding, viewing, and searching for jobs by ID).

2. JobRepository:
   - Interface for CRUD operations with job notifications in a database.
   - For simplicity, you can use an in-memory database (e.g., H2) for testing the CRUD functionalities.

3. JobNotificationController:
   - REST API controller that will expose endpoints for the following operations:
     - POST to create a new job notification.
     - GET to retrieve all job notifications.
     - GET by job ID to retrieve a specific job notification.

Your Assignment:

You are required to design and implement the following:

1. JobNotification Model:
   - Define a simple model with attributes like jobId, jobTitle, description, location, and salary.

2. JobNotificationService Class:
   - Create methods to add new job notifications, retrieve all job notifications, and fetch a job by its jobId.

3. JobRepository Interface:
   - Extend Spring’s CrudRepository or JpaRepository for performing CRUD operations on job notifications.

4. JobNotificationController Class:
   - Expose three endpoints:
     - POST /jobs: For adding new job notifications.
     - GET /jobs: For retrieving all job notifications.
     - GET /jobs/{id}: For retrieving a specific job by jobId.

5. Application Runner:
   - Write the main class to run the Spring Boot application and test the functionality.

Learning Objectives:

1. Understand the fundamentals of CRUD operations in Spring Boot using JPA.
2. Learn how to create RESTful APIs in Spring Boot.
3. Practice building and testing a small application that performs typical CRUD operations.

Tasks and Deliverables:

1. Task 1: Implement the JobNotification model class.
2. Task 2: Implement the JobNotificationService class with methods for adding and retrieving jobs.
3. Task 3: Implement the JobRepository interface for CRUD operations.
4. Task 4: Implement the JobNotificationController to expose RESTful APIs for the operations.
5. Task 5: Write the main application to run the project and test the CRUD functionalities.

Additional Questions:

1. Reflection on RESTful Services:
   - How do RESTful services help in creating modular and scalable web applications?
   - Why is it important to separate concerns by using services, repositories, and controllers in Spring?

2. Enhancements (Optional):
   - Add a DELETE endpoint to remove a job notification by its jobId.
   - Implement validation for job notifications (e.g., ensure jobTitle is not empty).

Submission Instructions:

- Submit your code in a GitHub repository with clear comments explaining each part of the code.
- Write a brief report (1-2 pages) on how you implemented the CRUD operations and what you learned.

Assessment Criteria:

1. Correct implementation of CRUD operations.
2. Clean and well-organized code following Spring best practices.
3. Explanation of RESTful services and their benefits.

Grading Rubric:

| Criteria                  | Points |
|----------------------------|--------|
| Model Implementation       | 10     |
| Service Implementation     | 10     |
| Repository Implementation  | 10     |
| Controller Implementation  | 10     |
| Main Application Runner    | 10     |
| Optional Enhancements (Bonus)| 5    |
| Report and Reflection      | 5      |
| Total Points               | 50     |

By completing this assignment, you will gain practical experience in building RESTful APIs and managing CRUD operations in a Spring Boot application.
