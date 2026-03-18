# ⚠️ Important Notice

## Purpose of This Repository

This backend application exists **only for learning**, specifically to demonstrate and practice **Dockerfile optimization techniques**.

---

## 🚫 Not Intended for Standalone Execution

Please note the following:

- This service is **not meant to run independently**.
- It may be **incomplete, partially implemented, or intentionally non-functional**.
- Running the application outside of Docker (e.g., via local runtime) may lead to errors or unexpected behavior.

---

## 🎯 Learning Objectives

This repository is designed to help you:

- Understand Dockerfile structure and best practices  
- Practice **image size optimization**  
- Learn **multi-stage builds**  
- Improve **layer caching strategies**  
- Analyze and optimize **build performance**
- Access inside the **container**

---
### Note : The original Dockerfile doesn't need venv, as the backend itself is not complex. Doing it increases image build time.**Not every complex solution is Best fit ! Stick to the Needs**
---
## 🐳 How to Use

Interact with this project **only through Docker**, for example:

```bash
# Build the Docker image
docker build -f <docker_file> -t backend-optimization .

# Run the container (if applicable to your exercise)
docker run backend-optimization