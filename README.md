# YuleTideee
Learning project using React, and Vue UI frameworks and with Go and C++ runtimes.

Project tracks "Weissnacht Events" perpetrated by [SCP-4666 "Yule Man"](http://www.scpwiki.com/scp-4666). SCP-4666 is a monster created by Hercules Rockefeller in the fictional universe of the SCP Foundation which is an organization contains anomalous objects, entities, and phenomena. SCP-4666 basically is a Christmas horror movie monster that attacks families north of 40°N latitude. Data will be mocked according to the data in the aforementioned link and randomly created for each year up to 2020.

## Project Goals
* Website displays individual generated events with an interactive map
* Website displays analytics of events according to region, frequency, family size, and snow depth
* Website attempts to find the next location where an event will happen based on current location
* Unsettles the viewer, especially if they read the link and live north of 40°N latitude >:)

## Requirements
* Randomly created events must have the following properties:
  * Must be north of 40°N latitude
  * Must be at an residence
  * Must have at least 1cm of snow depth from December 21 to January 2
  * Must be in a rural area (less than 150 people per square kilometer)
  * Must be dated January 1 or January 2
* At least one event must happen every year
* Average number of events per year should be approximately 3
* Events stored in a database
  * Events are requested through an API
  * Events are generated from code on a yearly schedule
* Mock event generated for a location close to current location of user
* Interactive map with pins at each event
  * Pin data displays location data, family size, and name of child abducted
  * Location data includes city, country, and coordinates
  * Name of child abducted generated according to common names of respective country
* Graphs displaying agreggated data of events
* Disclaimer with various credits, that data is purely fictional, and that any coincidences with real people are also fictional
