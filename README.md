# [Banana Map: Winner of Northeastern University Hackathon 2023](https://github.com/jwke21/team_banana_hackathon)
**Carbon Emission and Energy calculator of various transportation routes**

The Banana Map is a web application that was created for the Northeastern University 2023 Hackathon within 24 hours. The theme for the Hackathon was "Tools of the Future" and our focus was climate change and environmental sustainability. The objective of our product is to provide incentives and day-to-day comparison for the user on their transportation choice. Transportation is the greatest contributor (~27%) of greenhouse gases emission in the United States. Hence, the first step of heading towards more sustainable life is to wisely choose our transportation option. For this project, we are comparing 4 transportation modes: driving, busing, walking, and cycling. 

For the back-end, we pre-processed the CO2 emission dataset to get the average car mpg (miles per gallon) and CO2 emission (metric tons/mile) in Python. We also gathered resources for energy and calorie calculations. We converted those energy to equivalent number of banana needed so that users can have a tangible comparison (it is also a great source of fuel for our body!). We also showed how much area needed for a forest to sequestered the emitted CO2 (metric tons/area/day). That way, the user will get both biological and environmental comparisons. 

The front-end was built using JavaScript. Mapbox API (open source) were utilized to show the map and get the distance between two addresses. The features includes trip distance calculator, CO2 emission tracking, kcal energy expenditure tracking, and equivalent banana calorie tracking. The web interface is shown below. 

Future development of this project includes cross-platform application, user rewards system (getting banana points!), and tracking other carbon saving choices such as household electricity and waste management. 


**Team Banana:**

* Jessica Tanumihardja
* Shreya Goyal
* Randy Ramli
* Zhiwei Zhou
* Chunyun Zhang
* Jake Van Meter


## Creating and Using MapBox Access Token for Geocoding API

1) Go to: <a href="https://www.mapbox.com/">https://www.mapbox.com/</a> and sign
in to your account or sign up for one.

2) Go to the "Dashboard" or "Tokens" page and click "Create a token".

3) Enter a name for your token in the "name" box.

4) Scroll down and click "Create Token". (The default token scopes work fine for
the Geofetch API)

5) Copy the newly created Token and assign it to the
`MAPBOX_ACCESS_TOKEN = "<Place_Your_MapBox_Access_Token_Here>";` on line 1 of `main.js`.

6) Save `main.js` and open or refresh `index.html` and it should work.

7) Go bananas 🍌! ;)
