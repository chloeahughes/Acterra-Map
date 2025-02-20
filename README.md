Acterra Map Dashboard

Overview
This project visualizes environmental and low-income housing data on a publically accessible, digestible map dashboard for community members local to the Bay Area. 

Setup Instructions

Install Backend (Flask)

```sh
cd acterra-backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 data_processing.py  # Process CSV files
python3 app.py  # Start API
