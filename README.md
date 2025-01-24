# User Management API

## Setup
1. Clone the repository
2. Run `npm install`
3. Start the server: `node index.js`
4. API will be available at `http://localhost:3000`

## API Endpoints

### Get All Users
- **URL**: https://redesigned-barnacle-v6qr5qx9x9x6hxv9r-3000.app.github.dev`/api/users`
- **Method**: `GET`
- **Success Response**:
  - Code: 200
  - Content: 
  ```json
  [
    { "id": 1, "name": "John", "email": "john@example.com" },
    { "id": 2, "name": "Jane", "email": "jane@example.com" }
  ]
