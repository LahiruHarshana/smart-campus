<div align="center">

# 🏫 Smart Campus

[![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

**A modern smart campus management system to streamline university operations.**

[Getting Started](#-getting-started) •
[Features](#-features) •
[Tech Stack](#-tech-stack) •
[Project Structure](#-project-structure) •
[Contributing](#-contributing)

---

</div>

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔐 **Authentication** | Secure login & role-based access control |
| 📚 **Course Management** | Create, update & manage courses |
| 👨‍🎓 **Student Portal** | Student registration & profile management |
| 👨‍🏫 **Faculty Management** | Manage faculty members & assignments |
| 📊 **Dashboard** | Real-time analytics & reports |
| 🔔 **Notifications** | Alerts & announcements system |

## 🛠 Tech Stack

<div align="center">

| Layer | Technology |
|-------|-----------|
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Build Tool** | ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white) |
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

</div>

## 📁 Project Structure

```
smart-campus/
├── 📂 src/
│   ├── 📂 main/
│   │   ├── 📂 java/          # Application source code
│   │   └── 📂 resources/     # Configuration files
│   └── 📂 test/              # Unit & integration tests
├── 📄 pom.xml                # Maven dependencies
├── 📄 .gitignore
└── 📄 README.md
```

## 🚀 Getting Started

### Prerequisites

> Make sure you have the following installed:

- ☕ **Java 17+**
- 📦 **Maven 3.8+**
- 🐬 **MySQL 8.0+**

### Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/LahiruHarshana/smart-campus.git

# 2️⃣ Navigate to project directory
cd smart-campus

# 3️⃣ Configure database
# Update src/main/resources/application.properties with your MySQL credentials

# 4️⃣ Build the project
./mvnw clean install

# 5️⃣ Run the application
./mvnw spring-boot:run
```

### ⚙️ Configuration

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/smart_campus
spring.datasource.username=your_username
spring.datasource.password=your_password
```

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/students` | Get all students |
| `POST` | `/api/students` | Create a student |
| `GET` | `/api/courses` | Get all courses |
| `POST` | `/api/courses` | Create a course |
| `GET` | `/api/faculty` | Get all faculty |

## 🤝 Contributing

Contributions are welcome! Here's how:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit changes (`git commit -m 'Add amazing feature'`)
4. 📤 Push to branch (`git push origin feature/amazing-feature`)
5. 🔃 Open a Pull Request

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ by [Lahiru Harshana](https://github.com/LahiruHarshana)**

⭐ Star this repo if you find it helpful!

</div>
