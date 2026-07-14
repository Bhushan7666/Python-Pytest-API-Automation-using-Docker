# Python Pytest API Automation using Docker

## Project Overview

This project demonstrates API automation testing using Python, Pytest, and Docker. The test sends a GET request to a sample REST API and validates the response.

## Technologies Used

- Python 3.11
- Pytest
- Requests
- Docker

## Project Structure

```
Python-Pytest-API-Automation-using-Docker/
│── Dockerfile
│── requirements.txt
│── README.md
└── tests/
    └── test_api.py
```

## Build Docker Image

```bash
docker build -t api-pytest .
```

## Run Docker Container

```bash
docker run --rm api-pytest
```

## Expected Output

```
tests/test_api.py::test_get_users PASSED

============================== 1 passed ==============================
```

## Author

Bhushan Kampelwar
