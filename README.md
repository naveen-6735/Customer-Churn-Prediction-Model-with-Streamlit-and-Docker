# Develop and Deploy A Customer Churn Prediction Model using Python, Streamlit and Docker




**Our project directory structure should look like this:**
$ tree
.
├── Churn_EDA_model_development.ipynb

├── Churn_model_metrics.ipynb

├── Dockerfile

├── Pipfile

├── Pipfile.lock

├── WA_Fn-UseC_-Telco-Customer-Churn.csv

├── train.py

├── requirements.txt

├── README.md

├── images
│   
│ 
│   

├── model_C=1.0.bin

└── stream_app.py

## Prerequisite:

- An IDE/ Text Editor 
- Python 3.6+ 
- PIP (or Anaconda)
- Not required but recommended: An environment management tool such as pipenv, venv, virtualend, conda.
- Docker Desktop






Certainly! The link you provided is a tutorial on developing and deploying a customer churn prediction model using Python, Streamlit, and Docker. To execute the project on your Windows 10 machine, you can follow these steps:

Prerequisites:
**Install Docker:**

Download and install Docker Desktop for Windows from Docker's official website.

Follow the installation instructions provided on the Docker website.
**Install Git:**

If you don't have Git installed, download and install it from Git's official website.

**Clone the Repository:**

**1**.Open a terminal (Command Prompt or PowerShell).
**2.** Navigate to the directory where you want to clone the project.
**3.** Run the following command to clone the repository:


git clone https://github.com/docker/getting-started.git

**Project Execution:**
**-->**Navigate to the Project Directory:

**-->**Change your current directory to the project folder:

**cd your directory**

Build the Docker Image:

Build the Docker image using the provided Dockerfile:

**docker build -t churn-prediction .**

Run the Docker Container:

After building the image, run the Docker container:

**docker run -p 8501:8501 churn-prediction**

Access the Web App:

Open your web browser and go to http://localhost:8501.
You should see the Streamlit web app for customer churn prediction.

**Architecture:**

<img width="769" alt="image" src="https://github.com/naveen-6735/Customer-Churn-Prediction-Model-with-Streamlit-and-Docker/blob/main/images/Streamlit-Docker-Diagram.png.webp">


Notes:
If you encounter any issues, make sure Docker Desktop is running and properly configured on your Windows machine.
Ensure that port 8501 is not in use by another application on your system.
You can stop the Docker container by pressing Ctrl + C in the terminal.
This should guide you through the process of setting up and running the customer churn prediction project on your Windows 10 machine using Docker. If you encounter any specific issues, refer to the Docker documentation or seek help from the Docker community.







<img width="769" alt="image" src="https://github.com/naveen-6735/Customer-Churn-Prediction-Model-with-Streamlit-and-Docker/blob/main/images/Design.gif">




