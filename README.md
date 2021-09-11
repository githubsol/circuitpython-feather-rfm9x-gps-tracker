# circuitpython-feather-rfm9x-gps-tracker
A circuitpython project to run on an Adafruit Feather m0 with LoRa rfm9x and a GPS shield.

# Fjern skrivebeskyttelse på gps-tracker

- Find USB Serial device i Device manager, se id
- Start putty
- Vælg "serial" forbindelse, indtast id fra device manager
- Ctrl+C for at stoppe koden
- Skriv "import os" - tryk enter
- Skriv os.rename("/boot.py","/boot.py.bak") - tryk enter
- reset trackeren

Nu kan man skrive til filsystemet

Husk at rename boot filen tilbage til boot.py og reset trackeren igen