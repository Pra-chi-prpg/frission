# Selenium and Streamlit
Selenium: To automate browser actions and scrape live data from dynamic websites (like Google Maps).
Streamlit: To quickly build a web interface without HTML/JS.
CSV: To store and share the extracted data easily.

project-folder/
│
├── Backend(Selenium Script)/
│   └── main.py
│
├── Frontend (Streamlit UI)/
    └── Streamlit_app.py
 # WORKFLOW
User opens the Streamlit web app.
On clicking “Scrape IT Companies”, the backend:
  Launches a headless browser.
  Opens Google Maps and searches for "IT companies in Noida".
  Scrolls through listings and scrapes names, phone numbers, and addresses.
The data is saved to it_companies_noida.csv.
The data is displayed on the web page and available for download.

 # Frontend (Streamlit):
Provides a simple UI with a button to scrape data.
Displays scraped IT company data (Name, Phone, Address).
Allows CSV download.

# Backend (Selenium):
Opens Google Maps in a headless browser.
Searches for “IT companies in Noida”.
Extracts company info.
Saves it to it_companies_noida.csv.

