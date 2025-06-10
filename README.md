# penguin-ai
Internship Project for Week 1: Environment Setup

---

## 1.  Data Pipeline

- Data comes from:
  - User input through frontend UI
  - OR uploaded data in future extensions
- Data will be preprocessed before being sent to the model

---

## 2.  Model

- Model type: TBD (e.g., classification / recommendation / summarization)
- Currently this is a placeholder. The actual model will be integrated in later weeks.
- The goal is to return a mock result (e.g., fixed output or random response) through API.

---

## 3.  API Layer (FastAPI)

- Backend uses **FastAPI**
- Provides endpoints like:
  - `GET /ping` – for health check
  - `POST /analyze` – (future) receive input and return model output
- Runs locally on `http://127.0.0.1:8000`

---

## 4.  UI Layer (React)

- Frontend built with **React + Vite**
- Connects to backend API via HTTP calls
- Displays data or model output to user
- Placeholder UI is now live at `http://localhost:5173`

---



---

## 📌 Directory Structure (simplified)

