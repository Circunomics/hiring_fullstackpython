# Technical Assessment - Senior Full Stack Developer

## Overview

This technical assessment is designed to evaluate your skills and knowledge as a Senior Full Stack Developer. The assessment focuses on your ability to design and implement a full-stack application using modern web technologies.

## Assessment Objectives

The main objectives of this assessment are as follows:

1. **Frontend Development**
   - Build a user authentication system using **Angular**.
     - Implement **Login** and **Register** functionalities.
     - Design a user-friendly interface for the application.
   - Create a **Dashboard** page to display visualized data.

2. **Data Visualization**
   - Utilize **Plotly** to visualize data on the Dashboard.
   - Query relevant data from the API and represent it graphically.

3. **Backend Development**
   - Create a RESTful API using **FastAPI** in **Python 3**.
   - Implement endpoints to support user authentication and data retrieval for the dashboard.
   - Data retrieval in the backend shall be done using pandas.

4. **Database Management**
   - Use **SQLAlchemy** to manage the database.
   - Ensure proper schema design to handle user data.

5. **Data Handling**
   - Retrieve rents data from the `cities_data` folder.
   - Implement data cleansing techniques to handle noise and outliers in the rents data.

6. **Containerization**
   - Use **Docker** to containerize the entire application, ensuring that it runs consistently across different environments.

7. **Unit Testing**
    - Implement Unit tests.

## Submission Requirements

- **Code Repository**: Create a GitHub repository for your project. 
    - Needs to be private.
    - And provide access to jobs@circunomics.com
- **Documentation**: Include a detailed README.md file that explains your project structure, how to run the application, and any design decisions made.
- **Dockerfile**: Ensure a Dockerfile is included for building the application image.
- **SQLAlchemy Models**: Clearly define your SQLAlchemy models and relationships.
- **Data Visualization**: Provide at least two different types of visualizations in the dashboard.
    - These shall be time series data per city (City filter is required)
    - PieChart for rental price distribution

## Evaluation Criteria

Your submission will be evaluated based on the following criteria:

- **Functionality**: Does the application meet all the specified requirements?
- **Code Quality**: Is the code well-organized, readable, and maintainable?
- **Best Practices**: Are best practices followed in coding, API design, and data handling?
- **User Experience**: Is the frontend intuitive and user-friendly?
- **Containerization**: Is the application properly containerized with Docker?

## Important Notes

- You are encouraged to use best practices in terms of coding standards and documentation.
- Do not use Frontend styling frameworks - We want you to use CSS Flex.
- docker-compose yaml file is mandatory.
- Please make sure to use the programming languages and frameworks required.
    - Not doing so will automatically disqualify the candidate.

We look forward to reviewing your submission!
