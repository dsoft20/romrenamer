# romrenamer
This script takes the gamelist.xml generated files by the Universal XML-Scraper and replace the scraped name field (&lt;name>) with the rom name

		<path>./Game name (Europe).zip</path>
		<name>Game name</name>
							TO
		<path>./Game name (Europe).zip</path>
		<name>Game name (Europe)</name>

WINDOWS: place the file on \\raspberry\configs\all\emulationstation\gamelists\
		  
		  run the script via python rm.py
		  
RETROPIE: place the file in /home/pi/.emulationstation/gamelists/
		  
		  run the script via python rm.py
