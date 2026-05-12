# WangchukGyeltshen_02240370_DSO101_A4# CI/CD Pipeline Assignment

## Overview
A Flask web app with automated CI/CD using GitHub Actions and Render.

## Project Structure
project/
├── app.py             # Flask application
├── test_app.py        # Unit tests
├── requirements.txt   # Dependencies
└── .github/workflows/ci.yml  # CI/CD pipeline

## How It Works
1. Code is pushed to GitHub
2. GitHub Actions automatically runs tests
3. If tests pass, Render auto-deploys the app

## Live App
[Click here to view](https://wangchukgyeltshen-02240370-dso101-a4.onrender.com/)

**URL:** https://wangchukgyeltshen-02240370-dso101-a4.onrender.com/
## Running Locally
pip install -r requirements.txt
python app.py

## Running Tests
pytest