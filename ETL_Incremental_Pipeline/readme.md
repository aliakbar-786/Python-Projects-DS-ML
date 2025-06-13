# Oracle Incremental ETL Script Using Python

This project demonstrates an ETL (Extract, Transform, Load) pipeline using Python, SQLAlchemy, and cx_Oracle to perform **incremental loads** from a staging table (`RAW_EMPLOYEES1`) into a target table (`RAW_EMPLOYEES11`).

---

## 🔧 Technologies Used

- Python 3
- cx_Oracle
- SQLAlchemy
- pandas
- Oracle XE 11g/21c (local)
- Jupyter Notebook or any Python IDE

---

## 🛠️ Project Features

- Connect to Oracle database using SQLAlchemy and cx_Oracle
- Automatically retrieve the last ETL timestamp from the target table
- Extract only new or updated records
- Use `MERGE` SQL to upsert data into the target table
- Logs all processed employee records

---

## 📁 Folder Structure

oracle_etl_project/
│
├── etl_oracle_merge.py # Python script for incremental ETL
├── requirements.txt # Dependencies list (optional)
└── README.md # Project overview and instructions

yaml
Copy
Edit

---

## ⚙️ Setup Instructions

### Step 1: Install Dependencies

```bash
pip install cx_Oracle sqlalchemy pandas schedule
Step 2: Make Sure Oracle XE is Running Locally
Set your Oracle SID as xe and schema/user as hr.

Step 3: Run the Script
Use Jupyter Notebook, VS Code, or command line:


python etl_oracle_merge.py
📌 Use Case
This script is ideal for:

Performing incremental loads in an ETL pipeline

Testing MERGE logic without full table truncation

Practicing Oracle + Python integration

📬 Contact
Ali Akbar
Feel free to connect for suggestions or collaboration.


---

Would you like me to also prepare `requirements.txt` or GitHub upload instructions?