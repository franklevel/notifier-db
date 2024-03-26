# 🗄️ Notifier Database

Welcome to the Notifier DB repository! This project contains the configuration files for setting up the database environment using Docker Compose.

## 🛠️ Setup Instructions

Follow these steps to set up the database environment locally:

### 1. Clone the Repository

```bash
git clone <repository-url>
cd notifier-db
```

### 2. Start the Database Services

Start the database services using Docker Compose:

```bash
docker-compose up -d
```

This command will start the database services defined in the `docker-compose.yml` file in detached mode.

### 3. Verify Database Setup

Once the containers are up and running, you can verify the database setup by connecting to the database using your preferred database management tool (e.g., DBeaver, TablePlus) or by running database queries.

## 📦 Included Services

The following services are included in the Docker Compose configuration:

- PostgreSQL: Database server for storing application data.

## 🧰 Customization

You can customize the database configuration by modifying the `docker-compose.yml` file and environment variables as needed.
