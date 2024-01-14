# Develop and Deploy A Customer Churn Prediction Model using Python, Streamlit and Docker



[![Docker Extension for RedisInsight](http://img.youtube.com/vi/RhRIFjyzIqU/hqdefault.jpg)](https://www.youtube.com/embed/RhRIFjyzIqU)




## Prerequisite:

- An IDE/ Text Editor 
- Python 3.6+ 
- PIP (or Anaconda)
- Not required but recommended: An environment management tool such as pipenv, venv, virtualend, conda.
- Docker Desktop

## Installing the dependencies

```
pip3 install -r Pipfile
```

## Executing the Script

```
 python3 stream_app.py
```

## Viewing Your Streamlit App

```
You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://192.168.1.23:8501
 ```





Certainly! The link you provided is a tutorial on developing and deploying a customer churn prediction model using Python, Streamlit, and Docker. To execute the project on your Windows 10 machine, you can follow these steps:

Prerequisites:
Install Docker:

Download and install Docker Desktop for Windows from Docker's official website.
Follow the installation instructions provided on the Docker website.
Install Git:

If you don't have Git installed, download and install it from Git's official website.
Clone the Repository:

Open a terminal (Command Prompt or PowerShell).
Navigate to the directory where you want to clone the project.
Run the following command to clone the repository:
bash
Copy code
git clone https://github.com/docker/getting-started.git
Project Execution:
Navigate to the Project Directory:

Change your current directory to the project folder:
bash
Copy code
cd getting-started/customer-churn-prediction
Build the Docker Image:

Build the Docker image using the provided Dockerfile:
bash
Copy code
docker build -t churn-prediction .
Run the Docker Container:

After building the image, run the Docker container:
bash
Copy code
docker run -p 8501:8501 churn-prediction
Access the Web App:

Open your web browser and go to http://localhost:8501.
You should see the Streamlit web app for customer churn prediction.
Notes:
If you encounter any issues, make sure Docker Desktop is running and properly configured on your Windows machine.
Ensure that port 8501 is not in use by another application on your system.
You can stop the Docker container by pressing Ctrl + C in the terminal.
This should guide you through the process of setting up and running the customer churn prediction project on your Windows 10 machine using Docker. If you encounter any specific issues, refer to the Docker documentation or seek help from the Docker community.







<img width="769" alt="image" src="https://user-images.githubusercontent.com/313480/182178628-56770a72-d8fd-4fe8-9d7d-e2cc7b59d731.png">




