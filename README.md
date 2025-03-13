# Docker-Monitoring-plateform
# PFE Project

This project consists of two parts: **Frontend** and **Backend**. Follow the instructions below to set up and run the project.

---

## 🚀 Frontend Setup
1. Navigate to the **Frontend Part** folder.
2. Inside it, go to the `frontend/my-project` directory.
3. Install dependencies (if not installed):
        npm install
4. Run the following command:
        npm run dev
 The frontend should now be running on http://localhost:3000 (or another port if specified).


 
 ## ⚙️ Backend Setup
1. Navigate to the Backend Part folder.
2. Open the project in an IDE that supports Spring Boot (e.g., IntelliJ IDEA, Eclipse, or VS Code).
3. Ensure you have Java 17+ and Maven installed.
4. Build the project using Maven:
       mvn clean install
5. Run the Spring Boot application:
       mvn spring-boot:run
The backend should now be running on http://localhost:8080 (or your configured port).


 ## 🛠 Troubleshooting
  Frontend Issues:
    If npm run dev fails, try deleting node_modules and package-lock.json, then reinstall:
      rm -rf node_modules package-lock.json
      npm install
  Backend Issues:
    If Maven dependencies are missing, try:
      mvn clean package

