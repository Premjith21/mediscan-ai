# MediScan AI - Medical Report Generation System

## Setup
1. Create virtual environment: `python -m venv venv`
2. Activate: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows)
3. Install dependencies: `pip install -r requirements.txt`
4. Set up environment variables in `.env`

## Usage
- Run Flask app: `python app/app.py`
- Access at: `http://localhost:5000`

## Directory Structure
- `data/pdfs/uploaded/`: Temporary storage for uploaded reports
- `data/pdfs/generated/`: Final AI-generated reports
- `model/weights/`: Trained model weights# mediscan-ai
