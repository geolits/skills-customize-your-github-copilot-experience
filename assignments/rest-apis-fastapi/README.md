# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and deploy REST APIs using the FastAPI framework. You'll understand HTTP methods, request/response handling, data validation, and how to create scalable web services that communicate with clients over the internet.

## 📝 Tasks

### 🛠️ Create a Basic TODO API

#### Description
Build a simple REST API for managing TODO items. The API should allow users to create, read, update, and delete TODO items using HTTP endpoints. Implement proper request validation and error handling.

#### Requirements
Completed program should:

- Accept POST requests to create new TODO items with title and description
- Accept GET requests to retrieve all TODO items or a specific item by ID
- Accept PUT requests to update existing TODO items
- Accept DELETE requests to remove TODO items
- Return appropriate HTTP status codes (200, 201, 400, 404, etc.)
- Validate input data and return meaningful error messages

### 🛠️ Add Data Persistence

#### Description
Extend your API to persist TODO items to a JSON file or simple database. Ensure that data is saved and retrieved correctly across multiple API calls.

#### Requirements
Completed program should:

- Save TODO items to a persistent storage (JSON file or SQLite database)
- Load existing TODO items when the API starts
- Handle file I/O errors gracefully
- Maintain data consistency across API operations
