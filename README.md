# 💱 Currency Converter

A clean and responsive **Currency Converter** web application built using **Flask (Python)** for the backend and **HTML, CSS, JavaScript** for the frontend. It fetches real-time exchange rates and converts between major world currencies.

---

## 🌟 Features

- 🔁 Convert between popular currencies (USD, EUR, INR, etc.)
- 🌐 Fetches real-time exchange rates via an API
- 🖥️ Clean and responsive user interface
- 🧮 Accurate currency calculations
- 🗃️ Optional: stores conversion history using SQLite3
- 🔐 Login page and user-based history (if enabled)

---

## 🛠️ Built With

- Python 3
- Flask
- Jinja2
- HTML5 + CSS3 + JavaScript
- SQLite3 (optional for tracking history)
- Exchange Rate API (e.g., exchangerate-api.com, exchangerate.host)

---

## 📂 Folder Structure

currency-converter/
├── static/ # CSS and JS files
├── templates/ # HTML files (Jinja2 templates)
├── app.py # Main Flask backend
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── database.db # Optional: SQLite3 DB for user history


---

## 🚀 How to Run

### 1. Clone the repo

```bash
git clone https://github.com/Mohammed-Safwaan/Currency-Converter.git
cd Currency-Converter

2. Set up virtual environment (recommended)
bash
Copy code
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

3. Install dependencies
bash
Copy code
pip install -r requirements.txt
4. Run the Flask app
bash
Copy code
python app.py
Now visit http://127.0.0.1:5000 in your browser.

📸 Screenshots
Add screenshots of your app UI here if needed.

✅ Future Improvements
Add currency trends and history graphs

Allow PDF export of conversions

Add multiple themes (dark/light)

Add authentication and user dashboard

🙋‍♂️ Author
Mohammed Safwaan
GitHub: @Mohammed-Safwaan


