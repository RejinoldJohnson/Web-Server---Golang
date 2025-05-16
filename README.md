# Web Server in Golang

This is a simple web server built using Golang. It serves static files, handles form submissions, and provides a basic `/hello` endpoint.

## Features

- Serves static files from the `./static` directory.
- Handles form submissions via the `/form` endpoint.
- Provides a `/hello` endpoint that responds with a greeting.

## Endpoints

### `/`
Serves static files from the `./static` directory.

### `/form`
Handles `POST` requests with form data. Accepts the following fields:
- `name`: The user's name.
- `address`: The user's address.

### `/hello`
Handles `GET` requests and responds with:
hello!

### Run the Server
go run main.go

### `Open your browser and navigate to http://localhost:8080`