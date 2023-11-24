# hotels_and_properties_in_bd
This repository has been created as a part of the Capstone Project work submission for the Dokkho Career Data Science Course, Cohort-3. It summarizes data collected about hotels and properties of Bangladesh as listed in the Booking.com website

## Build from Sources
1. Clone the repo:
```bash
git clone https://github.com/lubnaonline228/hotels_and_properties_in_bd.git
   ```

2. Initialize and activate virtual environment:
```bash
virtualenv ---no-site-packages venv
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Download Chrome Webdriver from https://chromedriver.chromium.org/downloads
   
5. Run the scraper:
```bash
python scraper_for_properties_in_bangladesh.py
```
6. You will get a file named `properties_and_hotels_bd.csv` containing all the scraped fields
Alternatively check our scraped data here: https://github.com/lubnaonline228/hotels_and_properties_in_bd/blob/main/properties_and_hotels_bd.csv

## Analytics
Tableau public view: <br>
https://public.tableau.com/app/profile/nahid.akhtar/viz/HotelandPropertyDatafromBooking_com/Dashboard2?publish=yes
https://public.tableau.com/app/profile/nahid.akhtar/viz/HotelandPropertyDatafromBooking_com/Dashboard1?publish=yes
