# Lapup-scraper
Web scraping python script that checks if weather station at LapUp works ok

* scraper.py: 

1) Scrapes values from LAPUP weather station websiteLogs them to .db file

2) Checks for out-of-range values

3) Checks for consecutive zeros

4) Mails error for case 3 or 4 to recipients


Note: Add this script to a crontab or task scheduler to run eg. every 10 minutes.
