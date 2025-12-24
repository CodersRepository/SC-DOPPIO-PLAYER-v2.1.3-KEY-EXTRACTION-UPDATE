# SC-DOPPIO-PLAYER-v2.1.3-KEY-EXTRACTION-UPDATE

INSTALL INSTRUCTIONS FOR STREAMONITOR (SC DOPPIO PLAYER v2.1.3 KEY EXTRACTION UPDATE): 

1. Extract the StreaMonitor-master folder from the ZIP file.

2. Open a terminal/command prompt and navigate to the folder:
   cd path/to/StreaMonitor-master

3. Create and activate a virtual environment:
   
Linux and macOS
Create: python3 -m venv venv

Activate: source venv/bin/activate

Windows
Create: python -m venv venv

Activate (in command prompt): venv\Scripts\activate

4. Upgrade pip (optional):

   pip install --upgrade pip

5. Install required packages and Playwright browser
   
Run these commands in order (in your activated virtual environment):

pip install -r requirements.txt

pip install psutil playwright

playwright install chromium

6. Run StreaMonitor:
   python Downloader.py (on Windows)
   python3 Downloader.py (on Linux and macOS)

   StreaMonitor should start successfully.
   Open your browser to http://127.0.0.1:5000 or http://localhost:5000 to use the web interface.
