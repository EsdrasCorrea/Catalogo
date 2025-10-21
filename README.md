# 🧩 ASP.NET Core Web API – Learning Project (.NET 8)

## 📘 About the Project
This repository contains a **personal learning project** developed with **ASP.NET Core (.NET 8)**.  
The goal is to consolidate backend development concepts through practical application and hands-on experimentation.

The structure and learning path are **inspired by** the course:  
> _“Curso Web API ASP .NET Core Essencial (.NET 8 / .NET 9)”_  
> by **José Carlos Macoratti** — available on [Udemy](https://www.udemy.com).

⚠️ **Important Note:**  
This repository was **created from scratch** for **personal study and portfolio purposes**.  
No source code, materials, or assets were copied from the original course.  
All implementations, structure, and examples here are the result of independent development, following only conceptual guidance.

---

## 🧱 Project Structure
```
project-root/
├── backend/
│   ├── src/
│   │   ├── Api/
│   │   ├── Application/
│   │   ├── Domain/
│   │   └── Infrastructure/
│   ├── tests/
│   └── global.json
└── frontend/   (reserved for future development)
```

- **Api** → REST endpoints using Minimal APIs  
- **Application** → business logic and service interfaces  
- **Domain** → entities and core models  
- **Infrastructure** → database and external service integrations  

---

## ⚙️ Technologies Used
- **.NET SDK 8.0**  
- **ASP.NET Core Web API**  
- **Entity Framework Core (MySQL)**  
- **Swagger / OpenAPI**  
- **CORS Configuration** (for Angular frontend integration)  
- **Dependency Injection (DI)**  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>/backend
```

### 2. Check SDK version
Ensure the project runs on **.NET 8** (enforced via `global.json`):
```bash
dotnet --version
```

### 3. Restore dependencies
```bash
dotnet restore
```

### 4. Run the API
```bash
cd src/Api
dotnet watch
```

### 5. Access Swagger
Open your browser at:
```
https://localhost:<port>/swagger
```

---

## 🧠 Learning Objectives
- Practice **clean project architecture** using ASP.NET Core.  
- Understand **dependency injection**, **services**, and **data access layers**.  
- Implement a **RESTful API** using Minimal APIs.  
- Integrate with **MySQL** using Entity Framework Core.  
- Prepare for future **frontend integration (Angular 17)**.

---

## 🧰 Next Steps
- Add logging with **Serilog**.  
- Implement **DTOs and validation** using FluentValidation.  
- Add **Docker Compose** to orchestrate API + MySQL.  
- Create unit tests for services and endpoints.  
- Connect to the Angular frontend.

---

## 🪪 Credits
Course reference:  
**José Carlos Macoratti** – *Curso Web API ASP .NET Core Essencial (.NET 8 / .NET 9)* (Udemy)

Project author:  
**Esdras Correa**  
Learning & developing independently for educational and portfolio purposes.

---

## 🧾 License
This project is for **educational use only** and has no commercial intent.  
You are free to explore, fork, and learn from it.
