# VITyarthi — Student Project Tracker


**Project title:** VITyarthi: Student Project Tracker


**Overview:**
A lightweight web application to manage course projects: student registration, project submission, progress tracking, and simple risk prediction for timely completion. Designed to satisfy VITyarthi project guidelines.


**Features:**
- User management (student & faculty roles)
- Project submission, CRUD operations on projects
- Progress logging and milestone tracking
- Simple ML-based risk predictor (will flag projects at risk of delay)
- Reporting & simple analytics dashboard


**Technologies:**
- Python 3.10+
- Flask
- SQLAlchemy + SQLite (replaceable by PostgreSQL)
- WTForms
- scikit-learn (for basic predictor)
- Bootstrap (frontend)
- pytest (tests)


**Install & run:**
```bash
git clone <your-repo-url>
cd vit-yarthi-project
python -m venv venv
source venv/bin/activate # on Windows: venv\Scripts\activate
pip install -r requirements.txt
export FLASK_APP=app/app.py
flask run
