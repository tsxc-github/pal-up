# FastAPI Application

This is a simple FastAPI application that demonstrates a basic "Hello World" example.

## Project Structure

```
fastapi-app
├── src
│   ├── main.py          # Entry point of the application
│   └── api
│       └── hello.py     # Defines the /hello route
├── requirements.txt      # Lists project dependencies
└── README.md             # Project documentation
```

## Installation

To install the required dependencies, run:

```
pip install -r requirements.txt
```

## Running the Application

To run the FastAPI application, use the following command:

```
uvicorn src.main:app --reload
```

## Accessing the API

Once the application is running, you can access the following endpoints:

- `GET /hello` - Returns "Hello, World!" response.