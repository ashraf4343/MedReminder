# Medication Reminder Service with Twilio Integration

This project implements a medication reminder service that triggers phone calls using Twilio. It connects to MongoDB to log call activities and ensures proper error handling for robust functionality.

## Technologies Used

- **Node.js**: Backend server environment
- **Express**: Web framework for Node.js
- **MongoDB**: Database for storing call logs
- **Twilio API**: Integration for initiating phone calls
- **dotenv**: Environment variable management
- **mongoose**: MongoDB object modeling for Node.js
- **body-parser**: Middleware to parse incoming request bodies
- **cors**: Middleware for handling Cross-Origin Resource Sharing
- **Postman**: API testing tool

## Features

- **Call Triggering**: Endpoint (`/trigger-call`) to initiate reminder calls with Twilio.
- **Error Handling**: Proper error checks and responses for invalid requests.
- **Logging**: Stores each call attempt in MongoDB for tracking and auditing purposes.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd medication-reminder-service
