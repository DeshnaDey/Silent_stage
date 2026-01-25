# Silent Stage

Silent Stage is a platform for ASL (American Sign Language) avatar animation and performance. It allows users to drive digital avatars using real ASL videos or text input, creating an immersive "silent" concert experience.

## Project Structure

- `backend/`: FastAPI server for pose extraction and ML inference.
- `frontend/`: Next.js application for the user interface and avatar rendering.

## Getting Started

### Backend
1. `cd backend`
2. `pip install -r requirements.txt`
3. `uvicorn main:app --reload`

### Frontend
1. `cd frontend`
2. `npm install`
3. `npm run dev`
