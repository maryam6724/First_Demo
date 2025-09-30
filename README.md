# First_Demo
This is my first Git Repository
<br>
Author-Maryam Belvadi
## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/hungerfree.git
cd hungerfree


### 2. Backend Setup
```bash
cd backend
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux

pip install -r requirements.txt


### Create .env file inside backend/
```env
DATABASE_URL=postgresql://postgres:YOUR_PASSWORD@db.<project-id>.supabase.co:5432/postgres
JWT_SECRET_KEY=your_secret_key


### Run backend
```bash
python app.py

Backend runs at: http://localhost:5000

### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev

Frontend runs at: http://localhost:5173

---
