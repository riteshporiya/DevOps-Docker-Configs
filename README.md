# 🚀 Awesome Dockerized Database Setup 🛠️

Welcome to our repository for managing Docker Compose configurations for various databases! 🎉

## Prerequisites 📋

Before you begin, ensure you have the following installed on your local machine:

- [Docker](https://docs.docker.com/get-docker/): Ensure Docker is installed and running on your system.
- [Docker Compose](https://docs.docker.com/compose/install/): Make sure you have Docker Compose installed to manage multi-container Docker applications.


## Repository Structure 📂

- **mongoDB**: Contains Docker Compose files and configurations for MongoDB setup.
- **mysql**: Holds Docker Compose files and configurations for MySQL setup.
- **nats**: Docker Compose files and configurations for NATS setup.
- **postgresql**: Docker Compose files and configurations for PostgreSQL setup.
- **redis**: Docker Compose files and configurations for Redis setup.
- **elasticSearch**: Docker Compose files and configurations for ElasticSearch setup.

## Getting Started 🏁

To get started, follow these simple steps:

1. Navigate to the desired database directory.
2. Run the Docker Compose command to spin up the container:

```bash
  cd mongoDB
  docker-compose up -d
```
Replace `mongoDB` with the name of the database directory you want to set up.

## Basic Docker Commands 🐳

- `docker-compose up -d`: Start the containers defined in the Docker Compose file in detached mode.
- `docker-compose down`: Stop and remove containers, networks, and volumes created by up.

## 🤝Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Open a pull request.

## 📄License
This Project is licensed under the [MIT License](LICENSE.md), so you're welcome to use and share the content as you see fit.

Happy Learning! 📚🚀
