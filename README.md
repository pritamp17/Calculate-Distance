# Distance Calculating Django App
App that can show distance between user's location and searched location on map.

# Packages Used
1. Geopy
2. folium
3. crispy-form
4. Bootstrap

# How to run
\\\\ Navigate to the project directory.
```bash
cd Hacking-Scripts/python/Calculate-distance
```
```
create folder named 'geoip' in main project directory.
```
```
download city and country database
```
[For downloading city and country database ](https://www.maxmind.com/en/accounts/497315/people/84e6213c-91a4-4e02-ae2e-1d709084c544)
1. ![](https://github.com/pritamp17/Calculate-Distance/blob/main/1.paste.png)
2. ![](https://github.com/pritamp17/Calculate-Distance/blob/main/2.paste.png)

```
extract the zip files and copy paste 
1. GeoLite2-City.mmdb
2. GeoLite2-country.mmdb
to geoip folder
```
```bash
pip install -r requirements.txt
```
```bash
python manage.py runserver
```
# And there you go
![](https://github.com/pritamp17/Calculate-Distance/blob/main/django-1-test2.png)
![](https://github.com/pritamp17/Calculate-Distance/blob/main/django-2-test2.png)
![](https://github.com/pritamp17/Calculate-Distance/blob/main/django-3-test2.png)
