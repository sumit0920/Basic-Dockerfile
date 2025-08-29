
# Hello Captain - Docker Project

This is a simple Docker project that demonstrates how to build a minimal Docker image using **alpine:latest** and print `Hello, Captain!` to the console.

---

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

![Docker Flow](diagram.png)

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

## Author

Created by **Your Name** 🚀

```

---

## **5. Architecture Diagram (diagram.png)**
