# 🐳 DevOps Demo – Flask App with CI/CD

A simple DevOps-ready web app built with **Flask**, containerized using **Docker**, and integrated with **GitHub Actions** for continuous integration for infrastructure automation and testing pipelines.

---

## 🚀 Tech Stack

- Python 3.10
- Flask
- Docker
- GitHub Actions
- Pytest (placeholder)

---

## 📁 Project Structure

devops-demo/
├── app/ # Flask app source
│ └── app.py
├── tests/ # Test folder with placeholder
│ └── test_app.py
├── .github/workflows/ # GitHub Actions CI
│ └── ci.yml
├── Dockerfile
├── requirements.txt
└── README.md

---

## 🐳 Run Locally with Docker

```bash
docker build -t devops-demo .
docker run -p 5000:5000 devops-demo
