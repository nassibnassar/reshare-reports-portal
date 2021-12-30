# CNY Reports
A simple flask app to make it easy to run prepared reports for ReShare against LDP. Reports are taken from https://github.com/openlibraryenvironment/reshare-analytics/tree/main/sql/report_queries.

## Setup
Setup python
```
virtualenv -p python3.6 ENV
source ENV/bin/activate
pip install -r requirements.txt
```

Set your local settings
```
cp settings.template.py settings.py
```
## Run (for development)
```
FLASK_ENV=development python app.py
```

