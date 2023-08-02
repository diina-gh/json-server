# JSON Server API

Welcome to the JSON Server API! This API provides a simple way to interact with a JSON-based backend server. It's built using [JSON Server](https://github.com/typicode/json-server), which allows you to create a fully functional RESTful API with just a JSON file.

## Getting Started

1. Install JSON Server globally via npm:

```bash
npm install -g json-server
```

2. Start the JSON server:

```bash
json-server --watch db.json --port 3000
```
The server will run at http://localhost:3000 and serve the data from the db.json file.


## API Endpoints
The following endpoints are available:

### GET /data
Retrieve all the data available in the database.

### GET /data/{id}
Retrieve a specific data entry by its unique id.

### POST /data
Add a new data entry to the database.

### PUT /data/{id}
Update a specific data entry by its unique id.

### DELETE /data/{id}
Delete a data entry by its unique id.
