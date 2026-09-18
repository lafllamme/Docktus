<h1 align="center">⚡ Dockerized Directus</h1>

<p align="center">
  A Dockerized setup for hosting a Directus instance, perfect for modern web projects.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-Enabled-blue" alt="Docker">
  <img src="https://img.shields.io/badge/Directus-v9.0.0-blueviolet" alt="Directus">
  <a href="https://github.com/lafllamme/Docktus/commits/main"><img src="https://img.shields.io/github/last-commit/lafllamme/Docktus" alt="Last Commit"></a>
  <a href="https://github.com/lafllamme/Docktus/issues"><img src="https://img.shields.io/github/issues/lafllamme/Docktus" alt="Open Issues"></a>
</p>

---

## 🚀 Features

- **Fully Dockerized**: Get Directus up and running with minimal configuration.
- **Scalable Architecture**: Use Docker Compose for managing multiple services.

---

## 🛠 Prerequisites

Ensure the following are installed:

- [Docker](https://www.docker.com/get-started) (latest version)
- [Docker Compose](https://docs.docker.com/compose/install/) (latest version)

---

## 🗂 Project Structure

```plaintext
/Docktus
│
├── docker-compose.yml
├── .env
├── Directus/
│   └── [Directus project files]
```

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/lafllamme/Docktus.git
cd Docktus
```

### 2. Configure Environment Variables

Create a `.env` file in the root directory with the following content:

```env
# .env
DIRECTUS_PORT=8055
DATABASE_HOST=db
DATABASE_USER=admin
DATABASE_PASSWORD=secret
```

### 3. Start the Services

```bash
docker-compose up -d
```

### 4. Access the Services

- Directus: [http://localhost:8055](http://localhost:8055)

---

## 🧑‍💻 Usage

Use Docker Compose to manage the services:

| Command                 | Description                                  |
|-------------------------|----------------------------------------------|
| `docker-compose up`     | Start all services in detached mode          |
| `docker-compose down`   | Stop all services                            |
| `docker-compose logs`   | View logs for all containers                 |
| `docker-compose exec`   | Execute commands inside a running container  |

---

## 🔧 Ports & Configuration

### Exposed Ports

- **8055**: Directus admin panel

---

## 📚 Resources

- [Directus Documentation](https://docs.directus.io/)

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

Made with love by [Laflamme](https://github.com/lafllamme).

---
