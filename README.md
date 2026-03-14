# Simple Python Flask App

## Overview
This is a simple Python Flask application created for DevOps practice.

The application exposes a single HTTP endpoint and is intentionally kept lightweight so it can be used for learning and testing DevOps workflows such as CI/CD pipelines, Docker builds, and automation with GitHub Actions.

This project is being used as part of **Day 48 DevOps practice tasks**.

---

## Project Structure

```
.
├── app.py
├── requirements.txt
└── README.md
```

---

## Tech Stack

- Python
- Flask
- REST API Endpoint

---

## Prerequisites

Make sure the following are installed on your system:

- Python 3
- pip

You can verify installation using:

```
python --version
pip --version
```

---

## Install Dependencies

Install the required dependencies using the requirements file.

```
pip install -r requirements.txt
```

---

## Run the Application

Start the Flask application using:

```
python app.py
```

Once the application starts, it will run on:

```
http://localhost:5000
```

---

## Test the Endpoint

You can test the endpoint using a browser or curl.

### Using Browser

Open the following URL:

```
http://localhost:5000
```

### Using curl

```
curl http://localhost:5000
```

---

## Use Case for DevOps Practice

This simple application can be used for practicing:

- CI/CD pipeline implementation
- Docker image building
- Container deployment
- GitHub Actions workflows
- API endpoint health checks

---

## Learning Purpose

This project is part of a **DevOps learning journey** where the focus is on understanding how applications integrate with automation pipelines, container platforms, and deployment workflows.
