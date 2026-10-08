# CST8915 Lab 3: CST8915 Full-stack Cloud-native Development: Introduction to Docker

**Student Name**: Eric Tieu<br>
**Student ID**: 041273376<br>
**Course**: CST8915 Full-stack Cloud-native Development<br>
**Semester**: Fall 2026

---

## Demo Video

🎥 [Watch Demo Video](https://www.youtube.com/watch?v=v6rRt41_HgA) 2x speed

---
### What are the main differences between a Docker image and a Docker container?
A docker image are the read only blueprint of layers that a docker container runs on. A docker container is a running instance of a docker image.

### Explain how Docker's layered architecture improves efficiency.
The layers allow multiple containers to use the same layers. From the lab: Layers are cached and reused

### Why does each container get its own writable layer?
To isolate instances. Read only layers are reused for multiple instances, but changes will be isolated.

### What are the benefits of using Docker Compose over running containers individually?
Management. Multi-container applications and their relationships can be defined in a single Docker Compose.
