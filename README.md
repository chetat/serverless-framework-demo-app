# serverless-api-framework
A simple app to demonstrate how to deploy python applications on AWS Lambda using the Serverless Framework.


## Getting Started

Prerequisites: Python 3.8+

### Setup Python virtual environment. 

Create a new virtual environment named `venv`

`python -m venv venv`

Activate the virtual environment

`source venv/bin/activate`

Install requirements

`pip install -r requirements.txt`

### Running the application
Start the FastAPI application by running:

`uvicorn main:app --reload`

### Deploying to AWS
...

References

[FastAPI Documentation](https://fastapi.tiangolo.com/)
