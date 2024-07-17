# Receipt Processor

## Overview

The Receipt Processor project is a web service designed to process receipts and calculate points based on specific rules. It provides endpoints for submitting receipts and retrieving points awarded for each processed receipt.

### Features

- **Process Receipts Endpoint:** Accepts JSON formatted receipts and generates a unique ID.
- **Get Points Endpoint:** Retrieves the number of points awarded for a receipt ID based on predefined rules.

## Technologies Used

- **Language:** Go
- **Tools:** Docker

## Setup Instructions

To run the Receipt Processor locally or in your environment, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/receipt-processor.git
   cd receipt-processor
   
2. **Build and Run with Docker:**
   ```docker build -t receipt-processor .
      docker run -p 8080:8080 receipt-processor
