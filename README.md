DevOps FastAPI Demo
Deskripsi
Project ini adalah aplikasi FastAPI sederhana yang dibangun sebagai latihan DevOps untuk containerization dan API development.

Features
- FastAPI REST API
- Dockerfile untuk container image
- Dokumentasi otomatis /docs

Project Structure


<img width="217" height="238" alt="image" src="https://github.com/user-attachments/assets/e15f1f1b-9583-4bec-9043-1dbf7af5765c" />



Run Locally
uvicorn app.main:app --reload

Run with Docker
docker build -t devops-app:latest .
docker run -d -p 8000:8000 --name devops-app-container devops-app:latest

Roadmap
- Push image ke Docker Hub
- Setup GitHub Actions
- Deploy ke AWS EC2/ECS
- Monitoring & Logging
Author
manparta – DevOps Engineer

Dokumentasi 

<img width="1920" height="1080" alt="Screenshot (251)" src="https://github.com/user-attachments/assets/bd1681bb-6871-40e2-bd5c-87706fa8978e" />

<img width="1920" height="1080" alt="Screenshot (257)" src="https://github.com/user-attachments/assets/0511986b-51e4-4927-b999-16dd4e6546a4" />

<img width="1920" height="1080" alt="Screenshot (256)" src="https://github.com/user-attachments/assets/22e1e538-bced-4a1e-92f5-b64542f29d54" />

