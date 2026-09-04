# Student Management & CGPA Dashboard

A Streamlit-based Python web app to manage student records, subject marks, grades, and SGPA calculation.

## Features
- Add, view, and delete students
- Add and delete subject marks
- Automatic grade calculation
- SGPA calculation
- Dashboard with:
  - Total students
  - Class average SGPA
  - Highest/Lowest SGPA
  - SGPA bar chart

## Tech Stack
- Python
- Streamlit
- Pandas
- SQLite (via `database.py`)

## Project Structure
```bash
student-management-app/
│── app.py
│── database.py
│── calculations.py
│── requirements.txt
│── README.md
│── .gitignore
```

## Installation & Run (Local)

1. Clone repository
```bash
git clone https://github.com/YOUR_USERNAME/student-management-app.git
cd student-management-app
```

2. Create virtual environment
```bash
python -m venv venv
```

3. Activate virtual environment

- Windows (PowerShell):
```powershell
.\venv\Scripts\Activate.ps1
```

- Windows (CMD):
```cmd
venv\Scripts\activate.bat
```

- macOS/Linux:
```bash
source venv/bin/activate
```

4. Install dependencies
```bash
pip install -r requirements.txt
```

5. Run Streamlit app
```bash
streamlit run app.py
```

6. Open in browser:
```text
http://localhost:8501
```

## Usage
- Go to **Students** page to add student details.
- Go to **Marks & CGPA** page to add subject marks and credits.
- View performance metrics in **Dashboard**.

## Future Improvements
- Edit student details
- Export report cards to PDF/Excel
- Authentication (admin login)
- Deploy on Streamlit Community Cloud

## Author
**Saima Shaikh**

## License
This project is for learning purposes.