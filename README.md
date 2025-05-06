# application-Dashboard-collaboratif-de-visualisation-et-d-analyse-de-donnes
🧾 GUIDE_D_INSTALLATION.md
markdown
Copier
Modifier
# Guide d'installation du projet "Dashboard collaboratif"

## 🛠️ Prérequis

- Node.js (v18 ou supérieur)
- Python 3.11+
- PostgreSQL
- Git
- Navigateur web moderne (Chrome, Edge, etc.)

## 🧩 Installation du Backend (FastAPI)

```bash
cd backend
python -m venv env
env\Scripts\activate    # Sur Windows
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
🎨 Installation du Frontend (React + Vite + TailwindCSS)
bash
Copier
Modifier
cd frontend
npm install
npm run dev
🔐 Accès Admin par défaut
env
Copier
Modifier
Nom d'utilisateur : admin
Mot de passe : admin123
