# Pixiebooth
# 🎟️ Pixie: Event Discovery & Tracking Tool
An automated solution to proactively discover upcoming events for photobooth installations.

## 🚀 Setup & Usage
1. **Clone the repo:** `git clone https://github.com/YOUR_USERNAME/pixie-event-discovery.git`
2. **Install Dependencies:** `pip install -r requirements.txt`
3. **Run the Dashboard:** `streamlit run app.py`

## 🛠️ Features
- **Live Scraping:** Extracts Event Name, URL, and Status from BookMyShow.
- **Deduplication:** Only adds new events to the Excel database.
- **Expiry Logic:** Automatically marks past events as 'Expired'.
- **Interactive UI:** Built with Streamlit for easy filtering and data export.
