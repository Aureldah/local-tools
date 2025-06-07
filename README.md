# Local Tools 🛠️

![Local Tools](https://img.shields.io/badge/Local_Tools-v1.0.0-brightgreen.svg)
[![Releases](https://img.shields.io/badge/Releases-Check%20Here-blue.svg)](https://github.com/Aureldah/local-tools/releases)

Welcome to **Local Tools**, your go-to local development toolkit. This repository provides preconfigured containers for essential services, making it easier to set up and manage your development environment. Whether you are working on microservices or testing distributed systems, Local Tools has you covered.

## Table of Contents

1. [Features](#features)
2. [Services Included](#services-included)
3. [Getting Started](#getting-started)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Features

- **Preconfigured Containers**: Save time with ready-to-use Docker containers.
- **Essential Services**: Supports MongoDB, Kafka, PostgreSQL, Temporal, Redis, and Elasticsearch.
- **Microservices Ready**: Ideal for testing and developing microservices.
- **Easy Setup**: Simple commands to get everything running.

## Services Included

Local Tools comes with the following services:

- **MongoDB**: A NoSQL database for storing data in flexible, JSON-like documents.
- **Kafka**: A distributed event streaming platform capable of handling trillions of events a day.
- **PostgreSQL**: An advanced, open-source relational database system.
- **Temporal**: A workflow orchestration platform that allows you to build reliable applications.
- **Redis**: An in-memory data structure store, used as a database, cache, and message broker.
- **Elasticsearch**: A search engine based on the Lucene library, used for full-text search and analytics.

## Getting Started

To get started with Local Tools, you will need Docker and Docker Compose installed on your machine. Follow the instructions below to set everything up.

### Prerequisites

- Docker: Make sure you have Docker installed. You can download it from [Docker's official site](https://www.docker.com/get-started).
- Docker Compose: This is usually included with Docker Desktop. If not, you can install it separately.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Aureldah/local-tools.git
   cd local-tools
   ```

2. Pull the necessary Docker images:

   ```bash
   docker-compose pull
   ```

3. Start the services:

   ```bash
   docker-compose up -d
   ```

### Download and Execute Releases

For the latest releases, visit [Releases](https://github.com/Aureldah/local-tools/releases). Download the necessary files and execute them to get started.

## Usage

After starting the services, you can access each service on the following ports:

- **MongoDB**: `localhost:27017`
- **Kafka**: `localhost:9092`
- **PostgreSQL**: `localhost:5432`
- **Temporal**: `localhost:7233`
- **Redis**: `localhost:6379`
- **Elasticsearch**: `localhost:9200`

### Connecting to Services

You can connect to these services using your preferred client. For example, you can use MongoDB Compass for MongoDB, pgAdmin for PostgreSQL, and Kibana for Elasticsearch.

### Stopping the Services

To stop the services, run:

```bash
docker-compose down
```

This command will stop and remove the containers, but your data will persist.

## Contributing

We welcome contributions to Local Tools! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to reach out:

- **GitHub**: [Aureldah](https://github.com/Aureldah)
- **Email**: aureldah@example.com

Thank you for using Local Tools! We hope it makes your development experience smoother and more efficient. For updates and releases, always check the [Releases section](https://github.com/Aureldah/local-tools/releases).