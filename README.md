@'
# Backend Development Fundamentals – Lab 3

## Student Details
- **Name:** D. Mahesh
- **Registration Number:** 252U1R9034
- **Section:** S-24
- **Course:** CSE Gen-AI
- **University:** Aurora Deemed to be University

## Lab Title
REST API Development with Query Parameters, Validation, and Debugging

## Objective
To develop a RESTful API using Node.js, Express.js, and SQLite with CRUD operations, query parameters, input validation, and error handling.

## Technologies Used
- Node.js
- Express.js
- SQLite
- JavaScript
- PowerShell

## Setup Instructions
1. Install Node.js.
2. Open the lab-03 folder in VS Code.
3. Install dependencies: `npm install`
4. Start the server: `node server.js`
5. Server URL: `http://localhost:3001`

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/books` | Retrieve books |
| GET | `/books/:id` | Retrieve a book by ID |
| POST | `/books` | Create a book |
| PUT | `/books/:id` | Update a book |
| DELETE | `/books/:id` | Delete a book |

## Query Parameters
- `search_q` – Search by title
- `order_by` – Sort by column
- `order` – ASC or DESC
- `limit` – Number of records
- `offset` – Pagination offset
- `min_price` – Minimum price
- `max_price` – Maximum price

## Validation and Error Handling
- Validates title, author, and price.
- Returns HTTP 400 for invalid input.
- Returns HTTP 404 when a book is not found.
- Returns HTTP 201 when a book is created.
- Uses JSON error responses.

## Debugging
- Used port 3001 to avoid a port conflict.
- Checked module imports and SQLite table names.
- Used SQLite callback handling for database operations.

## Testing
The API was tested locally using PowerShell HTTP requests.

## Deployment
The API has been tested locally and has not yet been deployed.

## Conclusion
This lab helped me understand REST API development, CRUD operations, query parameters, SQLite integration, validation, and debugging.
'@ | Set-Content -Path ".\lab-03\README.md" -Encoding UTF8