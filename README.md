# GreenRoofProject
First thing first, thank u for coming to my page!!!

This project started at Sep.2019, ended at Dec.2019, in NewBrunswick, Rutgers University. It works as a tutorial process of my EI class, leaded and guided by Prof. Roger Wang in CEE Department.

Our basic aim is to use arduino board-connected sensor to sense, collect(read&write) soil moisture and outdoor temperature on Greenroof that is located on Richard Week Hall.

Then we need to use the python knowledge to edit the code to run the arduino board, then we need to process our data(e.g. refine our data; fit our data to the regression model; use different way/style to present our data)

We build up a numerial model to present the equation between soil moisture(Sm), percipitation(P) and total evaporation(E) 𝐷Sm/dt = aP+ bE

# Our device
1).Adafruit METRO w/Atmega328

2).My roomate's 10000mAh power bank

3).Half-sized breadboard

4).8g SD card & SD Reader

# Our sensor
1).Capacitive Soil Moisture Sensor V1.2 

2).TMP36 Temperature Sensor

# Challenges
1).Due to the tough weather in west coast, a short circuit problem happened frequently all the time: we always got 300+ degreee centigrade data (originally should be the degree of moisture). We didn't know if it was because of the overload of cpu. So we adjust the timing interval of testing to 5min and it still happened. So we believed that the senor might be moved or touched by our friend---squirrels.

2).We want to isolate the sensor from the environment in order to set the drainage volume to 0, so I put soft soil and our devices into a Nike shoe box and kept it half-opened. But unfortunately, the flashing light of sensor and the illuminated power bank in a mysterious black box lead to some concerns. Someone reported the RUPD, said a suspicious package looked like a Bomb.... I was almost arrested. After answered 200 question in front of the bomb specialist, 30 cops and 5 police dogs, I went back home. Life goes on...
