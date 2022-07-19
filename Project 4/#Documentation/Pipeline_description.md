# Pipeline description

## 1. Git hook

Circleci detects a new commit to our repo after adding the project to the service

## 2. Dependencies installation

Dependencies for the backend and frontend are installed

## 3. Frontend lint

The script that runs lint for the frontend piece gets executed

## 4. Backend and Frontend builds

Builds are created for the frontend and backend. Those builds are saved in the cache for later use.

## 5. Hold

Wait for the user to manually approve the deploy process

## 6. Deploy

Files are fetched from the cache and the deploy process starts.

Backend: the eb cli is used to deploy to Elastic Beanstalk
Frontend: files are copied to the s3 bucket with public permissions