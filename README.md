# GenAI_Usecase_OpenAI
SQL query from excel &amp; SQL database
## 🚀 Getting Started

This project is a Streamlit-based application for querying data using natural language and LLMs.

---

### ✅ Prerequisites

- Python 3.8+
- `pip` or `conda` for package management
- Recommended: use a virtual environment (`venv` or `conda`)

---

### 🛠️ Installation

1. **Clone the repo**

```bash
git clone https://github.com/ramoji4b5/GenAI_Usecase_OpenAI
cd sql_chatbot 



python -m venv .venv
source .venv/bin/activate      # Mac/Linux
.venv\Scripts\activate         # Windows

```
### Install dependencies

``` bash
pip install -r requirements.txt
```

### ▶️ Run the App
```bash
streamlit run sql_chatbot/app.py
```

### Data base connections URL string
``` 
format
postgresql+psycopg2://username:password@host:port/database_name


 Breakdown:
postgres: your PostgreSQL username

admin: your PostgreSQL password

localhost: database host (can be IP or domain)

5432: default PostgreSQL port

hr_data: your database name


```

