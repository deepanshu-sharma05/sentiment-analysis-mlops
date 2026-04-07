# Sentiment Analysis MLOps Pipeline

End-to-End MLOps project for deploying a Hugging Face Sentiment Analysis model using **MLflow**, **FastAPI**, **Docker**, and **Kubernetes**.

## Tech Stack
- Model: Hugging Face Transformers (DistilBERT)
- Tracking & Registry: MLflow
- API: FastAPI
- Container: Docker
- Orchestration: Kubernetes (Minikube)
- CI/CD: GitHub Actions

## Project Structure
...

## Quick Start
1. Clone the repo
2. `pip install -r requirements.txt`
3. `python src/train.py` → trains and logs model to MLflow
4. `uvicorn src.app:app --reload` → run API locally
5. Build & run Docker: `docker build -t sentiment-api .`

## Demo
[Add screenshot or video link later]