# Onboarding for IM team

## Backend
- Server to store and load images on MongoDB and S3
- Index and organize using MongoDB schema
- Save the actual files on S3
- Configure the API for such purposes
- Tools: FastAPI + Python 3.11, Pydantic + RestAPI

## Frontend
- VITE + React
- Page able to store and load from the dataset in backend
- Also to view the images stored in dataset

## Deployment
- Wrap in Docker image for serving
- Use docker-k8 for serving widely
