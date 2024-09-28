# SHMP with Dockerization

## Prerequisites

Before running this project, make sure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Any additional tools you might require for development (like a code editor).

## Getting Started

To get the application up and running, follow these steps:

### 1. Clone the repository:

```bash
git clone https://github.com/Aashish-Aryal/SIT725_HDTask.git
cd SIT725_HDTask
```

### 2. Build and run the container
```bash
sudo docker compose up -d --build
```

### 3. Access the application
Access the application by opening your browser and navigating to:
```arduino
http://localhost:3000
```

### 4. Stopping the containers
```bash
sudo docker compose down
```