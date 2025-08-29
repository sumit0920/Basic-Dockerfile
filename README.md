
# Basic Docker Project

This is a simple Docker project that demonstrates how to build a minimal Docker image using **alpine:latest** and print `Hello, Captain!` to the console.

---

# Project URL
```
https://roadmap.sh/projects/basic-dockerfile
```
## Project Structure
```

hello-captain/
│
├── Dockerfile
├── .dockerignore
├── README.md
└── diagram.png

````

---

## Steps to Build and Run

### 1. Build the image
```bash
docker build -t hello-captain .
````

### 2. Run the container

```bash
docker run --rm hello-captain
```

**Expected Output:**

```
Hello, Captain!
```

---

## Diagram

Docker Flow

<img width="1536" height="1024" alt="Image Aug 29, 2025, 10_40_16 PM" src="https://github.com/user-attachments/assets/01be4e4b-ea0c-43c2-9860-bb3b2f6aa432" />


---

## How it works

1. **FROM alpine\:latest** → starts from a lightweight Linux base image.
2. **CMD \["echo", "Hello, Captain!"]** → sets the default command to print the message when the container runs.

---

## Optional: Push to Docker Hub

1. Login:

```bash
docker login
```

2. Tag your image:

```bash
docker tag hello-captain your-dockerhub-username/hello-captain
```

3. Push it:

```bash
docker push your-dockerhub-username/hello-captain
```

---

## **Author**

**Sumit Sharma**
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumitsharma-ss/)
- [![X](https://img.shields.io/badge/X-black?style=flat&logo=twitter&logoColor=white)](https://x.com/sumitsharma_95)
- [![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@devopswithsumit)
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/sumit0920)
