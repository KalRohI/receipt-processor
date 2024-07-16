Receipt Processor
Overview
The Receipt Processor project is a web service designed to process receipts and calculate points based on specific rules. It offers endpoints for submitting receipts and retrieving points awarded for each receipt processed.

Features
Process Receipts Endpoint: Accepts JSON formatted receipts and generates a unique ID.
Get Points Endpoint: Retrieves the number of points awarded for a receipt ID based on predefined rules.
Technologies Used
Language: Go
Tools: Docker
Setup Instructions
To run the Receipt Processor locally or in your environment, follow these steps:

Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/receipt-processor.git
cd receipt-processor
Build and Run with Docker:

Ensure Docker is installed on your machine. Then, build and run the Docker container:

bash
Copy code
docker build -t receipt-processor .
docker run -p 8080:8080 receipt-processor
This will start the web service on http://localhost:8080.

Testing with Postman:

Use Postman or any HTTP client to test the endpoints:

Process Receipts: POST http://localhost:8080/receipts/process
Get Points: GET http://localhost:8080/receipts/{id}/points

API Specification
For detailed API documentation, refer to api.yml.
