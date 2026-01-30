<h1 align="center">🎵⛪ Church Website Project — Phase 0</h1>
<p align="center">
  <strong>Frontend + Backend skeleton</strong> — ready for Phase 1 development
</p>

---

##  Overview

Phase 0 sets up the **foundation** for the church website project:

- ✅ Local dev environment (Node.js, Java 17, Gradle, Git + SSH)
- ✅ Frontend skeleton (React + TypeScript + Vite)
- ✅ Backend skeleton (Spring Boot + Kotlin + H2 DB)
- ✅ Professional Git repository with `.gitignore`

> Goal: create a **clean, professional setup** to start building real features in Phase 1.

---

## 📁 Project Structure

| Folder        | Purpose                                        |
|---------------|-----------------------------------------------|
| `backend/`    | Spring Boot + Kotlin backend                  |
| `frontend/`   | React + TypeScript frontend (Vite)           |
| `docker/`     | Docker setup (optional)                       |
| `docs/`       | Documentation                                 |
| `README.md`   | Phase 0 summary                               |

> Empty folders are tracked with `.gitkeep` to maintain structure.

---

## ⚡ Phase 0 Achievements

<details>
<summary>💻 Local Environment Setup</summary>

- Installed **Node.js** for frontend development  
- Installed **Java 17 (Temurin)** for backend  
- Installed **Docker** (optional for future use)  
- Configured **Git + SSH** for smooth GitHub workflow  

</details>

<details>
<summary>🎨 Frontend Skeleton</summary>

- Initialized **React + TypeScript** using Vite  
- Dev server runs at [http://localhost:5173](http://localhost:5173/)  
- Committed frontend skeleton to Git  

</details>

<details>
<summary>🛠️ Backend Skeleton</summary>

- Spring Boot + Kotlin project initialized  
- Configured **H2 in-memory database** in `application.yml`  
- Backend server runs at [http://localhost:8080](http://localhost:8080/)  
- Added minimal **JPA configuration** for future database integration  

</details>

<details>
<summary>🧹 Git Repository Cleanup</summary>

- Added **.gitignore** to exclude:  
  - Build artifacts (`/build/`, `.jar`)  
  - Node modules (`/node_modules/`)  
  - IDE files (`.idea/`, `.vscode/`)  
  - OS artifacts (`.DS_Store`)  
- Removed previously committed JARs from Git  
- Repository is now clean and professional  

</details>

---

## 🗂 Lessons Learned

| Challenge | How It Was Solved |
|-----------|-----------------|
| Git authentication prompts | Configured SSH key for GitHub |
| Empty folders not showing | Added `.gitkeep` files |
| Nested backend folder | Moved files up one level |
| Backend build failure | Configured H2 DB in `application.yml` |
| Gradle stuck at 85% | Learned this is normal; server actually running |
| Large JAR committed | Added `.gitignore`, removed cached JAR |

> Every issue helped build **professional troubleshooting skills**.

---

## 🔄 Project Flow Diagram

```mermaid
flowchart LR
    A[Frontend: React + TypeScript] -->|REST API calls| B[Backend: Spring Boot + Kotlin]
    B --> C[Database: H2 in-memory]
    C --> B
    B -->|Responses| A



##  Next Steps (Phase 1)

- Build **music page features**: chords, transpose, Nashville numbers  
- Connect **frontend → backend** via REST APIs  
- Implement **UI for musicians** to manage songs  
- Add **unit and integration tests**  
- Prepare for **deployment & hosting**

---

## 🚀 How to Run Locally

### Backend
```bash
cd backend
./gradlew bootRun
# Open http://localhost:8080



