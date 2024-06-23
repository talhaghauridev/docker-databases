# Local Databases with Docker

This repository provides a quick and easy setup for running local instances of PostgreSQL, MySQL, Redis, and MongoDB using Docker. This setup is ideal for development and testing purposes, enabling you to spin up these databases quickly without complex installations.

## Databases Included

- **PostgreSQL**
- **MySQL**
- **Redis**
- **MongoDB**

## Getting Started

### Prerequisites

Make sure you have Docker Destop installed on your machine:

- [Docker](https://www.docker.com/products/docker-desktop)

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Starting the Databases

Navigate to the folder of the database you want to start and run docker-compose up. For example, to start PostgreSQL:

```bach
cd postgres
docker-compose up
```

Repeat the process for MySQL, Redis, and MongoDB by navigating to their respective folders and running the same command.

### Stopping the Databases

Repeat the process for MySQL, Redis, and MongoDB by navigating to their respective folders and running the same command.

```bach
cd postgres
docker-compose down

```

### Configuration

You can customize the configuration by modifying the docker-compose.yml file in each database folder. For example, you can change the default usernames, passwords, and ports.

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
