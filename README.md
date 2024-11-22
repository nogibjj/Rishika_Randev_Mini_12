[![Build and Push Docker Image](https://github.com/nogibjj/Rishika_Randev_Mini_12/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Rishika_Randev_Mini_12/actions/workflows/cicd.yml)

# Rishika Randev's Mini Project 12 (Flask calculator app) for IDS706

Instructions: Create a simple Python application containerized with a dockerfile. The goal here is to both demonstrate running your application within a docker container (using docker run terminal commands) but to also build a docker image in your CI/CD pipeline which will be pushed to Docker Hub or other container management service.

## ☑️ Steps
1. Prepare the necesary configuration files like the Dockerfile, .devcontainer folder with Dockerfile & json (for running your code on Codespaces), Makefile, requirements.txt, and cicd.yml for GitHub Actions integration. Ensure that the requirements.txt lists all necessary packages (for example, flask).
2. Create an app.py file where you add your Flask app code.
3. Optionally, create a templates folder with a HTML file for the frontend of the app, and a static folder with a style.css file for styling the frontend.
4. Create a Dockerfile to containerize the Flask app and run it on container port 5050.
5. Set up your Makefile to build a container from the Docker image, log in to dockerhub (using your username and password), push the image to dockerhub using your credentials, and run the container (either locally or on Codespaces). This is what the output of the make commands looks like.
<img width="902" alt="Screenshot 2024-11-22 at 2 37 33 PM" src="https://github.com/user-attachments/assets/b8b2d3b5-0c86-455c-8127-1f402f661011">
  
7. When you run the container, you will get a localhost URL which you can use to open and use your app on your browser.

## ☑️ DockerHub
Here is where you can see the container image pushed to DockerHub:
<img width="1291" alt="Screenshot 2024-11-22 at 2 43 18 PM" src="https://github.com/user-attachments/assets/2d9b36bc-3e50-486d-83c5-4be0495f2723">

Here is a screenshot of what the calculator app looks like on Codespaces:
<img width="1464" alt="Screenshot 2024-11-22 at 2 37 05 PM" src="https://github.com/user-attachments/assets/7ca749be-e62b-4eeb-9663-9eb74a5220ce">

## ☑️ Resources
Calculator app code (Flask, HTML, & CSS) taken from: https://www.tutorialspoint.com/python/building_a_web_based_calculator_with_flask.htm

