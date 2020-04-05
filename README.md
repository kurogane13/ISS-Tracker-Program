# CLI BASED ISS-Tracker-Program
This program is a CLI based python api-client that tracks the ISS (International space spation) coordinates.

It tracks the ISS from a public API(http://api.open-notify.org/iss-now.json), parses the json format to text, and displays its actual coordinates in the console.
You can pre-select the iterations(How many times to show snapshots and coordinates), and refresh intervals(Amount of seconds to show coordinates). 
It will open Google Maps with firerox(using selenium, and show the ISS coordinates as they change, 
taking snapshots of every location to store them in a folder by date. It also has a log file, 
where it appends the raw data in txt format.

ATTACHMENTS: I am attaching the program(ISS_google_maps_v3.py), and the selenium web driver (geckodriver-v0.22.0-linux64.tar.gz) which i used to trigger selenium.

1. Make sure to install all the libraries before running the program.
2. Place the selenium webdriver in your /usr/bin/geckodriver-v0.22.0-linux64.tar.gz path
or executable path.
3. Run the program with python 3. Tested with python3.6

Hope you like it!.




