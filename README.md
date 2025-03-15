# 🚀 AI-powered Web App Project Template

This project template provides a fully-configured, Dockerized development environment leveraging Python, FastAPI, React, Vite, Tailwind CSS, and an integrated LLM-powered coding assistant. Quickly spin up new AI-powered projects with minimal effort!

## 📂 Project Template Structure

- **backend/**: Python (FastAPI) backend.

- **frontend/**: JavaScript frontend with React, Vite, and Tailwind.

- **llm_context/**: Structured context files for IDE-integrated LLM assistant:

  - `STRUCTURE.md`: Detailed folder and file structure overview.
  - `PROJECT.md`: Project overview, goals, and objectives.
  - `tech_stack.json`: Tech stack with clearly defined versions.
  - `llm_instructions.txt`: Customized instructions for your IDE-integrated AI assistant.

- `.env`: Environment variables.

- `docker-compose.yml`: Docker compose configuration for backend and frontend.

---

## 🐧 Quick Start (WSL2 Setup)

### Step 1: Clone the WSL2 `.vhdx` Template (Import In Place)

- Save a copy of your pre-configured WSL2 `.vhdx` file.
- Register the `.vhdx` in place without copying it:

```powershell
wsl --import-in-place <DistroName> <PathToYourTemplate.vhdx>
```

### Step 2: Launch your New WSL Distro

```powershell
wsl -d <DistroName>
```

### Step 3: Start the Development Containers

Navigate to your project directory and launch Docker Compose:

```bash
cd projects/project_template
docker compose up
```

Your frontend will run at `http://localhost:3000` and backend at `http://localhost:8000`.

---

## 🤖 Configuring the IDE-Integrated AI Assistant

Your project comes with structured context files (`llm_context`) optimized for AI assistance:

- Modify `PROJECT.md` and `llm_instructions.txt` as needed for your specific project.
- The AI assistant will automatically use the provided context files to enhance your coding workflow.

---

## 🌟 Recommended Workflow

- **Customize context**: Quickly edit `llm_context/PROJECT.md` and `llm_context/llm_instructions.txt` for new projects.
- **Maintain consistency**: Stick to the predefined tech stack (`tech_stack.json`) for stability and efficiency.
- **Document clearly**: Keep your structured files up-to-date to get the most out of your IDE-integrated AI assistant.

---

🎉 Happy coding! Your fully integrated, Dockerized, AI-enhanced development environment is ready to accelerate your project creation and productivity.

