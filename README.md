 🔐 Hybrid Identity Management System

An enterprise-grade hybrid identity management system that integrates Spring Boot APIs with simulated legacy authentication layers and GitHub Actions CI/CD.  
Designed to model modernization from traditional mainframe auth systems to cloud-native microservices.

---

🚀 Tech Stack

- Java 17, Spring Boot 3
- Shell Scripting (Legacy integration simulation)
- Maven
- LDAP mock config
- Docker
- GitHub Actions (CI/CD)

---

 📂 Project Structure

Hybrid-Identity-Management-System/
├── identity-api/ # Spring Boot backend
│ ├── Dockerfile
│ └── pom.xml
├── legacy-auth-integration/ # Legacy shell scripts
│ ├── validate_user.sh
│ └── sync_users.sh
├── config/ # LDAP mock config
│ └── ldap-config.properties
├── .github/workflows/ # CI/CD pipeline
│ └── build.yml
└── README.md



 🔧 Key Modules

 ✅ identity-api (Spring Boot)
- REST API for identity-related operations
- Container-ready with Docker
- Maven project (pom.xml included)

 🧾 legacy-auth-integration
- `validate_user.sh`: Simulates mainframe user validation
- `sync_users.sh`: Mocks syncing from legacy to modern DB

 ⚙️ config (LDAP Simulation)
- LDAP connection properties for enterprises with directory-based auth

---

 🔄 GitHub Actions – CI/CD

- Automatically builds and tests the Spring Boot backend on every push/pull
- Located at `.github/workflows/build.yml`

```yaml
- Checks out code
- Sets up Java 17
- Runs Maven clean install
🐳 Docker Instructions
cd identity-api
mvn clean package
docker build -t identity-api .
docker run -p 8080:8080 identity-api
