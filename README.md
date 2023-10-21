# Embed_ML_Model_Web_App
This project focuses on embedding a Machine Learning model into a web application. It involves integrating advanced ML algorithms and models into a user-friendly web interface, allowing users to leverage the power of machine learning through an accessible and interactive online platform.
# Overview 
This project aims to:

Embed a Machine Learning model into a user-friendly web application.
Integrate advanced ML algorithms and models for interactive use.
Dockerize the application for easy deployment.
Deploy the app on Hugging Face for accessibility.
# Preview
Top
![image](https://github.com/EKmorkeh22/Embed_ML_Model_Web_App/assets/120388341/9f756c3f-af64-49ea-8824-25e4cd0853a3)

Bottom
![image](https://github.com/EKmorkeh22/Embed_ML_Model_Web_App/assets/120388341/82614595-5ca1-4b8a-8078-324a51b9b4ac)
# Technologies Employed
FastAPI: A modern, fast (high-performance) web framework for building APIs.
Docker: Containerization platform for packaging applications.
Hugging Face: An AI research organization providing models and resources.
Python 3.11: The programming language used for development
# Installation

## Clone the repository
git clone https://github.com/EKmorkeh22/Embed_ML_Model_Web_App

## Change directory
cd Embed_ML_Model_Web_App

## Install dependencies
pip install -r requirements.txt

## Run the FastAPI application
uvicorn main:app --reload

# Usage
Here's how you can use the project:

Access the web application at http://localhost:8000 in your browser.
Interact with the ML model through the user-friendly interface with features like the patients : Plasma glucose level,Body mass index,Blood pressure levels etc

# Documentation 
For detailed documentation and API usage, visit http://localhost:8000/docs after running the app locally.

# Dockerization
First create a Dockerfile, check documention : Docker Official Documentation - Dockerfile reference

Dockerize the application with the following commands:

# Build the Docker image
docker build -t app_name-app .

# Run the Docker container
docker run -p 80:80 app_name-app

# Deployment
The APP was further deployed on huggingface. You can interact with the app via huggingface following the steps below
# Usage Instruction
To access the sepsis prediction app, you will need to be signed in to Hugging Face:

If you don't have a Hugging Face account, you can sign up for free at Hugging Face.
After signing in, you can access the app using the following URL: 🤖https://gr8testgad-1-sepsis-prediction.hf.space/docs
Please note that you need to be signed in to Hugging Face to utilize this service. If you encounter any issues or have questions, feel free to checkout the huggingface documentation Huggingface Documentation for assistance.
