# Docker Learning 

A project documenting my learning journey from the Udemy course Docker & Kubernetes


📌 About This Repository
This repository tracks my hands-on experience, trials, and errors while learning Docker and Kubernetes.

It includes:
Step-by-step Docker projects 🛠️
Troubleshooting logs 📝
Key concepts & best practices 🔍


📂 Repository Structure
docker-learning/
│── project-1/
│   ├── Dockerfile            # Docker configuration
│   ├── app/                  # Application source code
│   ├── docker-compose.yml     # Compose file (if used)
│   ├── README.md              # Project details
│── project-2/
│   ├── Dockerfile
│   ├── ...
│── docs/
│   ├── trial-errors.md        # Challenges & fixes
│── README.md


📜 Projects Covered
1️⃣ Simple Node.js App in Docker
Build a basic Node.js app with Docker.
Run and debug the container.
Encountered & solved issues: EADDRINUSE, missing dependencies.
2️⃣ Multi-Container Setup with Docker Compose
Set up backend & frontend containers.
Configured volume & networking.
Debugged database connection issues.
📌 More projects coming soon!

📝 Troubleshooting & Fixes
Check out docs/trial-errors.md for a log of errors I encountered and how I fixed them.


# Build and run a container
docker build -t my-app .
docker run -d -p 3000:3000 my-app


🌟 Contributing
This is a personal learning project, but feel free to open an issue or suggest improvements.

