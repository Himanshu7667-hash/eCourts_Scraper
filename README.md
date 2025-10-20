# eCourts Case & Cause List Scraper

A smart Python-based tool to fetch, parse, and download court cause lists directly from eCourts India.
Designed for automation, accuracy, and simplicity — whether you're tracking a specific case or analyzing full daily listings.

## 📖 Overview
The eCourts Case Scraper is a Python project that helps users automatically extract court listings, case details, and PDFs from India’s official eCourts portal.

You can:

🔍 Search using CNR or Case Type / Number / Year.

🕐 Check if a case is listed today or tomorrow.

📄 Download the cause list PDF (if available).

💾 Export results in JSON, PDF, or text format.

🌐 Use the CLI or optional web interface to interact in real-time.

## 🚀 Features
✅ Fetch cause lists or individual case listings from eCourts.
✅ Search by CNR, case details, or court name.
✅ Works with both district and state courts.
✅ Automatic PDF download of cause lists (if available).
✅ Saves data as JSON for easy reuse or analysis.
✅ Flask web dashboard for viewing listings in your browser.
✅ Built-in error handling for HTML changes on court websites.

## 🧩 Files
| File | Purpose |
|------|----------|
| `main.py` | Command-line launcher |
| `ecourts_scraper.py` | Core scraping logic and data parser |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Ignore unnecessary files |

## 📦 Installation & Usage
You can run this project locally (if needed):

pip install -r requirements.txt
python ecourts_causelist_scraper.py



### ⚡ Run the Workflow
1. Go to **Actions → Court Data Fetcher**.
2. Click **Run workflow → Run workflow**.
3. Wait 1–2 minutes — GitHub will:
- Fetch PDFs  
- Parse the data  
- Create `cause_list.json` in the repo



### 📁 View Output Files
After the workflow finishes:
- Go to your repository **Files tab**
- Open the `data/` folder
- You’ll see:
- `cause_list.pdf` — downloaded file
- `cause_list.json` — parsed data

---

### 💻 View Mini Dashboard
To view the data dashboard:

1. Open the **`index.html`** file in your repo.  
2. Click **“Raw”** → then long press and copy the link.  



