# Digital Twin for Smart Sustainability

## Overview
This project is a **Digital Twin web service** built using FastAPI that allows users to track **water** and **electricity usage**. It helps visualize consumption against sustainable limits and promotes eco-friendly behavior.

## Features
- Track daily water & electricity usage
- Store data in SQLite (via SQLAlchemy)
- Compare usage with pre-defined limits
- REST API for integration
- Digital Twin JSON model

## Tech Stack
- **Backend**: FastAPI (Python)
- **Database**: SQLite + SQLAlchemy
- **Hosting**: (Future) Azure App Service
- **Visualization**: JSON + API endpoints

## Run Locally
```bash
pip install -r requirements.txt
uvicorn main:app --reload
